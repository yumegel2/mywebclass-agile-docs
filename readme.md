# MyWebClass.Org Project - Agile Documentation Assignment

For this assignment, you need to develop an initial draft of project documentation based on the principles of the [Agile
Manifesto](https://agilemanifesto.org/principles.html)
and [Lean](https://www.planview.com/resources/guide/lean-principles-101/). The purpose of this assignment is to help you
develop the mindset required take an idea and turn it into a product that people value. This is an open ended assignment
meaning that you need to think and create and not just follow a set of instructions. You are the one creating
instructions for yourself and the development team that you will be part of and/or possibly leading in the future.

## Things to consider:

1. Lean and Agile are both ideas that are complementary; however, neither is prescriptive in their implementation. Your
   project plan should be inspired by these ideas; however, how you implement them should be tailored to fit the
   particular project. Remember Lean's core idea is build, measure, and learn to create continuous improvement. Agile is
   essentially a way to organize within a software development team to make the development process sustainable and
   effective at producing working software with the least amount of waste.
2. In order to facilitate communication and provide a structure for project planning you must organize your project into
   themes, initiative, epics, user stories, and tasks, which are terms used within agile.
   **Themes:**
    * Themes are high-level categories of work that align with an organization's strategic objectives. They help to
      define and communicate the focus areas for a project or product. Themes can be used to organize and prioritize
      work, guide decision-making, and ensure that efforts are aligned with business goals.
      **Initiatives:**
    * Initiatives are a collection of related projects and activities that are aligned with a common goal or objective.
      They help to break down larger goals into smaller, manageable pieces. Initiatives are usually larger in scope than
      epics and are typically managed by a program or portfolio management team.
      **Epics:**
    * Epics are large pieces of work that can be broken down into smaller, more manageable pieces (i.e., user stories).
      They are larger in scope than user stories and often require coordination across multiple teams. Epics typically
      represent a major business or technical challenge that needs to be addressed.
      **User Stories:**
    * User stories are short, simple descriptions of a feature or piece of functionality from the perspective of a user
      or customer. They are used to communicate requirements and prioritize work. User stories are typically small in
      scope and can be completed in a single sprint (i.e., a short, time-boxed period of work). They help to ensure that
      development efforts are focused on delivering value to the end user.
      **Tasks:**
    * Agile Tasks:
    * Tasks are the smallest units of work in Agile development. They are specific, actionable items that need to be
      completed in order to deliver a user story. Tasks are usually estimated in hours and are used to track progress
      and identify obstacles. They are typically managed by individual team members and are part of the team's daily
      work.
3. Our goal is to develop a "pull" process for the development of the MyWebClass product and minimize or eliminate the
   amount of "push" in the MyWebClass.org
   project.  [Read this about the difference between push and pull to understand how these concepts relate to product development.](documentation/reading/push_vs_pull.md)
4. Every theme, initiative, epic, user story, and task needs a way to test that it is working. You can specify automated
   testing i.e. pytest for unit testing, Playwright for end to end testing, or manual testing. You may need to combine
   both manual and automated testing for themes, epics, and initiatives; however, tasks and user stories should us some
   type of automated testing as much as possible.
5. Every theme, initiative, epic, user story, and task should identify how you will measure it's effectiveness
   quantitatively. If you can't think of one now just put something in that might work in the future and this can be
   improved as things become more clear. YOu need to consider that to implement lean you have to build it, MEASURE IT,
   and LEARN, its not necessary or expected for something to be perfect, it is expected that any resources invested in
   something have some methodology to evaluate performance, and provide feedback for continuous improvement.

## Scope of the exercise

In the spirit of Lean and to start our project off using the "pull" approach to develompent we will only focus on the
following goal. MyWebClass is a website and we will have a development team that needs to work together in parallel
meaning that we eventually need to produce various content to support the objectives of the site. In order for this to
happen we need to create a basic web template that can be found using a search engine, addresses any legal requirements
that are relevant to our project, allows us to legally use Google Analytics to measure user behaviour on the site, and
passes [w3c validation](https://validator.w3.org), [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/), [GDPR Scanner](https://2gdpr.com). 

In addition to planning the initial 0.1.0 release of the website template we also need a plan setup a DevOps process that support the development of the project.  

In  general, you can exect that you have 3 major parts to your plan at this stage:
1. Basic Project Documentation and Project Management
2. DevOps 
3. MyWebClass.org base website template with all technical and legal requirements satisfied to use Google Analytics and be appropriately listed in a search engine by implementing the basic on page SEO requirements.


## Overview

Looking to learn modern software development technologies and processes in a hands-on learning environment? Look no
further than MyWebClass! Our platform provides an integrated learning experience that contextualizes technology with
business processes to provide realistic scenarios for students to learn technology in a hands-on real world environment.

## Our Project Values

## Agile Project Documentation

### Templates - Modify these as necessary

* [Theme Template](documentation/templates/theme/theme_template.md)
* [Initiative Template](documentation/templates/theme/initiatives/initiative_template.md)
* [Epic Template](documentation/templates/theme/initiatives/epics/epic_template.md)
* [User Story](documentation/templates/theme/initiatives/epics/stories/story_template.md)
* [Task Template](documentation/templates/theme/initiatives/epics/stories/task_template.md)

## Release Schedule

| Release Version | Release Date | Features                                                      |
|-----------------|--------------|---------------------------------------------------------------|
| 0.1.x           | TBD          | [Project Setup](documentation/theme_1/theme_project_setup.md) |

