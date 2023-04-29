# Security Policies And Procedures

> **Note**
> By interacting with [@svengreb][19] projects, organizations, and their communities you agree to abide to its [code of conduct][16] and follow [general open source contribution guidelines][17] and [etiquettes][18]!

This document outlines security procedures and policies for security vulnerabilities in [@svengreb][19] projects.

The security of projects is taken seriously, which includes all [@svengreb][19] (source code) repositories as well as any managed organization, or organizations this account is part of with a maintainer-like role, and their communities.

If you believe you have found a security [vulnerability][2] [^1] in any repository that meets the [definition of vulnerabilities][1], please report it as described below.

## Scope

Reports should only be related to…

- projects within the [`@svengreb` GitHub account][19].
  Only code that is actually owned by [@svengreb][19], or any managed organization, is supported while issues related to upstream projects, e.g. plugins or extensions, must be reported to the corresponding maintainers or companies of the upstream project. Support to report issues to the upstream team might be provided, but we are **not responsible for security vulnerabilities in upstream projects in any way**.
- any (GitHub) organization managed by [@svengreb][19], or organizations this account is part of with a maintainer-like role, and their communities.
  The same scope applies like for projects within the [`@svengreb` GitHub account][19], but additionally the task of the security vulnerability handling and disclosure process is part of the corresponding maintainer team when the project is also maintained by a community. Of course [@svengreb][19] will aid in closing issues as quickly as possible, but the main administration lies with the respective maintainers.

## Reporting Security Issues

> **Warning**
> Never report security vulnerabilities through public GitHub issues or any other public (communication) channel or platform!

Instead, please report security vulnerabilities by either…

- …[using GitHub‘s “Private Security Vulnerability Reporting“ system][3].
- …sending an email to [security@svengreb.de][4], if you prefer to submit without logging in or creating a GitHub account. If possible, please encrypt your email with Sven Greb‘s [Age][12] [^4] or [PGP][13] [^5] ([GPG][15]) key where both can be found [in the GitHub organization `.github` repository][14] [^6] [^7] and inlined below this list.
- …writing a private message in [Matrix][5] to [`@svengreb:matrix.org`][6] or join the official Matrix space of the specific project to ask for further help to submit a report. Alternatively, [contact `svengreb#2186`][20] on [Discord][21] or any verified community moderator or manager in official servers of specific projects.
  Please note that both [community platforms][7] are public areas. When escalating to that address please do not discuss the issue in public, e.g. no private messaging chats, but simply ask for ways to get a hold of someone from the project team if both direct contacts listed above are not available at the moment.

Public keys for encrypted communications:

<details>
  <summary><em>Age</em></summary>
  <pre>
    <code>age1ul0s8ctrsdydx68qs3t66ev5uhq700dt49pnqz3enh59qcrcyvasq7gvw8r</code>
  </pre>
</details>

<details>
<summary><em>PGP</em> (<em>GPG</em>)</summary>
<pre>
<code>
-----BEGIN PGP PUBLIC KEY BLOCK-----

mDMEZDvNbhYJKwYBBAHaRw8BAQdAAEZ+vBmlMnqdThx/vffo1TNpsFY0GxeJLelk
tONB+ua0JVN2ZW4gR3JlYiAoc3ZlbmdyZWIpIDxtZUBzdmVuZ3JlYi5kZT6IkwQT
FgoAOxYhBJq2ns8GnhxoSWFy9p7D3JDapH2qBQJkO81uAhsDBQsJCAcCAiICBhUK
CQgLAgQWAgMBAh4HAheAAAoJEJ7D3JDapH2qvn8A/0+U0gGqHM8OIRBtw0UPqaop
x5ojQ1FPZus5Upbcy+YaAP0YwCVnz4qrg9S/rQ5G0igRMidCl1InVRJ6ict3oTf5
CLg4BGQ7zW4SCisGAQQBl1UBBQEBB0AU2br3WMbWE37vQRI1xC9f1qq5HBWY9cYc
SUO7D0wKEQMBCAeIeAQYFgoAIBYhBJq2ns8GnhxoSWFy9p7D3JDapH2qBQJkO81u
AhsMAAoJEJ7D3JDapH2qFHUBAPFMiNWO7iiv0j7Syj5RTWHE15wb4YbV2MKJ4bqr
YvqtAQDJPujvk/2c0Og4nUGs0lBvU9dIicc5Va/JyjDAIK0JBg==
=Kb0/
-----END PGP PUBLIC KEY BLOCK-----
</code>

</pre>
</details>

Please include [as much information as possible][11], using the questions listed below as a guideline, to help us better understand the nature and scope of the possible issue and help us triage the report more quickly:

