# Overview of information development

This guide describes how **information development** shapes the user experience of digital products and services. As a whole, this guide offers:

-  An overview of information development and related concepts, with a focus on **technical writing** for [product documentation](/?id=product-documentation) and **UX writing** for [in-product content development](/?id=in-product-content-development).
- Voice, tone, and style guidelines for two key components of information development: [technical writing](/technical-writing) and [UX writing](/ux-writing).
- A description and high-level instructions for adopting a [docs-as-code](/online-documentation?id=what-is-docs-as-code) approach to creating and managing online documentation.

## Terminology

This section defines, delineates, and explains the relationship between information development and overlapping concepts (information experience, content design, and technical writing) to help the reader navigate the nuances.

**Information development** is concerned with designing the digital experience of product information: how information is formed, organised, delivered, presented, and so on. It encompasses activities such as writing, editing, structuring, and managing content to ensure that it's accurate, clear, and accessible to the intended audience. Because of the emphasis on writing, information developers are commonly also called **technical writers**, and they're often (but not always) involved in **UX writing** activities as well.

Information development is related to, but distinct from, **content design**. While information development primarily deals with the creation and management of content itself, content design focuses on how that content is presented and how users interact with content. This is why there was a move away from the term "content writer", which implies a focus on *written* content, to "content designer", which highlights content design as a UX design exercise.

The work of information developers affects the user's **information experience (IX)**. Information experience, or IX, refers to the holistic experience that users have when interacting with content. IX is a central part of user-centred design and considers the entire journey of the user, from discovering information to consuming it and completing tasks or achieving goals.

## What information developers do

**Information developers** work with software developers and UX designers to ensure that information is meaningful, accurate, user-friendly, and formatted appropriately, whether that's as part of documentation (**technical writing**) or in the product itself (**UX writing**). The aim is to optimise how people engage with information to maximise the user experience (UX) of a product. To this end, information developers are responsible for:

- Technical content authoring for a software company's products and services. For guidance on technical writing and, in particular, writing product documentation, see [Technical writing guidelines](https://jeunese.github.io/#/technical-writing).
- In-product content development (UX writing), such as error messages and on-screen text. For information on UX writing, see [UX writing guidelines](/ux-writing).
- Website infrastructure for product documentation. For an overview of this approach to managing documentation, see [Online documentation](/online-documentation).

In pursuit of providing a good IX for users, information developers also typically work closely with:

- Product teams, under the guidance of Product Management (PM), to help inform UI copy and understand user needs for technical documentation.
- Software developers and test engineers in Engineering to learn how a product or feature works and to effectively document it.
- Design teams to collaborate on UI content and guided workflows.
- Internationalisation (globalisation and localisation) teams to translate documentation and UI copy.

## Product documentation

Product documentation articulates technical concepts, in writing, for a software company's products so that these products can be implemented by its customers. The documentation provides "how-to" guidance to help administrators and users:

- Understand how a product or service works.
- Keep up with new releases.
- Learn how to install, upgrade, manage, use, and troubleshoot products and services.

> **Note:** Administrators are sometimes called "users" because they use tools described in the documentation to set up the product or service. We use the term "administrator" to differentiate this type of user from the *end users* of the product or service that the administrator sets up. 

Product documentation *isn't*:

* A complete list of every component or functionality.
* README content, which is more brief and includes details that don't belong in product documentation, such as licence or copyright details, and basic information about the code.
* Sales or Marketing material, such as blog posts or news articles, designed to convince a non-technical audience to adopt a feature or product. 
* A substitute for Technical Support, explaining or solving specific issues, in detail, with suggested fixes. 

That being said, good product documentation can reduce the number of calls to Technical Support by helping customers figure things out for themselves. Technical Support might also use product documentation as a shared point of reference and source of truth to help customers.

Other company employees might benefit from your documentation as well, using it to keep up-to-date with product developments. Additionally, the process of writing documentation during product development can potentially uncover issues with a feature or process before it's released.

There's also the wider audience to consider. Product documentation tends to attract key decision-makers, such as Product Managers (PMs) and executives evaluating the complexity, size, and cost of implementation, information that they can't fully garner from marketing and sales material. 

Nevertheless, product documentation can overlap with marketing and sales material and shouldn't directly contradict it, even though the purpose, style, perspective, and approach between these sources of content are very different. 

