# UX writing guidelines

User experience (UX) writing involves creating content for applications and websites to help users navigate the product or service. This includes in-product text, buttons, messages, labels, and other UI touch points that guide a user through a product or service. 

This page summarises best practices and industry standards for UX writing.

## UX writing approach

UX writing is an integral part of designing the customer journey. As such, UX writers should be involved early in the design process, alongside UX and UI designers, UX researchers, and information architects for context gathering, design, and review.

1. **Context gathering.** Before writing or reviewing UI content, the UX writer needs to know:

    -  Who they're writing for.
    -  What the user's goals and needs are.
    -  What the product is and how the product is used. 
	-  What the flow is.
    -  What the use cases are.
    -  What components of the product need written or reviewed (if not the end-to-end experience).

1. **Design.** As a design exercise, the optimal level of UX writer involvement in product design is at the beginning. This way, the UI can be designed as a unified source of information from the beginning of the design process, rather than having a UX writer come in at the end to fix surface-level issues with UI text.

1. **Review.** UX writers should check that the UX copy fulfils user needs with intended tone of voice. You can also seek insight from user research if it's needed and a viable option.

## General guidance

General guidance for UX writing includes:
-  Engage early with Product Design.
-  Take a user-centred approach.
-  Use present tense where possible.
-  Keep messages short.
-  Address the reader directly; avoid referring to "users" or "customers".
-  Avoid using the same word twice in the same screen.
-  Avoid negative phrasing.
-  Use sentence case for everything except global navigation and boolean values. If in doubt, use sentence case.
-  Avoid using abbreviations and acronyms in UI content unless space is severely limited or the acronym is better known than the full term (for example, URL).

## Progressive disclosure philosophy

Progressive disclosure is an interaction design pattern that involves sequencing information and actions across screens, and revealing only essential information. This avoids overwhelming the user and helps them manage complexity. It also makes products easier to learn and use, avoids frustration and confusion, and reduces the number of potential errors. Some guidelines include:

-  Don't bombard the user with a lot of information as soon as they're introduced to the product.
-  Allow the information to progress naturally, from simple to complex.
-  Help the user move from completing tasks with essential information to completing more complex tasks with additional information.
-  Build upon each subsequent step of information experience and learning.
-  Provide only the necessary information for the user to take each action, one at a time.

With the progressive disclosure philosophy in mind, you should consider when to use the following types of microcopy and contextual help to guide the user. You can decide on the type of copy you're providing based on the required level of detail.

## In-product content types

Good UX writing gives the user what they need, in context, when they need it. This minimises the end-user's need to engage with documentation by helping to make the UI more intuitive, which increases usability and reduces frustration. The main categories of in-product content are:

### Contextual help

Contextual help is on-demand content based on the state that an application is in when a user seeks help, such as [instructional text](/ux-writing?id=instructional-text), [in-line copy](/ux-writing?id=inline-copy), [tooltips](/ux-writing?id=tooltips), [guided workflows](/ux-writing?id=walkthroughs-guided-help), [page-level help](/ux-writing?id=page-level-help), and [UI messages](/ux-writing?id=ui-messages).

Help that's offered in context is easier to identify and use (has high affordance) and is less disruptive; rather than interrupt the workflow by forcing the user to browse an online manual or help centre, context-sensitive help delivers content relevant to the part of the product that the user is interacting with. It's thus better if the user can access this help without leaving the current workflow.

### Microcopy

Microcopy refers to the words or very short sentences that tell a user what to do, address user concerns, and provide context to a situation. Examples of microcopy include: title bars, buttons, menus, error messages, labels, supplementary explanations, checkbox options, dropdown lists, row and column headings and entries, and so on.

Microcopy should be written in second person and sentence case. For more guidelines on the individual elements for which microcopy is needed, see [UI elements and input controls](/ux-writing?id=ui-elements-and-input-controls).

## Instructional text

Instructional text, also called in-product instructions or on-screen text, is a type of [contextual help](/ux-writing?id=contextual-help) that's presented inside the UI, which avoids making users switch between tools to get help. Instructional text helps the user understand what a feature does or how to populate a field. This allows the user to solve problems without waiting for assistance or referring to a user manual, reducing the number of incoming queries to Technical Support.

