# Style Guide

Following a set of writing guidelines helps ensure consistency, content quality, and a good user experience of product documentation and UI content. The guidelines presented in this article are based on substantial research, content design principles, UX writing expertise, and industry standards.

This isn't a complete list of every language, grammar, or formatting rule or convention. The style guide is designed to deal with common scenarios and to recommend best practices for technical documentation and in-product content.

You can apply the following [Lean writing principles](/style-guide?id=lean-writing-principles), [Word choice guidelines](/style-guide?id=word-choice-guidelines), and [Writing conventions](/style-guide?id=writing-conventions) to both technical writing and UX writing (or content design).

For guidelines that are specific to technical writing, see [Technical Writing Guidelines](/technical-writing). For guidelines that are specific to UX writing, see [UX Writing Guidelines](/ux-writing).

## Tone of voice

This guide refers to *tone of voice* rather than voice and tone as separate constructs, defined in the [Voice and Tone](/voice-and-tone?id=voice-and-tone-or-tone-of-voice) article. Tone of voice defines how you talk to your audience.

Tone of voice is based on the type of company, target audience, and purpose of the content. For a software company, the purpose of product documentation is to provide administrators with quick product reference material for what the product does, how it works, and how to set it up. The purpose of in-product copy is to help end-users of the UI complete tasks easily and effectively with that company's software.

These are the high-level communication goals that inform the individual writing elements in this style guide.

- [Be clear](/voice-and-tone?id=be-clear) (direct, simple, precise, and concise)
- [Be human](/voice-and-tone?id=be-human) (conversational, personal, positive, and inclusive)
- [Be useful](/voice-and-tone?id=be-useful) (professional, user-centric, and action-focused)

To achieve these characteristics, your writing style the needs to follow some more granular principles and guidelines.

## Lean writing principles

Write clearly, precisely, and concisely to make content easier to read and understand.

### Keep content short and simple

Shorter paragraphs, sentences, and words are easier to scan, easier to understand, and more accessible to people who struggle with reading. Even advanced readers benefit from short and simple language because it results in faster processing and better comprehension. With this in mind, aim to:

- Write short sentences, and keep to a limit:
    - For online documentation, write sentences that are no more than 28 words.
    - For UI content, write sentences that are no more than 15 words.
- Separate different points or thoughts into different sentences.
- Use common contractions, such as "don't" instead of "do not".
- Use everyday words, such as "help" instead of "assistance".
- Remove excess words that don't add meaning to the sentence, for example: "Remove each ~~individual~~ item from the list." 
- Replace wordy phrases with single words where possible, for example: "due to the fact that" can be replaced with "because".
- Use as few words as possible to portray meaning, for example: "You'll be asked to change your password ~~at some point~~ before you next sign in."

### Write purposeful content

Write every sentence and choose every word with purpose, direction, and meaning.

- Write only to say something relevant that the reader or user can use.
- Use adjectives with purpose, not as filler.
- Don't write to take up space.
- Don't provide unnecessary context or detail.
- Don't tell the reader how to think or feel, such as "Setting this up is easy"; allow the reader to think or feel based on what you write.

### Get to the point, quicker

Follow these tips to get to the point in your communication with readers.

|Tip | Example |
|---|---|
|Avoid buried verbs (nominalisation): using a noun and a verb when a verb alone would portray the meaning.  | "Follow the guidelines for testing your software", rather than "Follow the guidelines for *performing a test of* your software". Turning the word "test" into an action removed the need for the word "performing".|
|Omit prepositional phrases. | "Select the plus sign ~~in order~~ to add a new user" or "~~In this case~~, delete the file." |
|Use adverbs in place of prepositional phrases.  | "This allows you to use the app effectively", rather than "This allows you to use the app *with great effectiveness*". |
|Replace prepositional phrases with the possessive.| "Find the computer's instructions", rather than "Find *the instructions for the computer*".|
|Use the active voice, which is more direct and easier to understand than the passive voice. |"You can send emails from your phone", rather than "Emails *can be sent from* your phone".|
|Write imperative sentences. | "If you need further help, ~~you can~~ contact the Support team". |
|Avoid grammatical expletives (words that add emphasis by delaying the subject), such as "it is" or "there are". |"There are six items in the list", could be reworded to "The list has six items".|

## Word choice guidelines

Use clear, consistent, and human language.

### Use unambiguous terms

-  Use terms that are clear and understood by global audiences without need of special or local cultural knowledge.
-  Avoid "would", "should", and "may", which can be ambiguous in describing whether something *will*, *must*, or *can* be done.
-  Don't use double-negatives, for example, use "like" instead of "not unlike".

