# Security Best Practices Guide

## Up to Date Security (CVEs, necessary patches, etc)

A project with hardened security efforts  is up to date with endorsed methods of protecting and securing its code. By keeping current with publications and releases relevant to the security of your project, you can integrate hardening methods to a project as quickly as possible to prevent possible exploitation. 

As a maintainer:

- Are you subscribed to relevant CVEs?
- Are you subscribed to the security announcements mailing lists for all languages, libraries, and dependencies related to your project, tools and anything else relevant to it?
- Are updates are automated when possible/safe for project?

Available for open source projects are free SAST tooling, like on Github or OSS-Fuzz, that can be quickly and easily merged to provide up to date bug and vulnerability issues directly from your code to your inbox. Simply by turning on and utilizing available testing tools, low-hanging fruit can be identified and fixed, allowing further security efforts to focus on more difficult or complex findings. 

Enabling automation in updates when securely possible will allow your project to move forward through merges and releases in a timely manner. By granting users the opportunity to automatically update, you’re providing them the chance to easily update the security of the project.


## Self-check

- [ ] Subscribe to security related announcements for project
  - [ ] Languages
  - [ ] Libraries
  - [ ] Dependencies 
  - [ ] Tools
- [ ] Are you able to automate updates for your project?
- [ ] SAST tooling 
  - [ ] Available free tooling
  - [ ] https://analysis-tools.dev/ 
  - [ ] OSS-Fuzz
  - [ ] https://github.com/dependabot/dependabot-core 


|  |  |
| :---  | ---:  |
| [Back](./04-follow.md)  | [Next](06-kb.md)  |
