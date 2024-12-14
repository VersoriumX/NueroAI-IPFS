---
title: "VX"
eleventyNavigation:
  order: 60
---

Pages in Tricky Choices
-----------------------

{% import "Ethereum.njk" as listing %}
{{ listing.childrenTableWithSynopsys(collections.all, page.url) }}
