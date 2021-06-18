# TACC Website Content

This is a project to maintain revision history for Liferay Portal [Web Content][lr-web-content] in the [TACC Website][tacc-website], but that are independent of the Liferay Portal infrastructure.

_This repo was created Nov 2019 by [W. Bomar][user-wb] so that the he could more easily perform, track, and review his changes to the website (in the absence of Liferay IDE¹)._

> ¹ Either [via Maven][lr-ide-maven] or [via Developer Studio][lr-ide-studio].

[lr-ide-maven]: https://help.liferay.com/hc/en-us/articles/360017872172-Using-Liferay-IDE-with-Maven "Liferay IDE with Maven"
[lr-ide-studio]: https://help.liferay.com/hc/en-us/articles/360018151491-Introduction-to-Liferay-IDE-and-Liferay-Developer-Studio "Liferay IDE and Liferay Developer Studio"
[lr-web-content]: https://portal.liferay.dev/docs/6-1/user/-/knowledge_base/u/web-content-management "Liferay Portal: Web Content Management"
[user-wb]: https://github.com/tacc-wbomar "Wesley B. of Communications, Media & Design"
[tacc-website]: https://www.tacc.utexas.edu "TACC Public Website"


## Directories

Into the appropriate directory add the content from the respective source.

| Directory | Control Panel Source |
| :- | :- |
| `advanced-styling` | Web Content Display instance¹ |
| `web-content` | [Web Content][cp-wc-content] |
| `structures` | [Web Content > Structures][cp-wc-structures] |
| `templates` | [Web Content > Templates][cp-wc-templates] |

> ¹ In the "Advanced Styling" tab of "Look and Feel" on any "Web Content Display" instance. This is manually duplicated as needed.

[cp-wc-content]: https://www.tacc.utexas.edu/group/control_panel/manage?p_p_id=15&p_p_lifecycle=0&p_p_state=maximized&p_p_mode=view&doAsGroupId=1084364&tabs1=web-content "Control Panel > Website > Web Content > Web Content"

[cp-wc-structures]: https://www.tacc.utexas.edu/group/control_panel/manage?p_p_id=15&p_p_lifecycle=0&p_p_state=maximized&p_p_mode=view&doAsGroupId=1084364&tabs1=structures "Control Panel > Website > Web Content > Structures"

[cp-wc-templates]: https://www.tacc.utexas.edu/group/control_panel/manage?p_p_id=15&p_p_lifecycle=0&p_p_state=maximized&p_p_mode=view&doAsGroupId=1084364&tabs1=templates "Control Panel > Website > Web Content > Templates"


## Usage

1. Find the content to edit.
2. Compare CMS web content to repository file(s) content.
    1. Replace repository file(s) content with web content.
    2. Compare differences by reviewing the `git diff` of the repository file(s).
    3. Resolve unexpected conflicts (for help, see "Known Issues").
3. Update repository file(s) content.
4. Test repository file(s) content as CMS web content.
5. Copy final working CMS web content to repository file(s).
6. Commit and push changes to repository file(s).
7. Save final working content as CMS web content.

### Known Issues

See [`./docs/known-issues.md`](./docs/known-issues.md).

## Markup Generation Utilities

See [How To - Legacy TACC - Markup Generation Utility](https://confluence.tacc.utexas.edu/x/AYGDC).


## Repository History

The first 300 commits of this repository are from a prior BitBucket repo that contained what is now multiple repositories imported from that original repository:

- [tacc-web-content](https://github.com/tacc-wbomar/tacc-web-content)
- [tacc-web-staff-dir](https://github.com/tacc-wbomar/tacc-web-staff-dir)
- [tacc-web-jobs-page](https://github.com/tacc-wbomar/tacc-web-jobs-page)
- [tacc-web-sc19-page](https://github.com/tacc-wbomar/tacc-web-sc19-page)
