# Lesson 5: From Theory to Practice

## Navigation
* [Overview](#overview)
* [Learning Objectives](#learning-objectives)
* [Open Science and Data Management Plans](#open-science-and-data-management-plans)
* [How Do We Plan for Making our Code Open?](#how-do-we-plan-for-making-our-code-open)
* [Engage and Build Communities](#engage-and-build-communities)
* [Contribute to Open-Source Software](#contribute-to-open-source-software)
* [Additional Resources](#additional-resources)
* [Lesson 5: Summary](#lesson-5-summary)
* [Lesson 5: Knowledge Check](#lesson-5-knowledge-check)
* [Open Code Summary](#open-code-summary)

## Overview

This final lesson will tie together open access software development with the operation of a software management plan (SMP). You'll be introduced to the community aspect of open software, beginning with a discussion on writing software management plans, then learning how to connect with open software communities. This will also be contextualized by the benefits of a software community and the roles involved in these groups. After being presented with a list of communities, you will be asked to explore and engage with some of them. Finally, this lesson will wrap up with additional resources and helpful suggestions for contributing to open software.

## Learning Objectives

After completing this lesson, you should be able to:

- Recall the definition of a software management plan, potentially as part of an Open Science and Data Management Plan (OSDMP), and where to find helpful resources.
- List ways to engage with and contribute to open software communities.

## Open Science and Data Management Plans

Many NASA solicitations require submission of an Open Science and Data Management Plan as part of the proposal package. NASA SMD's Open-Source Science Guidance states:

<img style="width: 100%; height: auto;" src="../images/media/codebg.jpg">

"A NASA Open Science and Data Management Plan (OSDMP) describes how the scientific information that will be produced from NASA-funded scientific activities will be managed and made openly available. The OSDMP should include sections on data management, software management, and publication sharing. (NASA Science Mission Directorate, 2025)" -NASA Science Mission Directorate, 2025

Image Credit: "Codes on Tilt Shift Lens" by Markus Spiske via [Pexels](https://www.pexels.com/photo/codes-on-tilt-shift-lens-2004161/) (external link)

---

Example sections to include in an OSDMP:

- Data Management Plan (DMP)
- Software Management Plan (SMP)
- Publication sharing
- Other open science activities
- Roles and responsibilities

#### Recall the steps for an SMP from the previous lessons

- **What:** Description of management, preservation, and release of code.
- **When:** The schedule for software/code archiving and sharing.
- **Where:** Location where software/code will be shared and archived over the long-term.
- **How:** Enable reuse of software/code through assigning a DOI, license, contribution guidelines, etc.
- **Who:** Roles and responsibilities of the team members.

<img style="width: 350px; height: auto;" src="../images/media/recallsteps.jpg">

## How Do We Plan for Making our Code Open?

### Should a Software or Data Management Plan be Written?

If you are planning a project that may require a software/data management plan, writing that plan is a great first step before beginning the project. However, there are several factors to consider before jumping right into a software/data management plan. “Software” here means scientifically or technically relevant computer programs as both source code and executable software. Below is a list of reasons why you should or shouldn't write an SMP:

|  |  |
|---|---|
| SMP is required | You need a SMP to: <ul><li>Propose for funding (e.g., NASA, NSF, and likely everywhere soon)</li><li>Collaborate on a team that intends to release software/code to the public</li><li>Successfully manage any large mission or project</li></ul> |
| SMP is not required | You probably don't need a SMP if you are working on: <ul><li>A paper by yourself (or with a very small group of collaborators)</li><li>The initial exploration of ideas or experimentation with analysis code</li><li>Education-focused activities</li></ul> |

Perhaps your project does not fit into these categories. For example, if your aim is for your results to be reproduced by others, then writing an SMP will be at your discretion.

The following material assumes that you have met the threshold and are writing a data/software management plan.

### Pen to Paper: Getting Started Writing a Plan

If you are applying for funding, it is almost guaranteed that there will be specific data management requirements detailed in the funding opportunity. For example, the funder may require a certain license or use of a specific repository. Make sure to cross-reference your plan with these requirements!

**Examples of Software Management Plans**

- [software.ac.uk/resources/guides/software-management-plans](https://www.software.ac.uk/resources/guides/software-management-plans) (external link)
- [esciencecenter.nl/national-guidelines-for-software-management-plans/](https://www.esciencecenter.nl/national-guidelines-for-software-management-plans/) (external link)
- [https://zenodo.org/record/7589725](https://zenodo.org/record/7589725) (external link)

**Requirements**

What are the Requirements for a SMP? (what does the funding agency or institution say to do?) 

- What data formats must be used?
- What are the software/code archival/preservation requirements?
- What roles and responsibilities are necessary to meet all requirements?

### Funding Agencies

Scientific funding agencies generally solicit peer reviews to support funding decisions. These reviews explicitly or implicitly evaluate related open software/code. Community participation is necessary to arrive at consensus regarding community standards for funding.

For example: The NASA Science Mission Directorate's (SMD) SPD-41a policy applies to all SMD-funded scientific activities and explicitly states that "funded software should follow best practices in the relevant open source and research communities." (NASA Science Mission Directorate, 2022)

### Established Open code Policies of Professional Societies

Professional societies such as AAAS, AGU, AAS, and more, influence funding agency policies and directly impact the policies surrounding software and code used to generate publications. It is important to engage with the community via consensus papers and professional societies in order to guide policy decisions regarding open source software in science.

Science/AAAS explicitly states: "In general, all computer code central to the findings being reported should be available to readers to ensure reproducibility."

### Institutions

The individual institutions we work with impose highly-variable restrictions on open source software due to security, privacy, intellectual property, commercial, or other concerns that do not necessarily align with the ethos of open science. It is important to engage with the institutional community to facilitate the movement toward policies that facilitate open source software as a foundation of open science.

### Activity 5.1: Writing an SMP

In this activity, review the SMP below and think about these questions as you read:

- What kinds of software/code does the SMP describe?
- When will the work be shared?
- Where will the work be shared?
- How will the work be shared so it is a citable artifact?
- Who will be responsible for different aspects of the software/code?
- What are some of the limitations of the software/code?
- How would lacking a plan impact code development years down the line?
- Are results reproducible without the original Interactive Data Language (IDL) code?
- Are there things in the example plan that you would add or be more specific about?

#### Example Software Management Plan

**1. Expected Software Types**

We will use established simulation models to conduct initial simulations for this work. These simulation models are written in Fortran and developed over the last decade. While not publicly available, they are available for the project to use (i.e.via private communication). The simulation models will lead to the generation of output files as described in the Data Management Plan (DMP). We will develop analysis software in Python to analyze the model output files, which will enable the development of derived data products, maps, and figures. Development of the Python analysis software will be shared on a GitHub repository.

**2. Development of Analysis Software**

All new development of Python code will be conducted openly on GitHub by members of this project. We will post and follow the established Code of Conduct for software development for our research project, which includes guidelines for contributions by additional members of the scientific community.

**3. Repositories and Timeline for Sharing Software**

This work will support the development of two peer-reviewed journal articles. All source code developed in Python to support each article will be archived on Zenodo no later than the article's publication date. The software will be made available under a permissive Apache License 2.0. Zenodo will assign a DOI to the archived software when it is archived.

**4. Software Sharing Exemptions**

This work does not support further development of the existing Fortran simulation models, which are maintained independently. We do not have permission to publicly share the Fortran source code for the simulation models.

**5. Roles and Responsibilities**

Initial simulation modeling and the development of Python analysis software will be completed by PhD students and postdocs. The Principle Investigator (PI) of this project holds overall responsibility for the execution of this plan.

## Engage and Build Communities

Open software communities are social learning spaces where individuals come together to learn a new skill, exchange knowledge and experiences, and then apply what they've learned from the community in their day-to-day work.

#### Communities offer:

- A low entry point for learning and improving your use of software in research.
- An opportunity to share individual experiences, identify common hurdles, and iteratively enhance knowledge and resolve problems.
- A way to build the collaboration around open source software in science and a great way to keep updated on the latest tools and practices.
- A non-hierarchical community of practice where all members of the open software community contribute.

### Connect with Communities

Here are some communities that can help you get started:

- [PyData](https://pydata.org/) (external link) 
- [SPEC](https://scientific-python.org/specs/) (external link)
- [rOpenSci](https://ropensci.org/) (external link)
- [pyOpenSci](https://www.pyopensci.org/) (external link)
- [PyHC](https://heliopython.org/) (external link)
- [Research Software Engineering](https://society-rse.org/) (external link)
- [NumFOCUS](https://numfocus.org/) (external link)
- [R-Ladies](https://rladies.org/) (external link)
- [PyLadies](https://pyladies.com/) (external link)
- [WoCCode](https://woccode.github.io/) (external link)
- [Pangeo](https://pangeo.io/) (external link)
- [ObsPy](https://discourse.obspy.org/) (external link)
- [The Turing Way](https://the-turing-way.netlify.app/collaboration/new-community.html) (external link)

Subscribe to and/or participate in forums (e.g. GitHub discussions, Stack Overflow, or discipline/software-specific), in-person workshops, conferences, and hackathons related to your discipline or software you contribute to. Connecting on social media is also a great way to participate in these communities. Last but not least, talk with your colleagues! They may be able to connect you to a larger community as well.

### Activity 5.2: Browse Through Some of the Communities of Practice

<img style="width:350px;height:auto;" src="../images/media/lightbulb.png">

- Find and browse through the websites associated with two communities of practice listed on the previous section, "Connect with Communities."
- Identify at least two points of entry for engagement, such as an upcoming event (virtual or in person), forums, etc.

#### Key takeaways: Browse through some of the communities of practice

- There are many opportunities to engage with communities working on open software.
- Engaging with open software communities can enrich and improve your software.

## Contribute to Open-Source Software

Contributing to open software provides many advantages and opens doors to a number of rewarding opportunities. There are few other industries that can boast the massive number of global contributions like the open source community can. Contributing to open source software is a great way to improve your coding skills and to document your work while growing your community.

There are several types of contributing to open software. Not all of them require writing actual code:

|  |  |
|---|---|
| **Add New Features** | The most obvious case for contributing to open software is enhancing its usability by adding new features. |
| **Fix Bugs** | Alternatively, you can reply to an already opened issue by fixing it. |
| **Report Issues and Make Suggestions About Improving Code** | Reporting an issue is a valuable contribution, even if you don't know how to fix it. For example, you might be using a different browser in which the software has not been tested yet, have discovered a particularly uninformative error message, or be unable to feed a valuable user experience back to the developers that can help to improve the overall usability of the software. |
| **Improving and Contributing to Documentation** | Contributing to documentation constitutes a great starting point for contributing to open source software and is often overlooked in its importance. Writing documentation allows you to familiarize yourself with the use of the software while helping to teach others. |
| **Create Tutorials, Use Cases, or Visuals** | Another way to contribute is to make your experience and use of the software publicly available. For example, you could create a tutorial based on your use of the software, summarize a use case, or provide a summary of your use in a graphic. This part of contribution is particularly appealing as it does not create much extra work to just publish what you have used the software for. |
| **Improve Layout, Automatization, Structure of Code** | Apart from creating new code, a good way to contribute to open source software can also be to improve, restructure, or automatize existing code. This is called refactoring and helps to make the software project more effective and stable. |
| **Organize and Attend a Community Meet-Up** | Another way to contribute to open source software is via community building. Many software products and toolboxes have a lively community of users that meet on a regular basis in person and online to discuss and improve the software and its use. Participating, or even organizing, such a meetup can be a good way to improve your knowledge of the software, get to know its community, and contribute to open-source projects. |
| **Code Review** | Requests to integrate new contributions into the main code base usually require a review of the contribution by at least one other user. Similar to peer review, code review entails writing a short summary about the quality of the code and making suggestions about improvements. |

## Additional Resources

### Disclaimer

Please note that we reference several papers throughout the course and, depending on the paper, it might be blocked by a paywall. If you would like to get a copy of the paper, please contact the author or search for it in an online preprint archive, such as [bioRxiv.org](http://biorxiv.org/) (external link).

### References and Guides

In addition to the resources listed elsewhere in this training, the below community resources are excellent sources of information about Open Software.

- [OpenSciency](https://zenodo.org/record/7662732) (external link)
- [NASA SMD's Open-Source Science Guidance](https://science.nasa.gov/science-red/s3fs-public/atoms/files/SMD%20Open-Source%20Science%20Guidance%20v1%2020221208.pdf)
- [Practical Guide to Software Management](https://zenodo.org/record/7589725) (external link)
- [FAIR Principles for Research Software (FAIR4RS Principles)](https://zenodo.org/record/6623556) (external link)
- [Open Source Software Policy Options for NASA Earth and Space Sciences](https://doi.org/10.17226/25217) (external link)
- [Turing Way handbook to reproducible, ethical and collaborative data science](https://the-turing-way.netlify.app/index.html) (external link)
- [Ten simple rules for documenting scientific software](https://doi.org/10.1371/journal.pcbi.1006561) (external link)
- [Journal of Open Source Software](https://joss.theoj.org/) (external link)

### Additional Training

In addition to the resources listed elsewhere in this training, the below resources represent additional training on open source software:

- [Software Carpentries](https://software-carpentry.org/lessons/) (external link)
- [How to contribute to Open Source projects – A beginners guide](https://www.freecodecamp.org/news/how-to-contribute-to-open-source-projects-beginners-guide/) (external link)

### A Journal with Thousands of Open-Source Research Software Success Stories

The [Journal of Open Source Software](https://joss.theoj.org/) (external link) has presented a venue for enhancing the quality and minimizing the effort of publishing open source research software:

- Peer-reviewed, open source "journal" covering open-source research software published via GitHub.
- The emphasis is on the software.
- Published thousands of open source research software projects, several of which are highly cited. JOSS is one of several journals. A list of many more journals that publish software can be found [here](https://www.software.ac.uk/which-journals-should-i-publish-my-software) (external link).

## Lesson 5: Summary

In this lesson, you learned:

- When an SMP should be written and that your funding organization or institution may have rules around how you develop and share your code.
- That joining software communities can be a great way to exchange knowledge and learn new skills around open code.
- That there are many ways to contribute to open code, and that not all of them require writing code.

## Lesson 5: Knowledge Check

Answer the following questions to test what you have learned so far.

*Question*

**01/02**

Read the statement and decide whether it's true or false:

*Engagement within open software communities is non-hierarchical; all members of the community should contribute.*

- True
- False

*Question*

**02/02**

Select the beneficial way(s) to contribute to open sources software.

- Add new features
- Fix bugs
- Document your work
- Refactoring
- All of the above

## Open Code Summary

Congratulations! Now you should be able to:

- Explain what open source software means, including the software development cycle, the benefits of open software, and some common limitations and how they are addressed.
- Discover open source software and assess it for reuse by evaluating provided documentation, including README files and licensing details; cite the software when appropriate.
- Create an open source software management plan that includes the strategy for selecting open software dependencies and open repositories such as GIT, and how open elements including metadata, README files, and version control will be included to make the software reusable and findable.
- Evaluate whether your open source software can be shared, as well as the best options for sharing to increase visibility.
- List the responsibilities a software developer has once the open source software is shared, including managing legal requirements and ensuring the software is maintained.

### References Cited

- NASA Science Mission Directorate. (2025). Open-Source Science Guidance. [https://assets.science.nasa.gov/content/dam/science/cds/open-science/SMD%20Open-Source%20Science%20Guidance%20v2.2%2020250205.pdf](https://assets.science.nasa.gov/content/dam/science/cds/open-science/SMD%20Open-Source%20Science%20Guidance%20v2.2%2020250205.pdf)
- NASA Science Mission Directorate. (2022). SMD Policy Document SPD-41a. [https://science.nasa.gov/wp-content/uploads/2023/08/smd-information-policy-spd-41a.pdf](https://science.nasa.gov/wp-content/uploads/2023/08/smd-information-policy-spd-41a.pdf)
