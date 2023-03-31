---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
layout: archive
redirect_from: 
  - /about
---

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

* Sep. 2019 - Jan. 2023: Research Assistant Professor
  * Department of Computer Science and Techology
  * Southern University of Science and Technology

* July. 2018 - Sep. 2019: Associate Researcher
  * Cixi Institute of Biomedical Engineering
  * Ningbo Institute of Materials Techology & Engineering, CAS

* Apr. 2016 - Jun. 2018: Pos-doctor
  * School of Biomedical Engineering
  * Shanghai Jiao Tong University
  
Publications(recent three years)
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

Academic Services
======
* Reviewer of MICCAI, BMVC, BIBM, IJCAI, ICPR, ICRA, OMIA, AECAI and so on
* Reviewer of Transactions on Computational Imaging, Artificial Intelligence in Medicine, Cybernetics and Systems, Expert Systems with Applications, Imaging Science Journal, Information Fusion, Scientific Report and so on
* International Technical Committee, 2023 8th International Conference on Communication, Image and Signal Processing (CCISP 2023)
* Program Committee Member, the 30th International Joint Conference on Artificial Intelligence (IJCAI 2021)

