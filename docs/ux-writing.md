# UX Writing Guidelines

General guidance for UX writing include:

-  Engage early with Product Design (PD).
-  Set the strategy early in your writing.
-  Take a user-centred approach.
-  Keep messages short.
-  Use voice, tone, and terminology consistently across different modes.
-  Address the reader directly; avoid referring to "users" or "customers".
-  Avoid using the same word twice in the same screen.
-  Avoid negative words.
-  Use sentence case for everything except global navigation and boolean values.

More specific guidance depends on the type of UX writing you're engaged in.

## UX writing categories

The main categories of UX writing are:

### Micro copy

Micro copy refers to the words or very short sentences that tell a user what to do, address user concerns, and provide context to a situation. Examples of micro copy include: title bars, buttons, menus, error messages, labels, supplementary explanations, checkbox options, dropdown lists, row/column headings and entries, and so on.

### Contextual help

Contextual help is on-demand content based on the state that an application is in when a user seeks help, such as instructions, tooltips, guided workflows, and so on. Help that is offered in context is easier to identify and use (has high affordance) and us less disruptive; rather than interrupt the workflow by forcing the user to browse an online manual or help centre, context-sensitive help delivers content relevant to the part of the program that the user is interacting with. It is thus better if the user can access this help without leaving the current workflow, which can achieved with **in-product instructions**.

### In-product instructions

In-product instructions (or on-screen text) are contextual help presented inline with the interface content, which avoid making users switch between tools to get help. They help the user understand what a feature does or how to populate a field. This allows the user to solve problems without waiting for assistance or referring to a user manual, reducing the number of incoming queries to the support team.

In-product instructions are the least demanding way to offer support because they prevent the user from having to rely on working memory or from having to take an extra step to find information. To maximise the chances of positive experience, in-product assistance should:

-  Cause minimal disruption to the user's workflow.
-  Result in quick issue or query resolution.
-  Foster ease-of-use.
-  Be timely and well-placed, appearing the moment the user needs them and embedded directly in the interface.
-  Provide **progressive disclosure**.

## Progressive disclosure philosophy

Progressive disclosure is an interaction design pattern that sequences information and actions across screens and reveals only essential information. This avoids overwhelming the user and helps them manage complexity. It also makes products easier to learn and use, avoids frustration and confusion, and reduces the number of potential errors. Some guidelines include:

-  Don't bombard the user with a lot of information as soon as they're introduced to the product.
-  Allow the information to progress naturally, from simple to complex.
-  Help the user move from completing tasks with essential information to completing more complex tasks with additional info.
-  Build upon each subsequent step of information experience and learning.
-  Provide only the necessary information for the user to take each action, one at a time.

With the progressive disclosure philosophy in mind, the UX writer should consider when to use the following types of micro copy and contextual help to guide the user as part of an in-product strategy. You can decide on the type of copy you're providing based on the required level of detail.

### On-screen copy (inline instruction)

On-screen copy is brief text that appears on the page, alongside the UI element it references, and it is used when the information is:

-  Essential to performing the task.
-  Directly actionable. 

If there is enough space, the UX writer might also decide to include:

-  Important but not directly actionable information
-  Supplementary information, preventing the user from having to navigate elsewhere to find it

Embedding information directly within a feature in this way is often the best choice for providing contextual help. It can, however, make the interface look cluttered or might not provide enough information to be useful. If this is the case, consider using **tooltips**.

### Tooltips

Tooltips are user-triggered, brief informative messages that appear when the user interacts with a UI element by clicking or hovering over it. Tooltips are offered when additional content might help the user make more informed decisions based on specific, contextual information. They typically provide a short description of the element or functionality that users might want or need to know more about; tooltips disappear, and so they shouldn't be used for directly-actionable or essential information required to perform a task.

Tooltips are useful with:

-  Unlabelled controls and command buttons with graphic labels.
-  Labelled controls and UI elements that benefit from supplemental information that doesn't fit as on-screen text.
-  As a form of progressive disclosure with help (?) and info (i) icons, eliminating the need for descriptive text on screen if not essential to the primary task.

### Walk-throughs (guided help)

