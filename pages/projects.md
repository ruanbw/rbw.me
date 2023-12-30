---
title: Projects - Rbw
display: Projects
description: List of projects that I am proud of
plum: true
wrapperClass: 'text-center'
projects:
  Current Focus:
    - name: 'Nuxt Playground'
      link: 'https://github.com/nuxt/learn.nuxt.com'
      desc: 'Interactive Playground for learning Nuxt'
      icon: 'i-logos-nuxt-icon saturate-0'
    - name: 'Nuxt DevTools'
      link: 'https://github.com/nuxt/devtools'
      desc: 'Unleash Nuxt Developer Experience'
      icon: 'i-logos-nuxt-icon saturate-0'

  Toys:
    - name: '1990 Script'
      link: 'https://github.com/antfu/1990-script'
      desc: 'Make your GitHub history back to 1990'
      icon: 'i-carbon-time'
---

<!-- @layout-full-width -->

<ListProjects :projects="frontmatter.projects" />