### When to use instructional text

Instructional text is a less demanding way to offer support because it prevents the user from having to rely on working memory or having to take an extra step to find information. To maximise the chances of a positive experience, in-product instructional text should:

-  Cause minimal disruption to the user's workflow.
-  Result in quick issue or query resolution.
-  Foster ease-of-use.
-  Be timely and well-placed, appearing the moment the user needs it and embedded directly in the UI.
-  Provide [progressive disclosure](/ux-writing?id=progressive-disclosure-philosophy).

### Guidelines for instructional text

**Keep it simple.** Don't overuse instructional UI text; copy should enhance the experience, not clutter it.

-  Don't explain fundamental features; if a user needs instructions, consider ways of making the design more intuitive.
-  Don't explain obvious features and workflows; instructional text can get in the way of an already intuitive workflow.
-  Don't make users engage with instructional text; users should be free to ignore instructional UI and still progress through the UI.
-  Don't repeat information; add a setting to display instructional UI instead.

**Keep it useful.** Use instructional text to make the onboarding flow as smooth as possible.
    
-  The most immediate instructions should be those that apply to every page.
-  Focus on the actions that the user needs to take.
-  Provide information about prerequisites and next steps.
-  Ensure warnings are relevant to the task.
-  Include tips that might help the user complete their task.

## In-line copy

In-line copy is brief text that appears on the page, alongside the UI element it references.

It is a type of [contextual help](/ux-writing?id=contextual-help) that provides immediate guidance within the UI, but is less comprehensive than [instructional on-screen text](/ux-writing?id=instructional-on-screen-text).

### When to use in-line copy

In-line copy is used when the information is: 

-  Essential to performing the task.
-  Directly actionable. 

