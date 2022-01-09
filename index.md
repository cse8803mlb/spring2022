---
layout: home
title: Home
nav_order: 1
seo:
  type: Course
  name: {{ site.title }}
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

<!-- {% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %} -->

## Instructors
{% assign instructors = site.staffers | sort: 'index' %} {% for staffer in instructors %} {{ staffer }} {% endfor %}

## Information
- **Time**: Monday and Wednesday, 12:30-1:45 PM
- **Location**: Klaus 2443
- **Teaching assistants**: Hira Anis ([hanis3@gatech.edu](mailto:hanis3@gatech.edu)); Hechen Li ([hli691@gatech.edu](mailto:hli691@gatech.edu))
- **Instructor office hours**: Monday 2:10-3:10 PM (weeks 1-13) or by appointment (weeks 14-16). Meeting link on Canvas.
- **TA office hours**: TBA.

## Course description

This graduate-level course focuses on the exciting intersection between machine learning and computational biology. We will cover modern machine learning techniques, including supervised and unsupervised learning, feature selection, probabilistic modeling, graphical models, deep learning, and more. Students will learn the development of the theoretical concepts for these methods and the applications of these methods to a variety of biological problems in genomics, single-cell analyses, structural biology, and system biology.  Students will also learn to implement deep learning models through assignments. This course is appropriate for graduate students or advanced undergraduate students in computer science, bioinformatics, biomedical engineering, mathematics, and statistics. Familiarity with basic linear algebra, statistics, probability and algorithms is expected. Background knowledge in data analytics will be helpful for this course. Students are also expected to have a programming experience.

## Evaluation

Students will be evaluated based on homework assignments, paper presentations, and final exam. There will be 5 homeworks throughout the semester (programming assignments may be included in the homeworks). Each student is expected to present one paper (alone or in a team, depending on the final number of students). Your grade will be based on the following criteria (Grade curving is possible if needed):
- Homework 50%
- Paper presentation 20%
- Take-home final exam 25%
- Participation: 5% 
