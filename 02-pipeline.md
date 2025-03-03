# Security Best Practices Guide

## A private security reporting pipeline with a designated handler¹²

We recommend that project teams have an easily accessible, dedicated form of communication to allow security researchers to securely and confidently contact the project team in case any vulnerabilities are identified. This could be, for example¹:

* Bug bounty programs such as BugCrowd, HackerOne, huntr.dev, Open Bug Bounty or Standoff
* [Private vulnerability reporting via Github](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability)
* An existing issue tracking system
* The generic "Contact Us" page on your website or Webform
* A social media account
* The most common method – a generic email addresses such as security@ or abuse@ with or without a PGP/GPG key for encryption

The most popular pipeline used by [Amazon](https://aws.amazon.com/security/vulnerability-reporting/), [Oracle](https://www.oracle.com/corporate/security-practices/assurance/vulnerability/reporting.html), [Intel](https://www.intel.com/content/www/us/en/security/security-practices/vulnerability-management/reporting-vulnerability.html) and many other large organizations is to provide an email address and a PGP key to encrypt your message. [Signal](https://support.signal.org/hc/en-us/articles/360007320791-How-can-I-report-a-security-vulnerability) is an example of an organization that provides the same but without the PGP key. Whether or not you provide a PGP key is up to you, but for those familiar it's use, it can be helpful in ensuring their messages are only read by the pipeline handler.

Who handles your pipeline and relevant reports is also important. You may want access to the project’s security reporting system to only be available to the software maintainers depending on the severity and type of project, as confidential submissions could potentially be shared or exploited. Alternatively, it may be wise to have at least some of that information shared with those working in the community to be able to recognize any relevant discussions that may emerge.

Regardless of the pipeline used, you should provide a SECURITY.md file in your open source repo to explain what constitutes a security vulnerability to the project and how to privately report it. You can also mirror this on your website at `/.well-known/security.txt` as per RFC 9116. An effective vulnerability disclosure policy should provide details on the scope (covered list of products and endpoints), the form of reporting, and other details important in the vulnerability disclosure process, including but not limited to: 

* Expected form of communication for vulnerability disclosure;
* Request for non-disclosure to third parties;
* Legal authorization for security research;
* Expected timeline of the process along with its description (this may include sharing the status of a reported vulnerability or its remediation with the reporter);
* Existence or absence of a bug bounty program, along with its conditions; and
* Description of the expected form of the report (impact, steps for reproducing the issue or proof-of-concept exploit, and root cause analysis, if possible).

If applicable, we recommend that project teams consult their legal team to ensure compliance with the applicable law. 


## Self-check

- [ ] Decide permissions
- [ ] Choose who will handle it
- [ ] Consider who else should have access and how much
- [ ] Prepare the pipeline (email, signal, etc)
- [ ] Make public
- [ ] Announce to the community
- [ ] Include pipeline link in security or general documentation
- [ ] Add SECURITY.md file to repo (and security.txt to website if applicable)

|  |  |
| :---  | ---:  |
| [Back](./01-introduction.md)  | [Next](03-response.md)  |

*¹ Vulnerability Disclosure Policy recommendations contributed by Least Authority*

*² This section also contains a modified version of "Vulnerability Disclosure Cheat Sheet" by Cheat Sheets Series Team, released with a CC BY-SA 4.0 license.*
