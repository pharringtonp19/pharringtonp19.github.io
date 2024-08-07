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

One of the challenges of learning statics in undergrad is that it usually isn't taught at the depth at which you can begain to compose ideas together. The result is that many people carry around a bunch of seperate and distinct ideas in their head rather than a coehsive framework. 

The starting point for learning statistics is to understand why you should care about the definition of a random variable. I admit, during my first years of graduate school I could recite the definition of a random variable, but I couldn't tell you why that definition was important.[^1] We didn't use in explicitly in any of the problem sets.

Let me write out the definition and then I'll try to illustrate why it's important to care about this defintion. 

<div style="margin: 0 auto; max-width: 80%;">
    <strong>Definition</strong> - A random variable is a function that maps from the sample space to the codomain. It is neither random (whatever that means) nor is it a variable. It's simply a function. The one constraint is that the pre-image of any open set in the codomain must be an element of the $\sigma$-algebra associated with the sample space. We refer to this constraint as "measurable."
</div>

The immediate question is -- why the constraint? Why do we care that the pre-image of any open sets in the codomain are elements of the initial $\sigma$-algebra? Well, recall what a random variable is doing. It maps elements of the sample space to elements of the codomain. We'd like to be able to assign probabilities to open sets in our codomain. To do so, for each set we can look at the probability associated with the pre-image of that set. With a measurable function, this is well-defined.

Okay, so that's the definition of a random variable and it assumes some understanding of the basics of probability spaces namely that probability measures are defined over $\sigma$-algebras and that a $\sigma$-algebra is a collection of subsets of the sample space[^2]  But stepping back, we see that the esseence of a random variable is that it maps a probability measure defined over one space to a probability measure defined over a space that we care about. 


$$\Big( \Omega, \mathcal{F}, \mathbb{P}\Big) \overset{X}{\longmapsto} \Big( \mathcal{R}, \mathcal{B}(\mathcal{R}), \mathbb{P} \circ X ^{-1}\Big)  $$

[^1] Admittedly, I didn't understand the definition.
 
[^2] A $\sigma$-algebra contains the empty set, and the sample space. It is closed under arbitrary unions and contains the complement of any set in the $\sigma$-algebra.

