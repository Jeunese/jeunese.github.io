# Technical Writing Guidelines

General guidance for technical writing includes the following:

- Define your documentation goals.
- [Create a content framework and strategy](/get-started?id=_2-create-a-content-framework-and-strategy).
- Take a user-centred approach.
- Describe things simply.
- Follow [lean writing principles](/style-guide?id=lean-writing-principles).
- Use voice, tone, and terminology consistently.
- Address the reader directly; avoid referring to "users" or "customers".
- Avoid negative phrasing.
- Use sentence case for everything except global navigation.

More specific guidance depends on the type of technical writing you’re engaged in. This article focuses on product documentation.

## What is product documentation?

Product documentation describes what a product or service does, how it works, and other technical details needed to set it up. The audience for this type of technical content is typically a customer's administrator. Administrators use this content to install, configure, update, and maintain these products and services.

For more information on what product documentation is (and isn't), see [Product documentation](/?id=product-documentation) in the **Information Development Overview**.

Product documentation covers:

- What the product is and does.
    - What capabilities does it offer?
    - What solution does it provide?
    - How does the product work?
- Why anyone would use the product. 
    - What problem does it solve and for whom?
    - What needs does it meet and for whom?
- What the dependencies are (requirements and pre-requisites, development environment, licensing, etc.)
    - What should administrators know about before installing?
    - What do users need to know to start using the product?
- What the context is.
    - How does the product and its features relate to other products and features?
    - What are the available options for installation and features?
    - What are the typical use cases?
- The end-to-end technical workflow for setting up the product, including:
    - How to install the product.
    - How and where to get the product.
    - How to configure the product.

Product documentation should help the reader get set up as quickly and smoothly as possible. Be careful not to repeat Marketing or Sales content. The focus should be on the product's capabilities, user need, and use cases.

For more information on what to include in product documentation, see [Scoping and planning](/get-started?id=scoping-and-planning) in the **Get Started with Product Documentation** article.

## Writing product documentation

Once you've learned everything you need to start writing about the product or feature, write only what the administrator needs to know, and no more. The aim is to reduce administrator fatigue and frustration.

### Avoid duplication

Avoid duplication by adopting a single-sourcing model. The following guidelines mean that you should only have to update the documentation in one place.

- Keep content in one place so that you can efficiently manage it.
- Arrange content logically.
- Create self-contained, complete pieces of content that don't overlap ("topics").
- Make liberal use of links to existing content and resources.
- Don't assume someone has read one piece of content before reading another.

### Make content easy to scan for relevant information

The primary purpose of the product documentation is to provide information to the administrator who's looking for it.

**Keep it short and simple:**
-  Keep content as short as possible to the reduce the need for users to scroll. 
-  Aim for paragraphs that are 75 words or fewer.
-  Sentences should be, on average, 15 words, and 28 words as a maximum.
-  Use shorter and less complicated words where possible.
-  Keep headings 12 words or fewer.

**Break up content:**
-  Use headings.
-  Adopt a flat hierarchy (2-3 tiers).
-  Write short blocks of text (2-4 sentences).
-  Use bullet points.

**Consider the location of content:**
-  Place important content "above the fold" in a webpage.
-  In left-to-right languages, people tend to read in an F shape, so place important content or navigation in the top left.

**Use bold and italics very selectively:**
-  Reserve bolding to call out UI elements and to place emphasis on specific actions. 
-  Don't use quotation marks for emphasis.
-  Avoid using italics for emphasis, where possible.
-  Rather than using bold or italics to emphasise whole phrases, use layout, callouts, headings, and short paragraphs to draw attention to important content or messages.

### Avoid redundancy to maintain the effectiveness of your content

Don't provide unnecessary information. For example, don't give a detailed history the product –– focus on what's new in the particular service and instructions for performing a specific task.

To modify a quote from Antoine de Saint-Exupery, good writing is achieved, not when there is nothing left to add, but when there is nothing left to remove. 

- Get straight to the point based on what users want and need.
- Eliminate titles that restate the body of an information box in the UI or a paragraph in documentation.
- Remove unnecessary words and content, for example, *"You'll be asked to enter your password~~, which you created in the previous step~~."
- Use as few words as possible to portray meaning. The table, below, outlines some guidance.

|Guideline | Examples |
|---|---|
|Remove empty or unnecessary determiners and modifiers. | "The set up is ~~basically~~ the same"; "The process is ~~actually quite~~ straightforward"; "Selecting this option is ~~really~~ only needed if you're using a Windows machine." |
|Prune every excess or redundant word. | "*Repeat* the steps ~~*again*~~" or "*Revert ~~back~~* to your previous settings." |
|Replace an intensifier or qualifier, along with the adjective it refers to, with a stronger word. | *"very important"* could be replaced with *"crucial"*.|
|Avoid manner adverbs (usually formed from adjectives by adding "-ly") and use precise language, instead. |  "The change takes effect *quickly*", could instead be "The change takes effect within *5 minutes*".
|Replace wordy phrases with single words where possible. | "With the exception of" could be replaced with "Unlike". |

## Writing instructional content

Step-by-step instructions for procedural tasks help avoid big blocks of text and provide a clear way to show a process. Separating out the steps in a process makes reading instructions easier to read, understand, and follow, for a better user experience and higher likelihood of success. 

Good writing, especially writing that's designed for instruction, should be to the point: clear, precise, and concise.

### Bullets and numbering

Use a numbered list to denote the order in which steps are carried out; use bullet points for a general list.

### Emphasis

**Bold** is the main form of emphasis used in instruction content. Use **bold** to call out UI elements and to place emphasis on specific actions, such as **Select**, **Delete**, and **Save**. 

Other forms of emphasis might include:
- Code keys and database elements with UPPER CASE.
- File paths and names with **Initial Caps and Bolding**.
- Code samples with `monospacing`.

### Style

Use the imperative mood for instructions. Sentences with an imperative mood start with an action verb and second person singular, with "you" as its implied subject. Imperative sentences are typically in the active voice. 

### Clickthroughs

Use chevrons (**>**) with spaces around them to separate items in a clickthrough; bold the chevrons. For example: *"To create a shareable link, navigate to the top menu and select **File > Share > Copy Link**"*.

### Terminology

Use the word **click** only to refer to specific mouse actions; in general, avoid talking about mouse actions. Instead, refer to user actions with words like "hover over", "point to", "choose", "select", and "enter". 
 -  Use **select** to instruct the reader to select an item, like text, objects, or cells. 
 -  Use **enter** to instruct the user to type their password or choose a selection from a dialogue box.

### Sentence structure

|Guidance| Example|
|---|---|
|Put conditional clauses before instructions. |*"For more information, see the disclosure document"* (rather than *"See the disclosure document for more information"*). |
|To direct the user to do something, mention the circumstances before you provide the instruction. |*"If you want a PDF of this page, select the **Download** button in the top-right of the screen"* (rather than *"Select the **Download** button in the top-right of the screen for a PDF of this page"*).|
|When writing a series of steps, mention the location, followed by the action. |*"From the drop-down menu, select the type of alert you want to send"* (rather than *"Select the type of alert you want to send from the dropdown menu"*). |

## Using visual content

Visual content, including images, screenshots, graphics, and videos, allow you to quickly *show* how something works, rather than relying solely on instructional text, which is slower and more effortful to absorb. However, there are both pros and cons to using visual content in product documentation. 

The benefits of visual content include:

*  **Processing speed** People absorb visual information faster and perform tasks better when instructions are provided with visual content.
*  **Scanning.** Visual content helps break up long blocks of text.
*  **User-friendliness.** Visual content can make documentation feel less intimidating.
*  **Visual interest.** Visual content can make documentation more pleasant to go through.
*  **Ease-of-use.** Visual content can be easier to follow than written content.
*  **Context.** Visual content helps to confirm the context and to reassure the user that they're taking the right actions.

The potential downsides of using visual content in product documentation include:

*  **Overhead.** Visual content gets easily out-of-date and is harder to maintain than written content.
*  **Accessibility.** Even with captions and [alt text](https://jeunese.github.io/#/ux-writing?id=alt-text) for your visual content, written instructions are necessary for those who rely on screenreaders.
*  **Distraction.** Too many images or images that are too large break up content so much that following necessary written instructions becomes harder.
*  **Quality.** Images of the real product are often detailed and require high resolution to be read and interpreted.
*  **Clutter.** Images create visual clutter that people become accustomed to skipping over instead of making use of them.

It can be difficult to determine what's too much and what's not enough when it comes to visual content. For example, showing just the relevant part of the UI removes context from an image, but showing the whole UI can provide too much information.

This is just one way in which the "show, don’t tell" mentality can be deceiving in its simplicity and flawed when it comes to its effectiveness in product documentation.

It's tempting to over-rely on visual content for documentation because images and screenshots seemingly remove the effort required to write and read the full instructions. However, images don't "speak for themselves". They require interpretation and explanation. We often rely on image annotation to highlight the important information in a screenshot precisely because images don't "speak for themselves".

If you want your documentation to be usable, inclusive, and easy to navigate, with accessible content that can also be scanned and actively searched, you can't replace written instructions with images. Use visual content to *enhance* the text, rather than to replace it or to add visual interest to the page. Only use visual content that serves a clear functional purpose. Visual content, especially annotated screenshots, add visual clutter, and visual content that includes the instructions within it is less accessible than written instructions for those that rely on screenreaders.

Given the above, some guidelines for using visual content in product documentation include:

* Make visual content complementary to written text, and not a substitute for it. Add this visual content *after* you've written your instructions and can be confident in someone's ability to follow them.
* Use context-relevant and functional visual content; avoid using visual content for visual interest or as a filler.
* Explain an image in text before including it. 
* Consider using [simplified user interface](https://katcassidy.com/blog/creating-beautiful-suis) (SUI) images.
* Regardless of the type of visual content (including SUIs and screenshots of just one element of the UI), make sure it's high quality.
* Balance the number and size of images against the amount of text that surrounds it; written instructions shouldn't be hard to see or search.
* For accessibility, consider size and colour contrast, and include captions and alt-text for screenreaders. 