# UX Writing Guidelines

General guidance for UX writing includes:

-  Engage early with Product Design (PD).
-  Take a user-centred approach.
-  Keep messages short.
-  Address the reader directly; avoid referring to "users" or "customers".
-  Avoid using the same word twice in the same screen.
-  Avoid negative phrasing and words.
-  Use sentence case for everything except global navigation and boolean values.
-  Avoid using abbreviations and acronyms in UI content unless space is severely limited or the acronym is better known than the full term (for example, URL).

More specific guidance depends on the type of UX writing you're engaged in.

## UX writing

A UX writer helps craft in-product content as part of the product design process. This includes in-product text, buttons, messages, labels, and other UI touchpoints that guide a user through a product or service.

This is not the same as a copywriter, who writes and edits Marketing material. A copywriter creates content to attract and persuade customers as a sales effort, which requires a different style of writing.

A UX writer is responsible for creating in-product content that's in line with the company's [tone of voice](/voice-and-tone?id=tone-of-voice) and that facilitates the user experience of the product. UX Writers take insights from UI and UX design, usability, and behavioural psychology to iterate and refine content that is designed for the end-user of a product, from large blocks of text to a product's UI elements and microcopy. 

Before writing or reviewing UI content, the UX writer needs to know:

-  Who they're writing for, such as end-users or administrators.
-  What the user's goals and needs are.
-  What the product is and how the product is used. 
-  What the use cases are.
-  What components of the product need written or reviewed (if not the end-to-end experience).

The aim is create a cohesive content experience. For this reason, it's sometimes described as a sub-discipline of content design. See [UX writing and content design](/ux-writing?id=ux-writing-and-content-design) for more information on the similarities and differences.

## UX writing and information development

Technical writers are also sometimes called "information developers", and may work with other writers as part of an information development or information experience (IX) team.

Depending on their background, a technical writer can help create user-friendly, in-product content. Many technical writing principles apply to UX writing, and both product documentation and in-product content needs to conform to a company's voice and tone.

It is thus common to ask technical writers to advise on aspects of UX writing. However, not all technical writers will take on the role of a UX writer, and UX writers will typically focus on the design of the product rather than writing the product documentation that comes with it, as technical writers do.

A technical writer's input for in-product design might include:

* Improving the functionality, readability, and understandability of on-screen text.
* Creating friendly, informative, and clear on-screen dialogues.
* Suggesting user-centered, action-focused wording on buttons and labels.
* Creating or editing content for error messages.
* Proofreading for consistency and for language, spelling, and grammatical errors.
* Recommending different terminology or turns of phrase.
* Providing copy for in-product help, hints, and explanations.

## UX writing and content design

UX writer and content designers (sometimes called content writers) have a lot in common. Both work with Product Design to create, deliver, and modify content to maximise the user experience of a product. 

However, UX writing focuses more using UI copy to facilitate the user experience of a product, while content design focuses more on the design of the product itself, which can include written content, but also involves designing the layout, flow, and the type of content to include. 

A content designer tends to be involved in a broader range of activities than a UX writer, identifying user needs for content and creating solutions that meet these needs. This solution might involve writing in-product content, but it might not. It might instead involve establishing consistency across platforms, restructuring the content on a page, making content more accessible, or developing other forms of media such as videos, graphics, animations, and audio. 

Content design is a more strategic role that is focused on the design outcome: what and how information is presented to users. The aim is to develop content that is purposeful, meaningful, structured, and usable to help end-users navigate through a product or service.

Though more strategic than a UX writer, a content designer isn't a content *strategist*, who would be more concerned with content priorities and planning based on business objectives, more so than the end-user experience. They analyse and manage content rather than create the content themselves.

## Required knowledge and skills

UX writing isn't about filling in the blanks and making suggested changes to the text after the product is already designed. 

As part of product design, UX writers should be involved early in the design process, alongside UX and UI designers, UX researchers, and information architects. A UX writer *is* a designer –– a designer *specialising in* UI copy.

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

## UI elements and input controls

To write consistent, accurate, and clear UI copy, a UX writer needs to understand what each UI element does and best practices for creating them. Every UI element has a specific purpose and guidelines you should follow. These guidelines streamline the content and promote consistency. General guidelines for UI elements and controls include:

### Alt text

Alt text is a label that screen readers can use to describe an image. Alt text appears when images don't render. Guidelines for alt text include: 

- Describe the image in brief (1-2 sentences).
- Use sentence case.

### Boolean values and toggles

Boolean values are a visual representation of an on/off state, such as a switch. If "off" and "on" are inappropriate for the context, different words that fit the context are used instead. Guidelines for boolean values include:

