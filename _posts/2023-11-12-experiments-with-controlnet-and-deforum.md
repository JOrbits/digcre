---
layout: post
title: "Experiments with ControlNet and Deforum"
author: "Jordan Suter"
categories: documentation
tags: [documentation,sample]
image: control-net.jpg
---

Using an input video of a woman dancing, I tried some first approaches with ControlNet and Deforum.

I used a pose estimation model with ControlNet. Although the output video copied the "dance moves" from the input video. There are some obvious visual problems, that might have been fixable if I would've used a fixed seed instead of an iterating one.

It's obvious that the entire background and the dancing woman itself change in appearance drastically. Getting smooth videos is a big challenge with current Stable Diffusion models.

<blockquote class="imgur-embed-pub" lang="en" data-id="a/G7uNWkL" data-context="false" ><a href="//imgur.com/a/G7uNWkL"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>