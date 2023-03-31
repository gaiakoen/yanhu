---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
layout: archive
redirect_from: 
  - /about
---

I received my BSc and MSc degrees in Department of Computer from Northeast Normal University, China. I received my PhD degree in Graduate School of Information Science and Techology, The University of Tokyo, Japan. After that, I worked as a posdoctoral fellow at Shanghai Jiaotong University. I am currently a research associate professor in Department of Computer Science and Techology at Southern University of Science and Techology, China.

Reseach Interest
======
My main research interests are computer-aided surgery based on machine learning and deep learning algorithms. Currently, I am working on
* medical image processing aided for diagnosis and surgery, such as image registration, segmentation, 3d reconstruction
* surgery video processing aided for operation and evaluation, such as instrument segmentation and tracking, action localization
* image processing aided for treatment analysis

<font color="Red">Openings: We are opening to MSc and PhD students, research assistant working on those topics who are good at coding and/or math.</font>

Education
======
* PhD  in Graduate School of Information Science and Technology, The University of Tokyo, 2013/04-2016/03
* M.S. in Department of Computer, Northeast Normal University, 2008/09-2011/07
* B.S. in Department of Computer, Northeast Normal University, 2004/09-2008/07


Work experience
======
* Feb. 2023 - now: Research Associate Professor
  * Department of Computer Science and Techology
  * Southern University of Science and Technology
  * Team leader: Prof. Jiang Liu

* Sep. 2019 - Jan. 2023: Research Assistant Professor
  * Department of Computer Science and Techology
  * Southern University of Science and Technology
  * Team leader: Prof. Jiang Liu

* July. 2018 - Sep. 2019: Associate Researcher
  * Cixi Institute of Biomedical Engineering
  * Ningbo Institute of Materials Techology & Engineering, CAS
  * Team leader: Prof. Jiang Liu

* Apr. 2016 - Jun. 2018: Posdoctoral Fellow
  * School of Biomedical Engineering
  * Shanghai Jiao Tong University
  * Team leader: Prof. Zhifeng Shao
  
Publications(Recent three years)
======
  {% assign pubs = site.publications | where_exp: "item", "item.year > 2020" | group_by: "year" | reverse %}
{% for pub in pubs %}
  {% assign posts = pub.items %}
  <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ pub.name }}</h2>
  <ul>
  {% for post in posts %}
    <li>{{ post.citation }}</li>
  {% endfor %}
  </ul>
{% endfor %}
  
Projects
======
{% include projects.html %}

Honors & Awards
======
* 2021, MICCAI Challenge First
* 2016-2018, funded by "Post-doctoral International Exchange Program"
* 2012-2016, awarded Japan Government (MONBUKAGAKUSHO) MEXT Scholarship
* 2010, Excellent Student Cadre from Northeast Normal University
* 2008-2011, Government Scholarship from Northeast Normal University
* 2008, North Normal Decoration from Northeast Normal University
* 2007, selected as one of "Ideals and Talent Cultivation"
* 2004-2008, Awarded scholarship during undergraduate

Academic Services
======
* Reviewer of MICCAI, BMVC, BIBM, IJCAI, ICPR, ICRA, OMIA, AECAI and so on
* Reviewer of Transactions on Computational Imaging, Artificial Intelligence in Medicine, Cybernetics and Systems, Expert Systems with Applications, Imaging Science Journal, Information Fusion, Scientific Report and so on
* International Technical Committee, 2023 8th International Conference on Communication, Image and Signal Processing (CCISP 2023)
* Program Committee Member, the 30th International Joint Conference on Artificial Intelligence (IJCAI 2021)

