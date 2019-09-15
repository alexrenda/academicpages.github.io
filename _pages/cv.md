---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. student in EECS at MIT
  * Working with **[Michael Carbin](https://people.csail.mit.edu/mcarbin)** on learning-based systems and efficient neural networks.
  * 2018 - present
* B.S. (Summa Cum Laude, with Honors) in Computer Science with a minor in Linguistics, Cornell University, May 2018
  * Worked with **[Adrian Sampson](http://adriansampson.net)** on **[Opal](https://capra.cs.cornell.edu/research/opal/)** as an undergraduate member of the **[Capra](https://capra.cs.cornell.edu)** group
  * 2014 - 2018

Publications
======
  {% assign publications = (site.publications | sort: 'date') | reverse %}
  <ul>
  {% for post in publications %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>

Teaching
======
  {% assign teaching = (site.teaching | sort: 'date') | reverse %}
  <ul>
  {% for post in teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>

Honors
======
* Best Paper award for Ithemal at the [ML for Systems workshop](http://mlforsystems.org) at ISCA 2019
* MIT EECS Great Educators Fellowhip, 2018-2019
* Cornell University: Summa Cum Laude with Honors

Industry Experience
======
* Summer 2018: Software Engineering Intern at **[Two Sigma](https://www.twosigma.com)**
* Summer 2017: Software Engineering Intern at **[Two Sigma](https://www.twosigma.com)**
* Summer 2016: Software Engineering Intern at **[Facebook](https://www.facebook.com)**
* Summer 2014: System Validation Intern at **[Tesla](https://www.tesla.com)**

Relevant Coursework
======
* Fundamentals of Program Analyis, Prof. Armando Solar-Lezama, Fall 2019
* Randomized Algorithms, Prof. David Karger, Spring 2019,
* Machine Learning, Profs. Devarat Shah, David Sontag, Suvrit Sra, Fall 2018
* Distributed Algorithms, Prof. Nancy Lynch, Fall 2018
* Category Theory, Prof. Ross Tate, Spring 2018
* Advanced Machine Learning Systems, Prof. Chris de Sa, Fall 2017
* Certified Software Systems, Profs. Andrew Myers and Greg Morrisett, Fall 2017
* Applications of Parallel Computers, Prof David Bindel, Fall 2017
* Advanced Programming Languages, Prof. Adrian Sampson, Spring 2017
* Introduction to Compilers, Prof. Andrew Myers, Spring 2016
