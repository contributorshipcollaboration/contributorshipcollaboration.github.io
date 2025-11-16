---
title: Tenzing update - Acknowledgments
sidebar: false
description: Tenzing release 0.4.1
date: 2025-11-16
---

Our free website, [tenzing](tenzing.club), is used by many researchers to manage co-author information such as affiliations and CRediT contributions, and to generate manuscript title pages. Thanks to our new release, now you can also use tenzing to generate acknowledgments sections. 

![](/images/favicon.png){ width=20% }

### What Does It Do?

The acknowledgments feature allows researchers to systematically document and report the contributions of non-author contributors. Tenzing now enables you to:

- **Create structured acknowledgments sections** that specify what each acknowledgee contributed, using CRediT taxonomy roles where appropriate
- **Include ORCID identifiers** for acknowledgees, making their contributions machine-readable and potentially indexable by scholarly databases
- **Produce properly formatted acknowledgments text** ready for manuscript insertion
- **Generate JATS-XML metadata** for acknowledgees, similar to how author metadata is handled, facilitating publishers including this information in article metadata (no publisher that we know of does this, but we are trying to show the way)

## Why This Matters

We have done this as part of our broader project to enhance the recognition that individuals who aren't co-authors receive.

### Surfacing the Hidden Contributors

Research relies on diverse expertise that sometimes goes unrecognized. Consider:

- **Field and lab technicians** who collect and process samples, maintain equipment, and advise on study design
- **Librarians and information specialists** who design systematic searches for meta-analyses and systematic reviews—work that can take over a year
- **Statisticians and methodologists** who design studies and develop new analytical approaches
- **Software engineers** who create specialized research software and manage data infrastructure
- **Research managers** who handle permits, ethics approvals, and compliance
- **Junior students and interns** who contribute to data collection and analysis

Unfortunately, acknowledgments today are essentially invisible to the systems that allocate research funding and career opportunities. As [Kiermer et al. (2025)](https://osf.io/download/geqjx) put it: "there is currently no robust mechanism for ensuring that research assessment committees consider non-author contributors, and contributors are deprived of downstream credit."

Scholarly databases don't index the people listed in acknowledgments sections, so they are difficult to find and tally. But that could change, especially if others adopt the practice tenzing now encourages, of including ORCiD information about individuals in acknowledgments.

Such individuals often make dozens of small but essential contributions across many projects. Because they're mentioned only in acknowledgments—if at all—they receive far less career credit than those who make a few contributions that warrant authorship. This also means that the university managers that pay the salaries of such people find it hard to see their full value. 

In the future, we hope that publishers will include formal metadata, using JATS-XML, to make the identities of individuals in acknowledgments clear, in a way that will make it into databases.


For more detail about the rationale behind including acknowledgments in tenzing and our broader vision for boosting recognition of acknowledgees, see our preprint, [Improving Acknowledgments Sections to Better Credit Research Contributors](https://osf.io/preprints/metaarxiv/t2uwe_v1).

## Other improvements

Beyond the acknowledgments feature, this release of [tenzing](tenzing.club) provides several enhancements:

### Enhanced Contributor Lists
- **Choose between initials or full names** for contributors
- **List contributions by CRediT taxonomy** directly after contributor names

### Improved Data Management
- **Validation improvements**: Review your contributors table within the app even if it doesn't pass all validation checks

### Expanded Metadata Support
Two new columns have been added to the contributors table template:
- **ORCID iD**: Link contributors, both co-authors and acknowledgees, to their unique researcher identifiers  
- **Funding**: Document which contributors received which funding sources, and generate formatted funding acknowledgment sections

### Better Documentation
- CRediT taxonomy role names are now standardized in the contributors table
- Each role includes URLs directing to the official taxonomy documentation

## Use it today

Whether you're preparing a manuscript, planning a new research project, or ensuring your entire team gets proper credit, tenzing might help. 

Your colleagues, collaborators, and all those who make your research possible deserve to be seen.

Visit [tenzing.club](https://tenzing.club/) to use tenzing directly in your browser.

If you prefer to use it locally or as an R package: 

```r
# Install from GitHub
devtools::install_github("marton-balazs-kovacs/tenzing")

```

---

*Tenzing is an open-source project released under the MIT license. The project is maintained by Marton Kovacs, Alex O. Holcombe, and others.*

