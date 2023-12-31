<h1 align="center">
Balancing iSSR and iSTR for information security 💻🔐👨🏻‍💻
</h1> 

### Supporting materials used in our experiment. Note that a more detailed description of the research methodology and approach is included in the research paper. This repository contains only the supporting materials used in our experiment's main task (iSSR and iSTR solution).

The research is published in Computers & Security journal (ISSN 1872-6208). Please check open access paper here for more informations: **[Computers & Security](https://www.sciencedirect.com/science/article/pii/S0167404823003772)**. 

The repository consists of the following files/folders:

### [Readme](README.md) file 📜
Basic informations about the repository. Here, the materials that the participants used in the experiment's main task are described.

### [Materials](Materials) folder 📁

The folder contains materials related to the implementation of the experiment's main task (iSSR and iSTR prioritization). Here you can find the following:

- **[Informed_consent.pdf](Materials/Informed_consent.pdf)** -> informations to the participants in the experiment. This document contains basic information about the experiment (basic research information such as duration, conditions of participation, ethical approval reference number, etc.).
  
- **[Scenario.pdf](Materials/Scenario.pdf)** -> the scenario in which participants made their decisions. The scenario includes the problem domain and a description of the research process. In this way, the participants in the experiment knew what they had to do or what role they should take. The problem domain referred to "University X", which wanted to set up a new student information system. Note that only one scenario/problem domain is given. Regardless of whether the participants in the experiment belonged to the control or experimental group, they all worked according to this scenario.
  
- **[data_c_en.pdf](Materials/data_c_en.pdf)** -> data received by the control group (the reader should note that this document does not contain a mapping tool. The mapping tool represents an independent variable).
  
- **[data_t_en.pdf](Materials/data_t_en.pdf)** -> data received by the experimental group (does include the mapping tool).
  
- **Dictionary** -> dictionary includes explanations about the terms and concepts used in the research for easier understanding of information security functionalities (e.g., replay attack, OAuth, deserialization, ...). The purpose of the dictionary is to ensure a uniform understanding of the terminology (i.e., that the participants in the experiment are not familiar with the terminology used and that they do not have to search the internet for explanations).
  - **[dictionarypart1.pdf](Materials/dictionarypart1.pdf)** -> part 1 of the dictionary. 
  - **[dictionarypart2.pdf](Materials/dictionarypart2.pdf)** -> part 2 of the dictionary.
    
- **Templates** -> in this template, the participants of the experiment entered their decisions. For each decision, they had the opportunity to explain why they made that decision ("rationale column").
  - **[iSSR_template.pdf](Materials/iSSR_template.pdf)** -> template in which participants entered their iSSR decisions using the MoSCoW method. Only a limited number of security functionalities can be implemented:
    - Maximum 2 functionalities will be implemented for sure (must-be).
    - Maximum 2 functionalities will be very likely implemented (should-be).
    - Maximum 2 functionalities will be maybe implemented (could).
  - **[iSTR_template.pdf](Materials/iSTR_template.pdf)** -> template in which participants entered their iSTR decisions. Each training focuses on a single focus area (e.g., password management, email use, ...). An individual user can be sent to several trainings. There is room for a maximum of 50 users in all trainings together. For example: 10 users sent to Password management and Information handling training (2×10) and 30 users sent only to the first training (1×30) means that all the places are filled for training (2×10 + 1×30 = 50).

**Note**: Both the experimental group (also referred to as the treatment group in the literature) and the control group all received the same documents, except for the data (more precisely; **data_c_en. PDF OR data_t_en.PDF**). Data_t_en.PDF contains a mapping tool, while data_c_en-PDF does not. 

**Where to find the results in the article?**
Figure 7 in the paper shows the difference between the experimental and control groups in the experiment. It is the main result of the main task. The main task (iSSR and iSTR solution) was evaluated by evaluators. For a more detailed description of the methodology, see the original article (link above and source below [inside the green circle]).

**SOURCE:** <br />
BibTeX: <br />

@article{Fujs2023,<br />
  title = {Balancing software and training requirements for information security},<br />
  journal = {Computers & Security},<br />
  pages = {103467},<br />
  year = {2023},<br />
  issn = {0167-4048},<br />
  doi = {https://doi.org/10.1016/j.cose.2023.103467},<br />
  url = {https://www.sciencedirect.com/science/article/pii/S0167404823003772},<br />
  author = {Damjan Fujs and Simon Vrhovec and Damjan Vavpotič}<br />

APA: <br />

Fujs, D., Vrhovec, S., & Vavpotič, D. (2023). Balancing software and training requirements for information security. Computers & Security, 103467.
