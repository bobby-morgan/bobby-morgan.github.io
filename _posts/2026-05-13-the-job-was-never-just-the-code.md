---
title: The Job Was Never Just the Code
date: 2026-05-13 12:00:00 -0600
categories: [Engineering, Career]
tags: [software-engineering, ai, career, leadership]
description: Software engineering has spent decades organizing itself around implementation. That was always only a quarter of the job, and AI is making the imbalance impossible to ignore.
---
 
My first role was "Programmer." That was the actual title. A business analyst would drop a defined ticket on my desk; I would write the code, and when I was done, I would throw it over the fence to a QA tester, who would decide whether it was finished and ready for release. I didn't talk to users. I didn't weigh in on requirements. I wasn't involved in what happened after the deploy. Someone else figured out what to build, someone else verified that it worked, and I lived in the narrow middle.
 
I think about that title a lot now because the rest of the industry has been stuck framing software engineering the way my old title did. Ask a software engineer what they do, and most will say something along the lines of "I write code." Recruiters screen for it. Bootcamps teach it. GitHub measures it. The entire field has organized itself around a single step in a much longer process: implementation. Implementation is, at most, a quarter of the job. Recognizing the full scope reveals how software engineers can make an impact.
 
When a capable model can scaffold a service, write the tests, and refactor the result in the time it takes to get coffee, the question stops being "can you write this code?" and becomes "should this code exist, and if so, what should it actually do?" The engineers I see thriving right now aren't the fastest typists. They're the ones who were already spending most of their energy on the parts of the job that surround the code.
 
## What Software Engineers Actually Do
 
Here's a useful exercise: list everything you did last week that moved a product forward. Not the tickets you closed. But the actual activities.
 
For most engineers, the list looks something like this. Understanding what problem is worth solving and for whom. Talking to a PM about whether a requirement is a real constraint or a guess. Sketch three approaches on a whiteboard and discuss which one you'll regret least in two years. Writing the code. Reviewing someone else's code. Watching a dashboard after a deploy. Getting paged at 2 am and figuring out which of the 10 things released yesterday broke. Deprecating a service nobody owns anymore. Pushing back on a roadmap item that looks shiny but doesn't actually move the metric leadership cares about. These activities are vital to delivering value and driving the development of successful products.
 
Exactly one of those is "writing code." The rest are working too. They've always been the work. We just stopped counting them because they don't produce a green square on a contribution graph.
 
It's worth steelmanning the code-first view because it didn't come out of nowhere. Code is legible. You can count lines, count PRs, run tests against it, and grade a candidate on it in 45 minutes. Everything else is harder to measure and harder to teach. Curricula optimize for what's testable. Interviews optimize for what's defensible. Junior developers get hired for their coding ability, internalize that as the job, and carry that mental model into senior roles, where it quietly stops being true. The result is a field full of people who are very good at the parts of the job that are easiest to automate, and underdeveloped in the parts that aren't.
 
## A Maturing Engineering Discipline
 
Civil engineers don't spend the bulk of their time pouring concrete. Mechanical engineers don't spend their days at the lathe. Electrical engineers don't personally solder every joint. In every mature engineering discipline, the act of physical construction is a small slice of the work. The bulk goes to requirements, modeling, design, review, verification, and the unglamorous business of making sure the thing actually does what it's supposed to in the real world. Nobody calls a civil engineer who only knows how to pour concrete an engineer. They call them a contractor.
 
Software is the youngest engineering discipline, and for a long time, we got away with treating implementation as the whole job. The field was simple enough, the stakes were low enough, and the tooling was primitive enough that the person writing the code had to do most of the surrounding work in their head anyway. None of that is true now. Our systems are more complex, the stakes are higher, and the implementation itself can increasingly be delegated. What's happening to our field right now isn't a crisis. It's the same maturation every other engineering discipline went through. We're finally being asked to act like engineers.
 
## The Parts We Underindex
 
**Problem definition.** The most expensive code is the code that solved the wrong problem perfectly. Engineers who can sit with ambiguity, push back on requirements, and reframe a question before answering it generate disproportionate value. The skill rarely shows up in a job description, but this part of the job is becoming evermore important as AI speeds up the implementation phase.
 
**Design and architecture.** Not "drew a box diagram in Lucidchart" but the harder version: understanding what you're optimizing for, what you're trading away, and what your future self or successor will curse you for. Architecture decisions are compounded. Implementation choices usually don't.
 
**Stakeholder communication.** Most engineering failures I've seen up close weren't technical. They were a PM and an engineer who thought they agreed and didn't, or a team that built the right thing and couldn't explain why it mattered. Translating between business context and technical reality is a core skill, not a soft one.
 
**Observability and operations.** Code in production behaves differently from code in your head. Most engineers treat observability as something you add when something breaks; the good ones treat it as a feature of the change itself. They instrument what they ship before they ship it. They know what normal looks like for their service, so abnormal is obvious. They can debug using a graph rather than guessing. When the page comes at 2 am, the gap between the engineers who own their system and the ones who merely deployed it becomes a chasm. Production is the only environment that matters, and engineers who don't take ownership of how their code behaves there are only doing part of the job.
 
**Product ownership.** Of everything on this list, this is the one I'd push engineers on hardest. The old contract was simple: a PM owned the what and the why, an engineer owned the how. That contract is dissolving, and the engineers who lean into the dissolution are pulling ahead. Product ownership means talking to users directly. It means caring more about whether the feature solved the problem than whether the ticket got closed. It means being opinionated about the roadmap, willing to push back on the wrong work, and willing to kill a feature you built last quarter when the data says it isn't pulling its weight. The good news: you can wake up tomorrow and decide to be this kind of engineer. Nobody has to give you permission.
 
**Testing and validation.** Every engineer says they care about quality, but far fewer treat testing as something they own end-to-end. Owning validation means writing the tests, yes, but it also means investing in the CI and CD pipelines that make those tests cheap to run, fast to fail, and easy to trust. It means thinking about what could break in production and building the guardrails before it does. Engineers who treat testing as someone else's job or as a tax to minimize are the same engineers who panic on every deploy. Those who own it ship more confidently and more often because the system has their backs.
 
**Technical strategy.** Knowing what to build next, what to stop building, and what to never build at all. This is the highest-leverage activity in engineering and the one we train for least. Strategy is what separates a backlog of features from a coherent product, and a pile of services from a system that compounds. It's the North Star that aligns your team and the teams around you so everyone is pulling in the same direction. And when technical work comes up that isn't a flashy new feature, the migration, the platform investment, the deprecation, an engineer doing strategy well articulates it the same way we expect product managers to articulate features: with a clear problem statement and a well-defined impact. Strategy is what gets that work funded.
 
## Circling Back
 
My old title was honest about what the job was. "Programmer" described someone who wrote code, full stop. The upstream and downstream work belonged to other people with different titles.
 
Somewhere along the way, the title changed to "engineer," and the scope of the work changed with it. We just never fully caught up on how we talk about ourselves, how we hire, or how we measure. The implementation step is getting cheaper every quarter. The judgment surrounding it is becoming more valuable. Spending an extra hour understanding what users actually need will, over the course of a career, outperform another hour spent optimizing your editor setup.
 
This isn't a call to write less code. It's a call to stop treating the code as the work and start treating it as one artifact of the work. The visible tip of a much larger iceberg of thinking, deciding, communicating, and judging. The iceberg was always there. We're finally at a point where ignoring it is no longer an option.
 
If my career had stayed in the shape of that first title, I'd be in trouble right now. The engineers who internalize the broader scope of the job won't be the ones AI replaces. They'll be the ones who figure out how to harness it to build impactful products.
