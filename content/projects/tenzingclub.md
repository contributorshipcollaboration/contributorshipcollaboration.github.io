---
title: "tenzing.club"
sidebar: false
githublink: https://github.com/marton-balazs-kovacs/tenzing
link: http://tenzing.club/
description: Document and report your contributors' information with CRediT.
---

_[tenzing](https://tenzing.club)_, a simple web app, is designed for research scholars. It helps manage
project contributor info, and generates
reports about team member contributions using
CRediT, for insertion into manuscripts, and for publishers to
potentially incorporate into article metadata. 

[CRediT](http://credit.niso.org/) (Contributor Roles Taxonomy) is a
taxonomy of 14 categories of contributions to scientific scholarly
output. Each researcher can indicate which category they contributed to
in a scholarly project.

The app is named after the Nepali-Indian Sherpa Tenzing Norgay, who was
one of the two individuals who reached the summit of Mount Everest for
the first time. Despite his essential contribution, he received less
credit than his partner, the New Zealand mountaineer Edmund Hillary.


_tenzing.club_ can:

-   read all the necessary contributorship information from one file
    (.csv, .tsv or .xlsx)
-   create a report of the contributions
-   create the contributors’ affiliation information, designed for
    inclusion in the first page of a manuscript
-   create JATS XML with the contributions, suitable for publishers to
    include in metadata
-   create a YAML output that will automatically add the contributorship
    information to the `papaja` package used by some researchers to write
    APA-formatted manuscripts