- Write words to fit the context (for example, `On | Off`, `True | False`, `Yes | No`).
- Don't use all caps; use title case.
- If a label for an option runs long, don't truncate the label.
	- Wrap the label to multiple lines, if necessary.
	- Align the UI element with the fist line of the label.

A toggle provides users with a choice between the two mutually exclusive states of a boolean value. 

A user should be able to make selections with only a screen reader and keyboard. To this end, they should be able to:
- Understand the current state of the selection
- Tab through a set of options and navigate between options using the arrow keys
- Use the spacebar to select and deselect an option

### Buttons

Buttons are labels that, when selected, initiate an action that allows the user to complete a task. Guidelines for buttons include:

- Use clear, precise, predictable language.
- Lead with a verb that encourages an action, like `Cancel` and `Delete`.
-  Use one word for call-to-action (CTA) and text buttons unless there is a verb involved.
- If not a common action (like `Done` or `Close`) use the {verb}+{noun} formula (such as, `Test connection` or `Add selected items`).
- Don't include descriptors like "now" –– the resulting action from selecting a button should be instantaneous.
- Avoid introductory labels for buttons; the button label should be enough.
- Don't use buttons for a list of choices.
- Separate destructive buttons from non-destructive buttons so that the user must make an intentional effort to select the button.
- Be specific about single items (for example, `Choose picture` rather than `Import`).
- Use trailing ellipsis when the button opens another window, dialogue box, or app.
- If not using a specific action (as recommended), use the word `OK` rather than Ok, ok, or Okay.
- Use sentence case.

### Checkboxes

