## Welcome to Matthew Sutton's IA Portfolio

Here I have accumulated a few papers and projects from my university coursework.  Project files can be found in the folders above. A description of each project is included further down in this README.  Specifically, the papers I have included are:

* Amazon Echo Dot v2 Penetration Test Final Summary
  * View the [Full Project GitHub Repo](https://github.com/jhautry/echo-dot) for in-depth analysis
* Research and Test-bed Demonstration of the ZeuS Trojan Horse
* USAF Tongue and Quill Staff Study Regarding Apple Product Tagged Image File Format CVE
* An Introduction to Public-Key Cryptography Semester Paper (located in the Advanced Writing folder)

## Project/Paper Details

### IA Capstone Project - Echo Dot v2 Penetration Test
#### Products:

[Full Project GitHub Repo](https://github.com/jhautry/echo-dot)

[Final Project Summary Document](https://github.com/nfiniteecho/Matthew-Sutton-Portfolio/blob/master/PDFs/IA%20Capstone%20Project%20-%20Amazon%20Echo%20Dot%20v2%20Penetration%20Testing%20Final%20Summary.pdf)

#### Details:

The Certification and Accreditation capstone course at the University of Nebraska at Omaha is the final course for IA students.   We were tasked to "extend and apply undergraduate knowledge towards defining, implementing, and assessing secured information systems." Additionally, we were required to "demonstrate the ability to specify, apply, and assess different types of countermeasures at different points in a system or enterprise."  The course content can be viewed [here](https://github.com/MLHale/CYBR4580) on GitHub.  

Overall, a major group effort was executed to reverse engineer the inner workings of the Echo Dot v2.  Our team created visual diagrams and wrote new documentation about the device.  Per course requirements, we created five "user stories" applying to general user function and determined what could be done to exploit each user story.   After exploitations, we wrote user story realizations regarding the outcome of our penetration tests. 

The project went through three milestones with the following grading points:
* [Milestone 1](https://github.com/MLHale/CYBR4580/blob/master/projects/milestone1.md): Executive Project Summary, Project Timeline, Project-oriented Risk List, Application Requirements, Resources/Technology Needed, and First Sprint Plan
* [Milestone 2](https://github.com/MLHale/CYBR4580/blob/master/projects/milestone2.md): Architectural Diagrams, Beginning Activity Diagrams, Beginning User Story Realizations, Milestone 3 Planning, and Presentation
* [Milestone 3 (Final)](https://github.com/MLHale/CYBR4580/blob/master/projects/milestone3.md): Final Activity Diagrams, Final User Story Realizations, Packaging and Release, and Presentation

These grading points are displayed in GitHub repo.  The Final summary document was created for the "Packaging and Release" grading point.

--- 

### IA Fundamentals Project - Research and Test-bed Demonstration of the ZeuS Trojan Horse
#### Product:

[Full Project Paper](https://github.com/nfiniteecho/Matthew-Sutton-Portfolio/blob/master/PDFs/IA%20Fundamentals%20Project%20-%20Research%20and%20Test-bed%20Demonstration%20of%20the%20ZeuS%20Trojan%20Horse.pdf)

#### Details:

The IA Fundamentals project had four separate tracks for students to take.  I chose my own custom project to download and test the ZeuS Trojan Horse.  ZeuS is one of the most notorious pieces of banking malware that was responsible for millions of dollars in stolen money using a global network of money mules. In 2011, the source code for the ZeuS malware was leaked online.  I found it on GitHub and went to work compiling and testing it.  

This project outlines my compilation of the source code and an in-depth examination of bot functionality in an air gapped test environment.  I researched ZeuS' capabilities and underlying infection operations.  A fake custom bank website was created to show ZeuS' keylogging abilities, HTML injection abilities via man-in-the-browser attacks, and screenshotting abilities to bypass clickable PIN authentication interfaces. 

---

### Advanced Composition Semester Paper - An Introduction to Public-Key Cryptography
#### Product:

[Semester Paper](https://github.com/nfiniteecho/Matthew-Sutton-Portfolio/raw/master/Advanced%20Writing%20Coursework/Technical%20Writing%20Semester%20Paper%20-%20An%20Introduction%20to%20Public-Key%20Cryptography.pdf)

[Additional Coursework](https://github.com/nfiniteecho/Matthew-Sutton-Portfolio/tree/master/Advanced%20Writing%20Coursework)

##### Details:

This course required one advanced technical paper to be constructed over the course of an entire semester.  I chose my topic to be public-key cryptography because this topic is a fundamental concept for all IA professionals to comprehend. Over the semester we were required to complete five assignments all compounding upon one-another:
1. Write a memo describing the subject of my paper including research strategy and preliminary research
2. Write a proposal for the report including a cover letter
3. Submit a draft and style sheet for report including a cover letter explaining more progress
4. In-class presentation with narrated PowerPoint and a separate detailed outline of the presentation
5. Submit final report with included transmittal letter

The final report covers the following main topics to build an encompassing explanation of public-key cryptography for a lay audience:
* Cryptography Fundamentals
* Secret-Key Cryptography
* Public-Key Cryptography
* RSA Key-Exchange

---

### Computer Security Management - Staff Study

#### Product:

[Staff Study](https://github.com/nfiniteecho/Matthew-Sutton-Portfolio/blob/master/PDFs/Computer%20Security%20Management%20Semester%20Project%20-%20Staff%20Study.pdf)

#### Details:

The Semester Project was to write a staff study over one of three instructor selected Common Vulnerabilities and Exposures (CVE).  The staff study was required to be formatted using [*The Tongue and Quill*](http://static.e-publishing.af.mil/production/1/saf_cio_a6/publication/afh33-337/afh33-337.pdf) Air Force communication resource.  I chose to write my Staff Study on [CVE-2016-4631](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2016-4631) which allows remote attackers to execute arbitrary code or cause a denial of service (memory corruption) via a crafted Tagged Image File Format file.  The staff study is designed to be a three-tiered study.  The top level is written to analyze a problem, draw conclusions, and make recommendations at the management level.  The second level is written as a technical analysis for middle level support.  The third level is a deep technical analysis for technical support.

