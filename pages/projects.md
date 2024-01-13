---
title: Projects - Rbw
display: Projects
description: List of projects that I am proud of
plum: true
wrapperClass: 'text-center'
projects:
  权限系统:
    - name: 'NightBoot'
      link: 'https://github.com/1813967922/nightboot'
      desc: '基于SpringBoot、SpringSecurity、MyBatisPlus的单体后台权限管理系统。'
      icon: 'i-logos-nuxt-icon saturate-0'
    - name: 'NightBoot-UI'
      link: 'https://github.com/1813967922/nightboot-ui'
      desc: '基于Vben Admin的后台权限管理系统。'
      icon: 'i-logos-nuxt-icon saturate-0'
    - name: 'NestJs - Backend'
      link: 'https://github.com/1813967922/nestjs-backend'
      desc: '基于 Nest 实现 RBAC0 的一个权限管理系统,集成 TypeOrm、JWT、Redis、Winston 日志系统、多环境配置'
      icon: 'i-logos-nuxt-icon saturate-0'

  命令行工具:
    - name: 'nodem-clean'
      link: 'https://github.com/1813967922/nodem-clean'
      desc: '这是一个删除指定目录下的所有 node_modules 的命令行工具'
      icon: 'i-logos-nuxt-icon saturate-0'
---

<!-- @layout-full-width -->

<ListProjects :projects="frontmatter.projects" />
