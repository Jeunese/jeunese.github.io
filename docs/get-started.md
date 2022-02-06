# Get Started with Documentation

This article uses examples that apply to technical documentation for administrators (as opposed to end-users, developers, technicians, or peers) but the precise audience isn't important. What matters is that, once you've defined your target audience, you create content that is *helpful* for that audience. 

This isn't a case of simply aggregating information in one place. Technical documentation is about presenting *useful* content that is clear, searchable, and easy for your target audience to read, follow, and use. It should empower them to get their jobs done.

There are five high-level tasks involved in getting started with product documentation:

1. Define your documentation goals.
1. Create a content framework and strategy.
1. Create the content.
1. Test and deliver the content.
1. Analyse the documentation.

## Before you start

Investigate the existing tools at the company for whom you're writing documentation to see what you might be able to leverage and integrate. Many people are passionate about the topics you write, so link with other colleagues and communities, such as PMs and test engineers, and try to get stakeholder buy-in.

## 1. Define your documentation goals

Defining your documentation goals starts with some **discovery research**, which you can then also apply at [Step 2](/get-started?id=_2-create-a-content-framework-and-strategy). Discovery research might consist of:

* A content inventory to establish what already exists.
* Discussions with subject matter experts, colleagues in technical teams, and the administrators themselves.
* Mapping a technical workflow for your target audience to understand their needs.
* Outlining the customer use cases and problems they're trying to solve.
* Finding and evaluating other sources of insight, such as survey data and search logs.
* Evaluating existing content against known administrator needs and pain points as part of a docs audit.

From this you need to determine what you want your target audience to be able to do with the documentation:

* Get set-up quickly with a basic configuration?
* Easily navigate through various options and choose one?
* Learn how to use each of the features of your product?
* Transition from one product to another?
* Make sense of a complicated group of products?
* Solve specific customer problems with multi-product solutions?

## 2. Create a content framework and strategy

Describe the high-level roadmap to organising, scheduling, creating, and publishing content. 

