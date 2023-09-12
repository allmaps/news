---
title: Allmaps UX/UI Developer
description: First post.
image: images/allmaps-viewer.jpg
---

<!-----

Yay, no errors, warnings, or alerts!

Conversion time: 0.478 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β34
* Tue Sep 05 2023 04:02:41 GMT-0700 (PDT)
* Source doc: Allmaps UX developer draft description
----->

## Short intro

The Leventhal Map & Education Center (LMEC) at the Boston Public Library seeks to contract a creative software engineer with interests in the digital geohumanities and a strong background in front-end web development for the role of **_Allmaps UX/UI Developer_**. The successful candidate should have experience with TypeScript, SvelteKit, and Tailwind CSS, etc….

<img src="images/allmaps-viewer.jpg" />

## Full job description

**Allmaps** is an open-source, web-based platform for creating, curating, and viewing georeferenced maps. This UX/UI Developer will work closely with Bert Spaan (Allmaps Lead Developer) to refine existing features in the Allmaps platform, incorporate design feedback from user testing, and ultimately design and implement new user interfaces within the Allmaps ecosystem.

To begin, this work will include redesigning the UX/UI within **Allmaps Viewer**, an application for viewing georeferenced maps within the Allmaps platform. The Allmaps UX/UI Developer will create new tools with which users can engage georeferenced maps in Allmaps Viewer, as well as improve the current tool suite and existing user interfaces. In the longer term, the successful candidate can expect to work on the implementation of **Allmaps Curator**, an application for users to curate and georeference their own collections of georeferenced maps across institutions, as well as provide an institutional back-end for map-holding institutions to manage workflows like crowdsourcing and version control.

This contract work will be undertaken as part of a Digital Humanities Advancement Grant, _Making Open-Source Georeferencing Technology Collections-Ready with the Allmaps Platform_, awarded to the LMEC by the National Endowment for the Humanities. The project aims to polish existing functionality, as well as create new features, throughout the Allmaps platform with the goal of making it easier for map-holding institutions across the world to incorporate Allmaps into their digital collections.

This contracted position is renewable on a task-by-task basis. The project runs for 3 years, though we expect the UX/UI Developer to complete the majority of their work during the 2024 calendar year. The successful candidate can expect to work about 300 hours during the project duration at a rate of about $100/hour. **The contract will be denominated in $USD**.

## Requirements

We’re looking for an experienced and creative UX/UI developer who can both design and implement user interfaces.

Ideally, located

Allmaps is built using the following technology:

- **IIIF APIs** - The [International Image Interoperability Framework](https://iiif.io/) (IIIF) is a set of open standards that are used by cultural institutions to publish high-resolution images and their metadata. Allmaps uses the IIIF [Image API](https://iiif.io/api/image/3.0/) and [Presentation API](https://iiif.io/api/presentation/3.0/) to access digitized maps.
- **TypeScript** - All Allmaps apps and modules are written in [TypeScript](https://www.typescriptlang.org/).
- **SvelteKit & Tailwind CSS** - All Allmaps apps are built using [SvelteKit](https://kit.svelte.dev/) and [Tailwind CSS](https://tailwindcss.com/).
- **OpenLayers** - Many parts of Allmaps use [OpenLayers](https://openlayers.org/) to display interactive maps and IIIF images.
- **PostGIS** - We store data about georeferenced maps in a [PostGIS](http://postgis.net/) database and we run a small REST API that is built using [Express](https://expressjs.com/) and [Drizzle ORM](https://orm.drizzle.team/).
- **WebGL** - Allmaps uses WebGL to transform georeferenced IIIF images of maps in such a way that they align with the geographic area that is depicted on these maps. See [Allmaps Viewer](https://viewer.allmaps.org/?url=https%3A%2F%2Fannotations.allmaps.org%2F%3Furl%3Dhttps%3A%2F%2Frotterdamspubliek.nl%2Fiiif%2FNL-RtSA_4001_1972-755-1%2Finfo.json) for examples.
- **GitHub & Render** - We publish our source code on [GitHub](https://github.com/allmaps/allmaps), and we run our static sites and services on [Render](https://render.com/).

As Allmaps UX/UI Developer you’ll probably work with SvelteKit and Tailwind CSS the most, but we’re a small team so it would be great if you

We also want to focus on these things:

- **Accessibility** - Currently, Allmaps supports key bindings, but incorporating additional accessibility features in conformance with the [W3 Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/) will be an important aspect of the successful UX/UI Developer’s role.
- **Internationalization** - Currently, we only use English in our user interfaces. In the future, we would like to enable on-the-fly translation and other multilingual services.
- **Responsive design** - All Allmaps apps should work on small smartphone screens, on tablets, on laptops and on desktop computers.
- **Documentation, examples & tutorials** - While the UX/UI Developer is not expected to write documentation, they may be asked to help develop working code snippets and examples (e.g., Kaggle/Jupyter/Observable notebooks).
