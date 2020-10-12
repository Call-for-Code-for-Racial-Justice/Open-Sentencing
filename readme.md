# Outcarcerate Starter Kit

This solution starter was created by a team of IBM and Red Hat employee volunteers as part of the Emb(race) Call for Code Challenge.

##  Overview

### What's the problem?

People in the Black Community are faced with harsher downstream effects than people of other races for similar offenses. They are charged and convicted at higher rates, assigned more significant charges, given longer sentences, and denied parole more often.

We found that nearly all sentencing is completed at the plea level for defendants represented by a [*public defender*](https://www.youtube.com/watch?v=xqLE4ryWMX4).  We want to arm public defenders and defense attorneys against powerful and better equipped prosecutors and judges.

So we created a tool with the goal of ***reducing sentencing*** for people impacted by **bias** and **racism**.

### How can technology help?

Our public defenders are already overloaded. A simple to use tool that works with the [bias detection engine](https://github.com/embrace-call-for-code/bias-detection-engine) can analyze data and highlight bias and other insights to let public defenders and defense attorneys focus on reducing sentences and getting the best outcome for the case.

**Black Lives Matter** - let's fairly give people more of life outside of prison.

## The Idea

A web application where a defense attorney / public defender can upload information about a case and the defendant.

The web application:

* **Analyzes available data** about the type of charge, the accused, the case, and the proposed charges
* **Detects bias** based on similar cases in the [bias detection engine](https://github.com/embrace-call-for-code/bias-detection-engine)
* **Clearly highlights indicators of bias** including historical disparities, inappropriate charges and sentences, and recommendations for public defenders and defense attorneys
* **Publishes information and outcomes** to a public site so that anyone can see trends and request updates about **bias** in the criminal justice system

Public defenders can then act immediately on this information to negotiate a better plea or sentence for the defendant.

![A diagram of the bias detection and reporting process, its inputs, its actions, and its reported output.](https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/Bias%20Detection.png)

## How it works

#### Architecture
<!-- Ideally some text in here about what happens would be helpful. -->

![Architecture diagram for the project](https://raw.githubusercontent.com/embrace-call-for-code/outcarcerate-docs/master/architecture.png)

### Components

#### Aggregator
* Repo: https://github.com/embrace-call-for-code/outcarcerate-aggregator
* OpenAPI: https://github.com/embrace-call-for-code/outcarcerate-aggregator/blob/master/src/main/resources/swagger.yaml
* Service URL: https://outcarcerate-aggregator-decarcerate.embrace-dev-ocp43-vpc-7ec5d722a0ab3f463fdc90eeb94dbc70-0000.us-east.containers.appdomain.cloud/

#### User interface (UI)
*  Mock-up: https://ibm.invisionapp.com/share/92O0CQSMK7Q
*  Repo: https://github.com/embrace-call-for-code/outcarcerate-ui

![](https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/UI%20Example.png)
![](https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/UIexample2.png)


#### Skills required

<!-- Moved developer skills to the contributor section -->
* *End-users*:  skills: online training on navigating the tool
* *Public*: skills:  none (intuitive interface); user experience:  immediate, informative, targeted information
* *Private beneficiaries*:  N/A
* *SMEs* (Lawyers, American Bar Association, Southern Poverty Law Center, Judiciary NGOs):  skills:  unsupervised learning for training and expanding the ML/bias detection engine for new personas, locales, scope, crime types, etc.

## Get support

[Click here to get support](https://github.com/Call-for-Code/Embrace-Judicial-Reform/blob/main/SUPPORT.md)

## Contribute to the project

This project uses a combination of React, Java and Python. An understanding of open source software and data science is also useful.

All contributions are subject to the Developer Certificate of Origin, Version 1.1 (DCO) (https://developercertificate.org/) and the Apache Software License, Version 2 (http://www.apache.org/licenses/LICENSE-2.0.txt)

### Future directions

* Develop a getting started process for contributors
* Swapping out data sets
* Bias integration
* Expand to entire judiciary
* Personas and public facing dashboard (PS1 solution assessment of laws and bias mapped to assess your judges and local prosecutors) - integrated with all of theme 3 (arrest, police report, judiciary) and with hirings.
<!-- This doesn't make a lot of sense, can you add more details? -->


## Reference material

### Data sources

*  [United States Sentencing Commission](https://ida.ussc.gov/analytics/saw.dll?Dashboard)
* Uploaded files from lawyers, police, court staff, or links to case file management systems.
* Others Data Sources In progress (ideally we'd expand to all levels of government).
* Sponsor user interview based research conducted by Outcarcerate Team including a judge and attorneys.
![](https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/ToBePD.png)


### Background reading

* [Racial Disparity in Federal Criminal Sentences](https://repository.law.umich.edu/cgi/viewcontent.cgi?article=2413&context=articles)
* [Racial, Ethnic, and Gender Disparities In Federal Sentencing Today](https://www.ussc.gov/sites/default/files/pdf/research-and-publications/research-projects-and-surveys/miscellaneous/15-year-study/chap4.pdf)
* [The Growing Racial Disparity in Prison Time](https://www.themarshallproject.org/2019/12/03/the-growing-racial-disparity-in-prison-time)
* [Racial Disparity](https://www.sentencingproject.org/issues/racial-disparity/)
* [Unequal Treatment: Racial and Ethnic Disparities in Miami-Dade Criminal Justice](https://www.aclufl.org/sites/default/files/6440miamidadedisparities20180715spreads.pdf)
* [From police to parole, black and white Americans differ widely in their views of criminal justice system](https://www.pewresearch.org/fact-tank/2019/05/21/from-police-to-parole-black-and-white-americans-differ-widely-in-their-views-of-criminal-justice-system/)
* [Public Defenders: Last Week Tonight with John Oliver ](https://www.youtube.com/watch?v=USkEzLuzmZ4)
* [America's Public Defense System Is in Crisis](https://www.youtube.com/watch?v=xqLE4ryWMX4)


## Authors
<!-- Authors, please do add your GitHub/LinkedIn/IBM permalinks here. I added the GitHub profiles of those who committed directly to the outcarcerate repos. -->

* Adria Spivack
* Ann Marie Fred ([@amfred](https://github.com/amfred))
* Ben Chance
* Harendranath Vegi
* Hema Veeradhi
* Jean Carlos Ricardo Arruda ([@jefyelin](https://github.com/jefyelin))
* Jeimmy Cesar
* Jo Ann Hill
* Kate Tereshchenko
* Kyleni Rivers
* Stacy Forsyth ([@sforsyth089](https://github.com/sforsyth089))
* Matt Tribby
* Max Veit ([@maxveit](https://github.com/maxveit))
* Whitley Walters
* Yasmine Guedjou

![Graphic showing the Outcarcerate team: Adria Spivack, Ann Marie Fred, Ben Chance, Harendranath Vegi, Hema Veeradhi, Jean Carlos Ricardo Arruda, Jeimmy Cesar, Jo Ann Hill, Kate Tereshchenko, Kyleni Rivers, Stacy Forsyth, Matt Tribby, Max Veit, Whitley Walters, and Yasmine Guedjou](https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/OutcarcerateTeam.png)


*Thank you* for your interest and we truly hope this helps!

![The Call for Code logo](https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/Call%20for%20Code.png)
