# SEmotion Website

Website for the Workshop on Emotion Awareness in Software Engineering 2021

# Prerequisites

Before building the site from Markdown, make sure that you have installed
[GNU make](https://www.gnu.org/software/make/) and
[Pandoc](http://pandoc.org/installing.html).  You can check your installs by
running the commands `make --version` (or possibly `gmake --version`) and
`pandoc --version` on the command line.

# Building

At the command line, `cd` into the repository's root directory and run GNU make
(depending on your installation, the command with either be `make` or `gmake`).

# Deploying

If you have access to year-specific repository, the makefile can deploy the
website automatically.  Simply run `make deploy`.
