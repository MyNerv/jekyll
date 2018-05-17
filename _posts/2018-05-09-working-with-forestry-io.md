---
title: Working with forestry.io and netlify
date: 2018-05-09 11:21:46 +0000
layout: post
categories:
- forestry.io
- jekyll
- netlify
image: "/uploads/2018/05/17/Forestry editor media or url.jpg"
feature-image: ''
---
Jekyll is an awesome static site generator framework with **one** hurdle...It's not a CMS!

But here's the best bit - it can fake it! And fake it well!

> It's not a CMS...but it can fake it!

First, before we go into any of the details of how to use Jekyll as a CMS, let's acknowledge an equally awesome hosting environment provided by Netlify.

## Netlify - not just a static site hosting platform

Netlify offers a hosting platform for static sites that's incredibly simple to get started with, yet has an abundance of features to provide its clients with a broad range of opportunities to built amazing things!

### Netlify & Forms

As a simple example, it's easy to include custom forms on your site, using Netlify's [forms](https://www.netlify.com/docs/form-handling). Including a form is achieved with the inclusion of the `netlify` form attribute:

    <form name="contact" method="POST" netlify>
    ...
    </form>

_How awesome is that?!_

But this is just the tip of the iceberg for form handling. There are options to override the default success message with a redirect to `/pages/custom-success-page.html`, custom error handling, javascript, and so on. And there's an allocation of free form submissions to make it even more sexy!

If you're interesting in using forms in your flow, be sure to check out how [Netlify integrates with Zapier](https://www.netlify.com/docs/form-handling/#receiving-submissions), for a vast array of awesome interaction with third-party applications :).

### Netlify & Webhooks

Netlify supports both incoming and outgoing webhooks. Incoming are great for updating the site and outgoing are great for sending events to services, such as updating git commit status, or sending Slack message. Be sure to check out [Netlify's webhooks documentation](https://www.netlify.com/docs/webhooks/).

Forms and Webhooks are only two of the amazing features of Netlify, be sure to [check their documentation](https://www.netlify.com/docs/) for all the other wonderful stuff.

# Forestry.io

Forestry turns your static site into an editor-friendly CMS, that bridges the gap between developers and editors. It's best described in [their documentation](https://forestry.io/docs/): _"To put it simply, Forestry is an editor-friendly interface over Git. This means that developers and editors can now use the same workflow and tool set."_

I love it! It solves the problem that has held me back from using Jekyll and Hugo over Wordpress. But, with Forestry.io, I can now see many opportunities where the lightweight and speed of static sites are a no-brainer!

### The Editor

It's simply, clean and beautiful!

![The Beautiful Forestry.io Editor](/uploads/2018/05/17/Forestry.io editor-min-1.jpg "The Beautiful Forestry.io Editor")

Now slap me in the face if you think I'm wrong, but this is an elegant interface for editing posts and pages. And adding media is just as nice:

<img src="/uploads/2018/05/17/Forestry%20editor%20media%20or%20url.jpg" width="250px" alt="Adding media in Forestry.io" style="margin: auto;"/>

However, I have noticed some caveats, too. The most noticeable is the lack of text aligning, which I have not found a way to do with switching to 'Raw Editor' mode, adding a css class, and applying the styling via css styling.