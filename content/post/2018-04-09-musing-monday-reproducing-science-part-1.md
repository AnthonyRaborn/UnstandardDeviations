---
title: 'Musing Monday: Reproducing Science Part 1'
author: Anthony Raborn
date: '2018-04-09'
slug: musing-monday-reproducing-science-part-1
categories:
  - Musing Monday
tags:
  - Reproducibility
  - Science
  - Text Only
---

# Part 1 of Reproducibility
### Show me the methods!

One of the pet peeves I have regarding science in general is the lack of openness regarding the methods used. I'm not talking about which statistical tests were used (although sometimes that's hard to decipher from papers or talks). Rather, there seems to be a reluctance for academics to fully describe the steps they took throughout the entire research process--how they acquired the sample, any power analyses ran prior to the study to inform sample size requirements, techniques used to record and store data, decisions made with regards to missingness, etc. From my own readings, it seems like researchers give you just enough information to reassure reviewers and readers that the process was justified and to give the illusion of others being able to reproduce the results from start to finish. 

I'm not saying that this is the case everywhere; some fields are strongly pushing for experiment pre-registration as a part of the grant application process (primarily the biological-oriented sciences if memory serves). However, in my field of research methodology, it seems difficult to find the proper way to apply certain methods or use new statistical packages/routines without a concerted effort on the part of the reader. This is definitely not a desirable outcome--at least in my case, I research to help expand human knowledge, and making it difficult for others to follow my thought process seems self-defeating. One of the reasons I've become so enamored by R and creating R packages is because the software allows for people of all kinds to access methods they may not have heard of or been able to use otherwise. 

For example, most item response theory software requires a license or other form of payment to use, which would limit the availability of IRT analyses to those who are willing or able to pay for it. However, R has multiple different packages implementing IRT *for free*, so there's the potential for a large number of users to get involved in IRT analyses when they may have instead been forced to stick to other means. Computer adaptive testing can also be a cumbersome methodology to implement unless you've been studying it or work for a company with access to specialized software to implement it, but through R (and the free Firestar software that produces R code) a relatively inexperienced R user could simulate CAT models with ease ([Not to plug too much, but I have an R package that makes a variety of computer adaptive testing models easy to implement](www.github.com/AnthonyRaborn/caMST)). What bothers me most, probably because of how much it affects me when I do my own work in R, is the absolutely poorly-made documentation in most R packages. I couldn't tell you how many packages I've tried using for one thing or another that I end up uninstalling instantly due to the obtuse or incorporeal documentation that's included with it. How can we researchers expect others to use our ideas if we can't properly describe them and demonstrate how to use them in typical cases?

Ultimately, allowing more people to see and follow the steps you used in an experiment should help propel science forward, whether that be through pre-registering experiments and explaining how and why you deviated from the plan, through better documentation of the methodology in question, or something else. It should be a goal of every researcher to allow others to replicate his or her work as exactly as possible (even in cases where the entire experiment may not be replicable; see the body of literature on qualitative research in education as an example). Academics are ostensibly interested in comparing and debating ideas, and hiding them behind a shroud of carefully-chosen weasel words or outright omission does nothing for those ideas. 

I'm not sure what could be done to help incentivize researchers to being more open about their methods (new or used), but it would certainly make me feel better if they were in place. Maybe next week I'll have some ideas on the incentives.
