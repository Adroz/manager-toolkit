# Career Check-in Example

## Goals

#### What do you want to be doing today?
- Own some trailblazing efforts for GoldenGate
- Advise SiteVision team on testing and architectural best practices (state management, GraphQL)
- Provide active input into technical design and feature approach (write specs)
- Mentor junior developer for success and completion of technical projects.
- Backend contributions

#### What do you want to be doing in 1 year?
- Developing systems that stand as examples of great software across the company
- Domain expert in specific engineering field (React, Apollo, testing)
- Massively reducing regressions
- Influencing testing practices across the web platform

#### What do you want to be doing in 3 years?
- Architectural (systems-level) engineer
  - Like many engineers, I want to create the most seamless, best designed product possible. Bad design and architecture can get in the way of that ideal. Sometimes, I'm the cause. Other times, we live with the decisions made by those who coded before us, and by the product needs that have shifted over time. I think that high-quality senior engineers have sort-of 'second sight' - they anticipate the trade-offs, the debt, and design considerations which will echo throughout the product as it grows and changes priorities and so on. Those who master this skill benefit the entire organisation. I want to provide that kind of worth to my organisation.
- Applying well-rounded full-stack skill set
  - I want to be 'like water', able to take the engineering form necessitated by any situation without friction. At my current level, certain tasks and tickets are stymied either by my lack of technical knowledge or by my lack of institutional knowledge. I do often defer such tasks to other engineers and other teams, but I should simultaneously learn from their approaches and solutions in order to broaden my understanding of the product and the engineering design behind it.

#### What do you want to be doing in 8 years?
- Touring in a bluegrass band

## Reality

#### What is currently holding you back?
- Poor documentation - in code and in JIRA. Reliance on institutional knowledge.
- Unclear from leadership what software support is going to look like for SilverGate. Should I spend my time supporting regressions in GoldenGate? In SilverGate? How will that balance work moving forward?
- Everyone is remote, communication is more async.

#### What are you good at that you can do more of?
- Trying new approaches (QA regression testing, GraphQL)
- Facilitating better communication and listening between team members.
  - Articulate concepts between engineering and other stakeholders
- Roping other team members into pairing. (Good example of collaboration and communication)
  - Example - Design, QA and Web pairing. Lists of questions and nits and working through the list together.

#### What sort of opportunities are you looking for?
- Backend work → build a graph in photos service, orientation metadata into the photos model, BE tweaks filter fields.
- Hosting more RnD reviews
- More mentorship opportunities / mentee opportunities

#### What keeps you working here?
- Company culture is great and so is the team
- The work is challenging and interesting, feels like we have an impact
- Engineering culture also seems really cool with the hackathons and bi-annual challenges

#### If you could change something about your job, what would it be?
- It would be nice to not have so many ad-hoc bugs. Perhaps it wouldn't be a challenge if I was here for longer than a couple of months, but because I'm sort of learning everything as I go as the other BE devs are gone, each bug takes quite a bit of investigation on my part and puts most of my feature work behind.
- Have an in-person team gathering once or twice a year. It's lonely not being able to have some face time with my team.

## Planning
#### What projects can you take on in the next 6 months to get closer to your goals?
- Add photos graph in new photos service 
- Document pg-graphql code → release, building, developing locally, using tooling (lightstep, etc). Incorporate details for productionising and deploying this nodejs service in the pgcore ecosystem.
- Ownership of an initiative outside of SiteVision's feature set - i.e. Quality tool for ACS
  - Bring in multiple contributors a la the Analytics-Lib model.
- Create a document outlining a recommendation for SiteVision's testing success metrics (and why)
  - Could be: test coverage percentage, focused on a subset of test types (unit/integration/UI/etc), filed regressions, or something else

#### What tasks can you complete in the next 6 weeks to complete your projects (above)?
- [ ] @Joan Citizen Update PG GraphQL readme with up-to-date information 03 Nov 2020 
- [ ] @Joan Citizen Seek out mentor within ACS or outside of work to give advice on how to advance towards 'Senior Engineer' 01 Dec 2020
- [ ] @Joan Citizen Write up blurbs and high level views of hack week ideas 03 Nov 2020 (Follow up with potential teammates / recruit)
- [ ] @Joan Citizen What does 'quality' actually look like for SiteVision IRT our testing philosophy and approach? What metrics could we set for the team? 01 Dec 2020

#### What help will you need to get to those goals?
- Management to provide backend contribution opportunities (smaller tasks sprinkled within sprints). And backend team mate to pair with.

#### How will we know that you're on track?
- Completing the tasks listed above
- Recording a list of decision making history for review at the end of the year (for decision-making and contribution goals).

## What have you done so far?

*22 Oct 2020*
- Wrote and presented a Lunch and Learn session to the SiteVision team, focused on testing.
  - Also Presented an abbreviated Lunch and Learn testing talk within the a Web Town Hall
- Contributed to backend codebase
  - Solved photo report rotation issues by adding rotation and sizing metadata from photos into the reports-consumed data models. This means that report photos now rotate, scale, and shift correctly. This involved a lot of wrangling with CSS transforms, but was worth it as any reports consuming the photos component should receive this for free.
  - Added GoldenGate filtering and sorting support. Since Web is the only consumer for this it made sense to own this implementation. It's given me a better understanding of the codebase and more confidence to add or modify any filtering logic in the future.
  - Assisted with the generation of Swagger documentation (this is really important for both Public API documentation, and ACS feature-team onboarding).
- Have consistently set aside regular documentation time, making progress on GraphQL and Testing writing tasks. 

*10 Sep 2020*
- Successfully completed Web Photos rewrite!
  - The scope stayed tight (actively worked against scope creep)
  - Managed expectations (keep management and PM informed of roadblocks, dependencies and progress)
  - Presented to the SiteVision team in a Lunch and Learn about the new frontend.
- Through ownership of GraphQL gained better understanding of the Photo model, and Backend codebase.
  - Has been surfacing Backend regressions to backend dev.

*30 Jul 2020* 
- Present to Web Town Hall on GraphQL findings. Jointly formed a council, began discussions of federated GraphQL world.
  - Also presented a R&D Review - Talked about GQL and ask for joint ownership
- Worked closely with John Citizen (intern) as their mentor
  - Onboarded them to the GoldenGate code-base.
  - Performed regular 1:1s and pair-programming sessions
  - Ramped them up to be a valued contributor to the team - with a focus on adding features to Photos Reports.