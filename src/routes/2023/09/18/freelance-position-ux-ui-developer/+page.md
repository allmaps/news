---
title: 'Freelance position: UX/UI Developer for Allmaps'
description: 'Freelance position: Creative UX/UI developer to design and implement new features in the Allmaps platform'
image: 'opengraph/2023-09-18-freelance-position-ux-ui-developer.jpg'
---

<!-- ### Developer sought for NEH-funded project on georeferencing and digital humanities -->

<script lang="ts">
  import { base } from '$app/paths'

	import { MapMonster } from '@allmaps/ui'
  import { yellow } from '@allmaps/tailwind'

  const speechBalloonBackgroundColor = yellow
  const speechBalloonTextColor = 'black'
</script>

The [Leventhal Map & Education Center](https://www.leventhalmap.org/) (LMEC) at the Boston Public Library and the [Allmaps project](https://allmaps.org) seek to contract for a creative UX/UI developer with interests in the digital humanities for the role of **_Allmaps UX/UI Developer_**. Please submit applications by **Wednesday, October 18 **for full consideration. Applications will continue to be reviewed until the position is filled.

<a href="https://allmaps.org/"><img alt="Allmaps Viewer" src="{base}/images/allmaps-viewer.jpg" /></a>

## About the project

**Allmaps** is an open-source, web-based platform for creating, curating, and viewing georeferenced maps. We’re looking for an experienced and creative UX/UI developer **who can both design and implement user interfaces** to help us refine existing features in the Allmaps platform and incorporate design feedback from user testing. You’ll design and create user interfaces that are simple and fun to use, both on desktop computers and smartphones, and you’ll work on a design system and reusable components that will be used throughout the Allmaps project. As the Allmaps UX/UI Developer, you will work closely with [Bert Spaan](https://twitter.com/bertspaan) (Allmaps Lead Developer).

This contract work will be undertaken as part of a [Digital Humanities Advancement Grant](https://www.neh.gov/news/neh-announces-413-million-280-humanities-projects-nationwide), _Making Open-Source Georeferencing Technology Collections-Ready with the Allmaps Platform_, awarded to the LMEC by the National Endowment for the Humanities. The project aims to polish existing functionality, as well as create new features, throughout the Allmaps platform with the goal of making it easier for map-holding institutions across the world to incorporate Allmaps into their digital collections.

## Contract details

This position is to be structured as a contractual agreement between the developer and the Leventhal Map & Education Center. It will be governed by the laws of the State of Massachusetts in the U.S. and **denominated in $USD**.

Candidates are **not required to live in the United States or to have U.S. citizenship**. The project runs for 3 years, though we expect the UX/UI Developer to complete the majority of their work during the 2024 calendar year. The successful candidate can expect to work approximately 300 hours during the project duration at a rate of about $100/hour.

## Technology & principles

Allmaps is built using the following technology:

- **IIIF APIs** - The [International Image Interoperability Framework](https://iiif.io/) (IIIF) is a set of open standards that are used by cultural institutions to publish high-resolution images and their metadata. Allmaps uses the IIIF [Image API](https://iiif.io/api/image/3.0/) and [Presentation API](https://iiif.io/api/presentation/3.0/) to access digitized maps.
- **TypeScript** - All Allmaps apps and modules are written in [TypeScript](https://www.typescriptlang.org/).
- **SvelteKit & Tailwind CSS** - Allmaps uses [SvelteKit](https://kit.svelte.dev/) and [Tailwind CSS](https://tailwindcss.com/) to build its web apps.
- **OpenLayers** - Many parts of Allmaps use [OpenLayers](https://openlayers.org/) to display interactive maps and IIIF images.
- **PostGIS** - We store data about georeferenced maps in a [PostGIS](http://postgis.net/) database and we run a small REST API that is built using [Express](https://expressjs.com/) and [Drizzle ORM](https://orm.drizzle.team/).
- **WebGL** - Allmaps uses WebGL to transform georeferenced IIIF images of maps in such a way that they align with the geographic area that is depicted on these maps. See [Allmaps Viewer](https://viewer.allmaps.org/?url=https%3A%2F%2Fannotations.allmaps.org%2F%3Furl%3Dhttps%3A%2F%2Frotterdamspubliek.nl%2Fiiif%2FNL-RtSA_4001_1972-755-1%2Finfo.json) for examples.
- **GitHub & Render** - We publish our source code on [GitHub](https://github.com/allmaps/allmaps) and we run our static sites and services on [Render](https://render.com/).

During this project, we are also focusing on the following principles:

- **Open data** - Data about georeferenced maps produced by the various components of Allmaps is published as open data.
- **Accessibility** - Incorporating accessibility features in conformance with the [W3C Accessibility Guidelines](https://www.w3.org/WAI/standards-guidelines/) will be an important aspect of the successful UX/UI Developer’s role.
- **Internationalization** - Currently, we only use English in our user interfaces. In the future, we plan to translate our web apps to different languages.
- **Responsive design** - All Allmaps apps should work on smartphones, on laptops and on desktop computers.
- **Documentation, examples & tutorials** - While the UX/UI Developer is not expected to write documentation, they may be asked to help develop working code snippets and examples (e.g., Kaggle/Jupyter/Observable notebooks).

## Applying

You can apply by filling in [this form](https://airtable.com/appfE1BFZoHj0lgNu/shruyy2LqptK53AB1). We will begin reviewing applications on **Wednesday, October 18**, and will continue doing so on a rolling basis until the position is filled. If you have any questions, don't hesitate to email Ian Spangler ([ispangler@leventhalmap.org](mailto:ispangler@leventhalmap.org)) or Bert Spaan ([bert@allmaps.org](mailto:bert@allmaps.org)).

<div class="p-4 not-prose">
  <MapMonster
    mood="excited"
    color="yellow"
    {speechBalloonBackgroundColor}
    {speechBalloonTextColor}>
    <p class="not-prose">Maps are fun! Come work with us and help us make exploring, using and sharing digitized maps easier and more inspiring!</p>
  </MapMonster>
</div>
