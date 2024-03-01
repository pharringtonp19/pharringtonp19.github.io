

+++
title = "Research"
descripttion = "WIP"
+++

<style>
    body {
        font-family: 'Palatino';
        text-align: left"
    }
        .wide-heading {
        min-width: 600px !important;
    }
</style>


## Published Works 

<h3 style="min-width: 1000px !important;"> <a href="https://direct.mit.edu/rest/article-abstract/101/1/1/58660/How-the-Reformulation-of-OxyContin-Ignited-the?redirectedFrom=fulltext" style="color: inherit; text-decoration: none;" onmouseover="this.style.textDecoration='none'" onmouseout="this.style.textDecoration='none'">
 How the Reformulation of OxyContin Ignited the Heroin Epidemic</a> 
 </h3>

<div style="padding-left: 30px;  text-align: left; min-width: 900px !important;">
We attribute the recent quadrupling of heroin death rates to the August 2010 reformulation of an oft-abused prescription opioid, OxyContin. The new abuse-deterrent formulation led many consumers to substitute an inexpensive alternative, heroin. Using structural break techniques and variation in substitution risk, we find that opioid consumption stops rising in August 2010, heroin deaths begin climbing the following month, and growth in heroin deaths was greater in areas with greater prereformulation access to heroin and opioids. The reformulation did not generate a reduction in combined heroin and opioid mortality: each prevented opioid death was replaced with a heroin death.

William N. Evans, Ethan M. J. Lieber, Patrick Power; How the Reformulation of OxyContin Ignited the Heroin Epidemic. The Review of Economics and Statistics 2019; 101 (1): 1–15.
</div>


## Working Papers
<div style="clear:both;">
  <h3 style="clear:both;" > <a href="https://github.com/pharringtonp19/papers/blob/main/The_Right_to_Counsel_at_Scale_latest.pdf"> The Right to Counsel at Scale</a></h3>  
  <div style="padding-left: 30px;  text-align: left;  min-width: 900px !important;">We assess how the Right to Counsel affects housing stability. The Right to Counsel ensures that low-income tenants facing eviction have access to free legal representation. We exploit the recent adoption of this policy in some, but not all, zip codes in Connecticut. We show that legal representation improves court housing outcomes for those currently housed but adversely effects those currently unhoused. We use linear regression analysis for the intent-to-treat and IV estimates. We confirm our results using fine-tuned large language models and cluster regularized neural networks. We also provide insight about the type of tenants most likely to respond to the policy and how lawyers' strategies affect their clients housing outcomes.
    </div>
  <!-- <iframe src="/papers/The_Right_to_Counsel_at_Scale_latest.pdf" width="100%" height="400px" style="border: none !important; margin-top: 20px; margin-bottom: 20px; float: center;"></iframe> -->
</div>

<div style="clear:both;">
 <h3 style="clear:both;" > <a href="https://github.com/pharringtonp19/papers/blob/main/Instrumental_LLMs.pdf"> Instrumental LLMs</a></h3>  

  <div style="padding-left: 30px;  text-align: left; min-width: 900px !important;">
  In many applied microeconomic contexts, the underlying data is text (Health, Education, Housing). Causal inference in this setting has typically proceeded by hand selecting numerical representations of the text and estimating the corresponding conditional expectation function assuming that treatment or the instrument is locally randomly assigned.  Recent developments in Natural Language Processing/AI though have an introduced alternative ways to produce causal estimates from text. In this paper we (1) clarify the general framework for using fine-tuned large language models for causal inference and (2) highlight their relative strengths in the setting of IV with preferential treatment.
</div>
</div>

<div style="clear:both;">
 <h3 style="clear:both;" > <a href="https://github.com/pharringtonp19/papers/blob/main/Regularizing_the_Forward_Pass.pdf"> Regularizing the Forward Pass</a></h3>  

  <div style="padding-left: 30px;  text-align: left; min-width: 900px !important;">
In certain applied microeconomic settings, it's typical to view one's dataset as the realization of a stratified cluster randomized control trial: treatment is assigned at the cluster level (such as zip code), and controls vary at both the individual and cluster level. Locally, this makes it more likely that observation will be from the same cluster which can increase the variance for estimators which don't account for the clustered nature of the data. We introduce a framework for partialling out nonparametric cluster effects in a way that generalizes least squares and is inherently compositional even under regularization. We provide a python library based on JAX: <a href="https://github.com/pharringtonp19/rfp}"> rfp </a>
</div>
</div>

 






  <!-- <h3 style="clear:both;"id="regularizing-forward-pass"><a href="https://pharringtonp19.github.io/rfp_paper/">Regularizing the Forward Pass</a></h3> -->
  <!-- <iframe src="/papers/rfp_paper_adj.pdf" width="100%" height="400px" style="border: none !important; margin-top: 20px; margin-bottom: 20px; float: center;"></iframe> -->



<!-- **[A Deep Learning Assessment of the Right to Counsel](https://github.com/pharringtonp19/jmp_paper/blob/main/jmp.pdf)** (Job Market Paper) (with Shomik Ghosh and Markus Schwedeler)
<div style="padding-left: 30px;"> -->

<!-- <iframe src="https://slides.com/pharringtonp19/rtc/embed" width="576" height="420" title="rtc" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe> -->
<!-- 
Drawing from the Deep Learning Literature and in the language of Category Theory, we introduce a unified estimation framework that generalizes ordinary least squares, allows for nonparametric cluster effects, and is inherently compositional, even under regularization. With this framework, we examine the effects of the Right to Counsel: a policy which ensures that low-income households facing eviction have access to free legal representation. Specifically, we consider the extent to which the policy increases housing instability by making it harder for low-income households to secure housing in the first place. Exploiting the ongoing roll-out of the policy across the state of Connecticut, our preliminary results suggest that housing is harder to secure in areas with higher eviction rates, which suggests  that the policy is less effective at scale than previously understood. 
</div> -->

<!-- **[Regularizing the Forward Pass](https://github.com/pharringtonp19/rfp_paper/blob/main/Regularizing_the_Forward_Pass.pdf)** (with Shomik Ghosh and Markus Schwedeler)
<div style="padding-left: 30px;">
Applied microeconomic analysis involves making tradeoffs -- assessing which issues are first order, and which can potentially be addressed in an appendix or not at all. Based the recent deep learning literature on gradient based meta-learning and regularized neural ordinary differential equations, and in the language of category theory, we introduce a unified structure that allows one to think through these tradeoffs (as our structure generalizes OLS, allows for nonparametric cluster effects, and is inherently compositional even under regularization). We apply this framework to a variety of applied microeconomic contexts estimating average, local, and heterogeneous treatment effects.
</div> -->








