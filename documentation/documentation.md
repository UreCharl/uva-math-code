---
title: Main principles
layout: documentation_page
permalink: /doc/
nav_parent: Info
nav_nesting: true
nav_weight: 100
nav_id: Website Documentation
doc_page: true
---

# Main principles

## Collaborative editing powered by [GitHub](https://github.com)

Edits to the website are tested automatically so are unlikely to break anything.
Moreover, any edit can be reverted. Therefore, *you* are welcome to
participate in editing the content. The first step is to sign up on [GitHub.com](https://github.com)
and send your username to [L. Petrov](mailto:petrov@virginia.edu) to be added as a collaborator.

There are two main ways to edit the website content:

- **On the web**: Smaller edits can be made directly on the web at [GitHub](https://github.com/uva-math/uva-math-code).
- **Locally**: Clone the website code to your local machine, make edits, and then sync the changes back to [GitHub](https://github.com/uva-math/uva-math-code). For this we recommend installing the [GitHub Desktop app](https://desktop.github.com/) and the [Atom text editor](https://atom.io/). Both are available for both Windows and Mac, and Atom is also available for Linux.

In both cases, the changes in the code will trigger the website to automatically update, this takes about 5 minutes.

Having a local copy of the website allows to preview your edits locally using [Jekyll](https://jekyllrb.com/) (only on Mac and Linux). This procedure is described in detail in Jekyll documentation, see for example [here](https://jekyllrb.com/docs/installation/) and [here](https://jekyllrb.com/docs/usage/). **Note that due to API limitations seminar google calendars will not work in local previews**.

The website building (and testing) are powered by [Travis CI](https://travis-ci.org/). The current build status is&nbsp;&nbsp;[![Build Status](https://travis-ci.org/uva-math/uva-math-code.svg?branch=master)](https://travis-ci.org/uva-math/uva-math-code)

## Simple content structure powered by [Jekyll](https://jekyllrb.com/)

- Any simple change in content should require editing in only one place. More complicated edits (such as adding a new seminar) might need changes in up to two places. Typical editing scenarios are documented on these pages.
- The content is text file based, with no databases or complicated CMSs
- The simply structured content is then built (using [Travis CI](https://travis-ci.org/)) into a static HTML website (plus a little client-side javascript for google calendar interaction, math rendering, and responsive design)

## Flexible design powered by [Bootstrap](http://getbootstrap.com/)

- Most design elements can be tweaked independently of content (and most changes require editing only in one file)
- Design is fully customizable