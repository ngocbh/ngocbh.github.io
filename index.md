---
title: Ngoc Bui's homepage
layout: default
---

## News
{% assign new_list = site.data.news | sort:"date" %}
<div id="content"></div>
<p
      style="
        margin-left: 22px;
        color: rgb(0, 0, 238);
        margin-top: 0px;
        text-decoration: underline;
        cursor: pointer;
      "
      id="loadmore"
    >
      more...
    </p>
<ul id='newList' style="display: none;">
{% for new in new_list reversed %}
    <li>{{new.date | date: "%b %-d, %Y" }}: {{new.content | markdownify | remove: '<p>' | remove: '</p>' }}</li>
{% endfor %}
</ul>

## Biography

Ngoc Hong Bui is currently a resident (research intern) at VinAI Research, Vietnam. 
He is also pursuing a graduate degree at Hanoi University of Science and Technology.

He received a Bachelor of Science in Computer Science from Hanoi University of Science and Technology in 2021. As an undergraduate student, he participated in some research projects in Natural Language Processing and Operation Research as a collaborator in DSLAB and MSOLAB (HUST).

His career aspiration is to become a research scientist in Machine Learning. However, he is still on the way to finding specialized research topics to pursue.

## Publications

#### Conferences

* **Hong-Ngoc Bui**, and Viet-Trung Tran. "A Novel Conditional Random Fields Aided Fuzzy Matching in Vietnamese Address Standardization." *Proceedings of the Tenth International Symposium on Information and Communication Technology (SoICT)*. 2019. [[.pdf]](/assets/pdf/ngocbh_soict_2019.pdf)

## Projects

* GeneticPython: A simple and friendly Python framework for genetic-based algorithms. [[.code]](https://github.com/ngocbh/geneticpython)
* SCOSS: A source code similarity system for competitive programming. [[.web]](http://scoss.soict.ai/) [[.code]](https://github.com/BK-SCOSS/scoss)
* Comnato: A command line interfaces (CLI) to manage Codeforces’ groups. [[.code]](https://github.com/ngocbh/codeforces-management-tools)

## Thesis

* A bachelors thesis at Hanoi University of Science and Technology. *A Deep Reinforcement Learning based Online Charging Scheme for Target Coverage and Connectivity in WRSNs.* [[.pdf]](/assets/pdf/ngocbh_thesis__en_.pdf) [[.slide]](/assets/pdf/ngocbh_thesis_slides.pdf) [[.code]](https://github.com/ngocbh/odmc-wrsn)

## Awards and honors

* Problem Winner in ASEAN-India Hackathon, *2021*.
* The Third prize (Top 50) in ACM/ICPC Asia Ho Chi
Minh Regional, *2017*.
* The Third prize in Vietnam National Olympiad in Informatics, *2016*.

<h2 id='contact'>Contacts</h2>

* Email: ngocbh.pt (at) gmail (dot) com
* Github: [ngocbh](https://github.com/ngocbh)

## Signature

This is Consenkid.

<img src="{{ '/assets/images/cosenkid.jpg' | relative_url }}" width="200" height="200" alt="Paris" style='display: block;margin-left: auto;margin-right: auto;'/>


