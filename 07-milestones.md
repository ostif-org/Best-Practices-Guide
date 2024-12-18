# Security Best Practices Guide

## Milestones in mind for when you need to increase security efforts (e.g. harden further, get an audit, etc)

Maintainers ought to think ahead about when security efforts can be most impactful for their project. Alterations to a code’s function, large releases with new code, or the addition of new third party libraries are all mile markers to consider when planning major security improvements. 

Best security efforts can be determined by changed aspects of a given project, such as its attack surface, exposure to the Internet of Things, or whether it stores sensitive or uses private data. Improvements or releases to a project that change permissions or features can expose a project to new vulnerabilities or bugs that were incapable of exploitation earlier.

While laborious and time consuming, this kind of succession planning and drafting can not only guide project’s security work timelines but also strengthen the structure and outline paths to the project’s future objectives in ways that can be actionable for future reference and development. When you can cut down on releases, projects eliminate bloat and load on users as well as streamline features and their integration. This promotes a healthier security environment by resolving more vulnerabilities in fewer updates for users. 

One option for a security engagement in the development timeline is to source a security audit. Utilize Least Authority’s [Audit Preparation checklist](https://leastauthority.com/blog/audit-preparation-checklist-5-important-steps-to-prepare-for-a-security-audit/) as an exercise to see where your project can improve its best practices and if an audit is the right choice for your organization.



## Self-check

- [ ] Releases
  - [ ] Are there major updates to the function or code library?
  - [ ] How far ahead are releases planned for? 
  - [ ] Will there be new third party libraries or projects?
- [ ] Cryptography
  - [ ] Does your project use cryptography?
  - [ ] How does it use cryptography
  - [ ] Library
  - [ ] Self-rolled
- [ ] Exposure
  - [ ] Does your project require internet access?
  - [ ] How is it hosted?
  - [ ] Does it store any user PII?



|  |  |
| :---  | ---:  |
| [Back](./06-kb.md)  | [Next](08-what-next.md)  |
