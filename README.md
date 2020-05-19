# TACC Website Content

This is a project to maintain revision history for Liferay Portal [Web Content][lr-web-content] in the [TACC Website][tacc-website], but that are independent of the Liferay Portal infrastructure.

It was created Nov 2019 by [Wesley B.][user-wb] so that the he could more easily perform, track, and review his changes to the website.

[lr-web-content]: https://portal.liferay.dev/docs/6-1/user/-/knowledge_base/u/web-content-management "Liferay Portal: Web Content Management"
[user-wb]: https://github.com/tacc-wbomar "Wesley B. of Communications, Media & Design"
[tacc-website]: https://www.tacc.utexas.edu "TACC Public Website"

## Usage

1. Find the repository file content matching the relevant CMS web content.\*
2. Compare CMS web content to repository file(s) content.
    1. Replace repository file(s) content with web content.
    2. Compare differences by reviewing the `git diff` of the repository file(s).
    3. Resolve unexpected conflicts (for help, see [example conflicts][doc-conflicts]).
3. Update repository file(s) content.
4. Test repository file(s) content as CMS web content.
5. Copy final working CMS web content to repository file(s).
6. Commit and push changes to repository file(s).
7. Save final working content as CMS web content.

\* The directory of the page (in [Control Panel "Pages"][cp-pages] hierarchy) on which the web content exists is the directory in which you should find the relevant repository file.

[doc-conflicts]: ./docs/content-conflicts.md "Example Content Conflicts"
[cp-pages]: https://www.tacc.utexas.edu/group/control_panel/manage?p_p_id=156&p_p_lifecycle=0&p_p_state=maximized&p_p_mode=view&doAsGroupId=1084364 "Control Panel > Website > Pages > Public Pages"

## Add Files

See [`./content/README.md`](./content/README.md).

## Markup Generation Utilities

See [How To - Legacy TACC - Markup Generation Utility](https://confluence.tacc.utexas.edu/x/AYGDC).

## Repository History

The first 300 commits of this repository are from a prior BitBucket repo that contained what is now multiple repositories imported from that original repository:

- [tacc-web-content](https://github.com/tacc-wbomar/tacc-web-content)
- [tacc-web-staff-dir](https://github.com/tacc-wbomar/tacc-web-staff-dir)
- [tacc-web-jobs-page](https://github.com/tacc-wbomar/tacc-web-jobs-page)
- [tacc-web-sc19-page](https://github.com/tacc-wbomar/tacc-web-sc19-page)
