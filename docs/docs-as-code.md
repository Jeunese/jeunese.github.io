**THESE ARE JUST NOTES**

# Docs as Code

Good documentation works best when it's:

*  Comprehensive
*  Easy-to-view
*  Always up-to-date

Therefore, the best place for documentation to live is within the corresponding repo -- the repo of the product or service that it documents. This means that the documentation is:

stored in docs and in markdown form

*  Version-controlled
*  Easy to keep up-to-date
*  Has a low editing overhead
*  Removes the need for context-switching
*  Easy to view both online and offline
*  You don't have to rely on other software because you're only editing Markdown
*  Empowers colleagues in engineering to make their own changes, where appropriate

## Tools

You can use a static site generator, such as [Docsify](https://docsify.js.org/#/) to generate documentation that is easy to navigate and parse. You can extend Docsify with features such as collapsible menus, search tools, and themes, for example, with [docsify-themeable](https://jhildenbiddle.github.io/docsify-themeable/#/introduction).

You edit the documentation in a text editor, like [VSCode](https://code.visualstudio.com/). 

You can use a tool like [GitHub pages](https://pages.github.com/) to automatically serve the documentation online, and to then keep the online documentation up-to-date. Every time that you push to the online repo, it will update your documentation.

## Process

Using the above examples of possible tools, content is managed using Git for version control, maintained in Markdown files, formatted using ["GitHub Flavored Markdown" (GFM)](https://github.github.com/gfm/), and edited using VSCode.
The static site generator formats the markdown into HTML.
and automatically served remotely and locally using a static site generator, like github pages with docsify.
