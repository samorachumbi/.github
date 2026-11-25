# .github — the defaults behind every repository in this account

GitHub reads the community-health files in this repository as the default for every other repository in the
account that does not ship its own. So the way to reach a human, and the way to report a security problem,
are defined once here instead of being retyped per project.

| file | what it becomes |
|---|---|
| `SUPPORT.md` | the "Support" link GitHub shows in every repository's sidebar |
| `SECURITY.md` | the "Security policy" link, and the private reporting route |
| `.github/ISSUE_TEMPLATE/config.yml` | the contact links above the templates on every "New issue" page |
| `.github/ISSUE_TEMPLATE/bug_report.yml`, `feature_request.yml` | the default templates |

**A repository that defines its own file wins.** `dsh-media-reader`, for example, ships its own issue
templates and its own support routes, and GitHub ignores the defaults here for that repository — which is
the intended behaviour, not a bug.

The one address behind all of it: **samora@itikia.co.ke**.

*Reference: [creating a default community health file](https://docs.github.com/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).*
