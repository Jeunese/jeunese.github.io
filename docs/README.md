# Information Development Overview

An Information Development (or Information Experience, IX) team consists of technical writers that typically belong to Engineering and are responsible for:

-  Website infrastructure for product documentation
-  Technical content authoring for a company's products and services
-  In-product content development, such as error messages and on-screen text

As well as Engineering, information developers work closely with:
-  Product teams, under the guidance of Product Management
-  Product Design to collaborate on UI content and to ensure that guided workflows are provided
-  Globalization to create automatic translation

## Product documentation

Product documentation is "how-to" guidance written for administrators to help them:

-  Understand how a product or service works
-  Keep up with new releases
-  Learn how to install, upgrade, manage, and troubleshoot products and services

Product documentation articulates technical concepts in writing for a company's products and services. 

It isn't a complete list of every component, command, API reference, or library. That's what developer documentation is for. It also isn't Sales or Marketing material such as blogs or news designed to convince a non-techncial audience to adopt a feature or product. And, it isn't a substitute for Technical Support, with detailed content for explaining or solving specific issues with a suggested fix that goes beyond a brief summary.

Product documentation should help the reader get set up as quickly and smoothly as possible. There is also the expanded audience to consider, which often includes key decision-makers, such as product managers and executives, who are evaluating the complexity, size, and cost of implementation.

### Content framework and strategy

The administrator interaction with product documentation is, in itself, a user experience. This is additional to the interactions they have with the actual systems and interfaces that the product documentation refers to. To maximise the information experience of product documentation, you should plan and create a content framework and strategy. 

To provide a coherent, consistent narrative throughout the product journey, product documentation needs to be be organised around:

-  A core **content framework**: the **content and structural components**, including the information architecture (IA) this content is built around.
-  A core **content strategy**: the methods and guidelines for developing and curating content –– the **process and people components** of product documentation management.

#### **Content framework**

A content framework deals with the **content and structural components** of documentation –– how we present and organise content –– including:

*  Categorisation:
	*  Organisation schemes (e.g., alphabetical, chronological, geographical, topic, task, audience, story).
	*  Organisation structures (e.g., flat hierarchy, deep hierarchy, sequential, matrix, database).
*  Navigation and signposting:
	*  Labelling systems (representing information).
	*  Browsing systems (how users move through content).
	*  Search systems (how users look for content).
*  Implementation:
	*  Document and data types.
	*  Content objectives.
	*  Volume of content.
	*  Existing structure.
	*  Governance and ownership.
*  Context –– planning the content framework based on:
	*  Business goals for product documentation.
	*  Businsse culture, funding, and politics.
	*  Technology and resources for building a framework; constraints.

Content should be structured around the needs of the target audience so that administrators can find the right information and make use of it efficiently. Take the time to understand and plan for the target audience in the context of their needs and pain points, including: 

*  User goals and needs
*  User tasks and activities
*  Information-retrieval behaviour	
*  User knowledge and experience

Think about *where* information is best placed and *how* to communicate flows of information (procedures and processes). This information:

*  Helps the reader figure out where they are in the content.
*  Helps the reader determine where the information they want is in relation to their current position.
*  Informs the **content strategy**.

#### **Content strategy**

Content strategy deals with the **process and people components** of documentation –– how we create and maintain content –– including:

*  Determining the substance:
	*  What the content *is* or needs to be
	*  Ensuring the content is purposeful and meaningful for the intended audience
*  Determining the structure of content, based in part on the **content framework** and IA (above), but also in terms of the content itself, including:
	*  Content separation
	*  Priority of content
	*  Content bridging
*  Organising people components:
	*  Workflow –– how people create, manage, and maintain content, including roles, tasks, and tools required throughout the content lifecycle
	*  Governance, consisting of:
		*  Policies, standards, rules, and guidelines that apply to content and the content lifecycle, including how you'll sustain and evolve your content strategy
		*  The hierarchy of decision-makers and a communication structure for maintaining the quality of user experience based on content

