# TACC Hidden Style

## Purpose

Hide a "Web Content Display" from non-editor users.

### Use Case

1. Have an isolated (thus reusable) `<style>` tag in a "Web Content Display".
2. Add that "Web Content Display" to a page __above__ the content it styles.
3. Unless this advanced styling is used, an unsighlty gap appears.
4. Add visible text to describe the "Web Content Display" to editors.
5. Unless this advanced styling is used, that text appears for website users.

## Instructions

1. Open a page while logged in as a user that can edit the page.
2. Ensure "Edit Controls" is checked.
3. From the "WEB CONTENT DISPLAY" toolbar, click wrench icon a.k.a. "Options".
4. From the dropdown menu, click "Look and feel".
5. Via the tab navigation, open "Advanced Styling".
6. Add the class "tacc-hidden-tags" as needed:
    - __A.__ To hide the entire content, in "Enter your custom CSS class names.", enter "tacc-hidden-tags".
    - __B.__ To hide just some content, add class "tacc-hidden-tags" only to such content.
7. In "Enter your custom CSS.", paste the contents of [`./tacc-hidden-tags.css`](./tacc-hidden-tags.css).
8. Save choice and close window.
