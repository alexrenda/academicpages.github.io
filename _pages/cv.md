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
  * Working with **[Michael Carbin](https://people.csail.mit.edu/mcarbin)**.
* B.S. in Computer Science with a minor in Linguistics, Cornell University, May 2018
  * Worked with **[Adrian Sampson](http://adriansampson.net)** on **[Opal](https://capra.cs.cornell.edu/research/opal/)** as an undergraduate member of the **[Capra](https://capra.cs.cornell.edu)** group

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

Industry experience
======
* Summer 2018: Software Engineering Intern @ **[Two Sigma](https://www.twosigma.com)**
  * Worked on improvements for internal search, including gathering better logs, analyzing those logs to find deep patterns and trends in how people use search, delivering reports about topics users have trouble finding, and implementing both architectural and user-facing changes to improve the search experience

* Summer 2017: Software Engineering Intern @ **[Two Sigma](https://www.twosigma.com)**
  * Used Apache Spark to generate analytics of time-series data, working to improve estimation of option marketplace parameters, and automatically generating periodic reports for improved market understanding

* Summer 2016: Software Engineering Intern @ **[Facebook](https://www.facebook.com)**
  * Created new public-facing features for Facebook’s Android apps, including work on both Facebook and Messenger

* Summer 2015: Team Member @ **[CUAUV](http://www.cuauv.org)**
  * Refined the machine vision system and developed machine vision modules using OpenCV, scikit-learn, and Caffe

* Summer 2014: System Validation Intern @ **[Tesla](https://www.tesla.com)**
  * Wrote a user interface for test case management. The tool guided users through a series of prompts and dynamically createdcomplex queries based on user responses
