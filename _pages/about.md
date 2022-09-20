---
permalink: /
title: "Jiaqing Chen"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Master student at [Columbia University](https://www.columbia.edu), majoring [Computer Science](https://www.engineering.columbia.edu). Prior to this, I received my Bachelor's Degree in Computer Science from [City University of HOng Kong](https://www.cityu.edu.hk/). Smart data and intelligent coding change the world. I'm passionate about working with data and integrating with machine learning to build effective software and solve challenging problems, both in technical and finance fields.

# Education
* B.S. in Computer Science, City University of Hong Kong, 2017
* M.S. in Computer Science, Columbia University, 2022

# Work experience
* **Summer 2022: Goldman Sachs - Software Engineering Summer Analyst**
  * FICC Eng Team
  * Produced a trading order monitor application to track order status in real-time with Java Spring Boot, MongoDB, React

* **Summer 2020: Everbright Xinglong Trust Co., Ltd. - Quantitative Analytics Intern**
  * Investment Management Team
  * Built data pipeline and automated model verification in Python to assist in multi-factor based model research

* **Jun 2019 - Apr 2020: Hong Kong Exchanges & Clearing Ltd (HKEX) - Software Engineer Intern**
  * Corporate & Listing Team
  * Corporate listing system maintenance and testing; Designed VBA Macros to automate financial report generation
  * Oracle database maintenance

# Research experience
* **Jul 2019 - Apr 2021: City University of Hong Kong**
  * Supervisor: Prof. [Cong Wang](https://www.cs.cityu.edu.hk/~congwang/)
  * Research field: Big Data, Federated Learning, Blockchain, Cloud Computing
  * Achievement: 
    * Researched on data valuation algorithms in context of machine learning, collaborated to complete an academic survey journal
    * Designed and implemented an incentive allocation scheme with data valuation algorithm in Federated Learning, and extended it to be a federated optimization algorithm


# Skills
* Programming Languages: Java, Python, C/C++, SQL, JavaScript
* Frameworks and Tools: Spring, Flask, TensorFlow, PyTorch, Hadoop, Spark, AWS

  
# Activities
* 2021 Pearl River Delta Delta Region IT Project Competition
* 2022 Columbia Data Science Hackathon
* ICPC Columbia University Local Contest (CULC)


# Selected Portfolio

{% include base_path %}

<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
<tbody>
  {% for post in site.publications reversed %}
    {% if post.show %}
      {% include archive-single.html %}
    {% endif %}
  {% endfor %}
</tbody>
</table>

