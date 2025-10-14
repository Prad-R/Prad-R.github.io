---
layout: page
title: Project
subtitle: "DiceForge: A PRNG in C++"
---

DiceForge is a C++ library for **Pseudo Random Number Generation (PRNG)**. It provides functionality similar to that of the python standard library _random_. It implements several non-standard algorithms to improve the efficiency over standard PRNGs.

<img src="/assets/img/DiceForge.png" 
     alt="DiceForge vs Standard PRNGs" 
     style="display: block; margin: 0 auto; width: 100%; max-width: 500px;">

The comparison between our best PRNG, the XORShift 64 and other standard PRNGs is given in the graph above. We can see that our PRNG is about **9x faster than C++'s own PRNG**. The <a href="https://github.com/Mathematics-Club-IIT-Madras/DiceForge">GitHub Repository</a> containing the library is linked.