# Security Best Practices Guide

## Follow best practices for development, build pipelines, etc.

A project should ideally participate in recommended practices by the security community that can improve its security health. Such efforts will nurture the code’s health as well as harden it against attacks. With regards to testing, dependency handling, and continuous integration, the following steps can help prevent incidents and unpatched vulnerabilities in release versions: 

- A wide range of testing (e.g., adding integration testing, testing edge-cases and properties (fuzzing and property-based testing), and adding integrated testing in CI;
- Adhering to best practices in code review in the development process (utilizing GitHub pull requests and requiring code reviews before merging);
- Reviewing and updating dependencies, as well as integrating dependency checks and static analysis in CI, wherever possible;
- Keeping up with any security news within the ecosystem and any other utilized platforms or technologies to detect potential threats early; and
- Reviewing the internal operational security, including, for example, internal best practices on handling secrets, security of development devices and infrastructure, as well as the storage and security of user data.

Complying with standards and practices that are self-guided and promote healthy and updated code can strengthen a project’s security and processes and defend against low risk vulnerabilities, saving maintainers time and effort in the long run by reducing security risks and reports as well as providing clear benchmarks and systems to grade projects.

If feasible for your project, consider enabling [reproducible builds](https://reproducible-builds.org/). Projects can participate in the open source tenants of transparency and reproducibility by allowing the ability to prove nothing has been injected during compilation via comparison to the original build. Continuing comparisons as a part of security, projects can adapt the security processes of projects with similar functionality to them. Seeing what other maintainers have through reviewing project documentation can inspire you to take further action for your own project. 

Taking advantage of the open source ecosystem that prioritizes transparency and transformation, projects should adopt best practices that can be easily implemented and updated, appropriate to function, and generate long-term positive impact. Organizations that promote open source best security practices like Linux Foundation, OWASP, OpenChain, TODO, and the Best Practices for OSS Developers Group (run by OpenSSF) all provide free resources to promote widespread adoption of tested policies. 

## Self-check

- [ ] Determine viability of allowing reproducible builds
- [ ] Verifiable security
- [ ] Copy similar projects
- [ ] Do Self Guided Security Reviews
- - [ ] [OpenSSF Security Scorecard](https://github.com/ossf/scorecard)
- - [ ] OWASP Application Security Verification Standard


|  |  |
| :---  | ---:  |
| [Back](./02-pipeline.md)  | [Next](04-follow.md)  |

*¹ This section topic and recommendations contributed by Least Authority*