---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: 2022 Hello World Post!
date: 2022-01-01
name: Nate Moore
value: 128
isTech: true
category: ['one','two','three']
description: 2022 Hello World Post!
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

This is so cool!

Do variables work {frontmatter.value * 2}?
