# Get Started with Product Documentation

This article uses examples that apply to documentation for administrators (as opposed to end-users, developers, technicians, or peers) –– [product documentation](/?id=product-documentation) –– but the precise audience isn't important. What matters is that, once you've defined your target audience, you create content that is *helpful* for that audience. 

This isn't a case of simply aggregating information in one place. Technical documentation is about presenting *useful* content that is clear, searchable, and easy for your target audience to read, follow, and use. It should empower them to get their jobs done.

## Before you start

Investigate the existing tools at the company for whom you're writing documentation to see what you might be able to leverage and integrate. Many people are passionate about the topics you write, so link with other colleagues and communities, such as PMs and test engineers, and try to get stakeholder buy-in.

There are six high-level tasks involved in getting started with product documentation:

1. [Decide what to document](/get-started?id=_1-decide-what-to-document)
1. [Decide how to present it](/get-started?id=_2-decide-how-to-present-it)
1. [Plan your documentation](/get-started?id=_3-plan-your-documentation)
1. [Create the content](/get-started?id=_4-create-the-content)
1. [Implement the content](/get-started?id=_5-implement-the-content)
1. [Analyse the documentation](/get-started?id=_6-analyse-the-documentation)

## 1. Decide what to document

Do the work that will help you define your documentation goals. This starts with conducting discovery research, which you can then also apply at [Step 3](/get-started?id=_3-plan-your-content). 

### Conduct discovery research

Discovery research might consist of:

* A content inventory to establish what already exists.
* Discussions with subject matter experts, colleagues in technical teams, and the administrators themselves.
* Mapping a technical workflow for your target audience to understand their needs.
* Outlining the customer use cases and problems they're trying to solve.
* Finding and evaluating other sources of insight, such as survey data and search logs.
* Evaluating existing content against known administrator needs and pain points as part of a docs audit.

From this you need to determine what you want your target audience to be able to do with the documentation.

### Define your documentation goals

Define what you want administrators to achieve with the product documentation:

* Get set-up quickly with a basic configuration?
* Easily navigate through various options and choose one?
* Learn how to use each of the features of your product?
* Transition from one product to another?
* Make sense of a complicated group of products?
* Solve specific customer problems with multi-product solutions?

## 2. Decide how to present it

Once you have your documentation goals, you can start designing a style guide and creating online templates. 

Documentation needs more than text, diagrams, and screenshots. It needs to keep to a style and format that makes content easy to find and follow with:

* Simple and readable headers.
* Scannable content.
* A clean page structure.
* A clear table of contents.
* Consistent design elements.
* Accessibility.

### Create a style guide

