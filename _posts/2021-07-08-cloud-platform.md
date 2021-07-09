---
title: "What is Platform Engineer!"
date: 2021-07-09T15:34:30-04:00
categories:
  - blog
tags:
  - platform
  - DevOps
---
> *This blog is about my keynotes from <https://www.infoq.com/articles/platform-engineering-as-community-service>*
## Key Points
- **Platform Engineering** is about using tools and skills to build, maintain and provide a curated platform experience for the communities using it.


- Aim to create a platform that has clear boundaries & responsibilities; prioritises self service & automation; offers a flexible & evolvable experience; and is wholly reliable
- It is not just to provide a service, but rather to be a service to your communities. This involves being guided by community driven principles including making teams independent of you; promoting freedom not autonomy; being a role model; as well as respecting & recognising community differences.

> This concept encapsulates building a platform that serves *as a foundation for other engineering teams building products and systems on top of it for end users*.

So the goals include:
- Improving developer productivity and efficiency - through things like tooling, automation and infrastructure-as-code 
- Providing consistency and confidence around complex cross cutting areas of concerns - such as security and reliable auto scaling 
- Helping organisations to grow teams in a sustainable manner to meet increased business demands 

## Who gets help from Platform Engineers?
- Traditional Engineering Teams 
  For this community, a good platform will ease their lives considerably by providing tools and services to help with provisioning infrastructure, getting decent and possibly templated/cookie-cutter CI/CD pipelines up and running fast, and wherever possible, minimising the wrangling needed to do non business critical work
- Data Analysts & Scientists 
  you can’t just apply standard DevOps style processes to ML operations - there are some significant differences. Enter MLOps. It’s not only code involved now, but also data (both training and real), model parameters, multiple pipelines and more which all needs versioning, tracing and handling. Skill sets also differ vastly - the more scientist and less engineering focused nature of the work, requires processes be adapted to allow for a more experimental approach whilst still providing safety nets such as source control etc.
- Leadership & Governance
  This community is more interested in extracting valuable information out of the platform to measure and assess broader benefits, impacts and outcomes. For example they are often looking to gain information which will help them answer questions such as: Is our overall cloud spend and utilisation efficient and within limits (perhaps broader cloud contracts need negotiating, or budget/opex projections considered)? Are privacy, security and regulatory compliance standards being adhered to across the teams?

  **What does a successful platform experience look like?**

  - Clear Boundaries & Responsibilities
    Teams need to understand what is required of them to be a good platform citizen, as well as where they have license to go off-piste and the conditions allowing that. 

  - Self Service & Automation
    End users want to have tools and platforms which provide freedom and independence to go as fast as they can delivering value to their end users.
  
  - Flexible & Evolvable
    It is understood platforms will be opinionated to some degree to help ensure order, as well as provide improved productivity and efficiency. But to be practically useful, platforms must be able to adapt to diverse community needs, including allowing for deviation where required. [Eg. Spotify see more at](https://engineering.atspotify.com/2020/08/27/how-we-improved-developer-productivity-for-our-devops-teams) 

  -  Reliable & Caters for Day 2 Operations
    If engineers and operational staff are going to run their solutions on your platform, they will expect the fundamental operations underpinning it to be rock solid. 

 **How Platform Engineers do Well?**

  **1. Make Teams Independent of You**
    Blocking dependencies, these should be avoided at all costs.  Instead you want non-blocking dependencies through things such as self-service offerings and great documentation.

  - Define a Platform Contract 
    Often just a simple document on a wiki, below are examples for a Kubernetes-based platform of some of the areas typically covered in such a contract

  - Favour Automation & API Interactions 
    Automation and integration via APIs removes reliance on humans as well as minimises errors.

  - Provide Good Documentation
    Going beyond textual documentations on wikis, this includes keeping up-to-date reference implementations (for example how to deploy a specific microservice stack) through Helm chart templates, and so on. Also promoting a good developer experience via good command line docs and usage info.

  **2. Promote Freedom Over Autonomy** 

  Platforms should aim to provide teams with as much freedom as possible, but within agreed boundaries so that everyone can play nicely with each other.

  - Establish Ground Rules
    Establishing fundamental ground rules upfront is needed to make it crystal clear what the framework and context are for further decisions and options moving forward.
  
  - Choice Over “Anything Goes” 
    It is beneficial to provide limited but evolvable set of choices for teams such as **Technology Stacks, Ecosystems, Templated Pipelines**. 

  **3. Be A Role Model & Walk The Talk**
    Putting yourself in their shoes, as well as modelling the behaviour and approaches you would like and expect will go a long way towards achieving overall success.