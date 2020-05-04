# TACC Website Content - To Do List

## Documentation

1. Move some `README.md` content to Confluence.

## Styles

1. Fix redundant styles for `<abbr>` tag:
    ```css
    /* TODO: Add this to global CSS */
    /* FAQ: The global CSS styles this with a border bottom,
            but neglects to remove browsers' dotted underline style
            (has style: Firefox, Chrome…; no style: Safari…) */
    abbr[title] { text-decoration: none; }
    ```

## Content

1. For EPIC pages, replace abbreviations for CS with the words computer science.
1. For EPIC pages, use abbreviations and/or links for project/partner names.
