# **Solution Starter Kit - Outcarcerate**
## 
This solution starter was created by a team of IBM/Red Hat employee volunteers as part of the Emb(race) Call for Code Challenge.

Emb(race) Team Members:  Please see the end of this document!

### **Table of Contents:**

* Description of Problem
* How Tech Can Help
* Idea/Solution
* Users and Skills
* Technical Materials
* Data Sources
* Architecture Diagram
* Suggestions on how to take the idea in other directions
* References


## **Description of Problem**

People in the Black Community are faced with harsher downstream effects (charged at higher rates, assigned more significant charges, convicted at higher rates, given longer sentences, and denied parole more often) than people of other races for similar offenses.  We created a tool with the goal of ***reducing sentencing*** for people impacted by **bias** and **racism**.

> We found that nearly all sentencing is completed at the plea level for defendants represented by a [*public defender*](https://www.youtube.com/watch?v=xqLE4ryWMX4).  We want to provide more information to arm public defenders against powerful and more often strongly equipped prosecutors and judges.

## **How Tech Can Help**
A simple to use tool can make the process of collecting and analyzing data quicker and easier for already very busy and often overloaded public defenders. Our tool can quickly highlight bias and other insights saving valuable time allowing more focused on reducing sentences.

## **Idea/Solution** 

Web application where a defense attorney / public defender can upload information about a case and the defendant. 

* Analyzes available data
* Provides public defense attorneys with insights, connections, and bias indicators for each case 
* Information and outcomes from this tool will be fed into a public site where anyone can see trends and request updates for **bias** in the criminal justice system

> Public defenders can then act immediately on that information to negotiate a better plea or sentence for the defendant.

*Key Highlight*

Our tool will clearly indicate and denote when bias/racism was detected and highlight it for attorneys to use in defense process.
Bias detection (highlighted clearly), demographics from uploads, key sentencing information that we mined and have within our tool, as well as recommendations from our tool make a public defenders job easier and frees up time to focus on case(s).

![](https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/Bias%20Detection.png)

### **Users and Skills**

* *Developers*:  skills: React, OSS, full stack (java, python), data science; user experience: need to develop a getting started process
* *End-users*:  skills: online training on navigating the tool 
* *Public*: skills:  none (intuitive interface); user experience:  immediate, informative, targeted information
* *Private beneficiaries*:  N/A 
* *SMEs* (Lawyers, American Bar Association, Southern Poverty Law Center, Judiciary NGOs):  skills:  unsupervised learning for training and expanding the ML/bias detection engine for new personas, locales, scope, crime types, etc.

### **Technical materials** - 

Aggregator
* Repo: https://github.com/embrace-call-for-code/outcarcerate-aggregator
* OpenAPI: https://github.com/embrace-call-for-code/outcarcerate-aggregator/blob/master/src/main/resources/swagger.yaml
* Service URL: https://outcarcerate-aggregator-decarcerate.embrace-dev-ocp43-vpc-7ec5d722a0ab3f463fdc90eeb94dbc70-0000.us-east.containers.appdomain.cloud/

UI (User-Interface)
*  Mock-up: https://ibm.invisionapp.com/share/92O0CQSMK7Q
*  Repo: https://github.com/embrace-call-for-code/outcarcerate-u
i

![](https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/UI%20Example.png)
![](https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/UIexample2.png)

### **Data Sources**

*  [United States Sentencing Commission](https://ida.ussc.gov/analytics/saw.dll?Dashboard)
* Uploaded files from lawyers, police, court staff, or links to case file management systems.
* Others Data Sources In progress (ideally we'd expand to all levels of government).



### **Architecture diagram** 
![][https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/architechture.png]

**Suggestions on how to take the idea in other directions**
Swapping out data sets  Bias integration, expand to entire judiciary personas and public facing dashboard (PS1 solution assessment of laws and bias mapped to assess your judges and local prosecutors) - integrated with all of theme 3 (arrest, police report, judiciary) and with hirings.

### **References**

* [Racial Disparity in Federal Criminal Sentences](https://repository.law.umich.edu/cgi/viewcontent.cgi?article=2413&context=articles)
* [Racial, Ethnic, and Gender Disparities In Federal Sentencing Today](https://www.ussc.gov/sites/default/files/pdf/research-and-publications/research-projects-and-surveys/miscellaneous/15-year-study/chap4.pdf)
* [The Growing Racial Disparity in Prison Time](https://www.themarshallproject.org/2019/12/03/the-growing-racial-disparity-in-prison-time)
* [Racial Disparity](https://www.sentencingproject.org/issues/racial-disparity/)
* [Unequal Treatment: Racial and Ethnic Disparities in Miami-Dade Criminal Justice](https://www.aclufl.org/sites/default/files/6440miamidadedisparities20180715spreads.pdf)
* [From police to parole, black and white Americans differ widely in their views of criminal justice system](https://www.pewresearch.org/fact-tank/2019/05/21/from-police-to-parole-black-and-white-americans-differ-widely-in-their-views-of-criminal-justice-system/)
[Public Defenders: Last Week Tonight with John Oliver ](https://www.youtube.com/watch?v=USkEzLuzmZ4)
[America's Public Defense System Is in Crisis](https://www.youtube.com/watch?v=xqLE4ryWMX4)

In addition, sponsor user interview Based Research Conducted by Outcarcerate Team included a judge and attorneys.
![](https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/ToBePD.png)

[Find Support Here](https://github.com/Call-for-Code/Embrace-Judicial-Reform/blob/main/SUPPORT.md)

*Thank you* for your interest and we truly hope this helps!

![](https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/Call%20for%20Code.png)

Team Members:

![](https://github.com/embrace-call-for-code/outcarcerate-docs/blob/master/OutcarcerateTeam.png)
