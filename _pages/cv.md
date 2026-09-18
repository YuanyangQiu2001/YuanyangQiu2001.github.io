---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
[Download CV (PDF)](/files/Yuanyang_Qiu_CV_EN_20260918.pdf) · [下载中文简历 (PDF)](/files/Yuanyang_Qiu_CV_ZH_20260918.pdf)

Education
======

**Degree Program**

* **China University of Political Science and Law**, 2024.09 – 2027.07 (Expected)
  * Master of Law (Research Oriented), College of Comparative Law — GPA: 89.63/100
  * Coursework: Comparative Personal Data Law (94); Theory and Practice of Data Law (96); AI Intellectual Property Law (93)
  * Thesis: [The Comparative Study of the "Offense Doctrine" in U.S. Tort Law](/research/offense-doctrine/) (working)

* **China University of Political Science and Law**, 2020.09 – 2024.07
  * Bachelor of Law, Civil, Commercial and Economic Law School — GPA: 87.57/100 (Top 20%)
  * Thesis: [On the Application of the Preamble of the Chinese Constitution: Comparative Experience and Promotion Path](/publication/2024-01-01-constitution-preamble)

**Non-Degree Program**

* **Fordham University**, 2026.01 – 2026.05
  * Exchange, School of Law
  * Coursework: Information Law Survey; Information Privacy Law; AI, Cybersecurity and Legal Technology
  * Independent Study: [Stealing Prometheus's Fire: A Multi-Modality Framework for Regulating AI Knowledge Distillation](/research/ai-distillation/)

* **University of Hongkong**, Summer Institute on Computing Social Science, 2026.06

* **WIPO-China (RUC)**, Summer School on Intellectual Property, 2026.07

Publications
======

**Published**

  <ul>{% for post in site.publications reversed %}{% unless post.status %}
    {% include archive-single-cv.html %}
  {% endunless %}{% endfor %}</ul>

**Accepted**

  <ul>{% for post in site.publications reversed %}{% if post.status == "Accepted" %}
    {% include archive-single-cv.html %}
  {% endif %}{% endfor %}</ul>

**Under Review**

  <ul>{% for post in site.publications reversed %}{% if post.status == "Under review" %}
    {% include archive-single-cv.html %}
  {% endif %}{% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Research experiences
======

* **Research Assistant**, Institute for Network Sciences and Cyberspace, Tsinghua University, 2026.05 – Present
  * *AI Deception Project(under review at CHI 2027).* Worked on a two-phase online behavioral experiment testing whether AI agents in group chats can exert social influence on human dishonesty. Contributed to the design of a die-roll misreporting paradigm in which each participant's true outcome was visible to the whole group, and of the factorial conditions: Phase 1 varied the type and direction of norms delivered by an AI; Phase 2 varied whether peers were presented as humans or AI agents and how many of them misreported.

* **Research Assistant**, Alibaba DAMO Academy, 2025.08 – 2026.01
  * *PLawBench Project (ACL 2026).* Built a benchmark grounded in how legal practitioners actually work, translating real workflows into three task families — public legal consultation, practical case analysis, and legal document generation — across 13 practice scenarios and 850 questions. Drafted the scoring rubrics from scratch so that answers are graded against concrete, checkable legal points rather than overall impression, producing roughly 12,500 rubric items. Ran the expert annotation side of the project: recruited and trained legally trained annotators, wrote the annotation guidelines, and adjudicated disagreements to keep scoring consistent across domains.

* **Research Assistant**, Institute for Studies on AI and Law, Tsinghua University, 2025.08 – 2026.01
  * *Policy Translation.* Compiled technology law newsletters synthesizing legislative and regulatory developments; translated national standard contractual clauses for cross-border data entrustment between Chinese and English.
  * *Comment Drafting.* Monitored guidance from the EU EDPB and UK ICO to track global data governance trends; authored a comprehensive research report on the EU "Digital Omnibus" reform agenda, analyzing its implications for digital market regulation and platform accountability.

Service experiences
======

* **Associate Chief Editor**, CUPL Law Review, 2025.05 – Present
  * *Publishing Management.* Oversee the full editorial cycle — soliciting manuscripts, coordinating double-blind peer review, editing, and production. Supervised the complete pipelines for 2025 Issue 2 and 2026 Issue 1, and serve as the journal's direct liaison with China Legal Publishing House from manuscript delivery through publication.
   * *Administrative Operations.* Lead the journal's digitalization reform — working with CNKI to maintain the online portal and to build a new submission and peer-review system and an editorial office management system — and run its external programming, including AI-assisted academic writing workshops for 50+ participants, the annual symposium, and exchanges with legal scholars and peer law reviews nationwide.

* **Teaching Assistant**, CUPL Summer School, 2023.06
  * Recorded student attendance and graded coursework assignments.

Skills
======

* Languages: English (Fluent), Mandarin (Native)
* Qualification: PRC Bar Certificate
* Tech: Claude Code
