# Information Development Overview

An Information Development team consists of technical authors, also called content or information developers, that typically belong to Engineering. 

Information developers are concerned with designing the digital experience of product information –– how information is formed, organised, delivered, presented, and so on. For this reason, Information Development is also called **Information Experience**, which can be shortened to "IX". 

IX work with software developers and UX designers to ensure that information is meaningful, accurate, user-friendly, and formatted appropriately, whether that's as part of technical documentation or in the product itself. The aim is to optimise how people engage with information to maximise the user experience (UX) of a product. To this end, IX are responsible for:

- Technical content authoring for a software company's products and services. For guidance on technical writing and, in particular, writing product documentation, see [Technical Writing Guidelines](https://jeunese.github.io/#/technical-writing).
- In-product content development (UX writing), such as error messages and on-screen text. For information on UX writing, see [UX Writing Guidelines](/ux-writing).
- Website infrastructure for product documentation. For an overview of this approach to managing documentation, see [Online Documentation](/online-documentation).

Information developers in IX typically work closely with:

- Product teams, under the guidance of Product Management (PM).
- Software developers and test engineers in Engineering.
- Product Design (PD) to collaborate on UI content and guided workflows.
- Globalisation teams to create automatic translation.

## 4 rules for creating a good information experience

Regardless of whether you're creating product documentation or designing UI content, there are four basic rules for creating a good information experience.

1. **Understand your target audience.** The type and amount of information your audience wants and needs depends on who they are and what they're trying to do. Take the time to understand:
	* The goals and activities of your intended audience.
	* What your intended audience already knows, doesn't know, and needs to know.
	* How to provide the information that the intended audience needs.
1. **Create a plan for implementing content.** Just as developers have coding processes and designers have design guidelines, IX should have a defined and systematic plan for creating and implementing content to:
	* Help integrate it as part of the product or feature.
	* Allow time to review content with colleagues, in context.
	* Create the bandwidth to make improvements during the development cycle.
1. **Follow a [style guide](/style-guide).** Create and use a style guide to foster:
	* Consistency.
	* Readability.
	* Accessibility.
	* Good format and design.
	* Scannable content.
	* Content that's useful (understandable and easy to follow).
	* Content that's in line with your company's [Voice and Tone](/voice-and-tone).
1. **Map content to your audience's processes and tasks.** Create task-based content that's structured around the intended audience's workflow. Build this content and decide where it should go based on:
	* What the intended audience is trying to do.
	* The steps involved in completing a task.
	* What information and resources the intended audience needs to complete a task.
	* What content and resources already exist.
	* What concepts require explanation.
	* How to present information so that the intended audience can scan and find content that fulfils their information needs.

After creating your information experience, you should evaluate and improve on it:

* Validate the logic behind your information flow as the intended audience moves between tasks. 
* Identify information gaps, such as incomplete steps, missing context or explanation, or a lack of technical depth.
* Identify and remove or fix confusing, out-of-date, inaccurate, redundant, or unnecessary information.
* Check your content for errors and that it meets the requirements outlined in your style guide.

## Product documentation

Product documentation articulates technical concepts, in writing, for a software company's products so that these products can be implemented by its customers. The documentation provides "how-to" guidance to help administrators:

- Understand how a product or service works.
- Keep up with new releases.
- Learn how to install, upgrade, manage, and troubleshoot products and services.

Administrators are sometimes called "users" because they use tools described in the documentation to set up the product or service. We use the term "administrator" to differentiate this type of user from the *end-users* of the product or service that the administrator sets up. 

Product documentation *isn't*:

* A complete list of every component or functionality.
* README content, which is more brief and includes details that don't belong in product documentation, such as licence or copyright details, and basic information about the code.
* Sales or Marketing material, such as blog posts or news articles, designed to convince a non-technical audience to adopt a feature or product. 
* A substitute for Technical Support, explaining or solving specific issues, in detail, with suggested fixes. 

That being said, good product documentation can reduce the number of calls to Technical Support by helping customers figure things out for themselves. Technical Support might use product documentation as well as a source of truth. To help customers, Technical Support might also refer to product documentation as a shared point of reference.

Other company employees might also benefit from your documentation, using it to keep up-to-speed with product developments. Additionally, the process of writing documentation during product development can potentially uncover issues with a feature or process before it's released.

There's also the wider audience to consider. Product documentation tends to attract key decision-makers, such as product managers and executives evaluating the complexity, size, and cost of implementation –– information that they can't fully garner from Marketing and Sales. 

