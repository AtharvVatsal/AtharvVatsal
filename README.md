<div align="center">

# Atharv Vatsal

### AI/ML · Computer Vision · Data · Systems · Photography

**CSE + AI/ML @ VIT Vellore · India**

[Portfolio](https://atharvvatsal.com) · [GitHub](https://github.com/AtharvVatsal)

<br>

> **I like building things that make me ask better questions.**

</div>

---

## About

I'm a final-year B.Tech Computer Science & Engineering student specializing in **Artificial Intelligence & Machine Learning at VIT Vellore**.

Most of my work sits somewhere between **machine learning, computer vision, data, software engineering, and product design**.

I enjoy the part before the model gets trained and after the demo stops looking impressive:

**What is the actual problem? What does the data look like? What can break? How do we know it works? And what does a real person do with the output?**

I've built projects around NLP, autonomous-driving perception, real-time object detection, quantitative systems, drone path tracking, developer tooling, web applications, and AI-assisted workflows.

And, somewhat unexpectedly, I've spent a significant amount of time behind a camera.

That combination is probably the most accurate description of me.

---

## Right now

```text
studying        →  Computer Science + Artificial Intelligence & Machine Learning
building        →  AI/ML systems, computer-vision projects, engineering experiments
learning        →  reliable AI, ML systems, data engineering, systems thinking
interested in   →  CV · NLP · statistics · mathematics · autonomous systems
also doing      →  photography · video · web design · visual storytelling
```

### Things currently occupying my brain

`reliable AI` · `LLM-assisted software engineering` · `computer vision`
· `simulation` · `autonomous systems` · `data products`
· `how to make software feel less mechanical`

---

# Projects

These are the repositories I'd point you to first.

<details>
<summary><strong>🚔 HP Police ReportStream — NLP for real-world reports</strong></summary>

An NLP/data-science system built around police-report data.

**Stack / methods**

`Python` · `DistilBERT` · `spaCy` · `NER` · `Pandas`

The interesting part wasn't simply getting a language model to produce an output. It was dealing with messy information and thinking about how extracted information could become useful structured data.

This project pushed me toward thinking more seriously about:

`data quality → extraction → reliability → downstream use`

</details>

<details>
<summary><strong>🚗 DriveSense — autonomous-driving perception</strong></summary>

A computer-vision project focused on the perception layer of autonomous driving.

**Data**

- BDD100K — ~70K training images
- BDD100K — ~20K validation images
- Cityscapes as an additional perception dataset

The question I find more interesting than *"can it detect the object?"* is:

> **What does the rest of the system do with that detection?**

</details>

<details>
<summary><strong>📈 LZ-Quant — real-time AI trading engine</strong></summary>

A quantitative / real-time systems project built around the path from raw data to a decision.

```text
data → signal → model → decision → execution
```

This is the kind of project that makes ML feel like engineering rather than just experimentation.

Latency, noisy inputs, determinism, evaluation, and the difference between a good backtest and a useful system all become part of the problem.

</details>

<details>
<summary><strong>👁️ YOLOv8 — real-time object detection</strong></summary>

A hands-on computer-vision project exploring the complete path:

```text
image
  ↓
preprocessing
  ↓
inference
  ↓
detections
  ↓
real-time output
```

The goal was to understand the pipeline and its trade-offs rather than treat the model as a black box.

</details>

<details>
<summary><strong>🗃️ keeper.raw — Rust</strong></summary>

A Rust project that takes me outside my usual Python/ML environment.

I like projects like this because they force me to think about the machine underneath the abstraction.

Sometimes the fastest way to become better at high-level engineering is to spend some time lower down.

</details>

<details>
<summary><strong>🧭 A.D.A.P.T. — autonomous drone path tracking</strong></summary>

An autonomous-drone project centred around **adaptive path tracking**.

The work sits at an interesting intersection of:

`geometry` · `perception` · `control` · `simulation` · `autonomous behaviour`

A small software decision here can have a very visible consequence.

</details>

<details>

<summary><strong>🏫 Sacred Heart School — web redesign</strong></summary>

A school website redesign built using **Next.js + Sanity CMS**.

A reminder that engineering isn't only models and algorithms.

Content architecture, maintainability, responsive interfaces, and information hierarchy matter just as much when the person on the other side is just trying to find something.

</details>

---

# The slightly weird part of my profile

## Organizer | Press & Media | graVITas'26

Alongside all the ML work, I served as **Head of the Press & Media Committee for Gravitas '26 at VIT**.

That involved photography, videography, social media, podcasts, event coverage, editing, publishing, and coordinating a large student media operation.

Some numbers:

| | |
|---|---:|
| Events covered | **~237** |
| Pieces of content | **~300** |
| Reach across 90 days | **6.7M+** |
| Instagram growth | **36%** from ~9K baseline |

The more interesting part, though, was the operational side.

Hundreds of assets moving through photographers, videographers, editors, approvals, branding, publishing, and deadlines starts to feel a lot like a **distributed system with humans in the loop**.

Different vocabulary.

Same problems:

`ownership` · `latency` · `handoffs` · `failure recovery` · `information flow`

That experience made me a better builder.

---

# And yes, I take photographs

Photography isn't something I put on a résumé because it sounds interesting.

I've worked as a photographer for **Rivera** and **Gravitas**, covered events, worked on reels and video, contributed to podcasts and social content, and spent a lot of time thinking about:

`light` · `composition` · `timing` · `motion` · `colour` · `story`

It also affects the way I build software.

> **Something can work perfectly and still feel terrible to use.**

I'm interested in the gap between those two things.

---

# Toolbox

### Languages

`Python` · `Java` · `C` · `C++` · `Rust` · `JavaScript`
· `SQL` · `R` · `MATLAB` · `Bash`

### AI / ML

`TensorFlow` · `Scikit-learn` · `NumPy` · `Pandas`
· `Matplotlib` · `Seaborn`

### Areas

`Machine Learning` · `Deep Learning` · `Computer Vision` · `NLP`
· `Data Analysis` · `Statistics` · `Digital Image Processing`
· `Machine Vision` · `Reinforcement Learning`

### Software / Web

`React` · `Next.js` · `Tailwind CSS` · `Sanity CMS`
· `Linux` · `Git` · `System Design`

### Other tools

`Power BI` · `Plotly` · `Cloudinary` · `EmailJS` · `Google Gemini API`

---

# How I work

I usually end up following some variation of this:

```text
interesting problem
       ↓
understand the constraints
       ↓
build the smallest useful version
       ↓
measure it
       ↓
break it
       ↓
figure out why
       ↓
iterate
```

I'm biased toward:

**evidence over vibes**  
**metrics over adjectives**  
**experiments over assumptions**

And especially when AI is involved:

> **"The model said so" is not an evaluation strategy.**

---

# Things I keep learning

<details>
<summary><strong>ML is often a data problem before it is a model problem.</strong></summary>

Bad inputs, weak labels, poor evaluation, and misunderstanding the data distribution can make a brilliant architecture almost irrelevant.

</details>

<details>
<summary><strong>Shipping changes what "good" means.</strong></summary>

A model that performs well in isolation is interesting.

A system that survives real usage is much more interesting.

</details>

<details>
<summary><strong>Low-level knowledge makes high-level engineering better.</strong></summary>

Working closer to the system makes abstractions easier to reason about and easier to question.

</details>

<details>
<summary><strong>Design is part of engineering.</strong></summary>

People don't experience your code.

They experience the thing your code creates.

</details>

---

# Experience

### Department of Digital Technologies & Governance  
**Government of Himachal Pradesh · ML / Data Science Intern · May 2025 – Jul 2025**

Worked on ML and data-science initiatives involving:

- data cleaning and exploratory analysis
- predictive modelling with Python / Scikit-learn
- Pandas-based data processing
- dashboards and analytical visualizations with Power BI and Plotly

One of the best lessons from this experience:

> Real-world data almost never arrives looking like a Kaggle dataset.

---

# Academic background

**B.Tech — Computer Science & Engineering, specialization in AI/ML**  
**Vellore Institute of Technology, Vellore**

Relevant coursework includes:

`Data Structures & Algorithms` · `Machine Learning` · `Deep Learning`
· `Computer Vision` · `Computer Organization & Architecture`
· `Digital Image Processing` · `Machine Vision` · `System Design`
· `Computational Mathematics` · `Speech & Language Processing`

---

# What I'm looking for

I'm most interested in roles and projects around:

`AI/ML Engineering` · `Computer Vision` · `Data Science`
· `ML Systems` · `Intelligent Products` · `Autonomous Systems`
· `Developer Tooling` · `Applied Research`

The strongest fit for me is usually a team where people care about the entire loop:

```text
understand → build → measure → learn → improve
```

---

# A small note about this GitHub

Not every repository here is meant to be polished.

Some are finished projects.

Some are experiments.

Some started as a good idea and ended as a very good lesson.

Some exist because I wanted to understand something and refused to leave it as a vague concept in my head.

That's intentional.

I'd rather have a GitHub that shows **what I was curious enough to build** than one that looks perfectly curated.

---

## Currently building / thinking about

```text
┌───────────────────────────────────────────────────────────┐
│                                                           │
│  → applied AI / ML systems                                │
│  → reliable AI-assisted engineering workflows             │
│  → computer-vision experiments                            │
│  → stronger systems + data engineering fundamentals       │
│  → final-year B.Tech project                              │
│  → making atharvvatsal.com better                         │
│                                                           │
└───────────────────────────────────────────────────────────┘
```

---

<div align="center">

### build something interesting.

<sub>
AI/ML · systems · data · computer vision · software · photography
</sub>

<br><br>

[**atharvvatsal.com**](https://atharvvatsal.com)

</div>
