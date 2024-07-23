---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
#  - block: hero
#    content:
#      title: The Reproducibility Working Group Bibliography 
#      text: ""
  - block: markdown
    content:
      title: "Welcome ! :wave:"
      subtitle: ''
      text: "This website gathers (useful) resources for the study of reproducibility in neuroimaging. This website is maintained by the reproducibility working group (led by [Camille Maumet](http://camillemaumet.com/)) of the [Empenn research team](https://team.inria.fr/empenn/)"
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest Added Articles
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'
---
