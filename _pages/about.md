---
layout: about
title: about
permalink: /
subtitle:

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  address: >

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

I'm a first-year Ph.D. student at MIT, and I'm very fortunate to be advised by [Stephen Bates](https://stephenbates19.github.io). I'm interested in **reliable AI for science** through **uncertainty quantification**. More broadly, I'm generally interested in applications of probability theory and mathematics to machine learning. In my free time, I enjoy playing basketball and guitar, and sailing.

During my undergraduate work at Princeton, I studied pure mathematics and was very lucky to work with Ching-Yao Lai. Since my masters degree in mathematics ("Part III") at the University of Cambridge, I've worked with Sofia Villar on alternative schemes to test experimental treatments in the medical community. Previously, I also interned at Meta Reality Labs.


  
# Active research projects

  
## Medical trial design
Suppose you're trying to find the best over-the-counter medicine that works for you for a mildly harmful condition such as seasonal allergies. In the near future, we could imagine that you download an app which is designed to figure out the best medication for you by recommending (possibly different) medications every morning, and taking feedback from you on how well it worked every night. One might think that this sort of futuristic medical treatment could be better that what is currently standard practice in the medical community: randomized controlled trials. 

Here we show that no such AI-powered app can significantly (i.e. beyond a factor constant in the number of patients) outperform the randomized controlled trial scheme currently in place, at least if the correct number of patients is chosen to participate in each study. We find this number to be $$O(\log(N))$$, where $$N$$ is the total number of patients affected by the condition.

While this work began with a concrete problem, we have harnessed it to prove a novel [refinement of Pinsker's inequality](https://charliecb.github.io/assets/pdf/Novel_refinement_of_Pinsker_s_inequality_via_medical_trial_design.pdf).

## Antarctic ice-sheet dynamics
Melting of Antarctic ice-sheets has been shown to lead to global sea-level rise and impacts the lives of millions of people worldwide. In this work, we map the hardness of ice-sheets across Antarctica using physics-informed neural networks.

Accurate modeling is critical for informing policy; therefore, we study and rectify a particular behavior of physics-informed neural networks we find leads to inaccurate predictions, known as *cheating*. Harnessing functional analysis, we provide methods to circumvent cheating, and find exact theoretical bounds on situations in which cheating can occur.

This effort has led to theoretical work in proving blow-ups of various equations in fluid dynamics, as reported in [Quanta](https://www.quantamagazine.org/deep-learning-poised-to-blow-up-famed-fluid-equations-20220412/).

## Ancient language processing
Ancient texts have been passed down by scribes over thousands of years. Scribes occasionally make mistakes, some of which lie undiscovered to this day. As unchecked errors have the potential to change the meaning of a text, finding and correcting scribal errors is a central aim in philology.

I'm a creator of [Logion](https://www.logionproject.princeton.edu), the project to identify and correct scribal errors which accumulate in ancient manuscripts. Understanding how to catch errors can help us to develop software for modern text editing. Logion has led to peer-reviewed changes in our interpretation of the works of ancient authors, which have been published in both classics and computer science venues (*TAPA*, *ACL*), and has become the subject of [graduate courses](https://hellenic.princeton.edu/study/graduate/courses/fall-2023/problems-greek-literature-greek-philology-past-and-future) at Princeton University. For a technical report, see [here](https://arxiv.org/abs/2305.01099).

