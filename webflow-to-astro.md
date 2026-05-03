---
title: "Why I switched from Webflow to Astro"
description: "The performance gains, developer experience, and simplicity of a modern static site generator changed how I build."
pubDate: 2026-04-28
image: "/images/astro-post.jpg"
tags: ["astro", "web"]
---

# Why I switched from Webflow to Astro

Webflow was great. It let me design visually without touching code. But after a few years, I hit limitations that made me reconsider.

## The Problem

Every page I built felt heavy. My 5-post blog was loading like it had 50 pages of content. The generated code was bloated. Deployments took forever. And the pricing kept creeping up.

I wanted to ship faster, control my code, and keep things simple.

## Discovering Astro

Then I discovered Astro. It's a framework that ships zero JavaScript by default—only HTML and CSS. This was a game-changer.

### What changed:

- **Performance**: Pages load in milliseconds instead of seconds
- **Cost**: Netlify hosting is free. Webflow costs $29/month minimum
- **Control**: My code is mine. No lock-in
- **Flexibility**: I can customize anything without fighting the platform

## The CMS Question

Astro doesn't come with a built-in CMS like Webflow. But Decap CMS solved that. It's free, open-source, and gives me a beautiful editing interface at `/admin`.

Now I get the best of both worlds:
- A visual editor for writing posts
- Full control of the design and code
- Zero vendor lock-in

## Migration

Migrating from Webflow took about 2 hours. I exported my posts, formatted them as Markdown, and added them to my Astro project.

The hardest part was unlearning Webflow's visual mindset. But once I got into the rhythm of writing Markdown, it was faster and more natural than the Webflow editor.

## Conclusion

Astro + Decap CMS isn't for everyone. If you love visual builders, Webflow is still the best. But if you want to ship fast, own your content, and keep things simple, Astro is worth exploring.

I'm never going back.
