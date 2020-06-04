---
title: "Testing Ground"
date: 2020-06-03T14:58:44+08:00
draft: true
toc: true
---


# Testing Hugo 

## Mermaid

{{< mermaid/source >}}
graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid/source >}}


## Observable Notebook

Embeding with short codes

{{< observablenotebook "https://api.observablehq.com/@tmcw/tables.js" >}}

## Specific observable charts

Require modification on html

{{< observablesoneoff >}}

