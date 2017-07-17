:books:
# Structured README
![start with why](https://img.shields.io/badge/start%20with-why%3F-brightgreen.svg?style=flat)

> Its time, README reached a much wider audience, beyond developers to speed up OSS adoption! Structured README is an effort to help evolve README in a more structured manner such that it covers information related to OSS usage in order to solve real life pain points.

## Table of content

- [Introduction](#introduction)
- [README pain points](#readme-pain-points)
- [Defining Structured README](#defining-structured-readme)
- [Benefits of Structured README](#benefits-of-structured-readme)
- [References](#references)

## Introduction

First came the software and then the README originated, mostly as an afterthought. To begin with, README was a special type of text ‘file’, among a bunch of other software files, such as executables, header files and code file, that made up a software bundle. README was intended to be a file about files, describing rather curtly, what each file contained or was meant for. The name README uses all capital letters so that most of the computers list it at the top of a directory list sorted ASCII alphabetically. Back then, none other than those who played with software would even refer to it. In today’s OSS friendly world, README has become a polite note at best, created by developers for other developers, who either want to use a new piece of software or contribute to it.

README was meant to be the [very first thing] that a developer would look into, in order to get their bearings straight, before taking the plunge into understanding or using a piece of software. But not essentially. Familiarity breeds contempt. There are developers, familiar with all things software, who don’t usually need a README beyond a cursory look. You see, given the time constraints, the software documentation folks and developers typically operate at opposite ends of code and concept spectrum.

With the proliferation of OSS culture, README audience has expanded beyond the developer community, to tech savvy customers, business decision makers, product management, technology writers, marketing, sales personnel and journalists. So far, README had a kind of unwritten code of conduct, which is still acceptable to most developers. There never was an iron-clad specification that demanded the usefulness of README to a wider audience. As a result of non-existent standardization, each README has its own level of content depth and coverage. Its no wonder that [documentation discontent] is widespread today, not only in non-developer audience but also amidst developers themselves, as everyone is hard pressed for time.

Lately, there have been several attempts to not only improve README but also about making it usable. Some notable ones are [awesome readme], [feedmereadme], [art of readme] and [several others] including [markdown] and [how to create readme for open source software]. Besides these, there is also [README Driven Development] (RDD) emphasis, highlighting the need to write the README first instead of post-facto. However, these efforts are but a drop in the ocean. If you think about it, README is the first customer touch point for any OSS. It is no longer for developers only. In today’s attention economy, absence of good README not only discourages its use but also results in wastage of effort spent in creating high quality software that is not easy to adopt.

Recent [OSS survey by GitHub] highlights the fact that open source is used by the whole world, but its contributors don't yet reflect its broad audience. It is high time README got a makeover, with a well defined structure, along with some guidelines on depth and coverage. This is not only critical for adoption but also for broad-basing the OSS contributors. Its imperative that every well written software is powered by a well written, accurate, crisp and complete README to ensure the OSS component not only stands out amidst the sea of OSS, but is also usable by different kinds of contemporary audience, thus increasing its chances of acceptance and adoption. A good README is not sufficient but it is certainly necessary to differentiate a OSS component amidst plethora of free software out there that are vying for adoption attention. Besides adoption, community growth is an absolute must for OSS evolution, to help build community contributions for overall longevity and success.

## README pain points

Here is a list of some of the common pain points associated with a typical README file, be it for a small or large OSS component:

•	Insensitivity to audience needs: There are several good enough README templates but none which addresses non-developer audience requirements effectively.
•	Level of detail: Most of the READMEs are sketchy at best, bare minimum, workable for developers but unusable by technical writers, marketing, product management, sales and business decision makers.
•	Use Case and Customer Pain Point orientation: Absence of use cases definitions, not easy to comprehend specific pain points that can be solved by the software component corresponding to a README
•	OSS Ecosystem Integration: Little or no information about integration with other OSS components which can have time, cost, manageability implications for the user.
•	Case Studies Missing: No pointers to published case studies where the software corresponding to a README was deployed and solved a real life pain point
•	Performance, Benchmarks: There is hardly any section which focuses on software performance and real-life deployment statistics, published reports, benchmarking insights or pointers to the same.
•	Balancing the development vs. adoption needs: There is a dichotomy when it comes to developer goal posts and customer/user adoption needs.  For a developer it is imperative to complete the software features and fix bugs for release instead of spending time on documenting it for onboarding purposes.  Marketing and sales are all about customer onboarding and related aids, documentation being one of the key aids. 
•	Contributions: Several OSS languish for contributions and encounter general user apathy. Besides time constraints, documentation typically lags software traditionally due to the fact that developers are not motivated to help new developers onboard a project for competitive reasons. This same attitude that works in proprietary enterprises does not work at all for OSS which sustains itself by community contributions.  It is a demand supply issue.  Earlier, with fewer OSS components, take it or leave it approach worked.  Not any more, especially when there are so many to choose from. What one can’t understand one can’t contribute to.  Contributions beyond developing code can be valuable to the success of an OSS.  It takes some level of expertise to become familiar with OSS before one can use it effectively.  It takes a lot more effort to contribute and unless onboarding is standardized and simplified, the barrier to adopting OSS for contribution will continue to remain higher for most potential contributors who have to jump different hoops to learn to contribute to one team vs. another team within the jungle of tools and technologies.

## Defining Structured README
We live in a software development world running agile sprints, professing DocOps and Content 4.0 strategies.  The documentation supply chain from developers to customers can be seeded with a Structured README and utilized effectively by all those who help promote the software and spearhead its adoption.  Here is what a potential Structured README looks like:

1.	Header: (Text prefereably with a few links)
a.	Project / Component Name 
b.	Purpose:  Why is it needed, who is the intended audience and when will they need this software.  Note, typical README focus is on what the software does as opposed to why was it created in the first place? [Word limit – maximum two sentences, link to project website or other document that describes its purpose]
c.	Optional: Badges, branding, Current Status, Adoption Statistics (if available) Demo screenshots, link to related concepts 
2.	Mid-Section: (preferably all links in this section pointing to details elsewhere.)
a.	Adoption Pre-requisites:
i.	:  Technology / Technical Concepts / SW Names only with suitable links
ii.	Recommended / Required scale of deployment
iii.	Performance / Benchmarks Statistics / Level of testing
b.	Adoption Assistance: 
i.	Adoption Examples – who is using this software and for what?
1.	Highlight use cases – what are the real life situations this OSS is deployed? 
2.	Point to customer case studies on website /elsewhere
ii.	Risk Reduction: 
1.	List metrics such as Trucking Factor (TF)10 that indicate a projects fragility/sustenance capability,
2.	Other links/data points to key GitHub like metrics such as commit frequency, pulse etc.
3.	Limitations / Known issues:  Summary with top 3, link to full bug or issue list elsewhere on website
iii.	Competitive Analysis Summary:  
1.	List of primary competing OSS / Proprietary SW which can be used as an alternative
2.	One line USP of this software as opposed to competition
3.	Low-level Detail:
a.	Setup Instructions
i.	Pre-requisites (Software only)
ii.	Configuration
iii.	Installation / Uninstallation
1.	README was meant to be a file about files.  It must list high level components / files that form part of the software once installed
iv.	Troubleshooting FAQ / Guide
v.	Building the software and other details related to creating an installable, testing, validating the installable
1.	If this is a must for contribution – it must be mentioned here or pointers to this information elsewhere
2.	Executing / Running
a.	How-to FAQ/Guide on actions
b.	How-to use the software after installation
3.	Support / where to get help? / Knowledgebase pointers / Context-sensitive help / Content 4.0
4.	Link to software Change log / versions
b.	References:
i.	Getting Started / User Manual / Deployment Guide
ii.	Tutorial
iii.	Reference Guide
iv.	Reports (if applicable) on OSS performance / scale / benchmarks
v.	Other Technical References meant specifically for developers
4.	Footer
a.	License
b.	Credits
c.	Contact
d.	Link to How-to Contribute?

## Benefits of Structured README

•	Simplicity: Retains the simplicity of README, targets wider audience.
•	Concise yet Complete: Structured key points in README can be browsed quickly by empowering the audience to compare two OSS components beyond ‘what each component does’ to a finer level of granularity – not only at technical and maturity level but also in terms of ease of onboarding.
•	Flexibility: Empowers the reader to get a snapshot quickly, comprehend the purpose, without getting lost in low level detail or go to the low level details right away, if they choose to.
•	Ease of Contribution: If it takes time to figure out how to contribute, there will be few takers willing to cross the chasm of time.  Having a well defined section that clearly addresses this need will make it easier to jump the chasm.
•	Speedy Value Proposition: With a structured README, prospective OSS users can figure out the maturity of the software and how receptive the developers are towards customer needs. This can have a tremendous impact not only on adoption but also towards contributions and avoidance of duplication of efforts.
•	Assess Adoption Risks Upfront: Metrics such as Trucking Factor (TF), active users, contributors and presence of user documentation can help business managers access risks associated with adoption of open source software. This can boost adoption of good quality OSS that are more reliable and adoption-ready than others.
Conclusion
Brevity is the ‘soul’ of wit but cryptic for a README bodes certain death and transcendence into the enormous expanse of unused and forgotten OSS graveyard. Incomplete or confusing documentation is the biggest problem1 encountered in open source.  README is simply the tip of the iceberg. The tremendous momentum that drives techniques for developing better software excludes the other very important aspects of developing software – its adoption, usage and eventual evolution for survival.  Without the latter, however cool the software may be, it is actually worthless. There may be umpteen high quality, freely available OSS, but if hardly anyone can figure out a way to productively use to solve real life pain points or deploy it easily, then it is of no use at all.  

•	Open source is used by the whole world, but its contributors don't yet reflect its broad audience.


This article highlights common README pain points and shortcomings that can be addressed via Structured README approach. Structured README is a step towards helping OSS components and their authors reach a wider audience, boost its adoption, and to make it easy for contributors to identify and contribute towards software development and evolution. 

Comments and suggestions welcome! mailto://shalz@hotmail.com

## References
- Wikipedia: <https://en.wikipedia.org/wiki/README>
- Origins of README: https://medium.com/@NSomar/readme-md-history-and-components-a365aff07f10
- Open source Project to help in review and enhancement of your README: https://github.com/LappleApple/feedmereadmes
- README templates: https://github.com/zalando/zalando-howto-open-source/blob/master/READMEtemplate.md
- The Art of README: https://github.com/noffle/art-of-readme
- RDD – README Driven Development: http://tom.preston-werner.com/2010/08/23/readme-driven-development.html
- How-to Open Source https://github.com/zalando/zalando-howto-open-source/blob/master/producttemplate.md
- How to write documentation that is actually useful https://insights.hpe.com/articles/how-to-write-documentation-thats-actually-useful-1707.html
- GitHub OpenSource Survey – Documentation Discontent http://opensourcesurvey.org/2017/
- Importance of Trucking Factor in OSS adoption https://arxiv.org/pdf/1604.06766v1.pdf

[awesome readme]: https://github.com/matiassingers/awesome-readme 
[very first thing]: https://en.wikipedia.org/wiki/README 
[documentation discontent]: http://opensourcesurvey.org/2017/
[feedmereadme]: https://github.com/engram-design/FeedMe/blob/master/README.md
[art of readme]: https://github.com/noffle/art-of-readme
[several others]: https://github.com/dwyl/repo-badges
[markdown]: https://github.com/tchapi/markdown-cheatsheet
[how to create readme for open source software]: https://github.com/zalando/zalando-howto-open-source#creating-a-readme 
[README Driven Development]: http://tom.preston-werner.com/2010/08/23/readme-driven-development.html
[OSS Survey by GitHub]:  http://opensourcesurvey.org/2017/ 
