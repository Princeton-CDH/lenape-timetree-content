---
title: Site Credits
---

## Timetree interactive visualization

The Lunaapahkiing Princeton Timetree (LPT)  is an interactive visualization and timeline alternative that allows users to explore time-based events with an emphasis on connections rather than strict historical sequence.

The visualization was created by **[Rebecca Sutton Koeser](https://cdh.princeton.edu/people/rebecca-sutton-koeser/)** (LPT Visualization and Technical Lead; Lead Research Software Engineer, CDH) and **[Gissoo Doroudian](https://cdh.princeton.edu/people/gissoo-doroudian/)** (LPT Design Lead; UX Designer, CDH) as part of a CDH Research Partnership grant (2022-23) with **[Jeffrey Himpele](https://anthropology.princeton.edu/people/jeffrey-himpele)** (LPT Content Lead; Director, VizE Lab for Ethnographic Data Visualization and Lecturer, Anthropology, Princeton University). **[Keely Smith](https://history.princeton.edu/people/keely-smith)** (PhD Candidate, Department of History, Princeton University) served as Project Manager and Lunaape and Princeton Communities Liaison.

Because the LPT combines different kinds of creative and scholarly work, we provide citations for the aggregate work and also for each important scholarly component, to make the labor and contributions more visible. Here, we abide by best practices in Digital Humanities research, which aims for a comprehensive model of attribution of credit.

**The LPT visualization combines the project code and the project data.**

The LPT was developed as a collaborative project that incorporates the work of many contributors with a variety of expertise, which makes any single authorship attribution problematic. If your style guide prefers a single bibliography entry for this resource, we recommend:

{{< project_citation noAuthors=true >}}

If your style guide insists on author names, we request that you cite the project with all four names of the core team members:

{{< project_citation >}}

## LPT content (data)

The content for the 100+ leaves included in the timetree has been expanded and augmented from Jiyoun Roh’s initial 30 events by extensive research by additional Princeton students.

Content work was edited and managed by Himpele, who oversaw the team of student researchers:

* [Isabel Lockhart](https://indigenous.princeton.edu/people/isabel-lockhart) (historical research, 2021–2022)
* [Keely Smith](https://history.princeton.edu/people/keely-smith) (historical research, 2021–2023)
* [Moses Abrahamson](https://jrc.princeton.edu/people/abrahamson) (historical research, 2023)
* Julian Ibarra (photos and documents, 2023)
* [Ivan Melchor](https://anthropology.princeton.edu/people/ivan-melchor) (content entry, 2023)

We are grateful for the advice of [Suzanne Conklin Akbari](https://suzanneakbari.com/) (Institute for Advanced Study, Princeton, NJ) and Kristin Jacobs (Naahii Ridge Elementary, Eelünaapéewi Lahkéewiit / Delaware Nation at Moraviantown) for assisting with the use of terminology.

To cite the content, include leaf title and url, like this:

<div class="citation"><p>
Lockhart, Isabel, and Keely Smith. “Assunpink Trail.” ed. Jeff Himpele. <i>Lunaapahkiing Princeton Timetree</i>, version 1.x.x. Center for Digital Humanities at Princeton, 2023. https://lenapetimetree.indigenous.princeton.edu/#assunpink
</p></div>

All factual data included in this project is Public Domain. Site content is licensed under a Creative Commons Attribution 4.0 International License.

All images are used with permission or available in the public domain.

## LPT software (code)

To cite the codebase:

<div class="citation"><p>
Koeser, Rebecca Sutton, Doroudian, Gissoo, & Heuser, Ryan. (2023). lenape-timetree (v1.0.4). Zenodo. https://doi.org/10.5281/zenodo.8040362
</p></div>

The [source code is available on GitHub](https://github.com/Princeton-CDH/lenape-timetree), and is made available under the Apache License 2.0.

The LPT is implemented as a [Hugo static site](https://gohugo.io/) with a custom theme.  The data visualization is implemented with JavaScript and [d3.js](https://d3js.org/) for interactivity, layout, and visuals. Content for each leaf is a custom page type within the Hugo site, and content and data is then compiled into JSON for use in the timetree.

Content is organized into a network by branch and date; leaves are positioned vertically by time period and horizontally by branch using a d3.js force layout with custom forces. Branches are drawn using d3.js curves to connect the leaves along each branch. The alignment is not strictly sequential, and both the layout and the shapes of the leaves are drawn somewhat randomly; the timetree is intended to invite exploration as a generative interface that is never exactly the same.

The timetree was implemented with a responsive design and an alternate layout for mobile devices to make it equally engaging on smaller screens. The timetree is keyboard navigable in order to offer vision impaired users a comparable experience for exploring leaves by branch and tag.