### Use plain English

-  Avoid marketing language and technical jargon.
-  Use industry-standard terminology when it will improve user understanding.
-  Use technical language only when it's needed, and try to also explain it generally.
-  Spend time researching what words the intended readers use rather than defaulting to corporate language.
-  Use intended words instead of Latin abbreviations, such as "specifically" instead of "i.e.".

### Use terminology consistently

Without consistency, documentation can come across as unreliable or lacking credibility.

-  Don't switch between terms in the product documentation or in the product itself.
-  After introducing an acronym, don't switch back and forth between full words and the acronym.
-  Don't switch between language conventions, such as American and British spellings.
-  In instructions, refer to UI elements exactly as they appear in the product.

### Use unbiased and inclusive language

You're talking to humans, so be sensitive to the human meaning of words.

|Guidance | Example |
|---|---|
|Avoid offensive or violent terms, like "abort", "hit", "force", "reject", "kill", "hang", and "terminate". | **Do use:** "*End* your session." **Don't use:** "*Kill* your session." |
|Avoid terms that reflect historical racial bias such as using colour to communicate something is "good" or "bad", and references that carry forward the master/slave paradigm | **Do use:** "blocklist", "allowlist", "main table". **Don't use:** "blacklist", "whitelist", "master table". |
|Use gender-neutral alternatives to "he", "she", "him", and "her". | **Do use:** "them", "their", "they". **Don't use:** "him", "his", "her".|

### Be considerate, not over-polite

Avoid overusing "please", "thank you", and "sorry", especially for normal operations of the program. Adding these terms might seem polite, but they can come across as disingenuous and slow people down by adding wordiness to your sentences.

|Term | Guidance | When to use (example) | When to remove (example) |
|---|---|---|---|
|Please | Use "please" only in situations where you're asking someone to do something inconvenient or where the software is at fault. | "Please try again later." | "To view the file, ~~please~~ select **View**."|
|Thank you | Use "thank you" when you're asking someone to provide input that's inconvenient. Convey gratitude from the people behind the documentation or product rather than the system itself. |"Thank you for giving us your feedback!" |"Check that you've entered your email address correctly before submitting. ~~Thank you~~."  |
|Sorry | Use "sorry" only in situations that cause problems for the user, such as a system crash or data loss. Don't apologise for how the product or service is designed to function. | "Sorry. We were unable to connect you to the service. Please try again later." |"~~Sorry.~~ It looks like your card is expired." |

Software and product documentation should, above all else, be *considerate* more so than polite, which means putting the needs of of the reader or user first. 

For example, an error message that says *"Sorry! There was a generic error"* is polite, but not especially useful because it focuses on its own function, and not what the reader or user needs to do. 

## Writing conventions

This section provides guidance on some of the mechanics of technical writing, like punctuation, capitalisation, and lists –– the individual elements that help make content clear and understandable.

### Punctuation

Punctuation provides meaning in the absence of the rhythm, intonation, and pauses that speech would otherwise offer for clarity.

-  Keep punctuation simple. Complex constructions, using semicolons or multiple dashes, for example, can impair readability and can make translation difficult.
-  Use the serial (Oxford) comma to provide clarity and to maintain consistency across content. Use a comma for a series of three or more elements.
-  Don't use end punctuation (``. : ! ?``) in section titles, subheadings, UI titles, and items in a list that are three or fewer words.
-  Don't use a comma to combine two independent clauses (comma splicing). Instead, add a conjunction (like "and") or separate the clauses into two sentences. For example, *"I sent 100 emails, I plan to send 100 more"* could instead be either:
    - *"I sent 100 emails, and I plan to send 100 more."*
    - *"I sent 100 emails. I plan to send 100 more."*

### Capitalisation

There has been a recent shift to using sentence case in headings, except for global (primary) headers in a website, otherwise known as top-level navigation. This is because sentence case is easier to read. Sentence case involves capitalising only the first word and proper nouns in a heading.

In general, use sentence case for: 

-  Headlines, headers, and subheads.
-  Secondary web navigation and menu items.
-  Buttons and calls to action (CTA).
-  Titles and input fields.
-  Titles of charts, tables, and diagrams.
-  List items.

Use title case only for:

-  Main or global navigation on webpages (top-level/primary navigation).
-  Distinguishing products from general technology with similar names (for example, SQL Server from SQL database server).
-  Titles of books, podcasts, webinars, and videos.
-  Trademarked product names.

### Headings

Headings help with scanning by breaking up a page into sections and signposting those sections.

