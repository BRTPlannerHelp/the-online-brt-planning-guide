# The Online BRT Planning Guide
[![View the last stable version of the guide](https://img.shields.io/badge/view-last_stable-blue.svg?style=flat-square)](https://brt.robrt.io/branch/master/guide)
[![View the bleeding edge version of the guide](https://img.shields.io/badge/view-bleeding_edge-brightgreen.svg?style=flat-square)](https://brt.robrt.io/branch/development/guide)

The Bus Rapid Transit Planning Guide is the most comprehensive resource for
planning a bus rapid transit (BRT) system, beginning with project preparation
all the way through to implementation.

It is a huge effort by the Institute of Transportation and Development Policy
(ITDP), and dozens of authors and reviewers.

This project aims to make the guide more accessible and keep it up-to-date:

 - the guide is now available online in a website format that is easy to navigate
 - PDFs are also available to those that need to print it
 - the online publication of updates is automatic
 - the entire history of the guide is kept with Git
 - revisions and contributions are easier with GitHub


## File structure

Essentially, the project is divided in two top-level folders: the
[`/guide`](guide) and the [`/generator`](generator).

The first has the files for the entire contents of the guide (text, images,
tables, etc).  The text is written in a simple but powerful format, that at the
same allows ease of use, independence of content from style and is compatible
with version control.

The second contains the source-code for the generator tool, that takes the text
for the guide and the assets and builds, in a single run, both the full website
and the PDFs.


## Contributing

You can ask questions or report problems in the guide by [opening a GitHub
issue](https://github.com/protocubo/the-online-brt-planning-guide/issues/new).

If instead you want to propose changes to either the guide (i.e. a typo fix or
a new section) or, if you're a programmer or a designer, to the generator tool,
please (fork the repository and) open a pull request.

More documentation on how to work with the guide and with GitHub will gradually
become available. In the mean time, if you need help, do not hesitate to
[contact the geeks behind the curtain](mailto:contato@protocubo.io).

