---
title: belayer
sidebar: false
githublink: https://github.com/tenzing-contrib/belayer
link: https://github.com/tenzing-contrib/belayer
description: JSON Schema for journal article metadata.
---

_belayer_ is a [JSON Schema](https://json-schema.org/) standard that is designed to provide consistency for storing journal article author metadata. By using _belayer_, contributor metadata can be easily shared across applications, thus allowing for greater interoperability between tools used throughout the research pipeline. Moreover, contributors' information can be validated easily against the _belayer_ schema in different programming frameworks by using some of the available and open source [JSON Schema validator tools](https://json-schema.org/implementations).

Currently, we only use the _belayer_ schema behind our web extension pasang. However, we plan to base tenzing.club on _belayer_ in the future. This change will allow for the translation between the [tenzing contributors' spreadsheet template](https://docs.google.com/spreadsheets/d/1Gl0cwqN_nTsdFH9yhSvi9NypBfDCEhViGq4A3MnBrG8/edit#gid=0), _belayer_, and [JATSXML](https://jats.nlm.nih.gov/).

The _belayer_ schema project has its roots in [JAMS](https://github.com/jam-schema/jams) and might be superseded in the future by it. However, this change will not affect previous _belayer_ integrations.
 