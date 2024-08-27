---
layout: home
title: Advanced Topics in Natural Language Processing
nav_exclude: true
permalink: /:path/
seo:
  type: Course
  name: Advanced Topics in Natural Language Processing
---

<!-- # {{ site.tagline }} -->
<!-- {: .mb-2 } -->
# {{ site.description }}
#### {{ site.title }} &middot; {{ site.semester }} &middot; {{ site.university }}

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

<!-- <img src="assets/images/crafting_software_header_noBG.png" > 

## Welcome to 17-950 Crafting Software-->

In this research driven course, we will read and discuss the latest language modeling and representation learning methods in natural language processing. This includes prominent deep learning architectures including transformers, methods of self-supervised learning and transfer learning,, large language models and the power of scale, emergent properties of large language models, parameter efficient fine-tuning methods, learning from few training examples, task instructions, preferences, methods for making large language models more efficient, applications to other fields, and other recent topics in contemporary NLP. The format of the class will be a mix of lectures and research paper presentations. 

## Prerequisite Knowledge

Students who participate in this class are expected to be self-motivated graduate students or senior undergraduate students.

Prerequisites: CSE 3521/6521, 5521, 5243, 5525 highly recommended; students must have experience with machine learning and deep learning including necessary mathematical background (i.e., they should have taken courses in linear algebra (Math 2568), multivariate calculus, probability, and statistics.). Experience with natural language processing is a plus. 

Students should also feel comfortable with implementing machine learning algorithms and understanding/running open source machine learning code.

Students should also have experience with reading machine learning papers and developing a decent understanding of the main concepts/ideas presented in the paper.

Note: Students who haven’t taken any of these courses but feel comfortable with deep learning and modern NLP, and students from other relevant departments such as statistics, linguistics, neuroscience and biomedical science are welcome to participate but please contact the instructor for approval.

---

Lectures: Mondays at 1pm

Lecture Location: DL 317

---

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
### Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

## Code of Conduct

The strength of the university depends on academic and personal integrity. In this course, you must be honest and truthful, abiding by the University Academic Integrity Policy: https://oaa.osu.edu/academic-integrity-and-misconduct


