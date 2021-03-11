---
lesson-example: "https://carpentries.github.io/lesson-example/"
layout: default
title: "Learning how to build websites with Jekyll"
---

## Description
{{ site.description }}  

{{ assign lead = site.team_members | where:"role", "project lead" | first }}
The project is lead by {{ lead.name }}.
[See our full team](/about).

## About
More details about the project can be found in the [About](about.md) page.

Have any questions about what we do? [We'd love to hear from you!](mailto:{{ site.email }})

## Time
{{ site.time }}

See some [examples of our work]({{ page.lesson-example }})

