---
title: Changed the model from LGCP to GAM
subtitle: A special thing
layout: default
modal-id: 1
date: '2016-11-10'
img: dreams.png
thumbnail: dreams-thumbnail.png
alt: image-alt
project-date: April 2014
client: Start Bootstrap
category: Web Development
description: Lorem ipsum dolor sit amet, usu cu alterum nominavi lobortis. At duo
  novum diceret. Tantas apeirian vix et, usu sanctus postulant inciderint ut, populo
  diceret necessitatibus in vim. Cu eum dicam feugiat noluisse.
---

While log-Gaussian Cox process models are one way to model individual case data, implementing them in R-INLA can be somewhat fiddly, restricting the ability to automate.  Parallel work looking at the use of generalized additive models (GAMs) for this problem showed very good results. Furthermore, GAMs are straightforward to implement and run quickly. We therefore made the decision to swap LGCPs for GAMs. As the DiSARM pipeline has been built in a modular way, swapping out LGCPs for alternative modelling approaches was straightforward.