-  Keep headings (headlines and subheadings) short, clear, and to the point. 
-  Use action verbs whenever possible. 
-  Choose clarity over cleverness.
-  Highlight the main point of your content to give the reader a good sense of what they’re about to read. 
-  Create a benefit-driven statement written in conversational language.  
-  Keep your headline as short as possible, using a subheading to dive into the details.

### Lists

Use lists to present steps, groups, or sets of information:

-  Use bullets, not numbers, when the order of the list doesn’t matter. 
-  Number a list when the order is important, like describing steps of a process. 
-  Capitalise the first word of a list item. 
-  If a list includes standalone, complete sentences, use proper closing punctuation. 
-  Don’t add a full stop to the end of a list item if it’s not a complete sentence or if it contains fewer than four words.

Long lists of bullets are no easier to read than big blocks of text. So keep bulleted items:

* Short
* Related
* Consistent in style
* Eight items or fewer

Consider grouping longer lists into themes and under different subheadings. 

### Links

A link is an interactive reference to other (relevant and trusted) content or external resources that the user can access by selecting it. Guidelines for links include:

- Don't link preceding articles (a, an, the).
- Don't link punctuation.
- Ensure the link looks different from regular text.
- Include a hover state that communicates the link's interactivity.
- Write a normal sentence and link the relevant words in it.
- Don't include things like "Click here" on a link.

### Symbols

Don't use symbols or characters to substitute words:

-  Use "or" instead of ``/``.
-  Use "and" instead of ``&`` unless space is extremely limited in the UI, for example, in tab labels or screen titles.
 -  Use "more than" and "less than" instead of ``>`` and ``<`` unless space is extremely limited in UI labels.
 -  Only use ``+`` when you're adding a technical command or to indicate a count that exceeds a specific number when space is limited in the UI, for example, "30+ degrees".
-  Only use ``"`` when you're adding a technical command or to represent inches, for example, 10"x10".
-  Only use ``x`` when you're adding a technical command; don't use the letter ``x`` to indicate a multiplication sign.
-  Use an en dash (``-``) to indicate a minus sign or a hyphen.
-  Use "percent" with a number (for example, 5 percent) and "percentage" without a number.
	- Spell out the word "percent" (instead of using the `%` symbol), unless it's in a heading or table.
	- Always use a number with "percent" unless the number is the first word in a sentence.
	- Use a space between the number and the word "percent".
	-  Use "percent" without a number in column headings.
	-  Use the the `%` symbol in UI charts, and table cells, or as a technical symbol.


### Numbers

-  In the main body of text:
    -  Spell out numbers from zero through to nine.
    -  Use figures for 10 and above.
-  Use figures for numbers in headlines.
-  Use figures before million, billion, and trillion (for example, 1 million).
-  Use figures for specific dates, time, and measurements (for example, 5 minutes), unless that number is at the beginning of a sentence.

### Dashes and hyphens

- Hyphenate compound modifiers that act as adjectives, for example, "a high-definition user experience".
- Don't use a hyphen with adverbs ending in -ly, for example, "a highly mobile worker".
- Use em dashes (––) like parentheses, but don’t overuse them. 
- Be careful not to substitute an en dash (–) for an em dash (––), or vice versa.
- Use an en dash (–) to indicate a: 
	- Minus sign
	- Negative number
	- Range of numbers (for example, pages 95–110)

### Acronyms and abbreviations

Use shortened forms with care. 

Reserve acronyms and abbreviations for when space is limited or for when users are more familiar with the acronym or abbreviation than the phrase it's based on (for example, URL). When you do use acronyms and abbreviations:

-  Don't capitalise the words on which the acronym is based unless referring to a proper noun.
-  Avoid using the possessive form with abbreviations and acronyms.
-  Use the proper article with an acronym in the sentence.
-  Don't use an apostrophe for the plural of an acronym.
-  Avoid using abbreviations and acronyms for the first time in a title or heading, unless the abbreviation or acronym is a keyword, in which case, introduce the acronym in parenthesis following the full phrase it's based on.
-  Use abbreviations for a unit of measurement.
	-  If an abbreviation matches a preposition, include a period after. For example, "3 ft, 5 in."
	-  Insert a space between the number and the unit of measure.

In technical documentation, spell out acronyms on first reference. Include the acronym in parentheses immediately following the expanded form unless it's a long-established acronym (for example, HTML).

For more guidelines that are specific to technical writing, see [Technical Writing Guidelines](/technical-writing).

For guidelines that are specific to UX writing, see [UX Writing Guidelines](/ux-writing).