Nevertheless, product documentation can overlap with Marketing and Sales material and shouldn't directly contradict it, even though the purpose, style, perspective, and approach between these sources of content are very different. 

Although more technical and direct than other sources of content, product documentation should maintain a style that's consistent with the [Voice and Tone](/voice-and-tone) of the company as a whole. Consistency is integral to brand-building and trust, and product documentation shouldn't undermine a company's overall brand and business goals. 

### Content framework and strategy

The administrator interaction with product documentation is, in itself, a user experience. This is additional to the interactions they have with the actual systems and interfaces that the product documentation refers to. To maximise the information experience of product documentation, you should plan and create a core content framework and strategy:

- **Content framework:** the **content and structural components** of documentation, including the information architecture (IA) that this content is built around.
- **Content strategy**: the methods and guidelines for developing and curating content –– the **process and people components** of product documentation management.

#### Content framework

A content framework deals with how we build, present, and organise content. 

Content should provide a coherent, consistent narrative throughout the product set-up and maintenance journey –– structured around the needs of the target audience so that administrators can find the right information and make use of it efficiently. Take the time to understand the target audience in the context of their needs and pain points, including: 

*  Audience goals and needs.
*  Audience tasks and activities.
*  Information-retrieval behaviour.
*  Audience knowledge and experience.

Make everything you write scannable, discoverable, and searchable. Think about *where* information is best placed and *how* to communicate flows of information (the procedures and processes administrators must follow to complete their tasks). This information:

*  Helps the reader figure out where they are in the documentation.
*  Helps the reader determine where the information they want is in relation to their current position.
*  Informs the **content strategy**.

#### Content strategy

Content strategy deals with how we create and maintain content, including what that content needs to be.

Product documentation should be purposeful and meaningful for the intended audience. Thus, content should be created with the business goals and the target audience in mind. Take the time to define:

*  How your content will help you meet business goals.
*  The target audience and their needs.
*  The [Voice and Tone](/voice-and-tone) of content for your audience.

Product documentation should be updated based on a roadmap for organising, scheduling, creating, and publishing content. Increasingly, this is achieved with a **Docs-as-Code** approach.

### Infrastructure and process (Docs-as-Code)

It's becoming increasingly popular to adopt a [Docs-as-Code](/online-documentation?id=what-is-docs-as-code) approach to managing product documentation.

Docs-as-Code involves using similar tools and processes to create and manage documentation as developers use for creating and managing code. Docs-as-Code typically matches the agile approach to delivering output, which might include using an issue tracking manager (such as JIRA), assigning tickets in bi-weekly sprints, and demoing completed doc work. 

With a Docs-as-Code approach to product documentation, content for a release is published only when a feature or update is available to customers. A release typically includes one specific feature or a narrowly defined set of features, the scheduling of which is at the discretion of the PM. For more information on what might be included in product documentation, see [Create the content](/get-started?id=_4-create-the-content) in the **Get Started with Product Documentation** article.

Once a content need is identified, a ticket should be created in an issue tracking tool. Once the technical author has enough information, they can start drafting, which might include creating a working branch for the feature off of the main documentation branch in Git. Content is merged at the same time as the public release of the feature, following approval from Engineering and the PM. The technical author pushes content to a remote repository and creates a Pull Request (PR). Depending on stakeholder needs, content can be reviewed directly in the PR.

For more information on the tools and processes involved in a Docs-as-Code approach, see the [Online Documentation](/online-documentation) article.

## In-product content development

As well as creating product documentation, IX technical authors typically help write and review in-product content in a UX writing capacity. 

UX writing is the process of creating user-friendly content for the UI of digital products to help the end-user interact with it. Here, we're concerned with UI copy, visual design, and interactions with the UI itself. 

Many technical writing principles apply to UX writing, and both product documentation and in-product content needs to conform to a company's voice and tone. It's thus common to ask technical writers to advise on aspects of UX writing. However, not all technical writers will take on the role of a UX writer, and UX writers will typically focus on the design of the product rather than writing the product documentation that comes with it, as technical writers do.

Technical writers collaborate *with* designers to contribute to the UI for an effective and engaging user experience. In collaboration with PD and the PM, IX can be asked to:

-  Provide early design insights into prototypes and the proposed flow of a feature or product.
-  Participate in design reviews or focused walkthroughs to answer specific questions, or identify and help resolve specific issues in the design.
-  Provide new end-to-end design feedback and recommendations on the same feature or product later in the development lifecycle.

As with product documentation, this can involve issue tracking software, and be implemented as part of agile and sprint cycles.

