---
title: Stellenanzeigen in der Homepage
desc: Die war es leichter Stellenanzeigen in der eingenen Homepage einzubinden. Einfach im Formular eintippen und HTML Schnipsel in Hompage einbauen (lassen)
cat: Feature
date: 2022-02-02
image: https://images.unsplash.com/photo-1642573327554-153c53e48c6b?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw5fHx8ZW58MHx8fHw%3D&auto=format&fit=crop&w=400&q=60
---

# Stellenanzeigen in der Homepage

Das [Eingabetool für jobs](news/2022-01-18) ermöglicht es auch eingene Stellenanzeigen in die eigene Homepage zu integrieren. Besonders einfach geht es per [Yawik Widget](https://jobwizard.yawik.org/docs/widget/). Wenn sie folgende Zeilen ihn das HTML Ihrer Homepage einbauen lassen, werden die neuesten Jobs erscheinen.

```html
<link rel="stylesheet" href="https://yawik.gitlab.io/jobboard-widget/yawik-job-list.css"/>
<script src="https://yawik.gitlab.io/jobboard-widget/yawik-job-list.js"></script>
<yawik-job-list remote="https://api.yawik.org/api/jobs"></yawik-job-list>
```
