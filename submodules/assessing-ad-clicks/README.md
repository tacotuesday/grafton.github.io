# Assessing Online Ad Clicks
Case study to assess online ad clicks for significance.

## The problem
We currently run an online advertisement with blue text. The stakeholder believes that blue may not be the most effective color for their ad. To test this, the stakeholder purchased 3000 ads every weekday for a month. Each ad contained a randomly-assigned text color out of a pool of 30 colors. (The text colors were evenly distributed, so 100 viewers would see 100 ads each day.) The ask: which colors have a significantly different click-through rate than blue? 

## Minimum viable answer
The minimum viable answer is that blue does not have the highest click-through rate. The colors with higher click-through rates are Ultramarine, Sapphire, Aquamarine, and Teal. Practically and statistically, ultramarine has the highest click-through rate: not only against blue, but also against aquamarine, its closest competitor. Thus **the stakeholder should consider using ultramarine as the primary color for their ads if they want to maximize click-through rates and are constrained to only one color.** 

It is worth noting that the choice of analysis may have affected the statistical significance. For example, using a non-parametric test like permutation or Kruskal-Wallis against the entire dataset may have yielded different results with respect to statistical significance. It is important to remember that ultramarine was also the color with the highest practical click-through rate by a significant margin in the dataset, which is most likely reason enough to change to that color considering the low switching costs in this specific scenario. 