A series of messages or tooltips appearing one at a time to provide step-by-step instructions that will guide a user through a feature, used when the functionality or workflow is more complex or spread across multiple pages. A walk-through provides step-by-step guidance and instructions.

### Page-level help

Context-sensitive topics that are triggered when the user selects a link provided at page level, used when the user might need conceptual or bigger-picture information (such as UI use cases) to help them understand the page that the user is on. This provides users with a way of getting detailed information without having to navigate or search different sites.

## Writing and reviewing UI content

Before writing or reviewing UI content, the UX writer needs to know:

-  Who they're writing for, such as end-users or administrators.
-  How the product is used. 
-  What the use cases are.
-  What components of the product need written or reviewed (if not the end-to-end experience).

### Guidelines for tooltips

The text in a tooltip must be informative. You should aim to:

-  Avoid redundant information.
-  Provide helpful content.
-  Provide information that isn't otherwise obvious and doesn't repeat on-screen copy.
-  Focus on the control's action, for example, by beginning the tag with a verb.

Tooltip text should provide additional and useful information, such as why a field is required or what will be done using the value entered into a field. Other guidelines for using tooltips include:

-  Use the fewest words possible.
	-  For labelled controls, limit tooltips to 15 words (if more text is need, this suggests that the design is too complicated).
	-  For tooltips triggered by clicking help icons, limit text to no more than 40 words (if more content is required, consider adding a Learn more link to the exact documentation, but use such links sparingly, which you might achieve by including one link at the page level).
-  If you need to reduce the length of a tag, omit grammatical articles.
-  Keep in mind that localisation can lengthen text by 20 to 30 percent.

Tooltips used in touchscreen devices are called popup tips, following the same guidelines as tooltips, except that they require a specific initiation/termination method.

### Guidelines for instructional text

**Keep it simple.** Don't overuse instructional UI text; copy should enhance the experience, not clutter it.

-  Don't explain fundamental features; if a user needs instructions, consider making the service design more intuitive.
-  Don't explain obvious features and workflow (instructional text will get in the way of an already intuitive workflow).
-  Don't make users engage with instructional text; users should be free to ignore instructional UI and still progress through it.
-  Don't repeat information; add a setting to display instructional UI instead.

**Keep it useful.** Use instructional text to make the onboarding flow as smooth as possible
	
-  The most immediate instructions should be those that apply to every page.
-  Focus on the actions that the user needs to take.
-  Provide information about prerequisites and next steps.
-  Ensure warnings are relevant to the task.
-  Include tips that might help the user complete their task.

### Guidelines for UI messages

In general, messages should:

-  Be written in a consistent style.
-  Be friendly.
-  Use simple language.
-  Provide sufficient and not excessive information.
-  Avoid jargon and technical detail; if technical detail might be wanted or needed, use progressive disclosure.
-  Suggest next steps.

If a product requires an extended activity, direct the user with clear, conversational language, for example, *"Do you need more time?"*

For error messages:

-  Use a language that encourages the user to come back or try again. 
-  Turn error messages and 404 pages into positive reinforcement by guiding the user along until they complete their task. 
-  Focus on the solution, not the error or mistake.
-  Don't blame the user.
-  Be kind to users who encounter situations in the product UI that could be frustrating for them, such as 404 pages.
-  Use missteps as an opportunity to encourage users to keep navigating through the product.

General recommendations for each element of a message, whichever type it is, are:

-  For titles, use sentence case capitalisation and no ending punctuation, unless the statement is a question.
-  For the message body, use complete sentences, sentence case capitalisation, and ending punctuation.
-  For the buttons, use sentence case punctuation but no end punctuation, and use short, action verbs unless the buttons require a simple **Yes | No**.

### Guidelines for UI elements

-  Use a logical order for UI elements. Avoid alphabetical (because it is language-dependent) unless no other order can be found.
-  Use one word for CTA and text buttons unless there is a verb involved.
-  Don't use "click here" on a link.
-  Avoid using abbreviations and acronyms in UI content unless space is severely limited or the acronym is better known than the full term (for example, URL).
-  Use "percent" without a number in column headings.
-  Use the the `%` symbol in UI, charts, and table cells, or as a technical symbol.