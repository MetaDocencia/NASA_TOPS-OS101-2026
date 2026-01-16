# Lesson 1: Introduction to Open Data

## Navigation
* [Overview](#overview)
* [Learning Objectives](#learning-objectives)
* [Introduction](#introduction)
* [Definition and Considerations of Open Data](#definition-and-considerations-of-open-data)
* [Benefits of Open Data](#benefits-of-open-data)
* [Challenges of Open Data](#challenges-of-open-data)
* [Applying FAIR Principles](#applying-fair-principles)
* [Planning for Openness: Using the Use, Make, Share Framework for Open Data](#planning-for-openness-using-the-use-make-share-framework-for-open-data)
* [Lesson 1: Summary](#lesson-1-summary)
* [Lesson 1: Knowledge Check](#lesson-1-knowledge-check)

## Overview

This lesson will define open data, its benefits, and the practices that enable data to be open and transparent. Open data is a crucial cornerstone of open science, and in the digital age it is even more important now to make data accessible and reproducible. Additionally, you will take a closer look at how Findable, Accessible, Interoperable, and Reusable (FAIR) Principles apply to open data, as well as at the critical role of metadata in the world of science. Finally, you will end with a brief introduction to planning for open data in the scientific workflow, including tasks guided by the "Use, Make, Share" framework.

## Learning Objectives

After completing this lesson, you should be able to:

- Define what open data is and how the FAIR Principles are used to guide open data practices.
- List the benefits of open data.
- Explain how the "Use, Make, Share" framework can be used to modify the scientific plan for open data.

## Introduction

Data drives science forward. Nowadays, data is stored electronically to enable further analysis and research. As a result, digital technologies integrated into every aspect of modern scientific research has led to the production of large amounts of data.

In many ways, open data is a natural expansion of open science beyond scholarly publications to include digital research outputs. It has since become an integral part of the open science movement as open data allows anyone to see, use, and verify published results. Open data makes science more accessible and reproducible. In order to support this, data needs to be made available in formats that others can use, and metadata that describes the data and helpful documentation should be provided. When made available, open data enables new discoveries and unforeseen uses!

### Example: How Will Humans Live on the Moon or Travel to Mars When the Space Environment Threatens Human Health in Multiple Ways?

Bone loss, vertigo, anemia, muscle atrophy, increased risk for cancer - these are just some of the human side effects of space travel. To study these human health risks of space travel, scientists around the world use NASA's open-source GeneLab platform. GeneLab aggregates large volumes of space biology data in the [Open Science Data Repository (OSDR)](https://www.nasa.gov/osdr/), which includes data on human and model organism samples exposed to spaceflight conditions. Their [digital](https://osdr.nasa.gov/bio/repo/search?q=&data_source=cgene,alsda&data_type=study) and physical repositories include cell info as well as DNA, RNA, and proteins. As an open-source platform, all data from GeneLab is publicly accessible at no cost.

<img src="../images/media/image2.jpeg" style="width:100%;height:auto;" />
Image credit: "Astronaut at spacewalk" by Vadimsadovski via [AdobeStock](https://stock.adobe.com/contributor/203529807/vadimsadovski?load_type=author&prev_url=detail&asset_id=132366202), Standard license (external link)

### Example

Using vast space-flown animal and human samples as well as astronaut biological data from GeneLab, a recent paper published in Nature found what may be the culprit behind many of the side effects from travel to space: mitochondrial stress. (Clyde, 2021)

Mitochondria are components within our cells that affect respiratory and energy function. This discovery could be crucial to overcoming human health-related problems in space. Understanding the source of this issue could help scientists develop countermeasures and therapies to keep people healthy in space for longer periods of time.

For additional information about the study of mitochondrial stress in the bodies of astronauts, watch [Living and Working in Space: Twins Study](https://www.youtube.com/watch?v=c9moR-KQpDQ) (external link) on NASA's YouTube channel.

## Definition and Considerations of Open Data

### What is Data?

<img src="../images/media/image3.jpeg" style="width:350px;height:auto;" />
The Turing Way Community. This illustration is created by Scriberia with The Turing Way community, used under a CC-BY 4.0 license. [DOI: 10.5281/zenodo.3332807](https://zenodo.org/records/3332808) (external link)

---

Data is any type of information that is collected, observed, or created in the context of research. Today, data is increasingly stored electronically in a digital format.

Data includes:

**Primary (raw) data** – Primary data refers to data that is directly collected or created by researchers. Research questions guide the collection of the data. Typically, a researcher will formulate a question, develop a methodology and start collecting the data. Some examples of primary data include:

- Responses to interviews, questionnaires, and surveys.
- Data acquired from recorded measurements, including remote sensing data.
- Data acquired from physical samples and specimens form the base of many studies.
- Data generated from models and simulations.

**Secondary & Processed data** – Secondary data typically refers to data that is used by someone different from who collected or generated the data. Often, this may include data that has been processed from its raw state to be more readily usable by others.

**Published data** – Published data is data shared to address a particular scientific study and/or for general use. While published data can overlap with primary and secondary data types, we have "published data" as its own category to emphasize that such datasets are ideally well-documented and easy to use.

**Metadata** – Metadata is a special type of data that describes other data or objects (i.e. samples). It is often used to provide a standard set of information about a dataset to enable easy use and interpretation of the data.

The term open data is defined in the Open Data Handbook from the Open Knowledge Foundation:

<img style="width:100%;height:auto;" src="../images/media/opendatahandbookquote.jpg">

"Open data is data that can be freely used, reused and redistributed by anyone – subject only, at most, to the requirement to attribute and share alike." [-What is Open Data?, n.d.](https://opendatahandbook.org/guide/en/what-is-open-data/)
Image Credit: Photo by Killian Cartignies on [Unsplash](https://unsplash.com/photos/person-wearing-silver-bracelet-holding-a-light-oKb2_15Uc8w) (external link)

When talking about data in the context of this module, we focus on the data that you are preparing to share regardless of what type that is, such as data affiliated with a scientific publication. While you could share (and many do) laboratory notebooks, preliminary analyses, intermediate data products, drafts of scientific papers, plans for future research and similar items, these aren't usually required by funding agencies or institutions and thus won't be the focus for this module.

As stated by Hemphill et al. in a paper about data reuse, researchers are mostly looking for data which is "comprehensive, easy to obtain, easy to manipulate, and believable." For these criteria to be fulfilled, the data should:

- Be sufficiently described with appropriate metadata, which greatly affects open data reusability. There is no one-size-fits-all for metadata, as its collection is guided by your data.
- Have the appropriate license, copyright, and citation information.
- Have appropriate access information.
- Be findable in an accredited or trustworthy resource.
- Be accompanied by a history of changes and versioning.
- Include details of all processing steps.

(Hemphill et al., 2022)

Not all data may be shared or shared with all this information. There are different reasons why it might not be possible. However, the more information shared about data helps increase the reliability and reusability of the information.

## Beneﬁts of Open Data

Data underpins almost all of science. Openly sharing data with others enables reproducibility, transparency, validation, reuse, and collaborations. The many benefits of open data include the following:

---

**Greater Good** – Data greatly impacts our day-to-day lives. Open data, in particular, plays a key role. If you pause and think about it, you may realize that open data is not only common in our society, but you might have benefited from and used open data yourself.

#### Example: Open Data Helps Provide Life-Saving Information and Disaster Preparedness

Tsunamis are fast-moving, extremely large ocean waves that can cause significant danger to coastal populations. These waves can move across the ocean at speeds of over 500 mph. A network of ocean surface sensors and seismic activity detectors, owned by several domestic and international organizations, measure and collect data 24 hours a day. This real-time data about potential tsunami threats is made readily-accessible to the public through open data platforms, allowing anyone to access information about ocean conditions, potential dangers, and active tsunami warnings. The data enables faster response and preparedness measures that help save lives. People in at-risk areas can receive notifications about potential threats, allowing for quicker evacuation procedures.

The open data is available to anyone with internet access. This level of transparency allows the public to understand the basis for the tsunami warnings. One significant source of open tsunami data is collected and maintained by the National Oceanic and Atmospheric Administration (NOAA). The data is available on the [Tsunami Warning System website](https://www.tsunami.gov/) (external link).

**Informing Resource Management**

#### Example: Changes in Fish Composition in the Australian East Coast Recreational Marlin Fishery

A study in Springer Nature included data from the New South Wales game fish tagging program (external link) to help map changes in fishery catch composition. The findings helped emphasize the need for adaptive and sustainable management strategies for fishing practices at the local and global scale to reduce the effects of current fishing practices and the emergence of new fishing technologies on fish availability. (Guillemin et al., 2025) This example shows how open data can lead to policy change that directly impacts the lives of communities.

**Large-Scale Emergency Response**

#### Example: Hurricane Ida

Tsunami preparedness is not the only way open data can help a community. Open data can play a vital role in providing timely and actionable data to assist communities in reducing risk of many different natural disasters as well as aid in the response and recovery from a large-scale disaster. In 2021, NASA provided data such as soil moisture, flood detection, and vegetation changes to [support disaster response efforts from Hurricane Ida](https://science.nasa.gov/open-science/artificial-intelligence-hurricane-response/). The data was shared via the [NASA Disasters Mapping Portal](https://disasters-nasa.hub.arcgis.com/), where publicly uploaded photos were added to increase situational awareness, and AI was used to help assess hurricane damage. To further improve disaster response and resilience, [NASA is collaborating with IBM](https://science.nasa.gov/open-science/ai-model-weather-climate/) to develop open-source AI foundation models that can be used to assess flood risk and even forecast crop yields.

Data sharing has many benefits and can aid access to knowledge. Making vast data more accessible and usable can enhance decision-making in disaster management and long-term recovery.

**Citizen Science**

#### Example: Water Quality Testing in Beirut

A citizen scientist is a citizen or amateur scientist who collaborates with professional researchers to help gather or interpret data on a broader spatial and temporal scale than the researchers might be able to achieve on their own. This outsourcing of responsibility helps members of the public engage in scientific pursuits that ultimately benefit them, allowing research to be conducted on a grander scale than what might be possible with only professional researchers. Citizen science is gaining popularity and recognition as a valuable contribution to scientific advancements.

For example, as reported in Chapter 5 of Contextualizing Openness: Situating Open Science, volunteer citizen scientists in Beirut were recruited from 50 villages to help test local water quality. These volunteers were trained to be able to conduct the tests and in turn, not only was the data collected to inform the scientific advancements, the citizen scientists had the opportunity to learn to better manage their water resources and were able to improve conditions, creating a mutually beneficial interaction. (Chan et al., 2019)

**Open Data and Equitable Sharing of Knowledge**

Ultimately, free distribution of knowledge increases participation in science.

In a research ecosystem where knowledge is a commodity, with the main currency in the form of published papers and hoarded datasets, making research unavailable or difficult to obtain for the scientific community can limit scientific progress and negatively impact outcomes.

#### Example: Recognition for the Work of African Ebola Researchers

During the West African Ebola outbreak from 2014-2016, West African researchers actively worked to collect blood sample data to better understand the Ebola virus and to help put a stop to the rapid spread of the virus. However, most of the blood samples were sent overseas to the US and Europe, where researchers used those data samples to author papers about Ebola. As a result, the data took much longer to be disseminated back to the public, and the West African researchers received little credit. According to a 2019 article in Nature "this frustrated researchers in the countries ravaged by the virus, who had hoped that studying aspects of the epidemic would strengthen their ability to respond to future infectious-disease outbreaks." (Maxmen, 2019)

By fostering a transparent research culture where work is properly acknowledged, we will create a sustainable model that increases the transparency and quality of scientific output.

---

### Benefits of Open Data Summary

Open data that is open to scrutiny benefits scientific innovation by allowing for a more robust scientific process that draws from multiple perspectives. This openness also allows for the early identification of mistaken insights as well as early intervention of unforeseen negative impacts.

Open data allows non-traditional researchers to contribute to scientific development and bring their unique insights to the table. With these benefits in mind, we should always remember that open data requires careful consideration of its potential downsides. This module of the Open Science curriculum discusses important considerations for the responsible management, collection, and use of open data by all stakeholders.

### Benefits to You

Open data also benefits your research and career. For starters, you are your own future collaborator!

Doing open science not only lets other people understand and reproduce your results, but it lets you do the same. Implementing open science principles like good documentation and version control helps you, potential collaborators, and everyone else to understand your results. In 2 hours, 2 weeks, or 2 years, you will still be able to understand what you did.

Specific benefits of opening data for you as an individual:

- You will never lose access to your previous work, no matter what institute you are affiliated with. Many researchers change institutions and organizations, and by having your data publicly accessible in repositories, you will always have access to them.
- Your data can be cited and you will get credit.
- Publications that include links to data are cited more, according to a 2020 study. (Colavizza et al., 2020)

Furthermore, implementing best practices for open science can strengthen your funding proposals. Funding agencies are realizing that openly sharing research provides more return on their investment. Well-documented research products also demonstrate the quality of your work, which helps with public communication and can also attract quality collaborators. Everybody prefers to work with people who are reliable and do a good job.

### Activity 1.1 Open Data Review

Take a moment to reflect on what data sharing means to you.

<img style="width:100%;height:auto;" src="../images/media/image6.jpeg">

Image source: Word cloud "Open Research Data - the FAIRest Data is the Future of Science - Estonia national OpenAIRE event" by OpenAIRE is licensed under CC 4.0

The above word cloud showcases the variety of meanings and interpretations that people have about open data. How many terms in the word cloud do you recognize? Are any of them new to you?

## Challenges of Open Data

While open data has many benefits, there can also be challenges to its creation and use. Throughout this module, we discuss many of these challenges and possible solutions. In this section, we will take a look at a few of the most common concerns along with actions to mitigate them.

### Restrictions on Sharing Data

Some data should only be shared very carefully or not at all. Reasons not to share can include:

- Data includes a country's military secrets or violations of national interests.
- Data includes private medical information or an individual's personally identifiable data.
- Data includes intellectual property.

It is important to be familiar with the requirements, expectations, and limitations that will affect the sharing of your data, such as policies from your funding agency or institution, or laws regarding data protection. These are further discussed in later modules.

### Common Fears Around Sharing Open Data

#### NOTE: We will discuss many of the concepts mentioned in the discussion/mitigation column later in this module.

|  |  |
|---|---|
| Fear: Someone will reuse my data to publish a result I am working on (i.e. scooping) | Yes, this can happen. But, in many fields, if it is clear that someone is actively working on a problem, the decision by another to scoop may have a short term gain but long-term loss. In science, reputations are very important and being collaborative generally leads to increased career successes. If you are sharing your data, ensure it has a digital object identifier (DOI). This does not prevent someone from using your data without attribution, but it helps make it easy for others to cite your data. There is a nice article about this [here](https://datascience.codata.org/articles/10.5334/dsj-2017-029). |
| Fear: Misinterpretation or Misuse | Provide sufficient contextual information (documentation) to allow others to understand your data fully to reduce this risk. |
| Fear: My data will be used but not cited | While it is not common for researchers to cite data, science ethics dictates that you should be cited if your work is used. And remember to cite others' data, so you’re not adding to the problem! |
| Fear: Data is too sensitive to share | Use controlled access to help maintain sensitivity and security. |
| Fear: My data won't be useful to anyone else | You never know how materials might be used! Sailors in the 1800s collected temperature data that still remains an important part of our ocean climate record today. (NPR, 2019) |

These are all valid concerns when sharing data openly, but as indicated by the global move towards open science, the overall benefits outweigh the concerns.

Ultimately, you are free to deploy the open data principles and resources in your research to maximize its impact and meet the expectations of your sponsors and community while managing costs.

## Applying FAIR Principles

<img src="../images/media/image9.png" style="width:100%;height:auto;" />

Image Credit: A cartoon describing FAIR data sharing by Patrick Hochstenbach, is licensed under CC0 1.0

---

### FAIR: Findable, Accessible, Interoperable, Reusable

The vast majority of data today is shared online. Although FAIR was introduced in Module 2, Lesson 3, some additional details are provided below. FAIR Principles help researchers make better use of - and engage a broader audience with - their scientific data than outdated techniques would allow. FAIR data is more valuable for science because it is easier to use. Data can be FAIR regardless of whether it is openly shared or not. If data is openly shared, being FAIR helps with reuse and expands the scientific impact of the data.

FAIR Principles don't encompass comprehensive implementation instructions for every type of data, but offer general insights to improve shareability and reusability. Sometimes it takes a group effort and/or a long production process to make data and results FAIR. The process starts in the planning stage of a research project. A well-coordinated Open Science and Data Management Plan (OSDMP) is often needed for full compliance with FAIR, depending on the size and type of project the data is being used for.

**Up-to-date information about FAIR Principles can be found at the GO FAIR Initiative website**

[CLICK TO LEARN (EXTERNAL LINK)](https://www.go-fair.org/)

Let's review how to make data FAIR for your community.

*Select each tab to find out more information.*

<table>
  <thead>
    <tr>
        <th>FINDABLE &#9745;</th>
        <th>ACCESSIBLE</th>
        <th>INTER-OPERABLE</th>
        <th>REUSABLE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>To ensure that data are findable by those in your community:</p>
            <ul>
            <li>Deposit data in repositories to preserve the data over time.</li>
            <li>Assign your dataset a persistent identifier (PID), such as a digital object identifier (DOI).</li>
            <li>Add rich, self-describing metadata in your data files and register the metadata in a metadata catalog, enabling your data to be properly curated.</li>
                <ul>
                <li>Note that some images or binary files cannot be readily indexed or searched and will need to have companion metadata files or dictionaries to ensure they can be discovered in a search.</li>
                </ul>
            <li>Automate the sharing of your metadata with targeted communities, if applicable.</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FINDABLE</th>
        <th>ACCESSIBLE &#9745;</th>
        <th>INTER-OPERABLE</th>
        <th>REUSABLE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>To ensure that data can be accessed by those in your community:</p>
            <ul>
                <li>Archive in a data repository/data center with standardized access protocols.</li>
                <li>Repository access protocols should be well-defined and ideally should support machine-to-machine access.</li>
                <li>Provide information on how users can access your data, ideally in an automated, machine-based fashion.</li>
                <li>If the full content cannot be made openly available for any reason (e.g. data sensitivity, infrequent data access, file storage issues), the metadata can still be made openly available so that users can find out who they need to contact to request the data (if possible).</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FINDABLE</th>
        <th>ACCESSIBLE</th>
        <th>INTER-OPERABLE &#9745;</th>
        <th>REUSABLE</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>To ensure that data are interoperable for those in your community:</p>
            <ul>
                <li>Report the data in community standard format.</li>
                <li>Use existing standardized metadata if available to minimize "lost in translation" issues and support machine-readability.</li>
                <li>The use of controlled terminologies, vocabularies, and ontologies is necessary to support interoperability, but may not yet be available in all research fields.</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>FINDABLE</th>
        <th>ACCESSIBLE</th>
        <th>INTER-OPERABLE</th>
        <th>REUSABLE &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="4">
            <p>To ensure that data are reusable by those in your community:</p>
            <ul>
                <li>Ensure that metadata accurately describes the data and its variables as well as any particularities or limitations.</li>
                <li>Specify clear usage licenses for your data.</li>
                <li>Provide accurate information on provenance in your metadata.</li>
                <li>Add enough metadata information so that your data can be properly cited when it is used.</li>
            </ul>
        </td>
    </tr>
  </tbody>
</table>

### Metadata's Central Role in Applying FAIR

Metadata is important for search engines to find data and for people to be able to easily compare what is returned.

- Metadata is essential to the implementation of FAIR Principles and enable the data to be used by machines in an automated fashion.
- The richer and more self-describing metadata is, the better it will be handled by anyone who is interested in your data.

### Licensing Data

A license is a legal document that tells users how they can use a particular dataset. If you don't license your dataset, others can't and shouldn't reuse it - even if you want them to! It is imperative to understand the licensing conditions of a dataset before data reuse. Without a good understanding of what a license allows, data users may run into copyright infringement or other intellectual property issues.

To ensure open reuse of your data, you can use an open license. An open license has language that describes the user's ability to access, reuse and redistribute the dataset. There are many types of data licenses that are open to varying degrees, and these will be discussed further in Lesson 3, "Making Open Data."

## Planning for Openness: Using the Use, Make, Share Framework for Open Data

### Open Science and Data Management Plans

Most scientific funding agencies and organizations ask for a plan for sharing your research when you propose a project. One example of an open science plan is the Open Science and Data Management Plan ([OSDMP](https://science.nasa.gov/researchers/sara/faqs/osdmp)) for NASA's Science Mission Directorate (SMD) that describes how the scientific information that will be produced from scientific activities will be managed and made openly available. The OSDMP includes sections on data management, software management, and publication sharing; the latter two will be discussed in future modules. If your study has other types of outputs, such as physical samples, hardware, or anything else, you should include those in the plan too. More information and templates can be found on [OSDMP at NASA](https://science.nasa.gov/researchers/sara/faqs/osdmp/).

A best practice when beginning your open data journey is to create a data management plan (DMP), which goes within the OSDMP. This describes how you will manage, preserve, and release data, during and after a research project. Common elements of DMPs relevant to open data include a description of the following:

|  |  |
|---|---|
| What? | Data types, volume, formats, and (where relevant) standards. |
| When? | The schedule for data archiving and sharing. |
| Where? | The intended repositories for archived data. |
| How? | How the plan enables long-term preservation of the data. |
| Who? | Roles and responsibilities of the team members in implementing the DMP. |

Investigate if your home institution or funding source has guidance, standards, or templates for DMPs. Other organizations have DMP guidelines and examples as well:

- [USGS](https://www.usgs.gov/data-management/data-management-plans) (external link)
- [NOAA](https://marinedebris.noaa.gov/sites/default/files/DataManagementPlanGuidance%26Sample.pdf) (external link)
- [NSF](https://new.nsf.gov/funding/data-management-plan) (external link)

More details about how to create these plans will be provided in the lesson "From Theory to Practice".

### Scientiﬁc Workﬂow

There are a variety of scientific workflow models that explain open science. Data plays a central role in the scientific workflow, where users can propose to create new data, collect and package their data during their project, then archive it for long term storage, use, and reuse.

For this curriculum, we use a workflow model derived from Opensciency and The Turing Way. (OpenSciency Contributors, 2023; The Turing Way, 2024) It is used to illustrate that regardless of the workflow model you use, the adoption of open data is performed throughout the entire workflow and production of associated deliverables.

If your project is already in progress, it is a good idea to update future data releases to adhere to open data principles as much as possible. For new projects, your proposals should include creating open data from the start of your project.

<img src="../images/media/image10.jpeg" style="width:100%;height:auto;" />
Open Science Workflow Products Source: Opensciency.

In this curriculum, content is organized by how you might use it, make it, and share it. Part of doing open science is building on others' materials (using), creating materials yourself (making), and sharing those so others can use those results (sharing). The lessons are all organized around these steps in the scientific workflow.

The "Use, Make, Share" framework categorizes the tasks commonly used in the practice of open science.

<img src="../images/media/image11.png" style="width:100%;height:auto;" />

### Roles in Use, Make, Share

Individuals interacting with data at various points in the scientific workflow can take on different roles. It is possible that these roles can overlap depending on project requirements, the size of your team, and even funding. All members should be using open data principles to perform their tasks. Generally, roles include:

*Select each tab to find out more information.*

<table>
  <thead>
    <tr>
        <th>DATA USERS &#9745;</th>
        <th>DATA MAKERS (DATA PROVIDERS)</th>
        <th>DATA SHARERS (DATA PUBLISHERS)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Data users primarily discover, assess, and utilize data in research projects.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>DATA USERS</th>
        <th>DATA MAKERS (DATA PROVIDERS) &#9745;</th>
        <th>DATA SHARERS (DATA PUBLISHERS)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Data makers often process data collected by a project/activity and package it according to open science principles.</p>
        </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
        <th>DATA USERS</th>
        <th>DATA MAKERS (DATA PROVIDERS)</th>
        <th>DATA SHARERS (DATA PUBLISHERS) &#9745;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td colspan="3">
            <p>Data sharers bear the responsibility of disseminating and building awareness of the data to the public.</p>
        </td>
    </tr>
  </tbody>
</table>

Making data open (and FAIR) is a group effort – everybody in the data pipeline has a role to play.

## Lesson 1: Summary

In this lesson, you learned:

- Open data is an essential pillar of open science. Openly sharing data with others enables reproducibility, transparency, validation, reuse, and collaborations.
- Several challenges to creating open data exist, but most have straightforward mitigation measures.
- FAIR Principles can be applied to data to make them more open.
- Open-data principles and tasks are used throughout the entire scientific workflow.

## Lesson 1: Knowledge Check

Answer the following questions to test what you have learned so far.

*Question*

**01/04**

Read the statement and decide whether it is true or false.

*Open data can be freely used, re-used and redistributed by anyone - subject, at most, to the requirement to attribute and share alike.*

- True
- False

*Question*

**02/04**

Finish the sentence:

*Making data open helps YOU because _____.*

- your data can be cited and you will get credit
- you won’t lose access to your data, even if you move institutions
- your publications are more likely to get cited when you link to open data
- all of the above

*Question*

**03/04**

Choose the FAIR Principles from the list below. Select all that apply.

- Reproducible
- Reusable
- Responsible
- Findable
- Interactive
- Interoperable
- Interspersed
- Accessible
- Authorizable

*Question*

**04/04**

Which of the following can help make your data FAIR? Select all that apply.

- Get a license for your data
- Make your metadata accessible only as long as your data is available
- Obtain a PID for your data

### References Cited

- Chan, L., Okune, A., Hillyer, R., Albornoz, D., and Posada, A. (2019). Contextualizing openness: Situating open science. The University of Ottawa Press.
- Clyde, D. Spaceflight causes mitochondrial stress. Nat Rev Genet 22, 69 (2021). [https://doi.org/10.1038/s41576-020-00322-8](https://doi.org/10.1038/s41576-020-00322-8) (external link)
- Colavizza G, Hrynaszkiewicz I, Staden I, Whitaker K, McGillivray B (2020) The citation advantage of linking publications to research data. PLoS ONE 15(4): e0230416. [https://doi.org/10.1371/journal.pone.0230416](https://doi.org/10.1371/journal.pone.0230416) (external link)
- Guillemin, T.A., Pepperell, J.G., Schilling, H.T. et al. 90 years of catch data reveal changes in catch composition in the Australian east coast recreational marlin fishery. Rev Fish Biol Fisheries 35, 371-389 (2025). [https://doi.org/10.1007/s11160-024-09906-7](https://doi.org/10.1007/s11160-024-09906-7) (external link)
- Hemphill L, Pienta A, Lafia S, Akmon D, Bleckley DA. How do properties of data, their curation, and their funding relate to reuse? J Assoc Inf Sci Technol. 2022 Oct;73(10):1432-1444. [doi: 10.1002/asi.24646](https://doi.org/10.1002/asi.24646) (external link). Epub 2022 Mar 23. PMID: 36246529; PMCID: PMC9542848.
- Maxmen, Amy. (2019, July 24). Science under fire: Ebola researchers fight to test drugs and vaccines in a war zone. Nature, 572, 16-17. doi: [https://doi.org/10.1038/d41586-019-02258-4](https://doi.org/10.1038/d41586-019-02258-4) (external link)
- NPR. (2009). 1800s-Era Sea Logs Chart Course Of Climate Change. [https://www.npr.org/2009/10/18/113916471/1800s-era-sea-logs-chart-course-of-climate-change](https://www.npr.org/2009/10/18/113916471/1800s-era-sea-logs-chart-course-of-climate-change) (external link)
- OpenSciency Contributors (2023, February 22). Opensciency - A core open science curriculum by and for the research community. Zenodo. DOI 10.5281/zenodo.7392118 [https://doi.org/10.5281/zenodo.7392118](https://doi.org/10.5281/zenodo.7392118) (external link)
- What is Open Data? (n.d.). Open Data Handbook. [https://opendatahandbook.org/guide/en/what-is-open-data/](https://opendatahandbook.org/guide/en/what-is-open-data/) (external link)
- The Turing Way. (2024). The Turing Way. [https://book.the-turing-way.org/](https://book.the-turing-way.org/) (external link)
