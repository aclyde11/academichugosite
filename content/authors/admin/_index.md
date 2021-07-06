---
role: Ph.D. Student, University of Chicago
avatar_filename: img_0938-1-.jpeg
bio: I am interested in X
interests:
  - "Research: Machine Learning for"
  - on
  - and with High Performance Computing*; particuarlly for molecular design and
    simulation.
social:
  - icon: envelope
    icon_pack: fas
    link: /#contact
  - icon: twitter
    icon_pack: fab
    link: https://twitter.com/AustinClyde13
  - icon: graduation-cap
    icon_pack: fas
    link: https://scholar.google.com/citations?user=uvm1jY0AAAAJ&hl=en
  - icon: github
    icon_pack: fab
    link: https://github.com/aclyde11
  - icon: linkedin
    icon_pack: fab
    link: https://www.linkedin.com/in/aclyde/
organizations:
  - name: University of Chicago
    url: https://www.uchicago.edu/
  - name: Argonne National Laboratory
    url: https://www.anl.gov
education:
  courses:
    - course: M.S. in Computer Science
      institution: University of Chicago
      year: 2019
    - course: B.A. in Mathematics
      institution: University of Chicago
      year: 2019
    - course: Ph.D. in Computer Science (in progress)
      institution: University of Chicago
superuser: true
highlight_name: false
title: Austin Clyde
email: ""
---
My primary research interests is currently virutal screening with deep learning.

Medicinal chemists and biologists use virtual screening to scan large chemical databases to find molecules of interest to perform expensive downstream analysis. The standard practice uses classical techniques such as structural docking or traditional machine learning to screen libraries on the order of 100k. The recent introduction of deep learning means we can score massive libraries (order tens of billions). And if that isn't enough, there have been recent successes in de-novo molecule generations. In my testing, these generators can output valid molecules at a rate of 25,000 unique to all known databases per second per GPU. In this regime, downstream analysis such as MD on even 0.001% would be intractable.

**My work focuses on solving this problem in two ways:**

* Creating workflows and analysis that can intelligently sample these enormous libraries always to provide downstream analysis the best possible candidates 
* Rethinking the way lead discovery is performed, so we don't have to think of these steps as all unique. If we reframe the problem with the specific goal in mind, it may be the case the workflow arises different (postmodernism can teach you a bit about this concept) 

In many ways, I am skeptical of typical supervised deep learning. The workflow of collecting data, generalizing over it, and predicting off it has its uses--but in the regime discussed, it seems aimless. And yes, I am very inspired by 20th-century French philosophy.