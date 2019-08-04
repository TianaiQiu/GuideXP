<h1> GuideXP Landing Page (2019 S2) </h1>

<h2><a name = "content"> Contents </a></h2>
<a href = "#Title1"><b> 1. Project Description </b></a><br/>
<a href = "#Title2"><b> 2. Outputs </b></a><br/>
<a href = "#Title3"><b> 3. Stakeholders </b></a><br/>
<a href = "#Title4"><b> 4. Team Roles and Management </b></a><br/>
<a href = "#Title5"><b> 5. Prototypes </b></a><br/>
<a href = "#Title6"><b> 6. Schedule </b></a><br/>
<a href = "#Title7"><b> 7. Links Summary</b></a><br/>

<br />
<h2><a name = "Title1"> 1. Project Description </a></h2>

The [GuideXP](https://guidexp.wordpress.com) is a local startup in Canberra with the vision of creating immersive visitor experiences for galleries, museums and more. GuideXP is a unique, cloud-based approach to audio guides, which allows for access to content from multiple attractions in one place and aims to minimise effort required in uploading and updating content.
In 2019, GuideXP is partnering with the ANU TechLauncher program to kick start our development. The program will enable us to create a first stage of our product roadmap while engaging with students and providing them real world experience.
We are currently seeking a partner institution to create or share visitor experience content and provide us with feedback as we develop the minimum viable product and test our value propositions. The partner institution will benefit from free use of the service for the duration of 2019.
The GuideXP Team consists of four members plus the our ANU TechLauncher team (TBC), with a myriad of experience in tech delivery projects, startups, and visitor experience. We are motivated and excited by the prospect of working with a renowned institution such as the National Capital Exhibition.


<br />
<h2><a name = "Title2"> 2. Outputs </a></h2>

**The Systems We Developed last semester**

As our client required, our source code is not open to the public. You need to use the GitHub account we provided to view the source code. We have provided this account in our audit presentation. We also sent an email that includes this account to tutors, examiners and shadow team. If you didn't get the account, please [open an issue](https://github.com/DannyFirmin/GuideXP/issues) in this repository and leave your email address, we will send it to you as soon as possible. We do apologise to the inconvenience.

* Visitor System:  
  * Deployed Address: http://new.guidexp.me/
  * [Source Code](https://github.com/DannyFirmin/guidexp.me) (Need to apply for permission here: http://new.guidexp.me/audit/)
  * JavaScript
  * Html/CSS
  * Bootstrap
* Administrator System: 
  * Deployed Address: http://admin.guidexp.me/
  * [Source Code](https://github.com/LiangHong95/django) (Need to apply for permission here: http://new.guidexp.me/audit/)
  * Django
  * Django REST framework
  * MySQL
  * Bootstrap
* API:
  * Return all exhibitions as JSON: http://admin.guidexp.me/api/exhibition/
  * Return the art's collection as JSON: http://admin.guidexp.me/api/exhibition/ExhibitionTest/
* Servers:
  * Configured Amazon Web Services (AWS) - Elastic Compute Cloud (EC2)
  * Configured Crazy Domains AU for DNS and domains
  * Configured nginx/uWSGI/Ubuntu

**The output for this semester**

This semester we will customize our system to support National Capital Exhibition.


* [Statement of work](https://github.com/LiangHong95/GuideXP-S2/blob/master/Statement%20of%20Work.pdf)
* [Meeting minutes](https://github.com/LiangHong95/GuideXP-S2/tree/master/Meeting%20minutes)
* [Decision log](https://github.com/LiangHong95/GuideXP-S2/blob/master/Decision%20Log.pdf)
* [investigation in National Capital Exhibition](https://github.com/LiangHong95/GuideXP-S2/blob/master/Meeting%20minutes/Investigation%20%20minutes.pdf)
* [last semester relfection](https://github.com/LiangHong95/GuideXP-S2/blob/master/Reflection.pdf) 
* [design of website](https://github.com/LiangHong95/GuideXP-S2/blob/master/Architecture.png)
* Setup PHP with Nginx on Linux Server
* GuideXP Internal Files Access Application (html+CSS+php)


<h2><a name = "Title3"> 3. Stakeholders </a></h2>

Visitors, Content creaters, galleries and museums

<br />



<h2><a name = "Title4"> 4. Team Roles and Management </a></h2>

**Roles**

| Team Member                      | Role                                     | 
|----------------------------------|------------------------------------------| 
| Kelin Zhu                        | Project manager                          | 
| Rutai Sun                        | Back-end(logic,algorithm)                | 
| Liang Hong                       | Back-end(database,test)                  |
| Yu Qiu                           | Back-end, API                            | 
| Yuanze Niu                       | Front-end (HTML,CSS), Documentation      | 
| Danny Feng                       | Front-end (HTML,CSS), Documentation      | 
| Yu Qiu                           | Back-end, API                            | 
| Tianai Qiu                       | Front-end (HTML,CSS), Documentation      |             

**Agile Tasks Assignment and User Stories**

[Trello](https://trello.com/b/ggidOa5S/guidexp-user-stories) <br />
![Trello](https://github.com/LiangHong95/GuideXP-S2/blob/master/trello.png)<br/>


**Team Communication**

Team meetings <br />
Team activities <br />
Slack <br />
Meeting Minutes <br />
<br />

<h2><a name = "Title5"> 5. Prototypes </a></h2>

[GUI Interaction](https://marvelapp.com/317d466/screen/33853357) <br />
[Wordpress](http://www.guidexp.me/) <br />

<h2><a name = "Title6"> 6. Schedule </a></h2>

**Schedule:**

|Period            |    Milestones                                                                                | 
|------------------|----------------------------------------------------------------------------------------------| 
|Week2 - Week3     |Discovery report                                                                              |
|Week4 - Week5     |Optimize existing system to support new requirements                                          |
|Week6 - Week7     |Build a prototype guide with several example exhibitions from the National Capital Exhibition |
|Week8 - Week9     |IImprove the website pattern & add all the data                                               |
|Week10 - Week11   |Add multi-language supporting function                                                        |  
|Week12            |Test, debug and gather feedback from clients and pass onto our clients                        |

<br />

**Milestones:**

| Phase          |    Milestones                                                                               | 
|----------------|---------------------------------------------------------------------------------------------| 
| Phase 1        |Discovery report                                                                             |
| Phase 2        |Database construction and webpage functions.                                                 |
| Phase 3        |Useable prototype guide of several example exhibitions from the National Capital Exhibition  |
| Phase 4        |Improved guide for the National Capital Exhibition with provided exhibition data             |
| Phase 5        |Website supports multi-language                                                              |  
| Phase 6        |Test the website and pass to clients                                                         |

<br />


<h2><a name = "Title7"> 7. Links Summary </a></h2>

* [GuideXP Previous Landing Page](https://github.com/DannyFirmin/GuideXP)
* [GuideXP Vistor System](http://new.guidexp.me/)
* [GuideXP Admin System](http://admin.guidexp.me/)
* [GuideXP API](http://admin.guidexp.me/api/exhibition/)

We will offer shadow team members, tutors and examiners premission to access the following contents in the first audit
the permission can be reqired by the following link[http://new.guidexp.me/audit/]

* [GuideXP Agile Board (Trello)](https://trello.com/b/ggidOa5S/guidexp-user-stories) (NEED PERMISSION)
* [GuideXP Visitor System Git-repo](https://github.com/DannyFirmin/guidexp.me) (NEED PERMISSION)
* [GuideXP Admin System Git-repo](https://github.com/LiangHong95/django) (NEED PERMISSION)

You can apply for access permission here: http://new.guidexp.me/audit/ 
