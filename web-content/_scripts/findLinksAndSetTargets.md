# TACC Hidden Style

## Purpose

(Within a given element) Open links with external URLs in a new window/tab.

### Use Case

Have a list of links (like an "Asset Publisher") that go to external sites.

## Instructions

### Be Able to Edit Content

1. Open a page while logged in as a user that can edit the page.
2. Ensure "Edit Controls" is checked.

### Prepare List of Links for Processing

3. From the "ASSET PUBLISHER" toolbar, click wrench icon a.k.a. "Options".
4. From the dropdown menu, click "Look and feel".
5. Via the tab navigation, open "Advanced Styling".
6. In "Enter your custom CSS class names.", enter "js-find-links-set-targets".
7. Save choice and close window.

### Load JavaScript to Process Links

8. Add "Web Content Display" to the page.
9. Show "JavaScript - Open Ext. Links in New Window (Find Links & Set Targets)".\*
10. Save choice and close window.

<sub>\* If such web content—or similarly-named web content—does not exist, create it with the content from [./findLinksAndSetTargets.html][script]</sub>

[script]: https://github.com/TACC/tacc-web-content/blob/main/web-content/_scripts/findLinksAndSetTargets.html
