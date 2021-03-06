---
title      : "Software Testing"
date       : 2019-09-05T12:40:15+02:00
publishdate: 2019-09-06T12:40:15+02:00
draft      : false
comments   : true
weight     : 5
revision   : 0
series:
- myLearning
categories:
- testing
tags:
- test
---

> Test automation is software development

## What do s/w testers do?

Programmers test code, testers test applications

> Much of the cost of software development is maintenance[^1]

## How to earn money as s/w tester?

1. Croudtesting
2. [Bug bounty](https://en.wikipedia.org/wiki/Bug_bounty_program)
   1. https://www.guru99.com/bug-bounty-programs.html
   2. https://www.bugcrowd.com/bug-bounty-list/

>  Why do people abandon testing projects?
> the most common answer is that the tests quickly became brittle and
too costly to maintain

## Test Case

### Good test case

> How can you make your ATC scalable for future?
> How can you make tests more scalable than they already are?

* Avoid dependencies b/w tests
  * VAlids login, change password, then Login with new password
* move LOGIC to LIBRARY KEYWORD
* Creating NEW Tc should be easy using context Keywords
* One TC should test **only** one thing
* single level of abstraction principle
* Use `polling` instead of `waits`
* Remove incidental details from TC[^1]
* Workflow test-cases
  * Precondition
  * Action
  * Verification
  * Cleanup
* Data-driven tests
  * One high-level keyword per test

## Software Testers to look upto

* Elisabeth Hendrickson
*

## New Direction

* RPA - Robot process Automation[^6]
  * [Blueprism](https://www.blueprism.com/)
  * [RPA tools](https://www.guru99.com/robotics-process-automation-tools.html)
  * Pick any task and ask this question, what would I have to do to automate it?
* Usually requires FLOWCHARTS to decide workflow paths
* Python Automation | RPA
  * context and scope of application

## Design Testing

1) Functionality Testing
   1) Look for broken links on page
      1) External Links
      2) Incoming links
      3) Anchor and mailTo links
   2) HTTP codes for URL paths
   3) Image Validations
   4) What happens if a user deletes their cookies while visiting the site?
   5) What happens if a user deletes cookies following a site visit?
2) Usability testing
   1) TimeZone config is respected?
3) Interface testing
   1) All interface components are actively responding
4) Compatibility testing / Crossbrowser testing
5) Performance testing
6) Security testing
   1) Javascript INjections in forms
   2) Cookies Manupulation
   3) ProxyServer testing
   4) Credential Encryption / Man in the middle attack
   5) Open ports on server
   6) Network Vulnability Attacks
   7) Webframework specific exploits

## Questions?

1. which companies are succeding with testing and test automation?
2. Worlds best s/w testing professionals[^2]
3. Best QA companies[^4] in the World?[^3]
4. Interesting[^5]


### Footnotes

[^1]: http://dhemery.com/pdf/writing_maintainable_automated_acceptance_tests.pdf
[^2]: https://www.aditiconsulting.com/worlds-top-software-testing-professionals/
[^3]: https://medium.com/datadriveninvestor/which-are-the-best-software-testing-and-quality-assurance-companies-in-the-world-in-2019-90f85db7fe47
[^4]: https://hackernoon.com/top-20-software-testing-companies-worth-your-attention-in-2019-f8cc8899dc11
[^5]: [The Periodic Table Of Data – Pipe Dream or Possibility?](https://www.ministryoftesting.com/dojo/series/the-testing-planet-archive/lessons/the-periodic-table-of-data-pipe-dream-or-possibility)
[^6]: https://en.wikipedia.org/wiki/Robotic_process_automation
