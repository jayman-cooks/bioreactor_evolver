---
title: "Bioreactor selective evolver"
author: "Jack (U0792RSM26A)"
description: "A bioreactor that evolves bacteria to produce strains that eat co2"
created_at: "6/20/2025"
---

# June 20th - 2.5h
Did some research on my idea. Here's my idea:
- 4-8 jars with a solution of my bacteria with lighting on the sides
- CO2 sensors detect when each jar has lowered the co2ppm by a certain amount
- The jar that ate the most co2 the fastest replaces the other jars
- Repeat for weeks to get meaningful evolutions
There's still a lot of design considerations I need to tackle:
1. How big do my jars need to be (how much bacteria do I need?)
  I want the jars to be as small as possible to minimize the amount of water I use, but they also need to be a certain size for the co2 sensors to acurately register a change. My (and chatgpt's) vibes say around 50mL? This might be a f around and find out kind of thing though.
2. How do I regrow more strains?
  I could either regrow them in the measuring jars, or pump them into a seperate larger jar with growth media. Pumping them into a larger jar with growth media would be much more complicated, but could be faster. Regrowing them in the same measuring jars would eliminate this step. Idrk which would be faster.
3. Do I want to measure co2 removed per biomass or just co2 removed?
  If I just measure co2 removed, the bacteria will probably just develop traits to replicate faster. I'm not really sure which result I want. Measuring biomass would add quite a bit more cost (drying biomass + weighing), but would make for cooler results. 
4. Which bacteria to use
  Synechococcus elongatus PCC 7942 would probably be best, since it is specifically engineered for this. However, it costs a lot (like $300). Other generic cynobacteria are much cheaper (like $20), but probably aren't as efficient and take longer to grow. I could also just get some from a pond and try to screen it for only cynobacteria - but I don't really know how well that would go. The other question is whether I can get access to a UV irradiator. Irradiating the bacteria would weaken the dna and would make it more likely to mutate. This would increase variety by a lot (by maybe 10x) but irradiators are way to expensive, and probably aren't easy to make. 
5. Bubble co2?
   I dont really know if I need to bubble co2 through the water (to have more of it dissolved and increase concentration). Bubble co2 = lower volume required, but + complexity and cost. 
6. Measuring CO2:
  Originally I thought measuring the ppm of co2 would be easiest, but maybe measuring the ph would be better. CO2 sensors (like this one https://www.alibaba.com/product-detail/High-Accuracy-Carbon-Dioxide-Sensors-Ndir_1601125505342.html) have an accuracy of about 50ppm, but ph meters would be better. Ph meters are also cheaper. The main issue with this is that the ph will change as the growth media is eaten by the bacteria. Maybe I could somehow account for this with a control? Maybe this also doesn't matter - since faster growth = less co2.

Tomorrow I will try to run some calculations to figure out the answers to these questions. 
