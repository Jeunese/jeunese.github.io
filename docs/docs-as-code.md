# Online Documentation

Technical documentation should ideally be hosted online. 

PDF documentation needs to be actively shared and downloaded, after which, its contents are no longer under your control. PDFs get out-of-date. Outdated information can eventually become harmful. 

Even if you regularly create updated PDFs, you then have an issue with version control. You can't force people to delete their older versions. You can't be sure that people have the most up-to-date version. The readers themselves might not be sure that they have the most up-to-date version, or which of their PDFs might be the correct one. And, the most recent PDF might be buried in an email thread somewhere.

As a technical writer working with PDFs, you have to wait until the next version to fix any issues, whether those are small fixes, like typos, or a major oversight, like incorrect technical detail. Even if you ship your documentation *with* the product itself in a README file, you can't fix any issues until the next release, and this might depend on convincing customers to upgrade.

Online documentation removes these issues, especially if you adopt a "Docs-as-Code" approach. 

You don’t have to adopt a Docs-as-Code approach to maintain online documentation. The approach just streamlines the processes involved and ensures that the product and its documentation are aligned. 

Using the Docs-as-Code approach, documentation becomes *part* of the product or feature, and so can't be neglected. Documentation must be written before a product or feature can be released. 

## What is good documentation?

Good technical documentation is clear and useful to the reader, aided with the use of a good [writing guide](https://jeunese.github.io/#/guidelines), as well as empathy for the intended audience. But, this input is only one aspect of technical writing. Technical documentation also benefits from an efficient and effective process for delivering the *output*. 

Good documentation works best when it:

*  Is version controlled
*  Is easy to keep up-to-date and to apply fixes
*  Is in sync with product releases
*  Has a low editing overhead
*  Removes the need for context-switching
*  Is easily viewable both online and offline
*  Empowers colleagues in different teams to collaborate and contribute

That's what a Docs-as-Code approach offers.

Docs-as-Code allows you to output technical documentation alongside the products your content refers to. It also allows you to collaborate with others to keep the content up-to-date and to track changes to content with version control.


## What is Docs-as-Code?

Docs-as-Code is an approach to writing and publishing technical documentation using the same tools as Engineering. Just as Engineering continuously integrates, deploys, tests, and monitors their work, technical writers continuously develop the documentation that helps people *use* the product. 

Content is managed as code, which has the following benefits:

* Efficiency, by publishing in alignment with Engineering working practices.
* Accuracy (which also helps to establish trust) by making documentation easy to maintain and update.
* Consistency, both in style and purpose.
* Findability, by making content easy to tag, to include keywords for SEO, to access online, and to search.
* Collaboration, by fostering communication and cooperation between teams.
* Integration, by synchronising documentation release with the functionality of the product.

Using Engineering processes and tools to publish content allows technical writers to review and publish updates faster. Publishing is no longer a special or challenging event. Rather, the approach involves a simple and functional process in which you build the documentation and ensure that changes don't introduce errors before pushing it to a live website.

Docs-as-Code also empowers colleagues, especially the Engineers who build the product, to provide their own input. Even large teams of technical writers can't know everything about the product, and people are typically eager to contribute when they get to talk about something they care about. People like to share, so much so that many do it for free –– at work, in gaming, in open-source software projects, and in wikis. 

Ideally, you still create the majority of technical documentation yourself as part of a Continuous Integration (CI) release process, or "continuous documentation" (Docs-as-Code). Your job as a technical writer is largely about quality-control, aided with an established review and approval process. 

Contributors don't publish changes directly to a production website, but can suggest changes, which then pass through a review and approval process with a technical author.

### Terminology

Before continuing, let's cover some terminology.

| Term | Abbreviation |Description |
|---|---|---|
| Cascading Style Sheet |CSS | A style sheet language used to express the presentation of a document written in markup language, such as HTML. It is used to format the layout of Web pages by defining things like text style and table sizes –– aspects of Web pages that could previously only be defined in the page's HTML.|
| Cascading Style Sheet document | CSS document | A file that defines styles to be used by any page that references it. This is instead of defining the style of each element in each page's HTML, which helps create a uniform look across pages and makes it easy to make changes across multiple pages. |
|Continuous Integration | CI | A development practice in which developers frequently integrate code into a shared (remote) repo. Developers checkout code from the remote repo to work on locally, create a new branch for their work, and run tests on it in their own development environments. Once tests pass, they push commits to the remote repo, where their code is verified by an automated build. |
|Dynamic HTML file (compare with **static HTML file**) | | A page delivered to the web browser that offers a live or interactive user experience (such as the BBC website or Facebook); it can change over time depending on different pieces of information that the server writes into a single web page. | 
|Extensible Markup Language | XML | A **markup language** that defines a set of rules for encoding documents in a format that's both human-readable and machine-readable. |
| Formal specification | | A file that lists the criteria for a product, including edge cases, for conformance testing the otherwise ambiguous parts of the syntax, such as how much indentation is needed for a sublist.|
|GitHub-Flavored Markdown |GFM | A dialect of **Markdown** supported for content in GitHub. It's a formal specification that defines the syntax and semantics of GFM, which is a superset of CommonMark. Any GitHub content that isn't specified on the original CommonMark Spec are extensions, and highlighted as such. | 
|Hypertext Markup Language | HTML | An example of a markup language (a publishing format), which is used to create web pages. |
|Markup language| | A publishing format that uses tags to define page layout and the elements within a page.|
|Static HTML file |  | A page delivered to the web browser exactly as it is stored; it doesn't change over time unless it's replaced by another HTML file. |
|Static site generator | SSG | A tool that generates a full static HTML website based on raw data and a set of templates, automating the task of coding individual HTML pages and getting those pages ready to serve to users ahead of time.|
|Style sheet language | | A programming language that describes the presentation of structured documents; a constrained approach to creating standardised content that allows content to be reused in different contexts and helps content writers move away from versioning. |
| (Git) repository | Repo | Virtual storage of a directory or project. A remote repo is a version of your project hosted on a network or on the Internet. A local repo is a git repository on your local machine. |
|Version Control System (or Source Code Management tool) | VSC (not to be confused with VSC*ode*) | A tool that allows you to track and view changes over time, and to undo or redo those changes. A VSC is also used to co-ordinate the work of multiple people.

### Tools

These tools allow you to leverage CI and review tools for writing efficiently, effectively, and collaboratively with Engineering. They aren't the only tools available to you. Many alternatives exist. The tools listed, below, are used to help describe the Docs-as-Code process with concrete examples.

| Tool | Description |
|---|---|
|Docsify | An SSG that takes static files, like **Markdown** documents, and turns them into an HTML page.|
|Git | An open-source VSC for managing changes to source code, text files, and directories. |
|GitHub | A cloud-based hosting service for managing Git repositories. It helps you manage open-source projects that use Git. There are alternatives to GitHub, including GitLab and BitBucket, which are referred to as "remotes".|
|GitHub Pages | A static site-hosting service that takes files from a repository on GitHub to publish to a website.|
|Markdown | A lightweight/streamlined markup language that, as well as being a publishing format, is also a writing format, designed to be easy for humans to read, write, and understand.|
|Markdownlint |An extension for **VSCode** that automatically checks content style based on its library of rules, flagging anything that requires attention.|
|Visual Studio Code (VSC*ode*, not to be confused with VSC) | A free text and source code editor for building and debugging web and cloud applications.|

### Process

Broadly, the process for managing content using Git (for version control) to then push to a website, would be as follows:

1. Technical writers create and maintain content as code –– static data (such as Markdown files) –– in their local repo, edited in a text editor (like VSCode).
1. A static site generator (SSG) (such as Docsify) converts these files into a static HTML file (a static Web page). This page can be served in one of two ways:
    *  Locally through a browser on your machine. No Internet connection is needed for this, but you can't share it.
    *  Remotely through a static site-hosting service (like GitHub Pages), available to anyone with an Internet connection and a browser.
1. To host the content on a Web page, the static HTML file is pushed to a remote repo on a cloud-based hosting service (such as GitHub).
1. A static site-hosting service (such as GitHub Pages) takes files from the remote repo to publish on a website.

Markdown isn't the only kind of static data that an SSG can convert to HTML. The data could also be JSON, yml, images, or any other kind of static data file.

There is no formal standard for Markdown. However, in 2017, GitHub released a formal specification for GFM, which is emerging as an industry standard for Markdown, and a growing list of tools that support it. 

Markdownlint is an extension used for automated style checks on content written in VSCode. It doubles as a conformance test, highlighting any issues that violate one of Markdownlint's rules. This extension can be modified to create exceptions to the Markdown rules. 

### Example use case

Using the above examples of possible tools, content could be managed using Git for version control, maintained in Markdown files that are formatted using [GFM](https://github.github.com/gfm/), edited using [VSCode](https://code.visualstudio.com/), and stored in a remote repo on [GitHub](https://github.com/). 

You could then use [Docsify](https://docsify.js.org/#/) to generate documentation that is easy to navigate and parse. You can extend Docsify with features such as collapsible menus, search tools, and themes, for example, with [docsify-themeable](https://jhildenbiddle.github.io/docsify-themeable/#/introduction).

Every time you push to your remote repo, either through the command line or with VSCode, you trigger Docsify to convert your Markdown files to HTML before your content is published on your website through [GitHub Pages](https://pages.github.com/).

Alternatively, you could generate your HTML page with Docsify locally, and upload it onto GitHub pages.

### Get started with Docs-as-Code

1. Set up Git
1. Set up GitHub
1. Set up a local repo
1. Download Docsify
1. ...