For example, you can use in-line copy to provide informative [error message](https://jeunese.github.io/#/ux-writing?id=error-messages) when users encounter issues or input errors. You can also use it to provide feedback to users after they complete actions or submit forms, using in-line copy to confirm successful completion.

If there's enough space, you might also decide to include:

-  Important but not directly actionable information.
-  Supplementary information, preventing the user from having to navigate elsewhere to find it.

Embedding information directly within a feature is often the best choice for providing contextual help. It can, however, make the interface look cluttered or might not provide enough information to be useful. If this is the case, consider using [tooltips](/ux-writing?id=tooltips).

### Guidelines for in-line copy

**Keep it simple.** Keep in-line copy concise and to the point.

-  Use clear and simple language that's easy for users to understand without ambiguity or confusion.
-  Use as few words as possible to convey the intended message.

**Keep it relevant.** Ensure that in-line copy is contextually relevant to the user's current task or interaction within the interface.
    
-  Place in-line copy directly adjacent to the relevant interface element, such as buttons, form fields, or navigation links, to provide immediate guidance.
-  Use actionable language that prompts users to take specific actions or provides clear instructions on how to proceed.

## Tooltips

Tooltips are user-generated, brief informative messages that appear when the user interacts with a UI element by selecting or hovering over it. They are used:
- For preventing drop-off at friction points by reassuring users and alleviating doubt.
- For additional context or necessary information that's too long to put on the screen.
- To walk users through a process that has multiple steps.

Tooltips used in touchscreen devices are called popup tips, following the same guidelines as tooltips, except that they require a specific initiation and exit method.

### When to use tooltips

Tooltips are offered when additional content might help the user make more informed decisions based on specific, contextual information. They typically provide a short description of the element or functionality that users might want or need to know more about. 

Tooltips disappear, and so they shouldn't be used for directly-actionable or essential information required to perform a task.

Tooltips are useful:

-  With unlabelled controls and command buttons with graphic labels.
-  With abelled controls and UI elements that benefit from supplemental information that doesn't fit as on-screen text.
-  As a form of [Progressive disclosure](https://jeunese.github.io/#/ux-writing?id=progressive-disclosure-philosophy), eliminating the need for descriptive on-screen text if not essential to the primary task.

Tooltips are opened when a user hovers over a labelled control or when a user directly interacts with a help (?), info (i), or important (!) icon. For tooltip icons:
- Use a question mark (**?**) for tooltips that answer the *questions* "why?", "how?", or "what does this mean?", like why an email address is needed, where to find a reference number, or what a term means.
- Use the letter "**i**" for tooltips that provide supplementary information that users might benefit from without having to navigate away from the UI, like useful knowledge, insights, or tips to add value or clarification. For example, you might want to let users know what they can do with a feature ("You can customise this design") or provide extra guidance like password requirements.
- Use an exclamation point (**!**) for tooltips that provide important information or context, like how personal information will be used or how something is calculated. If information is *necessary*, consider using [in-line copy](https://jeunese.github.io/#/ux-writing?id=in-line-copy) instead.

### Guidelines for using tooltips

**Be informative.** You should aim to:

-  Avoid redundant information.
-  Provide helpful content.
-  Provide information that isn't otherwise obvious and doesn't repeat on-screen copy.
-  Focus on the control's action, for example, by beginning the tag with a verb.

Don't use tooltips if there's space in the [in-line copy](/ux-writing?id=inline-copy). Tooltip text should provide additional and useful information, such as why a field is required or how the value entered into a field will be used. 

**Keep it short.** Use as few words as possible. 

- For labelled controls, limit tooltips to 15 words. If more text is needed, this suggests that the design might be too complicated. 
- For tooltips opened by selecting icons, limit the text to no more than 40 words. 
- If more content is required, consider adding a `Learn more` link to the relevant documentation; use such links sparingly, which you might achieve by including one link at the page level.

**Other guidelines** for writing tooltips include:

-  Use short, complete sentences that address concerns and tell users what to do.
-  Consider using a title, in sentence case, phrased as a question in first person, for example, "Why can't I update my address?"
-  If you need to reduce the length of a tag, omit grammatical articles.
-  Include a `Close` label next to an `X` in the upper right corner.
-  Use links in tooltips only if necessary.
-  Use bullets for lists of items; use paragraphs for explanations.

## Walkthroughs (guided help)

A walkthrough provides step-by-step guidance and instructions: a series of messages or [tooltips](https://jeunese.github.io/#/ux-writing?id=tooltips) appearing one at a time to provide step-by-step instructions that will guide a user through a product or feature, used when the functionality or workflow is more complex or spread across multiple pages.

### When to use walkthroughs

Walkthroughs are often used for:

- Product tours, showcasing the key benefits and functionalities of a product or service to potential customers. 
- New user onboarding, helping the user to navigate the interface, understand basic functionality, and get started with using a product or feature effectively.
- Breaking down complex features or workflows into manageable steps that help users understand the sequence of actions and reduces the likelihood of confusion or errors.
- Significant product updates or changes, helping existing users familiarise themselves with the new features for a smooth transition and minimal disruption to the user experience.
- Task completion assistance for when users encounter roadblocks or challenges while completing a specific process.
- User engagement and retention to encourage users to explore different areas of the UI, discover hidden features, or learn advanced techniques.

### Guidelines for using walkthroughs

**Be user-centric.**
- Align content with the user's goals and objectives, for example, "Create your account to get started".
- Use action-oriented language, for example, "select" instead of "click".
- Address the reader directly with “you” rather than “the customer” or “users”.

**Provide context.** Help users understand why they are performing a certain action.
- Highlight the benefits of completing each step to motivate users to continue the walkthrough.
- Explain how each action contributes to achieving the overall goal of the walkthrough.
- Anticipate user questions or concerns and address them proactively within the walkthrough.
- Include links to relevant help resources for users who need further assistance, such as support articles or contact information.

**Keep it simple.** Write concisely and use everyday language. 
- Use simple and straightforward language.
- Keep sentences short.
- Use visuals wisely, to illustrate key concepts or demonstrate specific actions when necessary.

**Other guidelines** for walkthroughs include:
- Provide clear explanations and examples to guide users through each step of the process.
- Use consistent terminology and writing style throughout the walkthrough to avoid confusion.
- Ensure that the tone of voice aligns with the overall brand personality and user expectations.
- Use the imperative mood to provide clear and direct instructions, for example, "Choose a payment method" instead of "You can choose a payment method."
- Use bold sparingly. Avoid bolding whole sentences or paragraphs. Everything included in a walkthrough should be already be important.
- Use sentence case, even in headers and buttons.

## Page-level help

Context-sensitive topics that are triggered when the user selects a link provided at page level. This provides users with a way of getting detailed information without having to navigate or search different sites.

### When to use page-level help

Page-level help is used when the user might need conceptual or bigger-picture information (such as UI use cases) to help them understand the page they're on. Specifically, page-level help can be useful:

- When features, controls, or workflows are complex.
- For introducing new features.
- For sensitive information, such as privacy policies, terms of service, or account settings.

### Guidelines for page-level help

**Keep it simple.** Provide information in a clear and concise manner.
- Avoid overwhelming users with too much text.
- Keep explanations brief and to the point.
- Use simple language and avoid technical jargon or industry-specific terms.

**Keep it relevant** Ensure that the help content is relevant to the context of the page. 
- Explain the purpose of the page and how it fits into the overall user journey or workflow.
- Tailor the help content to address common user questions or concerns related to the page's functionality. 
- Provide examples or scenarios that demonstrate how the page's features or functionality can be used in real-world situations.

**Be helpful.**
- Provide clear and actionable step-by-step instructions to guide users through the process. 
- Use numbered lists or bullet points for readability.
- Use visuals can help clarify complex concepts or illustrate step-by-step instructions.
- Link to additional resources, such as support articles and video tutorials.

## UI messages

Messages are information in the UI that address an immediate need and appear while the user interacts with the product. Messages typically require an action from the user on their way to completing their tasks. Messages should help the user complete these tasks as efficiently, effectively, and easily as possible. 

How a message is written will depend on its purpose. In general, messages should:

-  Be written in a consistent style.
-  Be friendly.
-  Use clear and simple language.
-  Provide sufficient and not excessive information.
-  Convey technical information in simple terms; avoid jargon and technical detail.
-  If technical detail is wanted or needed, use progressive disclosure.
-  Suggest next steps.
-  Be kind to users who encounter situations in the product UI that could be frustrating for them, such as 404 pages.

### Message elements

General recommendations for each element of a message, whichever type it is, are:

-  For titles, use sentence case capitalisation and no ending punctuation, unless the statement is a question.
-  For the message body, use complete sentences, sentence case capitalisation, and ending punctuation.
-  For the buttons, use sentence case with no end punctuation, and use short, action verbs unless the buttons require a simple **Yes | No**.

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

- Frame the confirmation message as an action and as a question to determine if the user wants to proceed.
- Explain the outcome or why the user might not want to proceed.
- Use sentence case.
- Use a command button.

### Success messages

Success messages provide positive feedback on a completed action. Guidelines for success messages include:

- Use sentence case.
- Use a a command button, such as `Close` or `OK`

### Error messages

Error messages appear when a problem occurs. The best error messages explicitly describe what's wrong and how to fix it, resulting in the user resolving the issue by themselves. An error message can provide more than one action for the user. 

A good error message has three parts:

1. Problem identification: describe the exact issue, clearly and unambiguously, so that the user knows the reason for the message.
1. Details of the cause (if helpful or necessary); don't over-explain the problem.
1. A solution (if possible); if not, specify an action the user can take, like where to go to find support or investigate the problem.

Be explicit (1), specific (2), and helpful (3). Ensure the content (2) and action (3) match the message.

Other guidelines for error messages include:

**Language.**

- Use a language that encourages the user to come back or try again. 
- Use plain language; avoid referring to implementation details.
- Avoid negative words (for example, instead of "The form contains *errors*", try "Please enter a valid postcode").

**Tone.**
-  Don't blame the user.
-  Avoid a negative tone; be neutral.
-  Be courteous, respectful, kind, and useful.
-  Talk to the user like a person, in a conversational style.
-  Turn error messages into positive reinforcement by guiding the user along until they complete their task. 

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

## UI elements and input controls

To write consistent, accurate, and clear UI copy, a UX writer needs to understand what each UI element does and best practices for creating them. Every UI element has a specific purpose and guidelines you should follow. These guidelines streamline the content and promote consistency. General guidelines for UI elements and controls include:

### Alt text

Alt text is a label that screen readers can use to describe an image. Alt text appears when images don't render. Guidelines for alt text include: 

- Describe the image in brief.
- Use sentence case.

### Boolean values and toggles

Boolean values are a visual representation of an on/off state, such as a switch. If "off" and "on" are inappropriate for the context, different words that fit the context are used instead. Guidelines for boolean values include:

- Write words to fit the context (for example, `On | Off`, `True | False`, `Yes | No`).
- Don't use all caps; use title case.
- If a label for an option runs long, don't truncate the label.
	- Wrap the label to multiple lines, if necessary.
	- Align the UI element with the fist line of the label.

A toggle provides users with a choice between the two mutually exclusive states of a boolean value. A user should be able to make selections with only a screen reader and keyboard. To this end, they should be able to:

- Understand the current state of the selection.
- Tab through the options and between them using the arrow keys.
- Use the spacebar to select and deselect an option.

### Buttons

Buttons are labels that, when selected, initiate an action that allows the user to complete a task. Guidelines for buttons include:

- Avoid introductory labels for buttons; the button label should be enough.
- Be consistent with button placement across different UI elements. For example, don't reverse the placement of `OK` and `Cancel` in different parts of the UI.
- Don't use buttons for a list of choices.
- Separate destructive buttons from non-destructive buttons so that the user must make an intentional effort to select the button.
- Use trailing ellipsis when the button opens another window, dialogue box, or app.
- Use sentence case.

Guidelines for the language used in button include:

- Use clear, precise, predictable language.
- Lead with a verb that encourages an action, like `Cancel` and `Delete`.
- Use one word for call-to-action (CTA) and text buttons unless there is a verb involved.
- If not a common action (like `Done` or `Close`) use the {verb}+{noun} formula (such as, `Test connection` or `Add selected items`).
- Don't include descriptors like "now" –– the resulting action from selecting a button should be instantaneous.
- Be specific about single items (for example, `Choose picture` rather than `Import`).
- If not using a specific action (as recommended), use the word `OK` rather than Ok, ok, or Okay.

### Checkboxes

Checkboxes are controls that let the user choose between two opposite states, actions, or values. A checkbox is on when it contains a checkmark (indicating that it's selected) and off when it's empty. Guidelines for checkboxes include:

- Place an action at the beginning of the title.
- Keep the text for a checkbox on a single line.
- Use positive phrasing (selecting a checkbox shouldn't mean *not* performing an action, unless it's a "Don't show this again" checkbox).
- Make clear what happens when the box is selected versus not selected.
- Always follow a checkbox with a title or label; provide a title that implies two opposite states.
- Don't use ending punctuation, unless it's a colon at the end of a label for a group of checkboxes.
- Add "Recommended" to the label for a checkbox that is strongly recommended.
- Use sentence case.

Guidelines for grouping and ordering checkboxes include:

- For each checkbox in a group, use parallel phrasing.
- For large sets, use subheadings to group choices. 
- Label a group of checkboxes to make the purpose of the checkboxes evident, ending with a colon.
- Present checkboxes in a logical order.

### Console (push) notifications

Push notifications are visual indicators on a list or details page in a console that show when a record or field has changed during a user's session. Guidelines for push notifications include:

- Use action-oriented, positive phrasing in top-level notifications.
- Keep the language simple.
- Keep the description brief for scanning.
- Provide information that helps the user resolve an error state.
- Use full sentences and standard end punctuation.
- Use sentence case.

### Dropdown menus and buttons

A Dropdown menu is graphical control elements, similar to a list box, except that it only allows the user to choose one value from a list. Guidelines for dropdown menus include:

- Consider adding watermark (hint) text to the field, such as "Select one".
- Use sentence case for both menu names and items.

Dropdown *buttons*, when selected, display a dropdown list, similar to a dropdown menu, of mutually exclusive items. 

### Input fields and forms

Input fields allow data to be entered into a form. Forms can collect various types of data, including text. Text fields, when selected, allow users to enter text. A text field can allow either a single line or multiple lines of text. 

Guidelines for input fields in forms include:

- Clearly explain the purpose of the input field in the title.
- Change the input type according to the data you're collecting, for example, separate long references numbers with a gap and limit the input to the exact length expected.
- Use sentence case for both titles and fields.
- Make the length of the input field proportional to the expected user input.
- Don't write instructions in a basic text area other than help text.

The general guidelines for forms are:

- Keep forms as short as possible.
- Always include a label for the input field.
- Avoid asking for private and personal information.
- Label fields as optional if the majority of fields are required.
- Label fields as required if the majority of fields are optional.
- If the field label is long, wrap it to multiple lines.
- Use clear and specific language for labels, placeholder, and helper text.

The guidelines for help text and errors in forms include:

- Provide concise, relevant help text.
- Write help text in sentence case and in as few words as possible.
- Don't use help text to explain the field in detail.
- Provide a character count when a field is restricted to a minimum or maximum amount.
- Show an error state when the user enters an incorrect character type.
- If a required field is left blank, display a default error message, such as "This field is required".

### Labels

Labels are static text that describe UI elements (including groups of elements) or provide a short message. Every control or element, such as a text field, button, or dropdown menu, needs a label. Guidelines for labels include:

- Use plain language; avoid technical jargon.
- Ensure the label accurately identifies the element it introduces.
- Group related elements and introduce them using a label.
- Follow a logical order.
- Use parallel construction.
- Use sentence case.

### Lists and list boxes

A list is a collection of items that presents groups, steps, or sets of information. Guidelines for lists include:

- Give context for the list with a brief introduction.
- Only number lists when there is an order (for example, steps in a process).
- Use sentence case.

List boxes look like dropdown menus but, like checkboxes, allow users to select multiple items. Guidelines for list boxes include:

- Consider adding watermark (hint) text to the field, such as "Select all that apply".
- Use sentence case for both menu names and items.

### Navigation

The on-screen elements that help users find their way through a product, such as a table of contents, breadcrumbs, tags, a search field, icons, links, and menus. Guidelines for navigation include:

- Use title case for main or global navigation
- Use sentence case for sub-navigation.
- Keep navigation links clear and concise.

### Radio buttons

Radio buttons are selectable circles placed next to each item in a set of related, mutually exclusive choices from which the user can select only one. A radio button is on when the circle is filled and off when it's empty. Guidelines for radio buttons include:

- Write labels as a phrase, not a sentence.
- Add "Recommended" to the label for an option that is strongly recommended.
- Add "Advanced" to the label for an option intended for advanced users. 
- Don't use ending punctuation unless it labels subordinate controls that follow it, requiring a colon.
- Give radio buttons meaningful titles; describe the effect of choosing each radio button.
- Keep labels brief; if the option requires more information, provide the explanation in a static text control or tooltip (using complete sentences an end punctuation).
- Use positive phrasing (for example, "do" instead of "don't").
- Use sentence case.

Guidelines for grouping and ordering checkboxes include:

- For each radio button in a group, use parallel phrasing.
- For large sets, use subheadings to group choices. 
- Label a group of radio buttons with text that describes the nature of the options, ending with a colon.
- Focus on the difference between options; if all options have the same introductory text, move that text to the group label.
- Present radio boxes in a logical order.

### Text links

Text links are labels that fall outside of a block of text and may start a task on a new page. Guidelines for text links include:
- Start with words that are related to the user action, such as "Download" or "View".
- Differentiate from unlinked text using colour.
- Use text links as part of a sentence or phrase.
- Don't use text links in place of buttons.
- If fewer than 3 words, consider using a button, especially if it starts a new task or it's a secondary action.
- Use text links to increase SEO on the page.
- If part of a sentence, use second person language.
- Avoid text links that don't convey a function or meaning, such as "click here".

For accessibility: 
- Text links should standalone and communicate meaning without added words.
- Users should be able to tell what the text link is about without reading the surrounding words.
- Text links should be written in direct, specific language.

### Watermark (hint) text

Watermark text, also known as hint, prompt, or placeholder text, is text included in text fields and boxes to help the user understand what to enter by way of example. Not all empty fields require watermark text. Watermark text is useful for communicating:
- Examples.
- Syntax, such as for an email address.
- Brief instructions, for example, "Choose a device".
- Validation rules, such as password requirements.

Guidelines for watermark text include:
- Consider alternatives, like placing hint text outside the empty field or as hover text so that it persists when the user starts typing.
- Use sentence case.