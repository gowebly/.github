# Security Policy

## Supported Versions

We commit to publishing security updates for the version of all `gowebly` 
projects currently on the `main` branch.

## Reporting a Vulnerability

To report a vulnerability, please e-mail 
[koddr.me@gmail.com][vic_shostak_email] with a description of the issue, the 
steps you took to create the issue, affected versions, and if known, 
mitigation for the issue.

We should reply within five working days, probably much sooner. 

> _Unfortunately, we do receive spam at this address, as well as well-meaning 
but ultimately misguided reports that do not represent issues for which this 
process is appropriate._

We use GitHub's security advisory feature to track open security issues. You 
should expect a close collaboration as we work to resolve the issue you have 
reported. Please reach out to [koddr.me@gmail.com][vic_shostak_email] again 
if you do not receive prompt attention and regular updates.

## Process

This section describes the process used by the `gowebly` project team when 
handling vulnerability reports.

Vulnerability reports are received via the 
[koddr.me@gmail.com][vic_shostak_email] e-mail alias. Certain team members 
who have been designated the "vulnerability management team" receive these 
e-mails. When receiving such an e-mail, they will:

1. Reply to the e-mail acknowledging its receipt, cc'ing
   [koddr.me@gmail.com][vic_shostak_email] so that the other members of the 
   team are aware that they are handling the issue. If the e-mail does not 
   describe an actual vulnerability, the process will stop here.
2. Create a new security advisory for `gowebly` project. One must be one of the 
   repo admins to do this. Vulnerability management team members who are not 
   also a repo admin will reach out to the repo admins until they find one 
   who can create the advisory. The repository administrator, who is also a 
   member of the vulnerability management team, is [@koddr][vic_shostak_url].
3. [Add the reporter][github_reporter_url] to the security advisory so that 
   they can get updates.
4. Inform the relevant team lead, adding them to the security advisory.

As the fix is being developed, they will then reach out to the reporter to 
ask them if they would like to be involved and whether they would like to be 
credited. For credit, the GitHub security advisory UI has a field that 
allows contributors to be credited.

When the issue is resolved, they will contact the release team and our PR 
team to coordinate the publication of the security advisory.

Security issues have the priority level. We attempt to fix them as quickly 
as possible.

_For more information on security advisories, see
[the GitHub documentation][github_documentation_url]._

<!-- Links -->

[vic_shostak_email]: mailto:koddr.me@gmail.com?subject=Security+issue+for+gowebly+project
[vic_shostak_url]: https://github.com/koddr
[github_reporter_url]: https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/adding-a-collaborator-to-a-security-advisory
[github_documentation_url]: https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/managing-security-vulnerabilities-in-your-project