Checkboxes are controls that let the user choose between two opposite states, actions, or values. A checkbox is on when it contains a checkmark (indicating that it's selected) and off when it's empty. Guidelines for checkboxes include:

- Make clear what happens when the box is selected versus not selected.
- Always follow a checkbox with a title or label.
- Provide a title that implies two opposite states.
- Place an action at the beginning of the title.
- Keep the text for a checkbox on a single line.
- Use positive phrasing (selecting a checkbox shouldn't mean *not* performing an action, unless it's a "Don't show this again" checkbox).
- For each checkbox in a group, use parallel phrasing.
- Label a group of checkboxes to make the purpose of the checkboxes evident, ending with a colon.
- Don't use ending punctuation, unless it's a colon at the end of a label for a group of checkboxes.
- For large sets, use subheadings to group choices.
- Present checkboxes in a logical order.
- Add "Recommended" to the label for a checkbox that is strongly recommended.
- Use sentence case.

### Console (push) notifications

Push notifications are visual indicators on a list or details page in a console that show when a record or field has changed during a user's session. Guidelines for push notifications include:

- Use action-oriented, positive phrasing in top-level notifications.
- Keep the language simple.
- Keep the description brief for scanning.
- Provide information that helps the user resolve an error state.
- Use full sentences and standard end punctuation.
- Use sentence case.

### Dropdown menus and buttons

Dropdown menus are graphical control elements, similar to a list box, except that it only allows the user to choose one value from a list. Guidelines for dropdown menus include:

- Consider adding watermark (hint) text to the field, such as "Select one".
- Use sentence case for both menu names and items.

Dropdown buttons, when selected, display a dropdown list, similar to a dropdown menu, of mutually exclusive items. 

### Forms and text fields

Forms and text fields ask the user to enter information. Text fields, when selected, allow users to enter text. A text field can allow either a single line or multiple lines of text. Forms can collect various types of data, including text. Guidelines for forms and text fields include.

- Clearly explain the purpose of the form or text box in the title.
- Change the input type according to the data you're collecting, for example, separate long references numbers with a gap and limit the input to the exact length expected.
- Keep forms as short as possible.
- Avoid asking for private and personal information.
- Use sentence case for both titles and fields.
- Make the length of input field proportional to the expected user input.

### Labels

Labels are static text fields that describe UI elements (including groups of elements) or provide a short message. Every control or element, such as a text field, button, or dropdown menu, needs a label. Guidelines for labels include:

- Use plain language; avoid technical jargon.
- Ensure the label accurately identifies the element it introduces.
- Group related elements and introduce them using a label.
- Follow a logical order.
- Use parallel construction.
- Use sentence case.

### Links

A link is an interactive reference to other (relevant and trusted) content or external resources that the user can access by selecting it. Guidelines for links include:

- Don't link preceding articles (a, an, the).
- Don't link punctuation.
- Ensure the link looks different from regular text.
- Include a hover state that communicates the link's interactivity.
- Write a normal sentence and link the relevant words in it.
- Don't include things like "Click here" on a link.
- Use sentence case.

### Lists and list boxes

A list is a collection of items that present groups, steps, or sets of information. Guidelines for lists include:

- Give context for the list with a brief introduction.
- Only number lists when there is an order (for example, steps in a process).
- Use sentence case.

List boxes, look like dropdown menus but, like checkboxes, allow users to select a multiple items at a time. Guidelines for list boxes include:

- Consider adding watermark (hint) text to the field, such as "Select all that apply".
- Use sentence case for both menu names and items.

### Navigation

The on-screen elements that helps users find their way through a product, such as a table of contents, breadcrumbs, tags, a search field, icons, links, and menus. Guidelines for navigation include:

- Use title case for main or global navigation
- Use sentence case for sub-navigation.
- Keep navigation links clear and concise.

### Radio buttons

Radio buttons are selectable circles placed next to each item in a set of related, mutually exclusive choices from which the user can select only one. A radio button is on when the circle is filled and off when it's empty. Guidelines for radio buttons include:

- Give radio buttons meaningful titles; describe the effect of choosing each radio button.
- Focus on the difference between options; if all options have the same introductory text, move that text to the group label.
- Write labels as a phase, not a sentence.
- Use regular (not bold) text.
- Don't use ending punctuation unless it labels subordinate controls that follow it, requiring a colon.
- Label a group of radio buttons with text that describes the nature of the options, ending with a colon.
- Keep labels brief; if the option requires more information, provide the explanation in a static text control or tooltip (using complete sentences an end punctuation).
- Use parallel phrasing.
- Use positive phrasing (for example, "do" instead of "do not").
- Add "Recommended" to the label for an option that is strongly recommended.
- Add "Advanced" to the label for an option intended only for advanced users. 
- Use sentence case.

### Watermark (hint) text

Watermark text, also known as hint, prompt, or placeholder text, is a included in text fields and boxes to help the user understand what to enter by way of example. Not all empty fields require hint text. Hint text is useful for communicating examples:
- Syntax, such as for an email address.
- Brief instructions, for example, "Choose a device".
- Validation rules, such as password requirements.

Guidelines for watermark text includes:
- Don't use end punctuation or ellipses.
- Consider alternatives, like placing hint text outside the empty field or as hover text so that it persists when the user starts typing.
- Use sentence case.

## In-product content

UX writing involves reviewing and recommending in-product content. The main categories of in-product content are:

### Microcopy

Microcopy refers to the words or very short sentences that tell a user what to do, address user concerns, and provide context to a situation. Examples of microcopy include: title bars, buttons, menus, error messages, labels, supplementary explanations, checkbox options, dropdown lists, row/column headings and entries, and so on.

For guidelines on the individual elements for which microcopy is needed, see [UI elements and controls](/ux-writing?id=ui-elements-and-input-controls).

### Contextual help

Contextual help is on-demand content based on the state that an application is in when a user seeks help, such as instructions, tooltips, guided workflows, and so on. Help that is offered in context is easier to identify and use (has high affordance) and us less disruptive; rather than interrupt the workflow by forcing the user to browse an online manual or help centre, context-sensitive help delivers content relevant to the part of the program that the user is interacting with. It is thus better if the user can access this help without leaving the current workflow, which can achieved with **instructional text**.

### Instructional (on-screen) text

Instructional text, also called in-product instructions or on-screen text, is contextual help presented inline with the interface content, which avoids making users switch between tools to get help. Instructional text helps the user understand what a feature does or how to populate a field. This allows the user to solve problems without waiting for assistance or referring to a user manual, reducing the number of incoming queries to the support team.

#### Guidelines for instructional text

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

#### When to use instructional text

Instructional text is the least demanding way to offer support because it prevents the user from having to rely on working memory or from having to take an extra step to find information. To maximise the chances of positive experience, in-product assistance should:

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

With the progressive disclosure philosophy in mind, the UX writer should consider when to use the following types of microcopy and contextual help to guide the user as part of an in-product strategy. You can decide on the type of copy you're providing based on the required level of detail.

### On-screen copy (inline instruction)

On-screen copy is brief text that appears on the page, alongside the UI element it references, and it is used when the information is:

-  Essential to performing the task.
-  Directly actionable. 

If there is enough space, the UX writer might also decide to include:

-  Important but not directly actionable information.
-  Supplementary information, preventing the user from having to navigate elsewhere to find it.

Embedding information directly within a feature in this way is often the best choice for providing contextual help. It can, however, make the interface look cluttered or might not provide enough information to be useful. If this is the case, consider using **tooltips**.

### Tooltips

Tooltips are user-triggered, brief informative messages that appear when the user interacts with a UI element by clicking or hovering over it. 

Tooltips used in touchscreen devices are called popup tips, following the same guidelines as tooltips, except that they require a specific initiation/termination method.

#### Guidelines for using tooltips

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

#### When to use tooltips

Tooltips are offered when additional content might help the user make more informed decisions based on specific, contextual information. They typically provide a short description of the element or functionality that users might want or need to know more about; tooltips disappear, and so they shouldn't be used for directly-actionable or essential information required to perform a task.

Tooltips are useful with:

-  Unlabelled controls and command buttons with graphic labels.
-  Labelled controls and UI elements that benefit from supplemental information that doesn't fit as on-screen text.
-  As a form of progressive disclosure with help (?) and info (i) icons, eliminating the need for descriptive text on screen if not essential to the primary task.

 For more information on progressive disclosure, see [Progressive disclosure philosophy](https://jeunese.github.io/#/ux-writing?id=progressive-disclosure-philosophy).

### Walk-throughs (guided help)

A series of messages or tooltips appearing one at a time to provide step-by-step instructions that will guide a user through a feature, used when the functionality or workflow is more complex or spread across multiple pages. A walk-through provides step-by-step guidance and instructions.

### Page-level help

Context-sensitive topics that are triggered when the user selects a link provided at page level, used when the user might need conceptual or bigger-picture information (such as UI use cases) to help them understand the page that the user is on. This provides users with a way of getting detailed information without having to navigate or search different sites.

## UI messages

Messages are information in the UI that address an immediate need and appear while the user interacts with the product. Messages typically require an action from the user on their way to completing their tasks. Messages should help the user complete these tasks as efficiently, effectively, and easily as possible. 

How a message is written will depend on its purpose. In general, messages should:

-  Be written in a consistent style.
-  Be friendly.
-  Use clear and simple language.
-  Provide sufficient and not excessive information.
-  Convey technical information in simple terms; avoid jargon and technical detail.
-  If technical detail might be wanted or needed, use progressive disclosure.
-  Suggest next steps.
-  Be kind to users who encounter situations in the product UI that could be frustrating for them, such as 404 pages.

### Message elements

General recommendations for each element of a message, whichever type it is, are:

-  For titles, use sentence case capitalisation and no ending punctuation, unless the statement is a question.
-  For the message body, use complete sentences, sentence case capitalisation, and ending punctuation.
-  For the buttons, use sentence case punctuation but no end punctuation, and use short, action verbs unless the buttons require a simple **Yes | No**.

### Notifications (informational messages)

Notifications alert the user to additional information that helps with related configurations, such as a general occurrence, a change in system state, or an event of interest. Guidelines for notifications include:

- Structure the notification as a statement or a fact.
- Describe the condition.
- Use sentence case.
- Optionally, use a command button.

### Warnings 

Warnings alert the user to a condition that may cause a potential issue. Guidlines for warnings include:

- Describe the the potential issue and why it's important.
- Use sentence case.
- Use a command button.

### Confirmation messages

Confirmation messages appear when the user is performing a task to explain the consequences of an action before determining if they want to proceed with it. Guidelines for confirmation messages include:

- Frame the confirmation message as an action as a question to determine if the user wants to proceed.
- Explain the outcome or why the user might wish not to proceed.
- Use sentence case.
- Use a command button.

### Success messages

Success message provide positive feedback on a completed action. Guidelines for success messages include:

- Use sentence case.
- Use a a command button, such as `Close` or `OK`

### Error messages

Error messages appear when a problem occurs, for example, when an incorrect instruction has been given; the best error messages explicitly describe what is wrong and how to fix it, resulting in the user resolving the issue by themselves. An error message can provide more than one action for the user. 

A good error message has three parts:

1. Problem identification: describe the exact issue, clearly and unambiguously, so that the user knows the reason for the message.
1. Details of the cause (if helpful or necessary); don't over-explain the problem.
1. A solution (if possible); if not, specify an action the user can take, like where to go to find support or investigate the problem.

Be explicit (1), specific (2), and helpful (3). Ensure the content (2) and action (3) matches the message.

Other guidelines for error messages include:

**Language.**

- Use a language that encourages the user to come back or try again. 
- Use plain language; avoid referring to implementation details.
- Avoid negative words (for example, instead of "The form contains *errors*", try "Please enter a valid postcode").

**Tone.**
-  Don't blame the user.
-  Be courteous, respectful, kind, and useful.
-  Talk to user like a person, in a conversational style
-  Turn error messages and 404 pages into positive reinforcement by guiding the user along until they complete their task. 

**Content.**
-  Focus on the solution, not the error or mistake.
-  Be concise; include only necessary and meaningful information.
-  Point out the exact location of a problem.
-  Point out where the user needs to go or what steps they need to follow to rectify the problem.
-  Use missteps as an opportunity to encourage users to keep navigating through the product.
- Use progressive disclosure for detailed information related to a message that might be useful :
	- Allow the user to select `Learn more` to find more details.
	- For more advanced users who might want to know the technical details, place these details under an expandable and collapsable section.
	- Where technical or complex details are needed, direct the user to a troubleshooting section to resolve the issue.