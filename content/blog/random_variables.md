+++
title = "Random Variables"
date = 2023-03-01
+++

<style>
    body {
        font-family: 'Palatino';
    }

</style>

One question I asked myself at lot at the beginning of graduate school was, "At what level do I need to know something?" My current rough answer to this question is that you should try to know something at the level at which you can begin to compose it with other ideas. Composing ideas is how we build things. So if you know it at this level, you can at least begin to build with your new knowledge. 

One of the challenges with learning statics in undergrad is that it usually isn't taught at the depth in which you can begain to compose things. The result is that many smart people struggle to really understand statistics. They don't have a framework or a sense for how things go togther. They carry around a bunch of seperate and distinct ideas in their head. 

The starting point for learning statistics is to understand why you should care about the definition of a random variable. I admit, even during my first years of graduate school that I could recite the definition of a random variable, but I couldn't tell you why that definition was important.

Let me give you the definition and then I'll try to illustrate why it's important to care about this defintion. Definition: A random variable is a function. Okay, that's an incomplete definition but it begins to convey its essence without hopefully overwhelming the reader. The key part of a random variable though is that it actually maps the probability measure defined on one space to another. 


$$\Big( \Omega, \mathcal{F}, \mathbb{P}\Big) \overset{X}{\longmapsto} \Big( \mathcal{R}, \mathcal{B}(\mathcal{R}), \mathbb{P} \circ X ^{-1}\Big)  $$




