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

Ngoc Bui is currently a research resident under supervision of Dr. Viet-Anh Nguyen at VinAI Research. He is also pursuing a Master degree in Data Science and Artifical Intelligence at Hanoi University of Science and Technology.

He received a BEng in computer science (under supervision of Assoc. Prof. Do Phan Thuan and Dr. Nguyen Phi Le) from Hanoi University of Science and Technology in 2021. Throughout the time at university, he also participated in research projects in Natural Language Processing (with Dr. Viet-Trung Tran in DSLAB) and Operation Research (with Assoc. Prof. Huynh Thi Thanh Binh in MSOLAB) as a collaborator.


He is interested in tackling combinatorial/operation research problems, and promoting robustness and explainability in machine learning models using distributional robust optimization, reinforcement learning, and graph neural network. 


## Publications

#### Conferences

* **Ngoc Bui**, Duy Nguyen, Viet-Anh Nguyen. "Counterfactual plans under Distributional Ambiguity." *ICLR*, 2022. [[.axiv]](https://arxiv.org/abs/2201.12487)
* **Hong-Ngoc Bui**, and Viet-Trung Tran. "A Novel Conditional Random Fields Aided Fuzzy Matching in Vietnamese Address Standardization." *SoICT*, 2019. [[.pdf]](/assets/pdf/ngocbh_soict_2019.pdf)

## Projects

* GeneticPython: A simple and friendly Python framework for genetic-based algorithms. [[.code]](https://github.com/ngocbh/geneticpython)
* SCOSS: A source code similarity system for competitive programming. [[.web]](http://scoss.soict.ai/) [[.code]](https://github.com/BK-SCOSS/scoss)
* Comnato: A command line interfaces (CLI) to manage Codeforces’ groups. [[.code]](https://github.com/ngocbh/codeforces-management-tools)

## Thesis

* A bachelors thesis at Hanoi University of Science and Technology. *A Deep Reinforcement Learning-based Online Charging Scheme for Target Coverage and Connectivity in WRSNs.* [[.pdf]](/assets/pdf/ngocbh_thesis__en_.pdf) [[.slide]](/assets/pdf/ngocbh_thesis_slides.pdf) [[.code]](https://github.com/ngocbh/odmc-wrsn)

## Awards and honors

* Best Thesis Presentation Award, *2021*.
* Problem Winner in ASEAN-India Hackathon, *2021*.
* The Third prize in ACM/ICPC Asia - Ho Chi
Minh Regional, *2017*.
* The Third Prize in Vietnam Olympiad in Informatics, *2016*.

<h2 id='contact'>Contacts</h2>

* Email: ngocbh.pt (at) gmail (dot) com
* Github: [ngocbh](https://github.com/ngocbh)

## Supervisors

* [Dr. Viet-Anh Nguyen](https://vietanhnguyen.net/)
* [Assoc. Prof. Thuan Do Phan](https://scholar.google.com.vn/citations?user=7Bpp8U0AAAAJ&hl=en) 
* [Dr. Phi Le Nguyen](https://scholar.google.co.jp/citations?user=L_NKoQwAAAAJ&hl=en)
* [Assoc. Prof. Huynh Thi Thanh Binh](https://scholar.google.com/citations?user=vJYe5lkAAAAJ&hl=en)
* [Dr. Viet-Trung Tran](https://scholar.google.com/citations?user=wYWRXQ0AAAAJ&hl=en)

## Collaborators

* Duy Nguyen *at VinAI*
* Tam Nguyen *at HUST*

## Mascot

This is Cosenkid (an unbeatable combination of **Co**nan, Hei**sen**berg, and Kaito **Kid**).

<img src="{{ '/assets/images/cosenkid.jpg' | relative_url }}" width="200" height="200" alt="Paris" style='display: block;margin-left: auto;margin-right: auto;'/>

