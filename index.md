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
    <li>{{new.date | date: "%b %Y" }}: {{new.content | markdownify | remove: '<p>' | remove: '</p>' }}</li>
{% endfor %}
</ul>

<!-- ## Biography -->

<!-- I am currently a second-year Ph.D. student in Computer Science at Yale University, advised by Prof. Rex Ying. Prior to Yale, I spent two wonderful years as a research resident at VinAI Research under the supervision of Prof. Viet Anh Nguyen. Before that, I earned a bachelor’s degree in Computer Science and a master’s degree in Data Science from Hanoi University of Science and Technology. -->

<!-- My research interests broadly include large language models (LLMs) and their applications, such as personalized assistants and synthetic data generation through simulations. I am also very interested in developing effective memory paradigms that enable LLMs to store and continually update their knowledge, which I believe is crucial for creating personalized and (multi-) agentic systems. -->

<!-- ## Selected Publications -->
<!-- <!-- #### Conferences --> -->
<!-- * **Ngoc Bui**, Duy Nguyen, Man-Chung Yue, and Viet Anh Nguyen. "Coverage-Validity-Aware Algorithmic Recourse", Accepted manuscript at *Operations Research (OPRE)* journal, 2024. [[paper]](https://arxiv.org/abs/2311.11349) [[code]](https://github.com/ngocbh/cvas) -->
<!-- * **Ngoc Bui**, Hieu Trung Nguyen, Viet Anh Nguyen, Rex Ying. "Explaining Graph Neural Networks via Structure-aware Interaction Index", *ICML*, 2024. [[paper]](https://arxiv.org/abs/2405.14352) [[code]](https://github.com/ngocbh/MAGE) -->
<!-- * Duy Nguyen, **Ngoc Bui**, and Viet Anh Nguyen. "Distributionally Robust Recourse Action", *ICLR*, 2023. [[paper]](https://arxiv.org/abs/2302.11211) -->
<!-- * Tuan-Duy H. Nguyen, **Ngoc Bui**, Duy Nguyen, Man-Chung Yue, Viet Anh Nguyen. "Robust Bayesian Recourse", *UAI*, 2022. [[paper]](https://arxiv.org/pdf/2206.10833.pdf) -->
<!-- * **Ngoc Bui**, Duy Nguyen, Viet Anh Nguyen. "Counterfactual plans under Distributional Ambiguity", *ICLR*, 2022. [[paper]](https://arxiv.org/abs/2201.12487) [[code]](https://github.com/ngocbh/COPA) -->

<!-- * **Ngoc Bui**, Phi Le Nguyen, Viet Anh Nguyen, Phan Thuan Do. "A Deep Reinforcement Learning-based Adaptive Charging Policy for Wireless Rechargeable Sensor Networks", IEEE *MASS*, 2022. [[paper]](https://arxiv.org/abs/2208.07824) [[code]](https://github.com/ngocbh/DRL-TCC) -->
<!-- * **Ngoc Bui**, and Viet-Trung Tran. "A Novel Conditional Random Fields Aided Fuzzy Matching in Vietnamese Address Standardization." *SoICT*, 2019. [[paper]](/assets/pdf/soict19.pdf) [[code]](https://github.com/ngocbh/stavia) -->

<!-- * **Ngoc Bui**, Tam Nguyen, Binh Huynh Thi Thanh, and Trong Vinh Le. "A phenotype-based multiobjective evolutionary algorithm for maximizing lifetime in wireless sensor networks with bounded hop", *Soft Computing*, 2023. [[paper]](/assets/pdf/softcomp23.pdf) [[code]](https://github.com/ngocbh/nebp_wsn) -->

<!-- ## Projects -->

<!-- * GeneticPython: A simple and friendly Python framework for genetic-based algorithms. [[pypi]](https://pypi.org/project/geneticpython/) -->
<!-- * SCOSS: A source code similarity system for competitive programming. [[pypi]](https://github.com/BK-SCOSS/scoss) -->
<!-- * Comnato: A command line interfaces (CLI) to manage Codeforces’ groups. [[pypi]](https://pypi.org/project/conmato/) -->

<!-- ## Thesis -->

<!-- *  Master's thesis. "Evolutionary and Deep Reinforcement Learning Algorithms for Optimizing the Lifetime of Wireless Sensor Networks". [[paper]](/assets/pdf/ms_thesis.pdf) [[slides]](/assets/pdf/ms_slides.pdf) -->

<!-- ## Awards and honors -->

<!-- * Honorable Mention in INFORMS Undergraduate Operations Research Prize, *2022*. -->
<!-- * Best Thesis Presentation Award, *2021*. -->
<!-- * Problem Winner in ASEAN-India Hackathon, *2021*. -->
<!-- * The Third Prize in Vietnam Olympiad in Informatics, *2016*. -->
<!-- * The Third prize in Asia HCMC Vietnam National Programming Contest, *2017*. -->


<h2 id='contact'>Contacts</h2>

* Email: ngocbh.pt (at) gmail (dot) com
* Github: [ngocbh](https://github.com/ngocbh)

<!-- ## References  -->
<!-- * [Prof. Rex Ying](https://www.cs.yale.edu/homes/ying-rex/) -->
<!-- * [Prof. Viet-Anh Nguyen](https://vietanhnguyen.net/) -->
<!-- * [Assoc. Prof. Thuan Do Phan](https://scholar.google.com.vn/citations?user=7Bpp8U0AAAAJ&hl=en)  -->
<!-- * [Dr. Phi Le Nguyen](https://scholar.google.co.jp/citations?user=L_NKoQwAAAAJ&hl=en) -->

<!-- * [Assoc. Prof. Huynh Thi Thanh Binh](https://scholar.google.com/citations?user=vJYe5lkAAAAJ&hl=en) -->
<!-- * [Dr. Viet-Trung Tran](https://scholar.google.com/citations?user=wYWRXQ0AAAAJ&hl=en) -->

<!-- ## Collaborators -->

<!-- * Duy Nguyen *at VinAI* -->
<!-- * Tam Nguyen *at HUST* -->

<img src="{{ '/assets/images/cosenkid.png' | relative_url }}" width="20" height="20" alt="Paris" style='display: block;margin-left: auto;margin-right: auto;'/>

