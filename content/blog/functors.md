+++
title = "Functors"
date = 2023-01-03
+++

> Functions map and preserve

A function maps a set into another set. 

$$f : \big(\mathcal{V}, +_v\big) \to \big(\mathcal{W}, +_w\big)$$ 

Certain functions, such as linear functions, preserve structure. To talk about this structure, we need more than just a set. As indicated above, if we want to talk about preserving the linear structure, we need to be able to perform addition on the sets. So functions in most applications actually map "spaces" into other "spaces". Where by "spaces" we mean a tuple including a set along with other functions defined on this set. 

$$f( v_1 +_v v_2) = f(v_1) +_w f(v_2) $$

<!-- A functor maps a category (objects, arrows) into another category such that the structure of the category is preserved. 

```haskell
f ::  
``` -->