---
tags: architecture, design
---
[Software Architecture is Overrated, Clear and Simple Design is Underrated - The Pragmatic Engineer](https://blog.pragmaticengineer.com/software-architecture-is-overrated/)

Moral: 
- People bend over for shiny and typical architecture patterns.
- But the most important thing about software: It solves problems. And patterns only get created **after** more and more people actually solved a problem choosing that architecture. 


A simple case on how Uber's dive redesign their software  distributed payment systems, with some surprising highlights
- No standard in software architecture planning
- No architect engineers in the team. the architecture was discussed and decided based on every feedback of the team that aims to one thing: resolve the current issue(scaling)
- No references to any common architecture patterns.

-> They shift their focus to answer the business problem and come up with simple designs. Then evaluate the tradeoffs and seek feedback. It's a team decision.

Many big techs follow strict architecture decisions. This is mainly known as top-down approaches and refrains developers to actively propose their architecture decisions. The process gets slower since the company thrives on optimizing developers as exchangeable resources (*i.e., easier to relocate on short notice*). 


tl;dr: 
Architecture patterns should give you the idea of how to improve the situation. The more people know about that pattern, the more pros & cons they understand to decide whether or not to pick it up as a solution. But they're not the goal. They can't be substituted for simpler designs. 

Patterns were born after engineers observed the similarity through cases. It worked, and people noted it down as a reference. 

**The goal should be more about solving solutions and learning through them rather than picking a shiny architecture pattern and hope that will solve your problem**