- Type of issue (e.g. buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the manifestation of the issue
- The location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit the issue

Note that all communications, following the global standard, must be in English to ensure that the process can take place with as few language barriers as possible and to avoid possible translation problems during the process.

## Public Disclosure Process

Confirmed vulnerabilities will be investigated and patched as quickly as possible and rolled out to affected users through a [patch][8] or [minor][9] release version, depending on the status of the current project development, release cycle process and ways to backport to other supported versions.

Resolved security vulnerabilities will be made public as [advisory][10] [][^2] [][^3] on GitHub and, in most cases, additionally announced via other official communication channels and platforms. This might also include a guide on how to apply mitigating steps to aid users in closing the security vulnerability as simply as possible.

<p align="center">
  <picture>
    <source srcset="https://raw.githubusercontent.com/svengreb/assets/main/static/images/elements/separators/logo/footer/dark/spaced.svg?sanitize=true" width="100%" media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)" />
    <source srcset="https://raw.githubusercontent.com/svengreb/assets/main/static/images/elements/separators/logo/footer/light/spaced.svg?sanitize=true" width="100%" media="(prefers-color-scheme: dark)" />
    <img src="https://raw.githubusercontent.com/svengreb/assets/main/static/images/elements/separators/logo/footer/dark/spaced.svg?sanitize=true" width="100%" />
  </picture>
</p>

<p align="center">
  Copyright &copy; 2016-present <a href="https://www.svengreb.de" target="_blank">Sven Greb</a>
</p>

<p align="center">
  <a href="https://github.com/svengreb/styleguide-javascript/blob/main/license" target="_blank">
    <img src="https://img.shields.io/static/v1.svg?style=flat-square&label=License&message=MIT&logoColor=eceff4&colorA=4c566a&colorB=88c0d0" />
  </a>
  <a href="https://www.svengreb.de">
    <img src="https://img.shields.io/static/v1.svg?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAABmJLR0QA/wD/AP+gvaeTAAABMklEQVQ4jcWQvUoDQRRGz52s5IfVIiDWPkGKFFaCIVaGdIagjcFAwICFb7DvIK6QQlNpY2UQLMQVBbEQ0SewFkGbKCQmOzaTJay7/lR+zTAf9xwuF/47Mv45rdezqWEq72v/RWZnHgqOMwDwHMfSj085JSqb6Pu38we7r18E3nqzhmYbsE11rxKsAvhDfQiSM30XYbOw57YDwfnaRl6U3ABWaMNn806H+oGPzBX3d+4UgChZiYBHYBgGsBLoKoAyhR0x9G20Zmpc4P1ZoMQDcwMNclFrdhBKv6M5WWi7ZQGtjEUn35IV4OwnVjSX/WGmKqCDDUa5rmyle3bvGFiMg3WGUsF1u0EXHoqTRMGRgkAy2eugKZrqijRLYThWANBpNDL2h3UE0J0YLJdbrfe42f/NJ0wqY7/KcXKPAAAAAElFTkSuQmCC&label=lovely%20crafted%20in&message=Germany&colorA=4c566a&colorB=88c0d0" />
  </a>
</p>

<!-- +--- Footnotes +--- -->

[^1]: https://csrc.nist.gov/glossary/term/vulnerability
[^2]: https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/about-coordinated-disclosure-of-security-vulnerabilities
[^3]: https://en.wikipedia.org/wiki/Coordinated_vulnerability_disclosure
[^4]: https://age-encryption.org
[^5]: https://www.openpgp.org
[^6]: https://github.com/svengreb/.github/blob/main/data/svengreb.age.txt.pub
[^7]: https://github.com/svengreb/.github/blob/main/data/svengreb.gpg.asc

<!--lint disable no-duplicate-definitions-->

<!-- This is required due to an false-positive match by remark which does not detect that GFM footnotes with the same number are not identital identifiers -->

[1]: https://en.wikipedia.org/wiki/Vulnerability_(computing)#Definitions
[2]: https://en.wikipedia.org/wiki/Vulnerability_(computing)
[3]: https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerabilitys
[4]: mailto:security@svengreb.de
[5]: https://matrix.org
[6]: https://matrix.to/#/@svengreb:matrix.org
[7]: https://github.com/svengreb/.github/blob/main/support.md#updates-communities--content

<!--lint enable no-duplicate-definitions-->

[8]: https://semver.org/#spec-item-6
[9]: https://semver.org/#spec-item-7
[10]: https://docs.github.com/en/code-security/security-advisories/repository-security-advisories/about-repository-security-advisories
[11]: https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/best-practices-for-writing-repository-security-advisories
[12]: https://raw.githubusercontent.com/svengreb/.github/main/data/svengreb.age.txt.pub
[13]: https://raw.githubusercontent.com/svengreb/.github/main/data/svengreb.gpg.asc
[14]: https://github.com/svengreb/.github/tree/main/data
[15]: https://gnupg.org
[16]: https://github.com/svengreb/.github/blob/main/code_of_conduct.md
[17]: https://opensource.guide/how-to-contribute
[18]: https://opensource.how/etiquette
[19]: https://github.com/svengreb
[20]: https://discordapp.com/users/448543165021159424
[21]: https://discord.com
