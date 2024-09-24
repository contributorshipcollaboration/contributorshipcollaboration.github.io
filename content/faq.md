---
title: Frequently Asked Questions
sidebar: false
---

# Why is it important to make information about who did what machine-readable?

To visualize, or quantify, the contributions of a researcher or researchers across a set of articles, one needs comparable things to tally. While some might prefer to stick to free-text essays about one's work, both for metascience for researcher evaluation purposes, the world needs things that can be counted. With a delineated taxonomy such as CRediT used in papers, this can be done. While AI can now read papers, some information is still hard to tally, and will not be taken up, unless a common standard is involved.

# How is CRediT information made machine-readable by journals?

Most journals use a paper submission system provided by the publisher of the journal. These submission systems are designed to collect the journal article metadata (such as the names and affiliations of the authors, the abstract of the paper) from the corresponding author and store them in a machine-readable file. Most systems use the [Journal Article Tag Suite XML](https://jats.nlm.nih.gov/publishing/1.3/) format to append these metadata in an organized manner to the journal article published online. While the latest JATS 1.3 format allows for recording author contributions according to CRediT in the article metadata not all submission systems collect authors contributions. PLOS journals are collecting this information as metadata through a form. 

# The CRediT categories aren't well-suited for my project; what should I do?

Other schemes exist, such as the [Contributor Roles Ontology](https://github.com/data2health/contributor-role-ontology), which extends CRediT into more specific roles, and the [Taxonomy of Digital Research Activities in the Humanities (TaDiRAH)](https://vocabs.dariah.eu/tadirah/en/). However, within science at least, other schemes unfortunately are not widely used. For reform of CRediT itself, you may wish to [contact the CRediT committee of NISO](https://www.niso.org/standards-committees/credit). 

# How do authorship and contributorship relate to each other?

Contributorship is about documenting who did what, which in principle is orthogonal to authorship and authorship guidelines. However, in practice publishers have made contributorship subsidiary to authorship. That is, only people listed as authors on a paper have the chance to also get CRediT information.

Contributor information need not be subsidiary to authorship. Publishers could start listing other people with CRediT information, people not marked as authors, in the JATS-XML metadata. Then, a wider range of contributors to scholarship would become known, and this information potentially flow into scholarly databases such as CrossRef. However, changes would have to be made to get such databases to support that, and to get universities and other stakeholders to start using that information.

# In the case of single-contributor papers, should there be a contribution statement?

It may seem redundant to have CRediT information or a "who did what" section for single-author papers. However, there is the possibility that some contributors did not qualify for or did not wish to become authors, but it may still be appropriate to name them (for example in an Acknowledgment section). Second, because CRediT metadata will flow into scholarly databases, there will be a gap if the CRediT information for a sole-contributor paper is not provided in that paper.
