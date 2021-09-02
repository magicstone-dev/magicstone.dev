---
layout: page
title: Why C4
permalink: /why-c4/
---

## Why C4?

Social media seems to be changing everything in the world except software development. Yes, there are memes and GitHub repos have stars, but we developers haven’t focused enough on building communities around software.

Conway’s Law says that software mirrors the kind of organization that creates it. If you give a project to a team of five it’ll be organized into four modules. Naturally somebody has to manage. In the federated free/libre and open source software community, where contributors are as distributed as the instances they spawn, most projects still run however via an ad hoc, yet centralized model.

It typically starts with a dream, made real by a developer joined perhaps by a few friends. The software gets reviewed by a blog, used by an influential project or company and with attention comes a stream of contributions by the community. The team manages this flow the best they can. Tooling like GitHub helps by suggesting a contributing doc, license and code of conduct but at that point much is left to chance and personal experience. Here’s the typical community software development process that emerges.

<img src="https://user-images.githubusercontent.com/38776/131413637-1064d565-86fd-4c04-ab75-3aca5d84e626.png" width="500" />

It all starts with a bug report which goes into the issue tracker. There a developer grabs hold of it because it is critical to them or an interesting problem or they instantly have an idea for a solution. The developer codes it up and tests it then submits a patch, known on GitHub as a pull request. The project’s reviewers examine the patch and request changes. The comments say something like “add a test”, “try this better approach” or “fix coding style”. The developer addresses the requested changes with an update to the PR, earning an approval from the reviewer. At this point, someone with commit access to the repo merges the code and closes the issue.

This process involves four different personas and five or more steps over a number of days, but sometimes weeks or months. In addition the review with changes requested loop involves communication about code, which is very expensive from a developer and reviewer standpoint. Depending on the details, it can take hours and lots of mental effort to review a patch. Every step in any process has failure modes and here delays and differences of opinion can be highly disruptive to participants and the community in which they operate.

<img src="https://user-images.githubusercontent.com/38776/131413664-a426ce3b-720d-43d5-ac4c-b45ac8d652e1.png" width="400" />

Above is another process which begins similarly with a problem that goes into an issue tracker. The reporter and community both are encouraged to discuss new problems there to determine if they are accurate and valuable. If not, they are refined and proven until there is consensus that this problem is now valid. A developer who visits the issue tracker, will then see a list of valid problems waiting to be solved. Again the developer chooses an issue, codes and tests a patch and submits a pull request. In the final step, a maintainer checks that the PR addresses a valid problem and merges the code.

This second process involves four different personas and four steps. The most time is spent by community members discussing whether the right problem is being addressed and what kind of value a solution would provide to users. When a developer gets involved they have certainty that any reasonable solution they offer will be accepted if it passes automated testing. The lack of a review with changes requested loop means we save on communication plus the time and effort of a reviewer mentally and sometimes literally running the code in the patch.

Feature\Process|**Typical process**|**C4**
:-----:|:-----:|:-----:
Community involvement|ⓧ|✅
Code review|✅|ⓧ
Automated testing|✅|✅
Problems vetted|ⓧ|✅
Steps|5+|4
Personas|4|4

While the first process is centralized on reviewers and maintainers who operate via adhoc process, the second can be completely distributed as long as maintainers follow the simple rules spelled out in the contract. The first process concentrates control over the code to a handful of people while the second minimizes owner responsibility to whether or not the rules are being followed. The second process is also more inclusive of the community, which is mostly not developers, reviewers, and maintainers, but users coming from every place and every background.

If we want software that can tackle markets which are distributed, always-on, and decentralized, then we need communities that have those same characteristics. Such communities can only grow if the process enables them to work with minimal central control and maximum opportunity for every member to contribute what they can.

Social media seems to be changing everything and with the C4 process, it may finally be time for it to change development of the software itself.
