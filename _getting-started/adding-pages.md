---
layout: page
title: Adding Pages
---

Pages are organized into one or more sections. Each of there sections has a corresponding folder in the root folder (e.g. `_getting-started`).

To add a new page to a section simply create a new `.md` file in the corresponding section folder.

Every page should include basic YAML front-matter that defines the page title and the template that should be used to display the content. An example of this YAML front-matter can be found below:

```yaml
---
layout: page
title: Adding Pages
---
```


## Creating Sections

To create a new section you should first create a new folder for the section pages in the root of the docs directory. The naming conventions for section folders is an `_` followed by the section name (e.g. `_getting-started`).

Next you need to add the new collection to the `_config.yml` file.

Update the `collections` array with your new collection. For example:

```yaml
collections:
  getting-started:
    title: Getting Started
    output: true
    permalink: /getting-started/:path/

```
