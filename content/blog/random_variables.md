+++
title = "Random Variables"
date = 2023-03-01
+++

<style>
    body {
        font-family: 'Palatino';
    }

</style>

One question I asked myself at lot at the beginning of graduate school was, "At what level do I need to know something?" My current "rough" answer to this question is that you should try to know something at the level at which you can begin to compose it with other ideas. Composing ideas is how we build things. So if you know it at this level, you can at least begin to build with your new knowledge. 

One of the challenges with learning statics in undergrad is that it usually isn't taught at the depth at which you can begain to compose things. The result is that many people carry around a bunch of seperate and distinct ideas in their head rather than a coehsive framework. 

The starting point for learning statistics is to understand why you should care about the definition of a random variable. I admit, during my first years of graduate school I could recite the definition of a random variable, but I couldn't tell you why that definition was important. We didn't use in explicitly in any of the problem sets.

Let me give you a "rough" definition and then I'll try to illustrate why it's important to care about this defintion. Definition - a random variable is a function.[^1] It's neither random nor a variable. It's simply a function. The esseence of a random variable is that it maps a probability measure defined over one space to a probability measure defined over a space that we carry about. That's what a random variable does.


$$\Big( \Omega, \mathcal{F}, \mathbb{P}\Big) \overset{X}{\longmapsto} \Big( \mathcal{R}, \mathcal{B}(\mathcal{R}), \mathbb{P} \circ X ^{-1}\Big)$$


[^1] To be more precise, a random variable is a measurable function.

