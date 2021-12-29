---
layout: no-title-page
title: FAQ
permalink: /faq/
---
## Frequently Asked Questions

# What is the purpose of Magic Stone in practical terms?

The project exists to solve two problems. One is not enough contributors (docs, code, testing) on fediverse projects and the other is high-friction, slow development processes. Slow processes turn off contributors so I want to take merge time for patches from what can be weeks or months down to hours and days.

The [C4 RFC](https://rfc.zeromq.org/spec/42/) defines a process where the merge speed depends on describing and valuing problems rather than reviewing and approving code. With this faster process, the hope is the community will grow and overall speed and quality will increase.

# How did this start?

The story started early in 2021 when we started thinking more seriously about social media and what a better future for it might be. We came to the conclusion that since nobody really knows, experimentation was key. This led to a survey of open source social networking projects that might be good platforms for experimentation. Mastodon came out as top candidates.

At that point, we realized it’s not only a problem of not knowing what better social media looks like, but also how to run a successful open source software project. That’s when we found Pieter Hintjens and the Collective Code Construction Contract (C4) that he developed with the ZeroMQ community. The core idea is that community is primary, not technology. Only a strong community can develop and maintain software for the long-term that will meet the needs of the market.

It’s at that point that Mastodon was forked and Magic Stone was formed. C4 hadn’t to our knowledge been applied to social media so part of the opportunity for this community is to test whether it can work. In order to prove anything from a scientific standpoint, we need reproducible results so we forked diaspora* as well. Since then we’ve been solving problems found by the community through using the software. 

# What is C4?

It’s short for Collective Code Construction Contract. A contract, a protocol, a set of rules to a game we’re playing, C4 is for making accurate software on the internet. You can [read the contract here](https://rfc.zeromq.org/spec/42/).

Who defines accurate? The market. We’re all part of different markets, the supermarket where we get food, employment market when we have to find a job, the housing market. A market brings a diversity of wants and skills and creates a place where success means satisfying some chunk of the population. The more you can satisfy the more successful the project.

More important than the game or the software or the market, is the community. Ours is very small right now. There are maybe half a dozen of us who are interested in Magic Stone. Many more are using C4 but it’s not possible to count. Certainly in dozens of ZeroMQ projects where it started but we'll have to do research to know more.

C4 is community-centric software development. We focus discussion almost entirely on problems and accept solutions freely. Automation and free collaborative platforms make it easy for anyone to help but ultimately it’s about laying out some rules then letting everyone do what they do best, alone or in groups of their choosing.

# Do you plan to federate diaspora\* and Mastodon or implement feature X? Where is your roadmap?

Under C4 we don’t have a roadmap, or assigned tasks, or releases. Our issue trackers are populated with interesting problems. Developers excited by any one of them are invited to submit pull requests. We find this a liberating way to work, never having a deadline, free to work alone or in groups and appreciating progress as it comes.

# Merging code is great and all but what about quality?

It is our belief that quality comes only from diverse community involvement. Typical open source project maintenance is places a heavy burden on the maintainer who must manage code reviews and make judgements about patches. Under C4, code is merged based on trust. The trust is there either way. Open source projects have been subtly backdoored in the past. It's true that our process makes it easy for anyone to add code to our projects and some might see this as a vulnerability.

# How are Ecko and Acropolis different from what upstream/other projects are doing?

The projects we've forked have done amazing work and created systems that are in use by many, many people. Magic Stone today is about building a community. This community runs each of its projects independently using the Collective Code Consctruction Contract. It is our hypothesis that every project becomes more successful through community-drive development. 

# Is C4 just for developer-centric projects?

The history of how C4 has been used was in ZeroMQ and that is a very developer-centric community, but we don't see any reason why it can't work just as well for other projects. People are the common ingredient in all human endeavor. We are excited to be stress-testing C4 in the social networking space.

The usual pattern for an open source project places developers in privileged positions of writing code, judging others code and which bugs get fixed and features resolved. A handful of very large projects broaden the opportunity to have a voice through design and UX teams.

In Magic Stone, we realize that diversity is the key strength of community so we invite everyone to raise and discuss any problems they want. So far most of our discussions have been in issue trackers on GitHub but discussion can happen anywhere. It's important for everyone to be able to see the reasoning so we do ask that discussion take place where it will be publicly available long-term.

# How can I try C4 with my project?

It’s a tough sell to switch development processes which is part of the reason we decided to fork these projects and operate independently. If you're ready to try C4 we recommend forking an existing repo and then recruiting one or two volunteers to follow the protocol. That way if after a few months it seems not to be working you can PR any interesting developments back upstream and leave the new repo alone. You may find [C4-tools](https://github.com/magicstone-dev/c4-tools) to be helpful for processing any stuck pull requests that you may have.

----

**Still have a question? 🚩 [Create an issue](https://github.com/magicstone-dev/magicstone.dev/issues) or 💬 [ask in our chat](https://matrix.to/#/#magicstone:matrix.org).** 
