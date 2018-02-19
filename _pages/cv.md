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
* B.S. in Computer Science with a minor in Linguistics, Cornell University, 2018 (expected)

Industry experience
======
* Summer 2018: Software Engineering Intern @ **[Two Sigma](https://www.twosigma.com)**
  * TBD!

* Summer 2017: Software Engineering Intern @ **[Two Sigma](https://www.twosigma.com)**
  * Member of the Quantitative Platform Engineering team
  * Used Apache Spark to generate analytics of time-series data, working to improve estimation of option marketplace parameters, and automatically generating periodic reports for improved market understanding
  * Created a production-ready data preprocessing and ingestion pipeline, using Java, Scala, Bash, Python, and SQL

* Summer 2016: Software Engineering Intern @ **[Facebook](https://www.facebook.com)**
  * Member of the Android Friend Sharing team
  * Created new public-facing features for Facebook’s Android apps, including work on both Facebook and Messenger
  * Refactored existing code to be more modular, accessible, and sustainable for future development
  * Discovered and corrected issues in Facebook’s backend related to my app work
  * Worked collaboratively with a fellow intern on a significant project we co-owned

* Summer 2015: Team Member @ **[CUAUV](http://www.cuauv.org)**
  * Refined the machine vision system that I wrote during spring 2015
  * Developed machine vision modules using OpenCV, scikit-learn, and Caffe
  * Worked on miscellaneous tasks involved with managing the software suite of an autonomous submarine, such as debugging CAN bus issues, managing the Linux install, and synchronizing desires with the motor controller

* Summer 2014: System Validation Intern @ **[Tesla](https://www.tesla.com)**
  * Member of the System Validation team
  * Wrote a user interface for test case management. The tool guided users through a series of prompts and dynamically createdcomplex queries based on user responses
  * Designed and implemented a Python interface to automatically upload test case results to a server
  * Developed an Android app to monitor results of automated regression tests

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
