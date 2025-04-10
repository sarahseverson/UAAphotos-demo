---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---


{% include feature/nav-menu.html sections="About the Collection;About the About Page" %}

{% include feature/image.html objectid="UAA-1969-132-001;UAA-1969-012-064;UAA-1969-018-039" %}

<iframe title="In Touch with U: The Archives" src="https://ualberta.aviaryplatform.com/embed/media/131657?embed=true&media_player=true" allow="fullscreen" frameborder="0"></iframe>
## Data download 

    {% include index/data-download.html %}

    {% include feature/modal.html button="This is a modal using a 'primary' colored button to invite clicking" title="when clicked:" text="A Modal will pop out a box with some more information" color="primary" %}

## Technical Credits

This site is generated using [CollectionBuilder-GH](https://collectionbuilding.github.io/gh/), a project to create a free and simple digital collection using [GitHub Pages](https://pages.github.com/) from: 

- a CSV of collection metadata
- a folder of JPG images or PDF documents



For full details of creating your own collection site, visit [CollectionBuilder Documentation](https://collectionbuilder.github.io/cb-docs/)!

<!-- IMPORTANT!!! DELETE this comment and the include below when you are finished editing this page for your collection. The include below introduces about page features. They will show up on your collection's about page until you delete it.  -->
{% include cb/about_the_about.md %} 
