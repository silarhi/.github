# Security policy

This policy covers the open-source packages published by SILARHI on [Packagist](https://packagist.org/packages/silarhi/)
and [npm](https://www.npmjs.com/org/silarhi), unless a repository has its own `SECURITY.md`.

## Supported versions

Security fixes go to the latest release of each package's current major version. Older majors only get a fix when the
upgrade path is hard; the advisory says so when that happens.

## Reporting a vulnerability

Please do not open a public issue, discussion or pull request for a security problem.

Report it privately through GitHub instead: open the **Security** tab of the repository, then **Report a
vulnerability**. If you can't use GitHub, email [dev@silarhi.fr](mailto:dev@silarhi.fr).

Include the package and version, what an attacker can do, and the steps or a proof of concept that shows it.

## What happens next

- We acknowledge the report within 5 working days.
- We confirm the issue, agree on a severity with you, and prepare a fix in a private fork.
- We release the fix, then publish a GitHub security advisory (with a CVE when it applies), which also notifies
  Packagist, npm and Dependabot users.
- We credit you in the advisory, unless you prefer not to be named.
