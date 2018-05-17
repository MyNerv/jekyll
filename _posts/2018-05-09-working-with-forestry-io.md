---
title: Working with forestry.io and netlify
date: 2018-05-09 11:21:46 +0000
layout: post
categories:
- forestry.io
- jekyll
- netlify
---
Jekyll is an awesome static site generator framework with **one** hurdle...It's not a CMS!

But here's the best bit - it can fake it! And fake it well!

> It's not a CMS...but it can fake it!

First, before we go into any of the details of how to use Jekyll as a CMS, let's acknowledge an equally awesome hosting environment provided by Netlify.

## Netlify - not just a static site hosting platform

Netlify offers a hosting platform for static sites that's incredibly simple to get started with, yet has an abundance of features to provide its clients with a broad range of opportunities to built amazing things!

As a simple example, it's easy to include custom forms on your site, using Netlify's [forms](https://www.netlify.com/docs/form-handling). Including a form is achieved with the inclusion of the `netlify` form attribute:

    <form name="contact" method="POST" netlify>
    ...
    </form>

_How awesome is that?!_

But this is just the tip of the iceberg for form handling. There are options to override the default success message with a redirect to `/pages/custom-success-page.html`, custom error handling, javascript, and so on. And there's an allocation of free form submissions to make it even more sexy!