Content should be created with the business and user goals and activities in mind. Take the time to define:

*  How your content will help you meet business goals.
*  The target audience.
*  The voice and tone of content for your audience.

Product documentation should be updated based on a roadmap for organising, scheduling, creating, and publishing content. Increasingly, this is achieved with a **Docs as Code** (or **Open Docs**) infrastructure.

### Infrastructure and process (Docs as Code)

With a **Docs as Code** (**Open Docs**) approach to product documentation, content for a release is published only when the feature is available to the public (general availability, GA). Features might also be published for private and public (technical) preview. 

Content authoring can start at any time providing the technical author has the information needed to start drafting. A release typically includes one specific feature or a narrowly defined set of features, the scheduling of which is at the discretion of the PM.  Candidates for product documentation include:

-  A new product, feature, or important component release.
-  An important update to an existing feature.
-  Information on how to install, upgrade, manage, or troubleshoot the product.
-  Public technical preview content.

Once a content need is identified, a ticket should be created in an issue tracking tool, such as JIRA. Once the technical author has enough information to start drafting, which might include creating a working branch for the feature off of a Master branch in Git.

Content is merged at the same time as the public release of the feature and so the PM must confirm GA of the feature before the technical author can publish approved content. Depending on stakeholder needs, content can be reviewed content directly in a Pull Request (PR). The technical author pushed content to a remote repository and creates a PR. 

## In-product content development

Information Development teams also tyically help write and review in-product content. This can also be done with issue tracking software, and as part of agile and sprint cycles.

IX might also:
-  Be available prior to the construction of wireframes and prototypes, providing content stubs or other insights relative to the proposed flow of the feature. 
-  Participate in design reviews or focussed walkthroughs, in collaboration with PD and the PM, to resolve specific questions or issues in the design, repeating this process until the design reaches RFI
-  Provide new end-to-end design feedback on the same feature several weeks or months later due to changing requirements.

### UX writing

UX writing is the process of creating in-product copy for the UI of digital products that helps the user interact with it, using emotions, accuracy, and strategy. UI text speaks to the user and helps them make their journey through the UI as smoothly as possible. When users hit a roadblock, effective help content can make the difference between a negative and a positive experience. 

UI copy includes buttons, menu labels, error messages, security notes, T&Cs, inline instructions, tooltips, and any kind of in-product instructions on product usage. 

The optimal level of UX writer involvement in product design should be at the beginning. The right words to accompany the right designs make all the difference to how a user engages with your product. This means that UX writing is as much a design exercise as an illustration or animation. For this reason, UI copy should be an integral part of designing the customer journey.  Fully involving a UX writer from the start of product design positively affects user satisfaction.

### UI review

Information Development engages with Product Design (PD) for UI content review when PD has developed a wireframe or prototype for a specific ticket. The typical engagement flow is as follows:

1. **Wireframes and prototypes.** PD notifies IX that there is content to review, with links typically included in a ticket. PD will often also provide a walkthrough of the design, links to demos, or a detailed explanation of some of the screens in the prototype.
2. **Information gathering.** IX reviews the associated tickets and requests additional information from PD if needed to understand the intent of the design. 
3. **Feedback.** IX provides feedback on the prototype and asks any outstanding questions for information, confirmation, or clarification. Where multiple approaches to on-screen content are possible, IX provides clear options and preferences. IX notifies PD that feedback is available.
4. **Review.** PD incorporates IX feedback and reviews the completed prototypes with the PM for approval.
5. **"Ready for Implementation" (RFI).** PD completes the design, which is approved by the PM for implementation by Engineering. 
	-  Depending on priorities and Engineering bandwidth, the design may or may not be implemented. 
	-  IX may start drafting documentation for these designs with the understanding that changes may be made, which may be significant depending on how far ahead this documentation is being drafted.


