---
layout: post
title: Changed the model from LGCP to GAM
post_date: '2016-11-10'
image: DiSARM_Pipeline
published: true
---

While log-Gaussian Cox process models are one way to model individual case data, implementing them in R-INLA can be somewhat fiddly, restricting the ability to automate.  Parallel work looking at the use of generalized additive models (GAMs) for this problem showed very good results. Furthermore, GAMs are straightforward to implement and run quickly. We therefore made the decision to swap LGCPs for GAMs. As the DiSARM pipeline has been built in a modular way, swapping out LGCPs for alternative modelling approaches was straightforward.
