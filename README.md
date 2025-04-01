# Simple Photography Portfolio theme with jekyll
- minimal web page for photography porfolio

## Setup
### _config.yml
```
title: "Photography Portfolio"
profile:
  name: "JeongMin Lee"
  email: "jeongmin.lihi@gmail.com"
  description: "A passionate photographer"
  location: "Seoul, South Korea"

collections:
  projects:
    output: true
    permalink: "/projects/:title/"

```
You can change title of page, and your profile

### _projects directory
You can make $projectName.md file
```
---
layout: project
title: "template"
period: "2024-2025"
folder: "project_template"
statement: |
    test
    test
    test
---
```
for your projects. When you set $folder, you need to create directory images>projects>$folder and put your image in it.

## Run
```
bundle exec jekyll serve
```