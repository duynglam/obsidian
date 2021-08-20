---
tags: testing
---

**V-Model**
stands for verification model/ validation model

**Keyword to start**
- Waterfall Model: A sequential model divided into different phases of SDLC. Each stage is designed to perform a specific activity. Testing phase starts only after implementation (the last stage) of the system is done.
- V-Model: A process where testing is done on each phase, happens parallel to development steps. 


**Problem with Waterfall Model**
- testing starts after Implementation
- easy to miss out the key details in the requirements 
- takes longer to detect error -> higher cost
-  products get shipped out wrong
- start all over again

**Why V-Model is the Solution**
- each development step comes with a corresponding test phase
- ensures the process move toward the same goal: build error-free product

![[img/v-model.png]]


**Core principles of V-Model**
- In V-model, testing is done in hierarchy. It breaks down from high-level design to detailed designs.
- Transparency in data and processes. Thus, documents are required to maintain the app once it's available in prod env.
- Scalability. The testing model must capable of adapting to the project size, complexity and duration. 

**Scenarios to apply V-Model**
- fixed & defined requirement
- stable and available resource

**The pros and the cons**
V-Model aims on verify and validate each activity in the circle. Maintaining
- Consistency
- Result-oriented
- Straighforward & simple rules

Though some downsides may be mentioned
- Does not support concurrent activities. 
- Hard to apply for project with complex and changable requirement

---

**More reading**
- [Modify The Traditional V-Model](https://insights.sei.cmu.edu/blog/using-v-models-for-testing/)