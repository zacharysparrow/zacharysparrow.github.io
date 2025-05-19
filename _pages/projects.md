---
title: Personal Projects
layout: collection
permalink: /projects/
#collection: projects
classes: wide
entries_layout: list
header: 
  overlay_image: assets/images/Mount+VanHoevenberg_crop.jpeg

feature_row1: 
  - image_path: /assets/images/climb_10_attention_weights.png 
    alt: "Guess the Grade" 
    title: "Guess the Grade" 
    excerpt: "A common problem in rock climbing is determining the difficulty of a climb. This question is particularly relevant for climbs set on system boards, which are short training walls with a standardized set of hand/foot holds. Climbs on these boards are often set by members of the climbing community, who also (somewhat unreliably) determine the difficulty of the climb. That begs the question---can an AI be trained to estimate system board climb difficulty?" 
    url: "/projects/guess_the_grade/" 
    btn_class: "btn--primary" 
    btn_label: "Learn More" 
 
feature_row2: 
  - image_path: /assets/images/filler.jpg 
    alt: "Plan My Marathon" 
    title: "Plan My Marathon" 
    excerpt: "Running a marathon requires a huge amount of training and dedication. Committing to a training plan can be difficult, especially when life's other commitments get in the way. What should you do when you have to skip a scheduled run because of prior committments, or because the weather is awful? For the recreational runner without access to a coach, it's hard to determine how to best adjust your training plan. So, let the Plan My Marathon AI do it for you!" 
    url: "/projects/plan_my_marathon/" 
    btn_class: "btn--primary" 
    btn_label: "Learn More" 
 
feature_row3: 
  - image_path: /assets/images/seneca7_sneak_peek.png 
    alt: "Visualizing the Seneca 7 Race Results" 
    title: "Visualizing the Seneca 7 Race Results" 
    excerpt: "The Seneca 7 is a 7 person relay race around Seneca Lake covering a distance of (approximately) 77.7 miles. Each team member runs three legs throughout the day as the rest of the team leapfrogs their way up the course (hopefully ariving at the exchange point in time to switch runners). Using Tableau, I visualized the results of the past several years of this chaotic race." 
    url: "https://public.tableau.com/app/profile/zachary.sparrow/viz/TheSeneca7/TheSeneca7" 
    btn_class: "btn--primary" 
    btn_label: "See the Viz" 
 
feature_row4: 
  - image_path: /assets/images/filler.jpg 
    alt: "The Wordle Bot" 
    title: "The Wordle Bot" 
    excerpt: "Almost everyone has heard of Wordle---The New York Times' daily word guessing game. This web app flips the game on its head. Instead of guessing the hidden word yourself, you get to determine the hidden word. Watch as The Wordle Bot finds your hidden word in six tries or less (or your money back) using an information theory-based algorithm! As a bonus, this algorithm can be used to determine some of the best (and worst) first word guesses." 
    url: "/projects/the_wordle_bot/" 
    btn_class: "btn--primary" 
    btn_label: "Learn More"

feature_row5: 
  - image_path: /assets/images/aabbcd.png
    alt: "AABBCD Python Package" 
    title: "AABBCD Python Package" 
    excerpt: "There are many occasions in science where you need to compute numerical integrals involving the product of two compact distributions (*i.e.* distributions that decay rapidly from their center). This compactness imposes a natural sparsity; distributions that are far from each other don't interact, resulting in an integral that is effectively zero. This package (Axis-Aligned Bounding Boxes for Compact Distributions, AABBCD) provides utility functions for leveraging such sparsity for computational savings using algorithms I developed to compute the exact exchange interaction in large-scale systems." 
    url: "/projects/AABBCD/" 
    btn_class: "btn--primary" 
    btn_label: "Learn More"
---

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="right" %}

{% include feature_row id="feature_row5" type="left" %}

