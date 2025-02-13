---
layout: splash
permalink: /
# hidden: true
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/Mount+VanHoevenberg_crop.jpeg
#  overlay_image: /assets/images/WhitefaceLookout_Womack3.JPG
#  actions:
#    - label: "About Me"
#      url: "https://zacharysparrow.github.io/about/"
#    - label: "Scientific Work"
#      url: "https://zacharysparrow.github.io/science/"
#    - label: "Projects"
#      url: "https://zacharysparrow.github.io/projects/"
#    - label: "Other"
#      url: "https://zacharysparrow.github.io/other/"
#  actions:
#    - label: "<i class='fas fa-download'></i> Install now"
#      url: "/docs/quick-start-guide/"
excerpt: >
  Postdoctoral Data Scientist<br />
#  <small><a href="https://github.com/mmistakes/minimal-mistakes/releases/tag/4.24.0">Latest release v4.24.0</a></small>

feature_row1:
  - image_path: /assets/images/filler.jpg
    alt: "Project 1"
    title: "Project 1"
    excerpt: "This is what I have to say about project 1"
    url: "/projects/project1/"
    btn_class: "btn--primary"
    btn_label: "Learn More"

feature_row2:
  - image_path: /assets/images/filler.jpg
    alt: "Project 2"
    title: "Project 2"
    excerpt: "This is what I have to say about project 2"
    url: "/projects/project2/"
    btn_class: "btn--primary"
    btn_label: "Learn More"

feature_row3:
  - image_path: /assets/images/filler.jpg
    alt: "Chemical Physics"
    title: "Chemical Physics"
    excerpt: "My Ph.D. and postdoctoral work focused on incorporating chemical data into chemical and quantum mechanical models, and the development of algorithms that allow application of those models to very large systems. Some of my more recent projects include developing a ML model to predict polymer properties and facilitate recycling, using deep-learning-based molecular dynamics to uncover fundamental diffusion mechanisms in water, the construction and analysis of benchmark quantum chemical databases, and the development of extremely fast (linear scaling) algorithms for simulating large-scale systems."
    url: "/science/"
    btn_class: "btn--primary"
    btn_label: "Learn More"

feature_row4:
  - image_path: /assets/images/filler.jpg
    alt: "Other Interests"
    title: "Other Interests"
    excerpt: "I spend a lot of time during the day getting to the bottom of things, one way or another. Naturally, I like to balance that out with activities that often involve getting to the top of things---rock climbing, hiking, and running (Ithaca has so many hills!). If you're interested in granola recipes, my progress towards completing the Adirondack 46ers, or some nice pictures of rocks, then this is where to look!"
    url: "/other/"
    btn_class: "btn--primary"
    btn_label: "Learn More"

about_me:
  - image_path: /assets/images/filler.jpg
    alt: "About me"
    title: "About Me"
    excerpt: "This is what I have to say about myself"
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
---

[![image-center](https://wsrv.nl/?url=https://github.com/zacharysparrow/zacharysparrow.github.io/blob/master/assets/images/bio-photo.jpg?raw=true&h=200&w=200&fit=cover&mask=circle&maxage=7d){: .align-center}](https://zacharysparrow.github.io/about/)

<p style="text-align:center;">I'm a postdoctoral data scientist in Ithaca, NY. I obtained my Ph.D. in computational and theoretical chemistry from Cornell University for insights into the data-driven design and large-scale application of chemical physical models. I love working with great people, turning data into insight, and developing algorithms to do things that weren't possible before.</p>

<hr>
<h1 style="text-align:center;">Featured Projects</h1>
<hr>

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="right" %}

<h3 style="text-align:center;">What is Machine Learning?</h3>
<p style="text-align:center;">At its core, machine learning is a technique to derive algorithms from data. These algorithms can be quite powerful, but they are algorithms nonetheless. Historically, the best and more reliable way to devlop an algorithm has been through a deeper understanding of the problem at hand---this has not changed. As such, a data scientist's role is first to analyze and understand. Strong models will naturally follow just as LLMs followed from understanding natural language. Machine learning follows from human learning.
