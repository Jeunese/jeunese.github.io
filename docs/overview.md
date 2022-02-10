# Information Development Overview

An Information Development (or Information Experience, IX) team consists of technical writers that typically belong to Engineering. IX are responsible for:

- Technical content authoring for a company's products and services. See [Technical Writing Guidelines](https://jeunese.github.io/#/technical-writing).
- In-product content development, such as error messages and on-screen text. See [UX Writing Guidelines](/ux-writing).
- Website infrastructure for product documentation. See [Online Documentation](/online-documentation).

As well as Engineering, information developers typically work closely with:

- Product teams, under the guidance of Product Management (PM).
- Product Design (PD) to collaborate on UI content and guided workflows.
- Globalisation teams to create automatic translation.

## Product documentation

Product documentation articulates technical concepts, in writing, for a software company's products and services so that these products and services can be implemented by its customers. It provides "how-to" guidance written for administrators to help them:

- Understand how a product or service works.
- Keep up with new releases.
- Learn how to install, upgrade, manage, and troubleshoot products and services.

Administrators are sometimes called "users" because they use tools described in the documentation to set up the product or service. We use the term "administrator" to differentiate this type of user from the *end-users* of the product or service that the administrator sets up. 

Product documentation shouldn't be confused with README content, which is more brief and includes details that don't belong in product documentation, such as licence or copyright details, basic information about the code, and how to build the project.

Product documentation isn't a complete list of every component or functionality. It also isn't Sales or Marketing material such as blogs or news designed to convince a non-technical audience to adopt a feature or product. And, it isn't a substitute for Technical Support, explaining or solving specific issues, in detail, with suggested fixes. 

That being said, good product documentation can reduce the number of calls made to Technical Support. Customers often call Technical Support when they can’t figure something out. Good product documentation helps customers figure things out for themselves. Technical Support might also use product documentation as a point of reference.

There's also the wider audience to consider. Product documentation tends to attract key decision-makers, such as product managers and executives evaluating the complexity, size, and cost of implementation –– information that they can't fully garner from Marketing and Sales materials. 

Nevertheless, product documentation can overlap with Marketing and Sales material and shouldn't directly contradict it, even though the purpose, style, perspective, and approach between these sources of content are very different. 

Although more technical and direct than Sales and Marketing content, product documentation should maintain a [voice and tone](/voice-and-tone) that is consistent with the voice and tone of the company as a whole. Voice and tone is integral brand-building and trust. Product documentation shouldn't undermine the company's overall brand and business goals.

### Content framework and strategy

The administrator interaction with product documentation is, in itself, a user experience. This is additional to the interactions they have with the actual systems and interfaces that the product documentation refers to. To maximise the information experience of product documentation, you should plan and create a core content framework and strategy:

- A core **content framework**: the **content and structural components**, including the information architecture (IA) this content is built around.
- A core **content strategy**: the methods and guidelines for developing and curating content –– the **process and people components** of product documentation management.

#### Content framework

A content framework deals with how we build, present, and organise content. 

Content should provide a coherent, consistent narrative throughout the product set-up and maintenance journey –– structured around the needs of the target audience so that administrators can find the right information and make use of it efficiently. Take the time to understand and plan for the target audience in the context of their needs and pain points, including: 

*  User goals and needs
*  User tasks and activities
*  Information-retrieval behaviour	
*  User knowledge and experience

Make everything you write scannable, discoverable, and searchable. Think about *where* information is best placed and *how* to communicate flows of information (procedures and processes). This information:

*  Helps the reader figure out where they are in the content.
*  Helps the reader determine where the information they want is in relation to their current position.
*  Informs the **content strategy**.

#### Content strategy

Content strategy deals with how we create and maintain content, including what that content needs to be.

Product documentation should be purposeful and meaningful for the intended audience. Thus, content should be created with the business goals and the target audience in mind. Take the time to define:

*  How your content will help you meet business goals.
*  The target audience and their needs.
*  The voice and tone of content for your audience.

Product documentation should be updated based on a roadmap for organising, scheduling, creating, and publishing content. Increasingly, this is achieved with a **Docs-as-Code** (or **Open Docs**) infrastructure.

### Infrastructure and process (Docs-as-Code)

With a [Docs-as-Code](/online-documentation?id=what-is-docs-as-code) approach to product documentation, content for a release is published only when a feature or update is available to customers. Features might also be published for private and public (technical) preview. 

A release typically includes one specific feature or a narrowly defined set of features, the scheduling of which is at the discretion of the PM.  Candidates for product documentation include:

-  A new product, feature, or important component release.
-  An important update to an existing feature.
-  Information on how to install, upgrade, manage, or troubleshoot.
-  Public technical preview content.

Once a content need is identified, a ticket should be created in an issue tracking tool, such as JIRA. Once the technical author has enough information, they can start drafting, which might include creating a working branch for the feature off of a Master branch in Git. Content is merged at the same time as the public release of the feature, following approval from Engineering. The technical author pushes content to a remote repository and creates a Pull Request (PR). Depending on stakeholder needs, content can be reviewed directly in the PR.

## In-product content development

IX technical authors also typically help write and review in-product content for end-users in a [UX writing](/ux-writing) capacity. This can also be done with issue tracking software, and as part of agile and sprint cycles.

In collaboration with PD and the PM, IX can be asked to:

-  Provide early design insights into design prototypes and the proposed flow of the feature.
-  Participate in design reviews or focused walkthroughs to answer specific questions, or identify and help resolve specific issues in the design.
-  Provide new end-to-end design feedback and recommendations on the same feature later in the development lifecycle.

### UX writing

UX writing is the process of creating in-product copy for the UI of digital products to help the end-user interact with it. UI text speaks to the user and helps them make their journey through the UI as smoothly as possible. When users hit a roadblock, effective help content can make the difference between a negative and a positive experience. 

UI copy includes buttons, menu labels, error messages, security notes, T&Cs, inline instructions, tooltips, and any kind of in-product instructions on product usage. 

The optimal level of UX writer involvement in product design should be at the beginning. The right words to accompany the right designs make all the difference to how a user engages with a product. This means that UX writing is a design exercise and an integral part of designing the customer journey.

### UI review

IX engages with Product Design (PD) for UI content review when PD has developed a wireframe or prototype for a specific Engineering ticket. The typical engagement flow is as follows:

1. **Early designs.** PD notifies IX that there is content to review, with links typically included in a ticket. PD might also provide a walk-through of the design, links to demos, or a detailed explanation of some of the screens in the prototype.
2. **Information gathering.** IX reviews the associated tickets and requests additional information from PD if needed to understand the intent of the design. 
3. **Feedback.** IX provides feedback on the prototype and asks any outstanding questions for information, confirmation, or clarification. Where multiple approaches to on-screen content are possible, IX provides clear options and preferences.
4. **Review.** PD incorporates IX feedback and reviews the completed prototypes with the PM for approval.
5. **"Ready for Implementation" (RFI).** PD completes the design, which is approved by the PM for implementation by Engineering. 
	-  Depending on priorities and Engineering bandwidth, the design might or might not be implemented. 
	-  IX might start drafting documentation for these designs.


