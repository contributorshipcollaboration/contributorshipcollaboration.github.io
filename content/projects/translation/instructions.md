---
title: Instructions for Contributors
description: Guidelines for contributing to the translations and other aspects of the project.
order: 2
layout: "translation/single"
---

**Our mission:** Make CRediT more inclusive by translating it into other languages, and assist communities to adopt CRediT.

# 💛  Contributing 

We invite all interested to contribute to the project.     

**General instructions:**

 1. Fill in the [Expression Of Interest (EOI) form](https://docs.google.com/forms/d/e/1FAIpQLSfdhqlnk4sw61MkkDuufZyqO1SKmnp--QE6vEG1_7qnP9MzJg/viewform?usp=sf_link), so we hae your name and contact details.
 1. To enable broad global participation, we will mostly work asynchronously online but have occasional Zoom hackathons.
 1. We expect all project contributors to familiarise themselves and follow our [code of conduct](https://github.com/marton-balazs-kovacs/tenzing/blob/master/CODE_OF_CONDUCT.md).
 1. If you would like to comment on this project or provide suggestions to improve this project, open an issue on GitHub or message on
Slack (invites will be sent to project participants who filled in the [EOI form](https://docs.google.com/forms/d/e/1FAIpQLSfdhqlnk4sw61MkkDuufZyqO1SKmnp--QE6vEG1_7qnP9MzJg/viewform?usp=sf_link)) or email (aoholcombe@gmail.com).   
 1. We will post updates on [the blog](https://contributorshipcollaboration.github.io/blog/), as well as the [language status table](https://github.com/contributorshipcollaboration/contributorshipcollaboration.github.io/blob/master/content/projects/translation/progress.md)
 1. All contributions to this project are voluntary. We will not provide financial remuneration for any contributions (we have no funding).
 1. You can withdraw from the project at any time.        

## 🧱  Translation contributions 

Anyone fluent in a language not already translated can help provide a new translation, or propose a change to an existing translation.

Before starting on a new translation:

* [Check the current status](https://github.com/contributorshipcollaboration/contributorshipcollaboration.github.io/blob/master/content/projects/translation/progress.md) of translation for your language.
* Follow the instructions in the below [translation section](#-Creating-a-translation).

### Creating a translation

*  We have created a Google Sheet for entering your translation work and seeing how others did it. Contact us for access to the Google Sheet.
* First, one speaker fluent in both languages translates the English into the target language and enters that on the Google Sheet. 
* A second speaker, ideally one not familiar with CRediT, back-translates the translation into English.
* Feel free to use Google Translate to assist, just don't rely on it, for example don't use it for both the forward and back-translation.
* Discrepancies between the original English and the back-translated English can tip one off to parts of the translation that deserve attention, where one should consider alternative phrasings. So, the two speakers confer and resolve any discrepancies.
* To make your translation machine-readable, we can help you create a JSON file. See instructions below.
 * To see if a .json file already exists, look [here](https://github.com/contributorshipcollaboration/credit-translation/tree/main/translations) for a file with the [two-letter abbreviation](https://en.wikipedia.org/wiki/List_of_ISO_639_language_codes) for your language.

### If a .json file for your language does NOT already exist:

Download one of the existing JSON files, such as [the German one](https://github.com/contributorshipcollaboration/credit-translation/blob/main/translations/credit_translation_de.json) and change all the German text to your target language. Then send it to us.

### If a .json for your language DOES already exist: 

* To edit the file, click on the pencil icon. Insert the content for your translation. See [the German one](https://github.com/contributorshipcollaboration/credit-translation/blob/main/translations/credit_translation_de.json) for an example.
* So that the Github repository gets updated, create a pull request by clicking on BLAH BLAH
* Don't forget to add information about how you did the translation in the "translationProcedure" string of the .json file, here is an example: "TL, CJ, and HH are all native speakers of German. A first version by TL existed for some time. CJ introduced an additional translation draft. TL and CJ merged the few differences between the two versions favoring broader (in the sense of suitability for as many disciplines and working environments as possible) translations. The final translation was then back-translated by HH, and finally approved by all parties." In this case, two forward translations were created, yielding discrepancies that surfaced parts to attend more to. As described in the above [Creating a translation](#-Creating-a-translation) section, however, another way to do that is to look at discrepancies highlighted by doing a back translation.
* Validate that your edits have not messed up the formatting by entering both the [schema](https://github.com/contributorshipcollaboration/credit-translation/blob/main/credit_translation_schema.json) and your file at [https://www.jsonschemavalidator.net/](https://www.jsonschemavalidator.net/). This checks for most formatting errors.
* Generate a pull request

### Validate your .json file

* Validate that your edits have not messed up the JSON file formatting by entering both the [schema]() and your file at [https://www.jsonschemavalidator.net/](https://www.jsonschemavalidator.net/).

### Send us your .json file, or upload it yourself

* If you're not familiar with Github, send us the .json file
* If you're familiar with Github,
 * Create the json file if it doesn't already exist
 * Create the pull request

## Contributing to other facets of the project (we'd love your help!)

* Code: check the Github issues or email us
* Outreach and implementation 
 * Contact scientific societies and scientific publishers who publish in these languages
* Organize a hackathon ad hoc or at a scientific conference
* Help write [the journal article about this project](https://docs.google.com/document/d/1wbRRpMWXfW6iKMQf8bLDy11Ig5fmiZmyJcRwuo4C4RA/edit?usp=sharing)

# 💝  Acknowledgement of contributions   

## Translation contributors 

Contributors will be recognized in that their names will appear in the attribution for the translation they helped create. For example, see the [human-readable page for German](https://contributorshipcollaboration.github.io/projects/translation/translations/credit_translation_de/).

Unfortunately we don't have funds to remunerate anyone for their work :(

<!-- All project participants who contributed any amount of work, and provided their details, will be acknowledged as project contributors on the project page, report, presentations, and manuscript. We will mainly use a CRediT-like statement format, but we will also keep a more detailed record of individual contributions to specific tasks within the stages of the project. This record will be also made publicly availabe as part of the open project materials (as a publicly available dataset). You can request to have your details removed or obscured at any time.    -->

## 📄 Co-authorship (or, should that be co-*contributorship*? 😀)
Project participants with substantial and high-quality contributions (as defined below) will become co-authors of the manuscript.
They will contribute to any or all of these: translation, checking, website code, coordination, and/or report drafting.   

A substantial contribution can be achieved by performing any X or more of the tasks listed below 
  
IMPORTANT: Authorship is also coditional on reading and approving the final manuscript draft before submission and providing all personal information (e.g., name, affiliation, email) needed for the submission.     

Additional contribution oportunities may be available.

First and last author positions are reserved for the project leads (they could be co-first and co-last positions). Subsequent authorship positions will be determined by the total amount and quality of contributions, as in the project records. For equal contributions the order of mid-authorship will be alphabetic. All authors must read and approve the final manuscript draft before submission. The manuscript will contain a CRediT statement detailing the roles of individual authors and contributors.   

# 📍 Final notes   
Project leads reserve the right to interpret and change the contribution rules at any time, if such need arises. In case of any disputes decisions of project leads will be final.    

# 🔧  Maintainers

[Alex Holcombe](https://github.com/alexholcombe), [Marton Kovacs](https://github.com/marton-balazs-kovacs)  

# 🖍️  License 
This work is licensed under a [Creative Commons Attribution 4.0 International License (CC-BY)](/LICENSE.md). Individual translations have different people to attribute the work to.
