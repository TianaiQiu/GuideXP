<h1> GuideXP Landing Page (2020 S1) </h1>


<h2><a name = "content"> Content </a></h2>
<a href = "#Title1"><b> 1. Links Summary For Previous Semesters</b></a><br/>
<a href = "#Title2"><b> 2. Project Description </b></a><br/>
<a href = "#Title3"><b> 3. Project Objectives </b></a><br/>
<a href = "#Title3"><b> 4. Stakeholders </b></a><br/>
<a href = "#Title4"><b> 5. Code and Documentation </b></a><br/>
<a href = "#Title5"><b> 6. Team Roles and Management </b></a><br/>
<a href = "#Title6"><b> 7. Prototypes </b></a><br/>
<a href = "#Title7"><b> 8. Timeline and Milestones </b></a><br/>


<br />

<h2><a name = "Title1"> 1. Links Summary For Previous Semesters </a></h2>

* [GuideXP 2019 S1 Landing Page](https://github.com/DannyFirmin/GuideXP)
* [GuideXP 2019 S2 Landing Page](https://github.com/LiangHong95/GuideXP-S2)
* [GuideXP Vistor System](http://www.guidexp.me/)
* [GuideXP Admin System](http://admin.guidexp.me/)

 



<br />
<h2><a name = "Title2"> 2. Project Description </a></h2>

The [GuideXP](https://guidexp.wordpress.com) is a local startup in Canberra with the vision of creating immersive visitor experiences for galleries, museums and more. GuideXP is a unique, cloud-based approach to audio guides, which allows for access to content from multiple attractions in one place and aims to minimise effort required in uploading and updating content.
In 2019, GuideXP is partnering with the ANU TechLauncher program to kick start our development. The program will enable us to create a first stage of our product roadmap while engaging with students and providing them real world experience.
We are currently seeking a partner institution to create or share visitor experience content and provide us with feedback as we develop the minimum viable product and test our value propositions. The partner institution will benefit from free use of the service for the duration of 2019.
The GuideXP Team consists of four members plus the our ANU TechLauncher team (TBC), with a myriad of experience in tech delivery projects, startups, and visitor experience. We are motivated and excited by the prospect of working with a renowned institution such as the National Capital Exhibition.


<br />
<h2><a name = "Title3"> 3. Project Objectives </a></h2>

**The Systems We Developed last semester**

As our client required, our source code is not open to the public. You need to use the GitHub account we provided to view the source code. We have provided this account in our audit presentation. We also sent an email that includes this account to tutors, examiners and shadow team. If you didn't get the account, please [open an issue](https://github.com/DannyFirmin/GuideXP/issues) in this repository and leave your email address, we will send it to you as soon as possible. We do apologise to the inconvenience.

* Visitor System:  
  * Deployed Address: http://new.guidexp.me/
  * [Source Code](https://github.com/DannyFirmin/GuideXP-Codes/tree/master/front-end) (Need to apply for permission here: http://new.guidexp.me/audit/)
  * JavaScript
  * Html/CSS
  * Bootstrap
* Administrator System: 
  * Deployed Address: http://admin.guidexp.me/
  * [Source Code](https://github.com/DannyFirmin/GuideXP-Codes/tree/master/back-end) (Need to apply for permission here: http://new.guidexp.me/audit/)
  * Django
  * Django REST framework
  * MySQL
  * Bootstrap
* API:
  * Return all exhibitions as JSON (NEW): http://13.239.36.190/api/get_exhibition/en/1/all
  * Return the art's collection as JSON: http://admin.guidexp.me/api/exhibition/ExhibitionTest/
* Servers:
  * Configured Amazon Web Services (AWS) - Elastic Compute Cloud (EC2)
  * Configured Crazy Domains AU for DNS and domains
  * Configured nginx/uWSGI/Ubuntu

**Other Files**

* [Statement of work](https://github.com/LiangHong95/GuideXP-S2/blob/master/Statement%20of%20Work.pdf)
* [Design of website](https://github.com/LiangHong95/GuideXP-S2/blob/master/Architecture.png)
* Database design
    - [first vision](https://www.lucidchart.com/invitations/accept/39d53fbc-2016-4d15-a900-5f4fec0fa3a1) 
    - [second vision](https://www.lucidchart.com/invitations/accept/417d04a8-97d1-422d-bb2d-6080383ad8e0)
    - [third vision](https://www.lucidchart.com/invitations/accept/3d2586b6-eec2-4e6a-8d67-1ba96490d14f) 



<h2><a name = "Title4"> 4. Stakeholders </a></h2>

Visitors, Content creaters, galleries and museums

<br />

<h2><a name = "Title5"> 5. Code and Documentation </a></h2>

 We write lots of code every week, check it here:
[**GuideXP Code Git-repo**](https://github.com/DannyFirmin/GuideXP-Codes) (You should have the premission to access)

**Documentation**

[**Google Drive Documents**](https://drive.google.com/drive/folders/1QoNqJZiU1M6AorfAg9V4DFvdGGcFCpim)

[**Satement of Work**]()

[**Non-Disclosure Agreement**]()

[**Decision Log**]()

[**Meeting Minutes**](https://drive.google.com/drive/folders/1h3PqQCQRvhWUd26UFqAXK24vy-yfvR3_)

[**Risk Register**]()

[**Project Constraints**]()


<h2><a name = "Title5"> 6. Team Roles and Management </a></h2>

**Roles**

| Team Member                      | Role                                     | 
|----------------------------------|------------------------------------------| 
| Tianai Qiu                       | Project manager,scrum manager            | 
| Bo Liu                           | Front-end (HTML,CSS), Documentation      | 
| Yihua Zhang                      | Front-end (HTML,CSS), Documentation      |
| Yu Qiu                           | Back-end, API, Documentation             |              

**Agile Tasks Assignment and User Stories**

[Trello](https://trello.com/b/XKZ5eXEm/guidexp-techlauncher-2020) <br />
![Trello](https://github.com/LiangHong95/GuideXP-S2/blob/master/trello.png)<br/>


<h2><a name = "Title6"> 7. Prototypes </a></h2>

[GUI Interaction](https://marvelapp.com/317d466/screen/33853357) <br />
[Wordpress](http://www.guidexp.me/) <br />

<h2><a name = "Title7"> 8. Timeline and Milestones</a></h2>

**Timeline:**

|Period               |    Schedule                                                                                  | 
|---------------------|----------------------------------------------------------------------------------------------| 
|Week2                |Discovery of requirements, organize all files and documents.                                  |
|Week3 -Week4         |Design Admin panel and create a wireframe for it.                                             |
|Week5 - Week6        |Implement the design of Admin panel.                                                          |
|Week7 - Week8        |                                                                                              |
|Week9 - Week10       |Finalize implementation of Admin panel, prepare testing.                                      |
|Week11 - week12      |Test, debug and gather feedback from clients and pass onto our clients.                       |

<br />

**Milestones:**

| Phase          |    Milestones                                                                               | 
|----------------|---------------------------------------------------------------------------------------------| 
| Phase 1        |Discovery report.                                                                            |
| Phase 2        |The design of Admin panel be confirmed by clients.                                           |
| Phase 3        |Useable prototype of Admin panel.                                                            |
| Phase 4        |Improved version of Admin panel.                                                             |
| Phase 5        |The Admin panel works with modern desktop web browsers and mobile devices.                   |
                                                      

<br />


