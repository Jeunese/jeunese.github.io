# Online Documentation

Technical documentation should ideally be hosted online. 

PDFs get out-of-date. Outdated information can eventually become harmful when it is shared and downloaded –– as PDF documentation must be of use in the first instance. Even if you regularly create updated PDFs, you then have an issue with version control. You can't force people to delete their older versions. You can't be sure that people have the most up-to-date version. The readers themselves might not even be sure that they have the most up-to-date version, or which of their PDFs might be the correct one. 

And, as a technical writer, you have to wait until the next version to fix any issues, whether those are small fixes, like typos, or a major oversight, like missing technical detail. Even if you ship your documentation *with* the product itself, you can't fix any issues until the next release, and this might depend on convincing customers to upgrade.

Online documentation removes these issues, especially if you adopt a "Docs as Code" approach. Under this approach, publishing is no longer a special or challenging event. Rather, Docs as Code involves an established review and approval process before pushing content to a production website. And, the process can be simple and functional –– building the documentation and ensuring that the changes don't introduce errors.

## What is good documentation?

Good technical documentation is clear and useful to the reader, aided with a good [style guide](https://jeunese.github.io/#/guidelines) and empathy for the intended audience. But, this is only one aspect. For readers to make the most of it, technical documentation also needs an efficient and effective process. 

Good documentation works best when it's:

*  Version controlled
*  Easy to keep up-to-date and to apply fixes
*  In sync with product releases
*  Has a low editing overhead
*  Removes the need for context-switching
*  Easily viewable both online and offline
*  Empowers colleagues in different teams to collaborate and contribute

That's what a Docs as Code approach does.

## What is Docs as Code?

Documentation as Code (Docs as Code) is an approach to writing and publishing technical documentation using the same tools as code. Engineering continuously integrates, deploys, tests, and monitors their work as part of a Continuous Delivery Pipeline (CDP). It makes sense that we should also be continuously developing the documentation that helps people *use* the product.

The benefits of this approach are:

* Efficiency –– publishing in alignment with Engineering working practices.
* Accuracy –– easy to maintain and update, which also helps to establish trust.
* Consistency –– consistent in style and purpose.
* Findability –– easy to tag, include keywords for SEO, and find.
* Collaboration –– fosters communication and cooperation between colleagues.
* Integration –– better alignment with Engineering such that documentation is synchronized with the functionality of the product.

Using Engineering processes and tools to publish content allows technical writers to review and publish updates faster.

Docs as Code also empowers colleagues, especially the Engineers who build the product, to provide their own input. Even large teams of technical writers can't know everything about the product, and people are typically eager to contribute when they get to talk about something they care about. People like to share, so much so that many do it for free –– at work, in gaming, in open-source software projects, and in wikis. 

Your job as a technical writer is largely about quality-control, aided by implementing a review and approval process. Contributers don't publish changes directly, but can suggest changes, which then pass through a review and approval process with a technical author.

Ideally, you'll still create the majority of technical documentation yourself as part of a Continuous Integration release process, or "continuous documentation" (Docs and Code). Documentation becomes *part* of the feature, and so must be written before a feature can be released.

### Terminology

| Term | Abbreviation |Description |
|---|---|---|
|Continuous Integration | CI | Part of the Content Delivery Pipeline (CDP) in which features in a backlog are implemented, refined, built, and integrated into a full system. |
|Extensible Markup Language | XML | A **markup language** that defines a set of rules for encoding documents in a format that is both human-readable and machine-readable |
| Cascading Style Sheet |CSS | A style sheet language used to express the presentation of a document written in markup language, such as HTML. It is used to format the layout of Web pages by defining things like text style and table sizes –– aspects of Web pages that could previously only be defined in the page's HTML.|
| Cascading Style Sheet document | CSS document | A file that defines styles to be used by any page that references it. This is instead of defining the style of each element in each page's HTML, which helps create a uniform look across pages and makes it easy to make changes across multiple pages. |
| Formal specification | | A file that lists the criteria for a product, including edge cases, for conformance testing the otherwise ambiguous parts of the syntax, such as how much indentation is needed for a sublist.|
|GitHub-Flavored Markdown |GFM | A dialect of **Markdown** supported for content in GitHub. It is a formal specification that defines the syntax and semantics of GFM, which is a superset of CommonMark. Any GitHub content that isn't specified on the original CommonMark Spec are extensions, and highlighted as such. | 
|Hypertext Markup Language | HTML | An example of a markup language (a publishing format), which is used to create webpages. |
|Markup language| | A publishing format that uses tags to define page layout and the elements within a page.|
|Static site generator | SSG | A tool that generates a full static HTML website based on raw data and a set of templates, automating the task of coding individual HTML pages and getting those pages ready to serve to users ahead of time.|
| (Git) repository | Repo | Virtual storage of a directory or project. A remote repo is a version of your project hosted on a network or on the Internet. A local repo is a git repository on your local machine. |
|Style sheet language | | A programming language that describes the presentation of structured documents; a constrained approach to creating standardised content that allows content to be reused in different contexts and helps content writers move away from versioning. |
|Version Control System (or Source Code Management tool) | VSC (not to be confused with VSC*ode*) | A tool that allows you to track and view changes over time, and to undo or redo those changes. A VSC is also used to co-ordinate the work of multiple people.

### Tools

These tools allow you to leverage continuous integration and review tools to writing efficiently, effectively, and collaboratively with Engineering.

| Tool | Description |
|---|---|
|Docsify | An SSG that takes static files, like **Markdown** documents, and turns them into an HTML page.|
|Git | An open-source VSC for managing changes to source code, text files, and directories. |
|GitHub | A cloud-based hosting service for managing Git repositories. It helps you manage open-source projects that use Git. There are alternatives to GitHub, including GitLab and BitBucket, which are referred to as "remotes".|
|GitHub Pages | |
|Markdown | A lightweight/streamlined markup language that, as well as being a publishing format, is also a writing format. It's a text-to-HTML conversion tool for web writers that's designed to be easy for humans to read, write, and understand.|
|Markdownlint |An extension for **VSCode** that automatically checks content style based on its library of rules, flagging anything that requires attention.|
|Visual Studio Code (VSC*ode*, not to be confused with VSC) | A free text and source code editor for building and debugging web and cloud applications.|

### Process
This process allows you to output technical documentation alongside the products your content refers to. 

### Example use case

### Get started with Docs as Code