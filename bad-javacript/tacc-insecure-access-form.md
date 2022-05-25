# TACC Insecure Access Form

## Purpose

Hide page contents from user unless they are authorized (have password).

## Important

This is __not__ a secure solution. Do __not__ use this to protect secure information.

## Caveats

- Anyone who knows HTML can reveal the content.
- Anyone who knows JavaScript can obtain the password.
- The form and content are only accessible if JavaScript is enabled.

## Use Case

1. User loads page.
2. Page content shows form.
3. User enters password into form.
4. Accurate submission shows restricted content and hides form.
5. Inaccurate submission shows error on form.

## Instructions

1. Edit the markup of the "Web Content Display" that has restricted content.
2. Wrap restricted content with container described in `tacc-insecure-access-form.html`.
3. After restricted content, add the password script described in `tacc-insecure-access-form.html`.
4. Set the password in the script.
5. Save the change.
6. Add a new "Web Content Display" to the page.
7. Choose the "(Insecure) Form to Access Restricted Content" web content.
8. Save.
9. Test.

Consider saving the password script in its own "Web Content" and hiding it via [`tacc-hidden-tags`](../advanced-styling/tacc-hidden-tags.md), like is done on [/about/conference-rooms](https://tacc.utexas.edu/about/conference-rooms).
