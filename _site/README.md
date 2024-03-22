# hiveopenmedia

bundle exec jekyll serve
http://127.0.0.1:4000/

## Make a new Page
To create a new page, create a new markdown file in the root directory. The file should have the following front matter:
```
---
layout: default
title: Page Title
permalink: /page-url/
---
```
The `layout` should be `default` for most pages. The `title` is the title of the page that will be displayed in the browser tab. The `permalink` is the URL of the page. The URL should be the same as the file name, but without the `.md` extension. For example, if the file is `about.md`, the `permalink` should be `/about/`.
