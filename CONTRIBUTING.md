# Introduction
A CONTRIBUTING.md file, in your open source repository or site, provides potential project contributors with a short guide to how they can help with your project or study group. It is convention to capitalize the word "contributing" as the file title, and to save it as a resource in markdown (hence the extension .md).

This file is for:
- Project owners - creators and maintiners of the file
- Project contributors - users of the file who want to know items they're welcome to tackle, and tact they need in navigating the project/respecting those involved with the project
- Project consumers - users who want to build off the project to create their own project

CONTRIBUTING.md should be in your root directory, think of it as an anchor for your project, around which you will build community and keep things tidy. It complements other "all-caps" resources like your README.md (which introduces your community to the project, its purpose and basic installation requirements), or your LICENSE.md (which provides information on the reuse and permissions associated with the code).

The CONTRIBUTING.md should be one of your first priorities in putting an open source/science project online to solicit contributions. If you have yet to define possible avenues of contribution, consider creating a CONTRIBUTING.md file with a "check back later, we will populate this soon" message, and the contact information of the project lead for follow-up.

You should try to build a draft of the CONTRIBUTING.md file with the core contributors to your project to help them feel a shared sense of responsibility and to create the best possible guide for encouraging new contributors. It is sometimes best to practice building a markdown file in an offline program like Mou or an online one like Dilliger before you post it online.

### Welcome contributors to the project
 Admit that you are eager for contributions and so happy they found themselves here.
### Explain what kinds of contributions you are looking for
 Writing//improving documentation, performing code reviews, managing bug reports and feature requests, etc. Basicly, anything that makes your work pleasant.
### Short links to important resources
   **Docs**: technical manuals describing the operation and use of the tool/product/technology<br/>
   **Todo/Roadmap**: let them know about [this section](https://github.com/DoronBrayer/repo-template/projects)<br/>
   **Bugs**: issue tracker / bug report tool<br/>
   **Comms**: forum, social network, real-time messaging, email<br/>
### Table of contents
If your CONTRIBUTING.md file is long, you might consider including a table of contents with links to different headings in your document. In github, each heading is given a URL by default, so you can link to that URL in the appropriate section of the Table of Contents for each heading. Do this in Markdown by wrapping the label/title in square brackets following by a parenthetical that includes the URL.</br>Example: `[Some text](https://www.some-url.com)`</br>Result: [Some text](https://www.some-url.com).
### Code of conduct
This project and everyone participating in it is governed by the {PROJECT-NAME} [code of conduct](https://github.com/DoronBrayer/repo-template/blob/master/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to {EMAIL-ADDRESS}.
### How to submit changes
Pull Request protocol etc. You might also include what response they'll get back from the team on submission, or any caveats about the speed of response.
### How to report a bug
Bugs are problems in code, in the functionality of an application or in its UI design; you can submit them through "bug trackers" and most projects invite you to do so, so that they may "debug" with more efficiency and the input of a contributor. Take a look at [Atom's example](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#reporting-bugs) for how to teach people to report bugs to your project.
Templates: in this section of your file, you might also want to link to a bug report "template" like this one [here](https://github.com/zurb/foundation-sites/issues/new) which contributors can copy and add context to; this will keep your bugs tidy and relevant.
### First bugs for contributors
Sometimes it is helpful to provide some guidelines for the types of bugs contributors should tackle (should they want to fix the bugs and not just submit them), see Atom's example section [here](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#styleguides).
### How to request an "enhancement"
enhancements are features that you might like to suggest to a project, but aren't necessarily bugs/problems with the existing code; there is a "label" for enhancments in Github's Issues (where you report bugs), so you can tag issues as "enhancement," and thereby allow contributors to prioritize issues/bugs reported to the project. See [Atom's example section](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#suggesting-enhancements).
### Styleguide / Coding conventions
[See Atom's example](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#styleguides).
### Recognition model
provide a pre-emptive "thank you" for contributing and list any recognition contributors might receive for participating in your project.
### Who is involved?
[Open Government's CONTRIBUTING.md](https://github.com/opengovernment/opengovernment/blob/master/CONTRIBUTING.md) has as a name/author, and it might be nice to have a more personal/friendly individual to attact to a project and reach out to with questions. You might list the core contributors and their preferred methods of contact here, or link to a [humans.txt](http://humanstxt.org/) file in your root directory (same place as your CONTRIBUTING.md file), which lets people know who they are working. Here is an [example of a humans.txt file](http://stereosemantics.com/humans.txt).
### Where can I ask for help?
a nice extension to the previous section, with links to good comms channels for anyone with questions.
### [OPTIONAL] Testing
how to test the project, where the tests are located in your directories.
### [OPTIONAL] Environment details
how to set up your development environment. This might exist in the README.md depending on the project. If so, include a link.
### [OPTIONAL] Create a system for rewarding people
Include a humans.txt file to give accolades to contributors. Store this in your root directory just like your CONTRIBUTING.md. On deployment, it will be available via your website at www.YOURWEBSITE.com/humans.txt.
