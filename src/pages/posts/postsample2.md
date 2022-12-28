---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: 2022 HelloJan 22
date: 2022-01-3.
name: Nate Moore
value: 128
description: 2022 Hello World Post!
category: ['one','three']
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

This is so cool!

Do variables work {frontmatter.value * 2}?
