# Known Issues

## Web Content

There could be a discrepancy between the CMS web content and the repository file content; some examples and explanations are documented.

All faults described assume that the current developer has not performed user error.

### Web Content Markup Moved HTML Tags

When HTML5 is placed inside Web Content, the saved version has the HTML5 markup moved to outside their original location.

_Maybe, CMS parses HTML as HTML4, and cannot parse (but does not delete) HTML5 tags._

### Web Content Markup has Different Formatting, But Same Markup

When content is saved in the CMS, the resulting markup has whitespace and attribute order changed to meet CMS standards.

_If this occurs upon saving the latest CMS content, it is because the last developer to commit changes to the file in the repository did not save CMS-formatted markup._
