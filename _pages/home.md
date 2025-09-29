---
layout: default
title: "Home"
permalink: /
author_profile: true
classes: wide
---

## About Me

Anja Sheppard is a PhD Candidate at the University of Michigan, where she works under Dr. Katherine Skinner in the Field Robotics Group. Her research focus is primarly in perception for robots in extreme environments. She is particularly interested about the use of robotics for science, such as rovers searching for water on the Moon or underwater vehicles surveying for undiscovered shipwrecks. Anja is a National Science Foundation Graduate Research Fellow and a Draper Scholar. She previously collaborated with NASA's Johnson Space Center on dense 3D reconstruction for humanoid robots and with NASA's Jet Propulsion Laboratory on the Mars 2020 Science Operations team. She earned her B.S. in Computer Science from the University of Texas at Dallas in 2022.


## News

| --- | --- |
| September 2025 | With other members of the Field Robotics Group, Anja leads a tutorial on [ShipwreckFinder](https://sites.google.com/umich.edu/oceans2025-tutorial/overview), a new open-source tool for shipwreck detection from bathymetric data. She also presents the full [paper](https://arxiv.org/abs/2509.21386) during the technical track.
| June 2025 | At RSS, Anja presents at the [Space Robotics Workshop](https://albee.github.io/space-robotics-rss/) on her preliminary work with probabilistic terrain mapping for lunar hazard detection. |
| May 2025 | Anja presents [Field Report on Ground Penetrating Radar for Localization at the Mars Desert Research Station](https://arxiv.org/pdf/2504.15455) at the ICRA Workshop on Field Robotics. |
| September 2024 | Anja presents at the [AUV 2024 Symposium](https://auv2024.sites.northeastern.edu/) in Boston, MA on the [AI4Shipwrecks](https://umfieldrobotics.github.io/ai4shipwrecks/) dataset. |
| June 2024  | Anja represents the Field Robotics Group at CVPR, where she presents her paper "[Learning Surface Terrain Classifications from Ground Penetrating Radar](https://openaccess.thecvf.com/content/CVPR2024W/PBVS/html/Sheppard_Learning_Surface_Terrain_Classifications_from_Ground_Penetrating_Radar_CVPRW_2024_paper.html)" at the Perception Beyond the Visible Spectrum workshop. |
| May 2024 | Anja is awarded a fellowship with the [Draper Scholars](https://www.draper.com/careers/scholar-program) program. |
| February 2024 | The Field Robotics Group is interviewed by the University of Michigan Library [blog](https://blogs.lib.umich.edu/bits-and-pieces/machine-learning-and-shipwrecks-interview-field-robotics-group). |
| January 2024 | Anja conducts field work in Utah at the [Mars Desert Research Station](https://news.mit.edu/2024/life-on-mars-together-0313) in collaboration with Duquesne University, Boston University, and MIT. |
| December 2023 | Anja advances to candidacy! |
| June 2023 | The Field Robotics Group conducts fieldwork on Lake Huron to test a [shipwreck detection network](https://www.youtube.com/watch?v=UtNK1Ite8no&t=1s). |


<h2 class="mt-4">Publications</h2>
{% assign publications = site.publications | sort: "year" | reverse %}
{% for pub in publications %}
<div class="pubitem">
  <div class="pubteaser">
    <a href="{{ pub.project_url }}">
      <img src="/images/{{ pub.slug }}_small.png" alt="{{ pub.slug }} publication teaser"/>
    </a>
  </div>
  <div class="pubdetails">
    <div class="pubtitle">{{ pub.title }}</div>
    <div class="pubauthors">{{ pub.authors }}</div>
    <div class="pubinfo">{{ pub.publication }}, {{ pub.year }}</div>
    <div class="publinks">
      {% if pub.pdf %}
      <a href="{{ pub.pdf }}"><i class="far fa-file-pdf"></i> PDF</a>&nbsp;&nbsp;
      {% endif %}
      {% if pub.project_url %}
      <a href="{{ pub.project_url }}"><i class="fas fa-arrow-right"></i> Project Page</a>
      {% endif %}
    </div>
  </div>
</div>
{% endfor %}


## Service

- Space Generation Advisory Council [Space Policy Task Force](https://spacegeneration.org/ncac-task-force)
- University of Michigan [Robotics Graduate Student Council President](https://robotics.umich.edu/academics/current-students/robotics-graduate-student-council/)
- International Astronautical Congress [Workforce Development/Young Professionals Programme Administrative Committee](https://www.iafastro.org/about/iaf-committees/administrative-committees/workforce-development-young-professionals-programme-committee-wd-ypp.html)
