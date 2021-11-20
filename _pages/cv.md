---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Research Interest
======
VLSI design and computer architecture for AI/ML applications or digital signal processing

Education
======
* M.S. in Electronics Engineering, National Taiwan University (NTU), 09/2019 - now
  * Thesis: An Energy-Efficient Deep-Neural-Network Processor Supporting Sparsity Scaling for On-Device Training
  * Advisor: Prof. Chia-Hsiang Yang
  * Cumulative GPA: 4.23/4.30
* B.S. in Electrical Engineering, National Taiwan University (NTU), 09/2015 - 06/2019
  * Cumulative GPA: 4.26/4.30 (Rank: **2**/190)

HONORS & AWARDS
======
* Bronze Medal Award, Macronix Golden Silicon Award (200+ teams), 2021
* Novatek Scholarship (Given to about 20 EECS students in the nation), 2020
* Garmin Scholarship (Given to about 10 EECS students in the nation), 2019
* Presidential Award, 5 times, National Taiwan University (Ranked top 5%), 2016 - 2019
* 1st Place, Undergraduate Innovation Award Contest, NTU, 2019
* 1st Place, National Integrated Circuit Design Contest, Ministry of Education, Taiwan (100+ teams), 2019
* E.SUN Bank Enterprise Award, MAKENTU Hackathon (40+ teams), 2018
* 1st Place, NTU System App Creativity Contest, NTU, 2017

Publications
======
* P.-S. Chen, Y.-L. Chen, Y.-C. Lee, **Z.-S. Fu**, and C.-H. Yang, "A 28.8mW Accelerator IC for Dark Channel Prior Based Blind Image Deblurring," IEEE Asian Solid-State Circuits Conference (A-SSCC), Nov. 2021.
* **Z.-S. Fu** and L. Su, "Hierarchical Classification Networks for Singing Voice Segmentation and Transcription," International Society for Music Information Retrieval Conference (ISMIR), Nov. 2019.

Research/Work Experience
======
* **Graduate Student Researcher**, Digital Circuits and Systems Lab, NTU, Taipei, Taiwan, 07/2019 - now
  * __Advisor: Prof. Chia-Hsiang Yang__
  * Designed an energy-efficient processor for sparse NN training (in collaboration with Qualcomm)
    * Carried out complete ASIC design flow, including algorithm design, chip tape-out, and chip measurement
    * The proposed design outperforms the state-of-the-art work by 3.7$\times$ improvement in energy-efficiency
  * Evaluated the energy and area of 3D circuits for AI applications (in collaboration with TSMC)
  * Developed an accelerator for DNN inference (in collaboration with Digwise)
  * Participated in the image deblurring IC project
  * Developed an in-house tool to make SoC designs utilizing picorv/Cortex-M3 easier
    * The tool supports generation of bus RTL files and header files from a system-describing JSON file
    * The tool chains C code compilation to RTL simulation of user’s testcases
* **Intern**, MemryX Incorporation, Taipei, Taiwan, 12/2019 - 08/2021
  * Developed a memory access optimization methodology for CNN computation
  * Designed peripheral controllers (including efuse, QSPI flash) for SoC integration of the new version product
* **Undergraduate Student Researcher**, Digital Circuits and Systems Lab, NTU, Taipei, Taiwan, 08/2018 - 06/2019
  * __Advisor: Prof. Chia-Hsiang Yang__
  * Conducted an in-house toolchain for mapping deep learning models to a designed processor
  * Designed a dedicated processor (RTL to P&R), a model mapping algorithm, and an user interface
* **Intern**, Genesys Logic Incorporation, Taipei, Taiwan, 02/2019 - 06/2019
  * Developed a compact NN model for multiple object detection on an in-house dataset
* **Research Assistant**, Institute of Information Science, Academia Sinica, Taipei, Taiwan, 03/2018 - 06/2019
  * __Advisor: Dr. Li Su__
  * Developed a neural network for automatic music segmentation and transcription
  * The proposed model outperforms all previous methods in transcription by 7.4% in terms of the F1-measure

Teaching Experience
======
* Teaching Assistant, Graduate Institute of Electronics Engineering, NTU, 09/2020 - 02/2021
  * Graduate-level Computer-aided VLSI System Design
  * Designed labs, homework, exams, and tutorials about VLSI design flow for 100+ students

* Teaching Assistant, Department of Electrical Engineering, NTU, 09/2018 - 02/2019
  * Undergraduate-level Digital Circuit Design Lab
  * Assisted 30+ students with their coursework about digital circuit design on FPGA platforms

Skills
======
* Programming Languages: Verilog, C/C++, Python, Matlab, Latex
* ML Frameworks: PyTorch, Tensorflow
* Cell-based ASIC Design: NC-Verilog, Verdi/nWave, Design Compiler, Innovus, Calibre DRC/LVS
* Chip Measurement: ADVANTEST V93000

<!--
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams

-->