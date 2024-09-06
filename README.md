# Contributorship Collaboration

The goal of the __Contributorship Collaboration__ project to make curating and reporting scholarly contributions easier and more transparent.

We use [CRediT](http://credit.niso.org/) (Contributor Roles Taxonomy) to document contributions. CRediT is a
taxonomy of 14 categories of contributions to scientific scholarly output. Each researcher can indicate which category they contributed to
in a scholarly project.

Our first tool, the tenzing Shiny app and associated R package, were developed to facilitate researcher reporting of contributorship information in manuscripts and journal articles. tenzing is named after the Nepali-Indian Sherpa Tenzing Norgay, who was one of the two individuals who reached the summit of Mount Everest for the first time. Despite his essential contribution, the achievement may not be credited to him as much as he deserves relative to his partner, the New Zealand mountaineer Edmund Hillary.

This repository contains the landing page for the contributorship-collaboration Github organization. The page was built with [hugo](https://gohugo.io/) and it uses a modified version of the [hugo-fresh](https://github.com/StefMa/hugo-fresh) theme.

## Development mode

To load the webpage locally for development purposes:

* [Install the extended version of hugo](https://gohugo.io/installation/) on your machine
* [Install go > 1.13](https://go.dev/dl/)
* Clone this repository to your machine
* cd into the cloned repository
* Run the site locally by typing `hugo server` in the terminal
* Open the site through the `http://localhost:1313` address in a browser

## Translations webpage

To trigger the Github action that renders the JSONs into HTML,
