---
layout: post
title:  "Bouquet diagram"
author: bouquet_diagram
categories: ['Survey']
image: assets/images/Hanataba_diagram_en.jpg
website: https://www.bouquet-diagram.app
lang: 'en'
---
We offer a service to beautifully visualize your survey data.

From the data you provide, we create various visualizations, including the "Bouquet diagram."

### Brief Description
This is a chart that shows pie charts at the end of branches based on attributes, like "the percentage of men in their 30s who celebrate Christmas" or "the percentage of women among people in their 40s who don't celebrate Christmas." It allows you to overview the characteristics of results under various conditions.

### Detailed Description
This is a diagram that represents multi-dimensional contingency tables with dendrograms and pie charts. Unlike normal dendrograms that inherently have a hierarchical structure, here, since the attributes themselves don't have a hierarchy, by default, we draw all combinations of branches. The different branches are not independent; combinations with the same conditions will have the same distribution (reflecting the symmetry of the hypergeometric distribution). Behind the scenes, we calculate p-values using exact tests or chi-squared tests, allowing us to "prune" the branches of the dendrogram (note that this involves issues with multiple testing, so care must be taken when assessing statistical significance). If you have specific filtering conditions you want to focus on, we can "prune" accordingly.