Draft a [style guide](/style-guide) (if you don't already have one) that explains what language to use, how to talk to users, and expected writing conventions. These guidelines tend to be based on your industry, your company brand, your company's guidelines for [voice and tone](voice-and-tone), your target audience, and purpose of the content.

### Create templates

For consistent design and structure, use templates. This should help you separate content from format, which allows you, as a technical writer, to focus on what you write, knowing that the outcome will be accessible, clean, easy to navigate, and well-designed. Well-design product documentation is better at communicating to its audience. Some guidelines for creating product documentation templates:

* Allow for white space to help break content up.
* Use consistent fonts and complementary colours across pages. 
* Use a flat hierarchy to ensure that content isn’t hidden or hard to find.
* Make sure your documentation adheres to your [style guide](/get-started?id=create-a-style-guide). 

## 3. Plan your documentation

Describe the high-level roadmap to organising, scheduling, creating, and publishing content. 

Even if you know your product really well, you need to plan to ensure that you’re helping users perform tasks, not just describing the product in all its glory. 

Take the time to who your target audience is and then consider:

* What to include and what not to include.
* What order the information should go in.
* What other resources exist that you might want to link to.
* Who's responsible for: 
    * Creating the documentation 
    * Approving the documentation
    * Maintaining the infrastructure for the documentation
    * Evaluating the effectiveness of the documentation
* Will the documentation be translated into other languages?

To answer these questions, start drafting a [content framework and strategy](/?id=content-framework-and-strategy).

### Build a content framework

Create a [content framework](https://jeunese.github.io/#/?id=content-framework) in a draft Table of Contents (ToC).
* Outline the topics you want to cover for meeting your documentation goals.
* Create a simple and logical navigation structure with a flat hierarchy.
* Create templates for consistent in-page design.

### Plan a content strategy

Create your [content strategy](https://jeunese.github.io/#/?id=content-strategy), from identifying content need through to publishing and maintaining it.
* Create an implementation plan, including the rules and tools used to create the content.
* Create a workflow, including a review process and a plan for automated tests to catch spelling errors and Markdown violations.
* Create a governance plan, including routines for creating, publishing, maintaining, and removing content.

## 4. Create the content

Use your documentation goals, content framework and strategy, and style guide to create content.

Product documentation describes more than just *what* a product or feature does. It's also concerned with *who*, *where*, *why* and *how* a product or feature is used.

If you don't know where to start, start at the beginning and walk yourself through the set up of the product, taking note of the pain points and any gaps in information that might help the reader complete their tasks. Break this content up into smaller parts. Build a list of items that might also need documented or that are uncovered by colleague or customer tickets, and deal with them one at a time, in line with your content framework.

Some guidelines for what to include in product documentation:

* Highlight what the product or feature does in the context of the user need. 
* Use real-world examples and use cases to put the product or feature in context for the administrator. 
* Focus on the solution that a product or feature provides, not just what it is and does. 
* Single-source your content so that you only need to update information in one location; avoid duplicating content –– explain something once and link to existing resources when they come up.
* Try to write content that's self-contained, making it easy to move around and link to.
* Treat each new article like a mini-onboarding, with pre-requisites, process overviews, and clear steps.

Importantly, describe how the user *performs a task* with the product or feature. For guidance on writing instructions for completing a task, see [Writing instructional content](/technical-writing?id=writing-instructional-content) in the **Technical Writing Guidelines** article.

After creating new product documentation based on a content framework and strategy, you then need to maintain and update your documentation. 

Most commonly, you'll write event-triggered content, typically a documentation release. A documentation release is content that's published at the same time as the public release of the product or feature. Your colleagues, such as the PM and other internal stakeholders identify content gaps and improvements to product documentation for you to scope, draft, and add. Candidates for product documentation include:

- A new product, feature, or important component release.
- An important update to an existing feature.
- Information on how to install, upgrade, manage, or troubleshoot the product.

You might also create product documentation under the following circumstances:

- **Public (technical) previews.** In this case, documentation is published along with a disclaimer stating that the feature is in preview and shouldn't be used in a production environment.
- **Limited public (technical) previews.** Access to a new product or feature prior public release is granted based on the customer type. Documentation is published along with a disclaimer describing who can access the feature and the conditions for access.
- **Private (technical) previews.** In this case, a select group customers are granted explicit access to a hidden product or feature. Documentation is delivered offline directly to those customers. 
- **Product or feature end-of-life and transitions.** Content needs to be updated, deprecated, and removed content as appropriate for a product or feature that is ending. Content typically includes disclaimers that indicate the expected removal of the product or feature and provide details about access to recommended alternatives or newer features.

To write technical content for product documentation, you should:

-  Understand the user persona, whether they're: network, IT, or security administrators; security officers; end-users; or data analysts.
-  Change the way you write based on the users and their expectations. Be aware of goals, needs, and backgrounds. Decide on the tone you use based on the product and target audience.
-  Understand at what stage in the customer journey the user is when they read your content.
-  Understand the product: narrow your perspective down to the specific functionality that requires content.

### Scoping and planning

To create content, a technical writer must first research and test the product or feature they're writing about. Communicating the knowledge you garner from research and testing in product documentation is the last step in the process. 

-  Collect knowledge of the product from subject-matter experts (SMEs).
-  Understand the real-world use cases for the product or feature.
-  Understand the solution provided by the product or feature.
-  Identify the competitors and what the product or feature differentiator is.
-  Consider globalisation standards (strings can be 2 times longer; content can be translated in an unfavourable way).
-  Create content based on a hands-on experience with the product or feature.
-  When writing content, walk through design flow the way a user would and document as you perform the steps.

Having in-depth knowledge of the product doesn't mean you have to become an engineer or know all its nuts and bolts. Being a technical writer is the difference between knowing how to drive a car and knowing what's under the bonnet of your car. You still need to understand the lights on the dashboard and pass your test to drive a car, but you're not a mechanic, and neither is your passenger (your audience).

Questions you can ask to collect the right information include the following:
- Feature description
	- Which screens are changing?
	- What is the current state for administrators versus what the feature will bring?
	- What steps are involved?
- Customer need/value
	- What prompted/triggered this feature?
	- What problems are we solving?
	- (How) does this feature impact subscribers/administrators?
- Pre-requisites and limitations
	- What do administrators need to know about this feature?
	- Are there any downloads, installations, 3rd party components, or storage/speed/connectivity requirements that we need to list?
- Information for publication
	- Affected product documentation page(s)
	- Will there be a Technical Preview?
	- Estimated release date

### Drafting

Start with an outline. You don't need all the information right away to start drafting. Leave a placeholder for information you don't yet have and start putting together what you do. Having the main steps involved to complete a task is a good starting point. You can build on the relevant preceding and proceeding information. 

Remember to write for the administrator, not the engineer that created the product, not for Marketing and Sales, and not for your manager.

This doesn't mean you should ignore other stakeholders in the company. For example, your company might be focusing on specific aspects of a product, and you, as a technical writer, might need to consider how to transition readers from the information in Marketing material to information in the product documentation.

You might even be able to leverage existing company materials for overviews and new content. Deep dive and technical content can be described at a higher level and in simpler terms. Marketing and Sales content can be streamlined and re-focused by removing promises about usability and performance, and adding step-by-step instructions for getting started with the product. 

Regardless, your resulting content should:

* Be clear and easy to use.
* Be accurate and up-to-date.
* Be consistent in design, structure, and writing style.
* Be accessible, adhering to W3C [Web Accessibility](https://www.w3.org/standards/webdesign/accessibility) standards. 
* Be findable, searchable, and discoverable.
* Have a logical structure, hierarchy, and flow that are easy to follow.
* Avoid big blocks of text and pages that are saturated content.
* Use simple and [plain English](/style-guide?id=use-plain-english) where-ever possible. 

For more writing guidelines for product documentation, see [Writing product documentation](/technical-writing?id=writing-product-documentation) in the **Technical Writing Guidelines** article.

### Reviewing

Before implementing your documentation, you should conduct a self-review of your content, and elicit feedback from peers and SMEs. 

The review process is a chance to collaborate with stakeholders to iterate a draft before a product or feature's release. Get internal feedback from colleagues who know less about the product you're writing about, from PMs, from other writers, and from the engineers that created the product. Get feedback when you plan your content, create a first draft, and when it's almost ready to publish. Make revisions as required.

The type of review you ask for can vary depending on who you ask and where the product or feature is in the development cycle. A review could consist of one, some, or all of the following:

- **A developmental review.** High-level input on the overall structure and content (rather than meticulously editing sentences and words), typically sought when you have an early or rough draft.
- **A copy edit.** A detailed, line-by-line edit review for grammar, punctuation, terminology, and spelling. Request a copy edit only after doing a self-review.
- **A technical review.** A review of technical terms and product naming for accuracy. Technical reviews are useful for new technical content, a significant new section or article, or existing content that has been significantly changed.
- **Proofreading.** A check for egregious errors. This is usually most helpful right before you publish.
 
The review process ends just before a feature is rolled out and can last as long as the development cycle. Depending on how long the development cycle is, you might engage in several rounds of feedback and review. 

The aim is to document as much as possible based on the available information and to solicit reviews as soon as possible in the authoring process. There may be gaps in your initial content due to SME unavailability or technical issues. Release dates can be unknown, ambiguous, or vague, and so content should be iterated early and often so that you're ready to publish it whenever the PM decides to roll out the feature. 

## 5. Implement the content

Given the evolving nature of product documentation, you might decide to take an incremental approach to implementing the content.

Instead of introducing documentation with a "grand opening", start small, find pain-points that you can resolve, test out different designs, implement some basic validation checks, try different workflows, prune what doesn't work, and build on the rest. 

Product documentation is meant to be a living artifact: dynamic and updated regularly. Content should be updated as new features are developed.

If you adopt a [Docs-as-Code](/online-documentation?id=what-is-docs-as-code) approach to delivering your content, you'll need to consider implementing systems that help you streamline the process and quality-control the documentation before it's published. Develop tools for testing, delivering, and maintaining the documentation.

## 6. Analyse the documentation

Collect and analyse statistics and feedback to refine your documentation and process based on your documentation goals.

Ideally, the most relevant metrics or key performance indicators (KPIs) should be comparable both before and after product documentation was created or changed. Your baseline might consist of the insights you gathered when you conducted discovery research as part of [Step 1](/get-started?id=_1-define-your-documentation-goals). You can use these baselines to establish trends in things like search log data and feedback on the product documentation.

Perhaps the site's previous KPIs are no longer directly applicable, for example, because it went through a major restructure or there is brand new content for which you're yet to gather insight. In this way, you've come full circle. There should always be opportunities to collect new points of measurement that you can use. "Discovery" and "Analysis" are two sides of the same coin.

## Documentation principles

What follows are some proposed principles for structuring, creating, and maintaining documentation, grouped by key goals.

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

**Keep content evergreen.**  Your content is useful if it's accurate.
* Stay accurate and up-to-date by updating content or archiving it. 
* Adopt an event-related approach to adding content (such as, new features or capabilities) –– fostered with a Docs-as-Code approach. 
* Keep on top of broken links; consider developing an automatic tool detecting broken, and a system for tracking changes and creating redirects.

**Collaborate.** Communicate and align with stakeholders to ensure documentation keeps its flow and is created pro-actively, rather than reactively. Encourage engagement with stakeholders with regular sync ups. Keep relevant parties informed.

**Workflow.** Establish documentation ownership and roles. Adhere to a writing, review, and approval process.

### Editorial quality

**Consistency.** Follow process, brand, and writing guidelines. Use a single, consistent template for creating content using a Docs-as-Code framework. Use tools for automatic validation and checks before publishing.

**Usefulness and relevance.** Ensure your documentation is *helpful* to your readers. Create purposeful content based on business goals, user needs, and purpose of the documentation. Provide overviews and summaries, but avoid duplication; link to other relevant content.

**Emphasis.** Highlight: 
* UI elements with **bolding**.
* Code keys and database elements with UPPER CASE.
* File paths and names with **Initial Caps and Bolding**.
* Code samples with `monospacing`.

### Experience design

**User needs.** Write content with the context, mental models, and tasks of the intended audience (administrators) in mind.

**User journey.** Keep the ToC organized around the administrator’s technical workflow and key tasks from the customer’s perspective.

**Use cases.** Write content with the core business cases of our customers in mind.