Although more technical and direct than other sources of content, product documentation should maintain a style that's consistent with the [Voice and Tone](/voice-and-tone) of the company as a whole. Consistency is integral to brand-building and trust, and product documentation shouldn't undermine a company's overall brand and business goals. 

### Content framework and strategy

The interaction with product documentation is, in itself, a user experience. This is additional to the interactions users and administrators have with the actual systems and interfaces that the product documentation refers to. To ensure the best information experience of product documentation, plan and create a core content framework and strategy:

- [**Content framework**](/?id=content-framework): the **content and structural components** of documentation, including the information architecture (IA) that this content is built around.
- [**Content strategy**](https://jeunese.github.io/#/?id=content-strateg): the **process and people components** of product documentation management, including the methods and guidelines for developing and curating content.

#### Content framework

A content framework deals with how we build, present, and organise content. 

Content should provide a coherent, consistent narrative throughout the product set-up and maintenance journey, structured around the needs of the target audience so that users can find the right information and make use of it efficiently. 

Take the time to understand the target audience in the context of their needs and pain points, including: 

*  Audience goals and needs.
*  Audience tasks and activities.
*  Information-retrieval behaviour.
*  Audience knowledge and experience.

Make everything you write scannable, discoverable, and searchable. Think about where information is best placed and *
how to communicate flows of information (the procedures and processes users must follow to complete their tasks). This information:

*  Helps the reader figure out where they are in the documentation.
*  Helps the reader determine where the information they want is in relation to their current position.
*  Informs the [content strategy](https://jeunese.github.io/#/?id=content-strategy).

#### Content strategy

Content strategy deals with how we create and maintain content, including what that content needs to be.

Product documentation should be purposeful and meaningful for the intended audience. Thus, content should be created with the business goals and the target audience in mind. Take the time to define:

*  How your content will help you meet business goals.
*  The target audience and their needs.
*  The [voice and tone](/voice-and-tone) of content for your audience.

Product documentation should be updated based on a roadmap for organising, scheduling, creating, and publishing content. Increasingly, this is achieved with a **docs-as-code** approach.

### Infrastructure and process (docs-as-code)

It's becoming increasingly popular to adopt a [docs-as-code](/online-documentation?id=what-is-docs-as-code) approach to managing product documentation.

Docs-as-code involves using similar tools and processes to create and manage documentation as developers use for creating and managing code. Docs-as-code typically matches the agile approach to delivering output, which might include using an issue tracking manager (such as Jira), assigning tickets in bi-weekly sprints, and demoing completed doc work. 

With a docs-as-code approach to product documentation, content for a release is published at the same time that a feature or update is available to customers. A release typically includes one specific feature or a narrowly defined set of features, the scheduling of which is at the discretion of the PM. For more information on what might be included in product documentation, see [Create the content](/get-started?id=_4-create-the-content) in the **Get started with product documentation** article.

After a content need is identified, a ticket should be created in an issue tracking tool. When the technical author has enough information, they can start drafting, which might include creating a working branch for the feature off of the main documentation branch in Git. Content is merged at the same time as the public release of the feature, following approval from Engineering and the PM. The technical writer (information developer) pushes content to a remote repository and creates a Pull Request (PR). Depending on stakeholder needs, content can be reviewed directly in the PR.

For more information on the tools and processes involved in a docs-as-code approach, see the [Online Documentation](/online-documentation) article.

## In-product content development

As well as creating product documentation, information developers often help write and review in-product content in a UX writing capacity. In collaboration with Design and the PM, an IX team can be asked to:

-  Provide early design insights into prototypes and the proposed flow of a feature or product.
-  Participate in design reviews or focused walkthroughs to answer specific questions, or identify and help resolve specific issues in the design.
-  Provide new end-to-end design feedback and recommendations on the same feature or product later in the development life cycle.

As with product documentation, this can involve issue tracking software, and can be implemented as part of agile and sprint cycles.

### UX writing

Good UX needs good content. UX writers help embed this content into the application or website itself. 

UX writing is the process of writing in-product content to facilitate the user experience of that product, in line with the company's [voice and tone](/voice-and-tone).

A UX writer take insights from UI and UX design principles, usability research, and behavioural psychology to create and refine content that's designed for the end-user of a product, from large blocks of text to a product's UI elements and microcopy.

#### What UX writing is and isn't
UX writing is the process of creating user-friendly textual content (copy) for the UI of digital products to help users interact with it.

UI copy includes buttons, menu labels, error messages, security notes, T&Cs, inline instructions, tooltips, and any kind of in-product instructions on product usage. The right UI copy to accompany the right designs, at the right time, influences how a user engages with a product. When users hit a roadblock, effective in-product content can make the difference between a negative and a positive experience. 

UX writing isn't the same as a copywriting. A copywriter writes and edits marketing material, creating content to attract and persuade customers as a sales effort, which requires a different style of writing.

UX writing also isn't about filling in the blanks and making suggested changes to the text after the product is already designed. A UX writer *is* a designer –– a designer *specialising in* UI copy.

The aim is to create a cohesive content experience. For this reason, it's sometimes described as a sub-discipline of content design. See [UX writing and content design](/?id=ux-writing-and-content-design) for more information on the similarities and differences.

#### UX writing and technical writing

Technical writers can contribute in a UX writing capacity by collaborating with designers for an effective and engaging user experience.

Many technical writing principles apply to UX writing, and both product documentation and in-product content should conform to a company's voice and tone. It's thus common to ask technical writers to advise on aspects of UX writing. However, not all technical writers will take on the role of a UX writer, and dedicated UX writers will typically focus on the design of the product rather than writing the product documentation that comes with it, as technical writers do. A technical writer's input for in-product design might include:

* Improving the functionality, readability, and understandability of on-screen text.
* Creating friendly, informative, and clear on-screen dialogues.
* Suggesting user-centred, action-focused wording on buttons and labels.
* Creating or editing content for error messages.
* Proofreading for consistency and for language, spelling, and grammatical errors.
* Recommending different terminology or turns of phrase.
* Providing copy for in-product help, hints, and explanations.

#### UX writing and content design

UX writers and content designers (sometimes called content writers) have a lot in common. Both work with Design to create, deliver, and modify content to maximise the user experience of a product. 

UX writing focuses more on UI copy to facilitate the user experience of a product, while content design focuses more on the design of the product itself, which can include written content, but also involves designing the layout, flow, and the type of content to include. 

A content designer tends to be involved in a broader range of activities than a UX writer, identifying user needs for content and creating solutions that meet these needs. This solution might involve writing in-product content, but it might not. It might instead involve establishing consistency across platforms, restructuring the content on a page, making content more accessible, or developing other forms of media such as videos, graphics, animations, and audio. 

Content design is a strategic role that's focused on the design outcome: what and how information is presented to users. The aim is to develop content that's purposeful, meaningful, structured, and usable to help end-users navigate through a product or service.

Though more strategic than a UX writer, a content designer isn't a content *strategist*, who would be more concerned with content priorities and planning based on business objectives, more so than the end-user experience. Content strategists analyse and manage content rather than create the content themselves.

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
* **Empathy.** Empathy for the user and a desire to improve the user experience.

### UI review

Having an information developer responsible for UI copy helps ensure that information is clear and consistent, for a better user experience.

To this end, technical writers (or information developers) in information development and IX teams engage often engage with the Design team for UI content review when the designer has developed a wireframe or prototype for a specific issue/ticket. The typical engagement flow is as follows:

1. **Early designs.** Product Design notifies the information developer that there is content to review, with links typically included in a ticket. Product Design might also provide a walkthrough of the design, links to demos, or a detailed explanation of some of the screens in the prototype.
2. **Information gathering.** The information developer reviews the associated tickets and requests additional information from Product Design if needed to understand the intent of the design. 
3. **Feedback.** The information developer provides feedback on the prototype and asks any outstanding questions for information, confirmation, or clarification. Where multiple approaches to on-screen content are possible, the information developer provides clear options and preferences.
4. **Review.** Product Design incorporates information developer feedback and reviews the completed prototypes with the PM for approval.
5. **"Ready for Implementation" (RFI).** Product Design completes the design, which is approved by the PM for implementation by Engineering. 
	-  Depending on priorities and Engineering bandwidth, the design might or might not be implemented. 
	-  The information developer might start drafting documentation for these designs.