1. Create a style or [writing guide](/style-guide) that explains what language to use, how to talk to users, and expected writing conventions. 
1. Create a [content framework](https://jeunese.github.io/#/?id=content-framework) in a draft Table of Contents (ToC).
    * Outline the topics you want to cover for meeting your documentation goals.
    * Create a simple and logical navigation structure with a flat hierarchy.
    * Create templates for consistent in-page design.
1. Plan your [content strategy](https://jeunese.github.io/#/?id=content-strategy), from identifying content need through to publishing and maintaining it.
    * Create an implementation plan, including the rules and tools used to create the content.
    * Create a workflow, including a review process and a plan for automated tests to catch spelling errors and Markdown violations.
    * Create a governance plan, including routines for creating, publishing, maintaining, and removing content.

## 3. Create the content

Use your documentation goals, content framework and strategy, and style guide to create content.

This content should:

* Be clear and easy to use.
* Created and maintained using efficient processes.
* Accurate and up-to-date.
* Consistent in design, structure, and writing style.
* Accessible.
* Findable, searchable, and discoverable.

Avoid duplicating content. Keep your content organised around a logical and easy-to-follow structure, and make sure processes are clear.

Get feedback, have your content peer reviewed, and make changes. 

## 4. Implement the content

Product documentation is meant to be dynamic and updated regularly. Develop tools for testing, delivering, and maintaining the documentation.

If you adopt a [Docs-as-Code](/online-documentation?id=what-is-docs-as-code) approach to delivering your content, you'll need to consider implementing systems that help you streamline the process and quality-control the documentation before it's published. 

Instead of introducing documentation with a "grand opening", start small, find pain-points that you can resolve, implement some basic validation checks, prune what doesn't work, and build on the rest. 

## 5. Analyse the documentation

Collect and analyse statistics and feedback to refine your documentation and process based on your documentation goals.

Ideally, the most relevant metrics or key performance indicators (KPIs) should be comparable both before and after product documentation was created or changed. Your baseline might consist of the insights you gathered when you conducted discovery research as part of [Step 1](/get-started?id=_1-define-your-documentation-goals). You can use these baselines to establish trends in things like search log data and feedback on the product documentation.

Perhaps the site's previous KPIs are no longer directly applicable, for example, because it went through a major restructure or there is brand new content for which you're yet to gather insight. In this way, you've come full circle. There should always be opportunities to collect new points of measurement that you can use. "Discovery" and "Analysis" are two sides of the same coin.

## Guidelines for technical documentation

What follows are some proposed guidelines for structuring, creating, and maintaining documentation, grouped by key goals.

### Findability and discoverability

Findability refers to content that users can reasonably presume would exist in the site. Discoverability refers to content that users may not have been aware of before they visited the product documentation.

**Understandable grouping.** Organize items based on user needs and to communicate where the administrator is in documentation, even if they don’t enter through the “front door” (homepage).

**Efficient and predictable navigation.**
* Don’t make users search for important information or tasks. 
* Use the minimum number of clicks to arrive at a destination. 
* Use a flat hierarchy to ensure that content isn’t hidden or hard to find.
* Use UI elements that behave consistently, in line with user expectations, with feedback, and with intuitive backtracking.
* Use clear and intuitive labels that are based on the user’s language and perspective. Labels should tell the administrator more than just where information is located, implying order and process.

**Highlight important relationships between content.** 
* Consider how different pages and sections support the content that comes before and after. 
* Use sequences of actions to imply relationships between information. 
* Set expectations in flows of information by naming and numbering sub-tasks. 
* Provide links to other relevant documentation and resources at the time that these are mentioned and most needed.

**Support wayfinding with scanning elements.**
* Meaningful headers
* Highlighted links
* Emphasis on important actions
* Bulleted and numbered lists
* Relevant images
* Descriptive captions

### Relevance and usefulness

**Focus on the administrator's workflow.** Create content that reflects relevant business cases in pursuit of administrator-centred goals. Provide meaningful choices and clear next steps.

**Set expectations.** Provide clear overviews of the steps involved in key activities and the expected outcomes. Create pages that focus on a particular goal, and task-based sections within these pages.

**Avoid information overload.** Provide only the necessary information for the user to take one action at a time. Allow this task-based information to flow progressively from simple to complex.

### Process

**Keep content evergreen.** 
* Stay accurate and up-to-date by updating content or archiving it. 
* Adopt an event-related approach to adding content (such as, new features or capabilities) –– fostered with a Docs-as-Code approach. 
* Keep on top of broken links; consider developing an automatic tool detecting broken, and a system for tracking changes and creating redirects.

**Collaborate.** Communicate and align with stakeholders to ensure documentation keeps its flow and is created pro-actively, rather than reactively. Encourage engagement with stakeholders with regular sync ups. Keep relevant parties informed.

**Workflow.** Establish documentation ownership and roles. Adhere to a writing, review, and approval process.

### Editorial quality

**Consistency.** Follow process, brand, and writing guidelines. Use a single, consistent template for creating content using a Docs-as-Code framework. Use tools for automatic validation and checks before publishing.

**Usefulness and relevance.** Create purposeful content based on business goals, user needs, and purpose of the documentation. Provide overviews and summaries, but avoid duplication; link to other relevant content.

**Emphasis.** Highlight: 
* UI elements with **bolding**.
* Code keys and database elements with UPPER CASE.
* File paths and names with **Initial Caps and Bolding**.
* Code samples with `monospacing`.

### Experience design

**User needs.** Write content with the context, mental models, and tasks of the intended audience (administrators) in mind.

**User journey.** Keep the ToC organized around the administrator’s technical workflow and key tasks from the customer’s perspective.

**Use cases.** Write content with the core business cases of our customers in mind.
