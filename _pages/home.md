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
  Postdoctoral Scientist<br />
#  <small><a href="https://github.com/mmistakes/minimal-mistakes/releases/tag/4.24.0">Latest release v4.24.0</a></small>

feature_row1:
  - image_path: /assets/images/filler.jpg
    alt: "Guess the Grade"
    title: "Guess the Grade"
    excerpt: "A common problem in rock climbing is determining the difficulty of a climb. This question is particularly relevant for climbs set on system boards, which are short training walls with a standardized set of hand/foot holds. Climbs on these boards are often set by members of the climbing community, who also determine the difficulty of the climb. These difficulty estimates can sometimes be quite unreliable. That begs the question---can an AI be trained to estimate system board climb difficulty?"
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
  - image_path: /assets/images/filler.jpg
    alt: "Visualizing the Seneca 7 Race Results"
    title: "Visualizing the Seneca 7 Race Results"
    excerpt: "The Seneca 7 is a 7 person relay race around Seneca Lake covering a distance of (approximately) 77.7 miles. Each team member runs three legs throughout the day as the rest of the team leapfrogs their way up the course (hopefully ariving at the exchange point in time to switch runners). Using Tableau, I visualized the results of the past several years of this chaotic race."
    url: "/projects/seneca_7/"
    btn_class: "btn--primary"
    btn_label: "Learn More"

feature_row4:
  - image_path: /assets/images/filler.jpg
    alt: "The Wordle Bot"
    title: "The Wordle Bot"
    excerpt: "Almost everyone has heard of Wordle---The New York Times' daily word guessing game. This web app flips the game on its head. Instead of guessing the hidden word yourself, you get to determine the hidden word. Watch as The Wordle Bot finds your hidden word in six tries or less (or your money back) using an information theory-based algorithm! As a bonus, this algorithm can be used to determine some of the best (and worst) first word guesses."
    url: "/projects/the_wordle_bot/"
    btn_class: "btn--primary"
    btn_label: "Learn More"

feature_row5:
  - image_path: /assets/images/filler.jpg
    alt: "Chemical Physics"
    title: "Chemical Physics"
    excerpt: "My Ph.D. and postdoctoral work focused on incorporating chemical data into chemical and quantum mechanical models, and the development of algorithms that allow application of those models to very large systems. Some of my more recent projects include developing a ML model to predict polymer properties and facilitate recycling, using deep-learning-based molecular dynamics to uncover fundamental diffusion mechanisms in water, the construction and analysis of benchmark quantum chemical databases, and the development of extremely fast (linear scaling) algorithms for simulating large-scale systems."
    url: "/science/"
    btn_class: "btn--primary"
    btn_label: "Learn More"

feature_row6:
  - image_path: /assets/images/filler.jpg
    alt: "Other Interests"
    title: "Other Interests"
    excerpt: "I spend a lot of time during the day getting to the bottom of things, one way or another. Naturally, I like to balance that out with activities that often involve getting to the top of things---rock climbing, hiking, and running (Ithaca has so many hills!). If you're interested in granola recipes, my progress towards completing the Adirondack 46ers, or some nice pictures of rocks, then this is where to look!"
    url: "/other/"
    btn_class: "btn--primary"
    btn_label: "Learn More"

<!---
about_me:
  - image_path: /assets/images/filler.jpg
    alt: "About me"
    title: "About Me"
    excerpt: "This is what I have to say about myself"
    url: "/about/"
    btn_class: "btn--primary"
    btn_label: "Learn More"
-->
---

[![image-center](https://wsrv.nl/?url=https://github.com/zacharysparrow/zacharysparrow.github.io/blob/master/assets/images/bio-photo.jpg?raw=true&h=200&w=200&fit=cover&mask=circle&maxage=7d){: .align-center}](https://zacharysparrow.github.io/about/)

<p style="text-align:center;">I'm a postdoctoral scientist in Ithaca, NY. I obtained my Ph.D. in computational and theoretical chemistry from Cornell University for insights into the data-driven design and large-scale application of chemical physical models. I love working with great people, turning data into insight, and developing algorithms to do things that weren't possible before.</p>

<hr>
<h1 style="text-align:center;">Personal Projects</h1>
<hr>

{% include feature_row id="feature_row1" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="right" %}

{% include feature_row id="feature_row5" type="left" %}

{% include feature_row id="feature_row6" type="right" %}
