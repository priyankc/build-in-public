---
layout: post
title: "A Clearer Hypothesis: It’s All About Managing Complexity"
date: 2025-03-09
categories: projects
---

We started with the vision of solving software architecture challenges for individuals and organizations. We launched two prototypes: design docs as an early-stage lever and code reviews as a final-stage check.

Users found them useful, giving us confidence that we were exploring the right problem space. When we reviewed all the feedback, we realized that our tools and the challenges users faced were all connected by one thing: managing complexity. We also think that redefining the problem space as improving or understanding complexity is a much better way to articulate our approach. Improving architecture lacks clear measures, while complexity can be tracked and analyzed.

Software complexity has real consequences. It slows down product development and affects developer happiness. Yet, there is no objective way to measure it. LLMs excel at compressing knowledge, making them a powerful tool for this challenge.

We built a quick prototype to track repository complexity over time. It considers factors like module responsibilities and dependencies. The absolute complexity number matters less than the trend. Our goal is to plot complexity at any granularity, track how it changes, and offer solutions.

The prototype will be ready in a few days. I will share an update soon.


<style>
    .site-footer {
        display: none;
    }

    .post-title {
        font-size: 36px;
    }
</style>