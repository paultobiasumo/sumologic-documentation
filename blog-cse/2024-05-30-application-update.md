---
title: May 30, 2024 - Application Update
keywords:
  - cloud siem
  - signal records
  - network sensor
tags: [application update]
image: https://help.sumologic.com/img/sumo-square.png
hide_table_of_contents: true
authors:
  - url: https://help.sumologic.com/release-notes-cse/rss.xml
    image_url: /img/release-notes/rss-orange.png
---

import useBaseUrl from '@docusaurus/useBaseUrl';

#### Record Message IDs in Signals

We've added the "aggregatedMessageIds" field to all Signals. The values of this field will list the Message IDs of each record that contributed to the Signal.

#### Updated Network Sensor

This update to the network sensor mitigates a known vulnerability in the openSSH library.

#### Minor Changes and Enhancements

* Filter added to rules list to filter by rule level signal supression.
* Updated Rules Details Summary to include rule level signal supression.

#### Bug Fixes

* Corrected "Create Incident" button behavior for CSOAR and Automation Service customers.