### UX writing

Good UX needs good content. The right UI copy to accompany the right designs, at the right time, influences how a user engages with a product.

UI copy includes buttons, menu labels, error messages, security notes, T&Cs, inline instructions, tooltips, and any kind of in-product instructions on product usage. UI copy speaks to the user and helps make their journey through the UI as smooth as possible.

This isn't the same as a copywriter, who writes and edits Marketing material. A copywriter creates content to attract and persuade customers as a sales effort, which requires a different style of writing.

UX writing also isn't about filling in the blanks and making suggested changes to the text after the product is already designed. A UX writer *is* a designer –– a designer *specialising in* UI copy.

As a design exercise, the optimal level of UX writer involvement in product design is at the beginning. UX writing is an integral part of designing the customer journey. This way, the UI can be designed as a unified source of information from the beginning of the design process, rather than having a UX writer come in at the end to fix surface-level issues with UI text.

A technical writer's input for in-product design might include:

* Improving the functionality, readability, and understandability of on-screen text.
* Creating friendly, informative, and clear on-screen dialogues.
* Suggesting user-centred, action-focused wording on buttons and labels.
* Creating or editing content for error messages.
* Proofreading for consistency and for language, spelling, and grammatical errors.
* Recommending different terminology or turns of phrase.
* Providing copy for in-product help, hints, and explanations.

Good UX writing gives the user what they need, in context, when they need it. When users hit a roadblock, effective in-product help content can make the difference between a negative and a positive experience. UX writers help embed this content into the application itself. This minimises the end-user's need to engage with documentation, by helping to make the UI more intuitive, which increases usability and reduces frustration.

#### UX writing and content design

UX writers and content designers (sometimes called content writers) have a lot in common. Both work with Product Design to create, deliver, and modify content to maximise the user experience of a product. 

However, UX writing focuses more on UI copy to facilitate the user experience of a product, while content design focuses more on the design of the product itself, which can include written content, but also involves designing the layout, flow, and the type of content to include. 

A content designer tends to be involved in a broader range of activities than a UX writer, identifying user needs for content and creating solutions that meet these needs. This solution might involve writing in-product content, but it might not. It might instead involve establishing consistency across platforms, restructuring the content on a page, making content more accessible, or developing other forms of media such as videos, graphics, animations, and audio. 

Content design is a more strategic role that is focused on the design outcome: what and how information is presented to users. The aim is to develop content that's purposeful, meaningful, structured, and usable to help end-users navigate through a product or service.

Though more strategic than a UX writer, a content designer isn't a content *strategist*, who would be more concerned with content priorities and planning based on business objectives, more so than the end-user experience. They analyse and manage content rather than create the content themselves.

#### Required knowledge and skills

Although UX writing is typically described in more narrow terms than content design, UX writers frequently engage in other important aspects of the design process, including:

* Conducting user research
* Writing style guides
* Engaging in early design processes
* Advocating for the end-user (the user experience)

Thus, UX writing involves a range of skills:

* **Writing.** The ability to write clearly and concisely, with attention to detail.
* **Creativity.** Lateral thinking and creative problem-solving.
* **UX design.** An understanding of product design processes and outcomes.
* **Research.** The ability to collate, understand, intepret, and present data, such as user testing and analytics that provide insight into how the product is used. 
* **Psychology.** An understanding of human behaviour and decision-making.
* **Empathy.** Empathy for the end-user and a desire to improve the user experience.

### UI review

Having an information developer responsible for UI copy helps ensure that information is clear and consistent, for a better user experience.

To this end, IX engages with PD for UI content review when the designer has developed a wireframe or prototype for a specific issue/ticket. The typical engagement flow is as follows:

1. **Early designs.** PD notifies IX that there is content to review, with links typically included in a ticket. PD might also provide a walk-through of the design, links to demos, or a detailed explanation of some of the screens in the prototype.
2. **Information gathering.** IX reviews the associated tickets and requests additional information from PD if needed to understand the intent of the design. 
3. **Feedback.** IX provides feedback on the prototype and asks any outstanding questions for information, confirmation, or clarification. Where multiple approaches to on-screen content are possible, IX provides clear options and preferences.
4. **Review.** PD incorporates IX feedback and reviews the completed prototypes with the PM for approval.
5. **"Ready for Implementation" (RFI).** PD completes the design, which is approved by the PM for implementation by Engineering. 
	-  Depending on priorities and Engineering bandwidth, the design might or might not be implemented. 
	-  IX might start drafting documentation for these designs.