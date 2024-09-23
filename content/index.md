---
title: Welcome to Quartz with FrontMatter Obsidian Property Shown!
Property_test: Hey this is showing a property!
Add_them_as_you_like: You can have as many as you wants!
Live_demo: This a live demo of this Properties component self-hosted on GitHub!
---

This is a blank Quartz with FrontMatter Obsidian Property Shown installation.
See the [documentation](https://quartz.jzhao.xyz) for how to get started with Quartz. 

The relevant file to get to install the Properties Component are:
- quartz/components/Properties.tsx;
- quartz/components/styles/properties.scss
- quartz/components/index.ts
- quartz.layout.ts

They can be found either in those path in the [v4](https://github.com/michelepapucci/quartz-visible-obsidian-property) branch or more explicitly in the [properties-component-files](https://github.com/michelepapucci/quartz-visible-obsidian-property/tree/properties-component-files) branch.

The first two files you need to copy them from this repository and paste them into the same path in your quartz installation;

In the third file after the list of imports, you have to add a *import Properties from "./Properties"* and at the end of the export list *Properties,*;

In the fourth file, you need to add *Component.Properties()* after *Component.ContentMeta(),*;


