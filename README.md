Using Github Pages and Github Actions, this repository creates  [webpages](https://contributorshipcollaboration.github.io/) for the contributorship-collaboration organization, using [hugo](https://gohugo.io/) with a modification of the [hugo-fresh](https://github.com/StefMa/hugo-fresh) theme.

# Contributorship Collaboration

The projects of the __Contributorship Collaboration__ try to make curating and reporting scholarly contributions easier and more transparent. We also pursue other ways to improve the recognition of contributions to scholarship.

[CRediT](http://credit.niso.org/) (Contributor Roles Taxonomy) is one way to document contributions and is used by hundreds of journals. CRediT is a
taxonomy of 14 categories of contributions to scientific scholarly output. Each researcher can indicate which category they contributed to
in a scholarly project.

First we developed the *tenzing* [Shiny app](tenzing.club) and associated R package, were developed to facilitate researcher reporting of contributorship information in manuscripts and journal articles. tenzing is named after the Nepali-Indian Sherpa Tenzing Norgay, who was one of the two individuals who reached the summit of Mount Everest for the first time. Despite his essential contribution, the achievement may not be credited to him as much as he deserves relative to his partner, the New Zealand mountaineer Edmund Hillary.

## Development mode

To load the webpage locally for development purposes:

* [Install the extended version of hugo](https://gohugo.io/installation/) on your machine
* [Install go > 1.13](https://go.dev/dl/)
* Clone this repository to your machine
* cd into the cloned repository
* Run the site locally by typing `hugo server` in the terminal
* Open the site through the `http://localhost:1313` address in a browser

## Updating the Hugo site, including the translations 

To trigger updating of the Hugo [HTML site](https://contributorshipcollaboration.github.io/) that this repository creates:
  * make any change  to this repo (which is distinct from the translations repo). That will trigger Hugo to re-render the HTML, including using the  translations of CRediT encoded in [the JSON files](https://github.com/contributorshipcollaboration/credit-translation/tree/main/translations) to create the HTML translation webpages.
