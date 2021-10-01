[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-blue.svg)](callforcode.org/slack)

![](/images/launch-logo.png)

# **Open Sentencing Solution Starter**

The Open Sentencing solution starter helps expose bias and empowers public defenders to address racial disparities in the judicial system directly.
## **Table of Contents**
- [**Open Sentencing Solution Starter**](#open-sentencing-solution-starter)
  - [**Table of Contents**](#table-of-contents)
  - [**What is Open Sentencing?**](#what-is-open-sentencing)
  - [**How Tech Can Help**](#how-tech-can-help)
  - [**Idea/Solution**](#ideasolution)
  - [**Users and Skills**](#users-and-skills)
  - [**Browser Support**](#browser-support)
  - [**Architecture Diagram**](#architecture-diagram)
  - [**Technical Materials**](#technical-materials)
  - [**Data Sources**](#data-sources)
  - [**Future Implementations/Ideas**](#future-implementationsideas)
  - [**Help Wanted!**](#help-wanted)
    - [**Partners**](#partners)
    - [**Research and Data Gathering**](#research-and-data-gathering)
    - [**UI improvements**](#ui-improvements)
    - [**Aggregator and Report Generator improvements**](#aggregator-and-report-generator-improvements)
    - [**Overall code improvements**](#overall-code-improvements)
  - [**References**](#references)
      - [**Team Members**](#team-members)
  - [**License**](#license)


<a name="out"></a>
## **What is Open Sentencing?**
People in the Black Community are faced with harsher downstream effects (charged at higher rates, assigned more significant charges, convicted at higher rates, given longer sentences, and denied parole more often) than people of other races for similar offenses. This systemic bias in the justice system has a profound and lasting impact on black families, communities and the country. The Open Sentencing solution starter helps expose bias and empowers public defenders  to address racial disparities in the judicial system directly. Our solution includes an engaging user interface (UI) that feeds into our pre-trained Bias & Disparity Detection Engine. This innovative engine analyzes fact patterns and rapidly provides statistical analysis that highlights deviations from guidelines by race throughout an accused person's judiciary process.  The reports from Open Sentencing solution starter provides clear insights for the public defender to aid in defending against detected bias, ultimately & ideally fairly reducing incarceration for members of the black community.

We created a tool with the goal of ***reducing sentencing*** for people impacted by **bias** and **racism**.

> We found that nearly all sentencing is completed at the plea level for defendants represented by a [*public defender*](https://www.youtube.com/watch?v=xqLE4ryWMX4).  We want to provide more information to arm public defenders against powerful and more often strongly equipped prosecutors and judges.

<a name="help"></a>
## **How Tech Can Help**
A simple to use tool can make the process of collecting and analyzing data quicker and easier for already very busy and often overloaded public defenders. Our tool can quickly highlight bias and other insights saving valuable time, allowing more focused on reducing sentences.  Black Lives Matter - let's legally give people more of life outside of prison.  

>Our solution works with the bias detection engine and open sentencing - Learn more here: https://github.com/Call-for-Code-for-Racial-Justice/bias-detection-engine and here: https://github.com/Call-for-Code-for-Racial-Justice/Open-Sentencing-Model

Please see the diagram below to understand how data flows through the solution:

![](/images/Data-Flow-Open-Sentencing-10_17_2020.png)

<a name="solution"></a>
## **Idea/Solution**

A Web application where a defense attorney / public defender can upload information about a case and the defendant.

* Analyzes available data
* Provides public defense attorneys with insights, connections, and bias indicators for each case
* Information and outcomes from this tool will be fed into a public site where anyone can see trends and request updates for **bias** in the criminal justice system

> Public defenders can then act immediately on that information to negotiate a better plea or sentence for the defendant.

*Key Highlight*

Our tool will indicate and denote when bias/racism was detected and highlight it for attorneys to use in defense process.
Bias detection (highlighted clearly), demographics from uploads, key sentencing information that we mined and have within our tool, as well as recommendations from our tool make a public defenders job more accessible and frees up time to focus on the case(s).

![](/images/Bias-Detection.png)

## Open Sentencing Video

[![Video Call for Code for Racial Justice Solution Starter: Open Sentencing ](https://img.youtube.com/vi/btqh9EKOg44/0.jpg)](https://www.youtube.com/watch?v=btqh9EKOg44)

<a name="skills"></a>
## **Users and Skills**

* *Developers*:  skills: React, OSS, full-stack (java, python), data science; user experience: need to develop a getting started process
* *End-users*:  skills: online training on navigating the tool
* *Public*: skills:  none (intuitive interface); user experience:  immediate, informative, targeted information
* *Private beneficiaries*:  N/A
* *SMEs* (Lawyers, American Bar Association, Southern Poverty Law Center, Judiciary NGOs):  skills:  unsupervised learning for training and expanding the ML/bias detection engine for new personas, locales, scope, crime types, etc.

<a name="browser"></a>
## Browser Support
* Chrome
* Edge
* Firefox
* Internet Explorer
* Safari

<a name="architecture"></a>
## Architecture Diagram
![](/images/architecture.png)

<a name="steps"></a>
## **Technical Materials**

<a name="agg"></a>
### Aggregator
* [Repo](https://github.com/Call-for-Code-for-Racial-Justice/Open-Sentencing-Aggregator)
* [OpenAPI](https://github.com/Call-for-Code-for-Racial-Justice/Open-Aggregator/blob/master/src/main/resources/swagger.yaml)
* [Service URL](https://outcarcerate-aggregator-decarcerate.embrace-dev-ocp43-vpc-7ec5d722a0ab3f463fdc90eeb94dbc70-0000.us-east.containers.appdomain.cloud/)
![Screen-Shot-2020-10-05-at-6-16-23-PM.png](https://i.postimg.cc/3xY9s3Lv/Screen-Shot-2020-10-05-at-6-16-23-PM.png)

<a name="ui"></a>
### UI (User-Interface)
* [Mock-up](https://ibm.invisionapp.com/share/Q5O0KIVUNE8)
* [Repo](https://github.com/Call-for-Code-for-Racial-Justice/Open-Sentencing-UI)

![](/images/UI-example.png)
![](/images/UI-example2.png)

<a name="open"></a>
### Open Sentencing Model
* [Repo](https://github.com/Call-for-Code-for-Racial-Justice/Open-Sentencing-Model)

<a name="bias"></a>
Bias Detection Engine
* [Repo](https://github.com/Call-for-Code-for-Racial-Justice/bias-detection-engine)

<a name="sources"></a>
## Data Sources

* [United States Sentencing Commission](https://ida.ussc.gov/analytics/saw.dll?Dashboard)
* Uploaded files from lawyers, police, court staff, or links to case file management systems.

* Bias Disparity (BDDE) Detection Engine accesses Dataset #3- Historical Sentencing documents showing how similarly charged Marijuana trafficking cases were settled, prioritizing those documents that carry publicly available defendant’s demographic info showing race and sex of defendants 
Public Data not requiring licensing agreement that contains private information requiring privacy protection

* Cook County State county data set used in Open Sentencing.


<a name="future"></a>
## Future Implementations/Ideas
As we advance, we hope the solution will have a global impact on the advancement of racial justice, and with the solution -- that institutions, organizations, and individuals -- can continue to build an understanding, participation, and collaboration to sustain and grow commitments towards an equitable safe and enhanced quality of life. Race will have nothing to do with who is in jail. The solution will get adopted at each level of government – from cities, counties, states and federal – with the associated data available and enhanced to enable effective analysis and make recommendations to address the disparities in the sentencing of Black defendants. We want to find partners who can help us get access to bigger and richer data sets, as well as partners who can help us build a solution that meets all of the legal and security standards that will allow us to use more information about individual defendants and cases.

## Help Wanted!
We would love your support to help us move this idea forward!
Please read the [CONTRIBUTING guidelines](/CONTRIBUTING.md)

[Open Issues](https://github.com/Call-for-Code-for-Racial-Justice/Open-Sentencing/issues)

Please see the Issues area within this GitHub project for specific open items we need help with!  We also have other ideas below!

Areas where we need help:

### Partners
* Sponsor Users: We need public defenders and other criminal defense lawyers who are willing to be sponsor users, and give us feedback on our tool(s) several times over the coming months. We want to make this as easy to use and helpful as possible; adding another tool to your day should be worth the effort. We would also like to conduct additional user interviews to understand your day-to-day work experiences.  The user interviews we have done so far have been benificial, but experiences will vary from one attorney or jurisdiction to another.
* Working the System: We would like to work with motivated government agencies and non-governmental organizations.
* Universities and law schools may be able to help us with research and data gathering.
* A Case-Management Software company could be a valuable partner if the company is also committed to an open-source solution. We could see our tools eventually integrating with case-management software.

### Research and Data Gathering
* The hard part, we have found, is finding machine-readable data with a license that allows us to use it. Researching to find that data and understand its licensing takes time and many people.
* Criminal Justice Funnel Data: We need data sets that show how defendants are moving through the criminal justice system "funnel" in many different jurisdictions, with race as one of the data points.  We've only found two data sets we can use so far. Sometimes the data sets aren't publicly available yet, or the licenses are not yet permissive enough for us to use them in our AI/ML processing, or the data is not readily available in a machine-readable format.
* Sentencing Guidelines: We need detailed machine-readable sentencing guidelines data for the same jurisdictions as above. This can eventually help us find sentencing guidelines that result in disparate outcomes.  It can also help us find cases where certain groups of people are more likely to receive sentences on the higher or lower end of the ranges specified by the sentencing guidelines.
* Plea Bargaining Data: For our project to reach its full potential, we want to collect data on the plea bargaining process across many cases.  Usually, plea bargain negotiations are not recorded in writing, or at least not available to us.  Whether this means conducting a formal research study or enhancing our tools to collect data with the proper consent and security/privacy controls, we will need help navigating that process.
* Fact Pattern Data: We need descriptions of cases and how the cases fit (or do not fit) with certain criminal charges, across various jurisdictions.

### UI improvements
* As we're able to add more functionality to our system, we'll need to continue to update the UI to display more information. We plan to post an Invision prototype for each iteration, and we will need front-end developers to make the vision a reality.
* We also envision a publicly-accessible dashboard, but we haven't started development on it yet.

### Aggregator and Report Generator improvements
* As we're able to add more functionality to our system, we'll need to continue to update the Aggregator and Report Generator to process that information. Watch out for Github issues opened for additional objects that we need in our database schema and reports.
* We'll also need more REST APIs overtime to retrieve and update the data.

### Overall code improvements
* We will need continuous improvements to our contribution and deployment guides. As you're trying to get these solutions deployed and running, please submit pull requests to our documentation to improve it.
* We would like guides for additional deployment options. For example, on your laptop, using OpenShift, or using various other cloud providers.
* Our microservices are spread across several repositories, and that could be confusing to new contributors. If you have a good example of how to combine multiple services that use different programming languages and frameworks into one repository, open an issue and let us know!

<a name="references"></a>
## **References**

* [Racial Disparity in Federal Criminal Sentences](https://repository.law.umich.edu/cgi/viewcontent.cgi?article=2413&context=articles)
* [Racial, Ethnic, and Gender Disparities In Federal Sentencing Today](https://www.ussc.gov/sites/default/files/pdf/research-and-publications/research-projects-and-surveys/miscellaneous/15-year-study/chap4.pdf)
* [The Growing Racial Disparity in Prison Time](https://www.themarshallproject.org/2019/12/03/the-growing-racial-disparity-in-prison-time)
* [Racial Disparity](https://www.sentencingproject.org/issues/racial-disparity/)
* [Unequal Treatment: Racial and Ethnic Disparities in Miami-Dade Criminal Justice](https://www.aclufl.org/sites/default/files/6440miamidadedisparities20180715spreads.pdf)
* [From police to parole, black and white Americans differ widely in their views of criminal justice system](https://www.pewresearch.org/fact-tank/2019/05/21/from-police-to-parole-black-and-white-americans-differ-widely-in-their-views-of-criminal-justice-system/)
[Public Defenders: Last Week Tonight with John Oliver ](https://www.youtube.com/watch?v=USkEzLuzmZ4)
[America's Public Defense System Is in Crisis](https://www.youtube.com/watch?v=xqLE4ryWMX4)

Besides, sponsor user interview Based Research Conducted by Open Sentencing Team included a judge and attorneys.

![](/images/ToBePD.png)

## Support

Join the [Call for Code Slack workspace](https://developer.ibm.com/callforcode/racial-justice/get-started/) and subscribe to
the #racial-justice-open-sentencing channel.

Contributions are subject to the Developer Certificate of Origin, Version 1.1 (DCO) (https://developercertificate.org/) and the Apache Software License, Version 2 (http://www.apache.org/licenses/LICENSE-2.0.txt)

*Thank you* for your interest and we genuinely hope this helps!

![](/images/Call-for-Code.png)

#### Team Members

This solution starter was created by a team of IBM / Red Hat employee volunteers as part of the Call for Code for Racial Justice Challenge.

![](/images/OpenSentencingTeam.png)

## Project Outreach / Events

[**IBM Developer via Crowdcast (March 1, 2021)**](https://www.crowdcast.io/e/open-sentencing-an-open/register)

[**The Linux Foundation Spring Member Meeting (March 9, 2021)**](https://events.linuxfoundation.org/lf-spring-member-meeting/)

[**Presentation slides for The Linux Foundation Spring Member Meeting (March 9, 2021)**](https://events.linuxfoundation.org/wp-content/uploads/2021/03/LFSMM_Final_Template-Jo-Ann-H-Hill-IBM-v2.pdf)

<a name="license"></a>
## **License**
The embed link applications are licensed under the Apache License, Version 2. Separate third-party code objects invoked within this code pattern are licensed by their respective providers pursuant to their own separate licenses. Contributions are subject to the [Developer Certificate of Origin, Version 1.1](https://developercertificate.org/) and the [Apache License, Version 2](https://www.apache.org/licenses/LICENSE-2.0.txt).
[Apache License FAQ](https://www.apache.org/foundation/license-faq.html#WhatDoesItMEAN)
The embed sites provide applications using data that has been modified for use from its original source, www.ida.ussc.gov, an official website of the U.S. Sentencing Commission. The U.S. Sentencing Commission makes no claims as to the content, accuracy, timeliness, or completeness of any of the data provided at this site. The data provided at this site is subject to change at any time. It is understood that the data provided at this site is being used at one’s own risk.

This project is licensed under the Apache 2 License - see the [LICENSE](/LICENSE) file for details

Content license pending legal guidance.
