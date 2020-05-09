# Global-Talents
Global Talents Requirement Specifications  

 

What is Global Talents? 

Freelancing happens to be the new favourite thing of individuals of this century. Research shows that year by year number of people freelancing has been increasing rapidly. And 63% of them chose freelancing by choice rather than by necessity in 2016. Apart from the supply side, demand side has also increased. Where, number of freelancers have increased, demand for such services has also increased. Study shows that in 2017, 46% of the freelancers saw an increased demand for their services in 2016.  

Global Talents provides a web based freelancing platform where the we connect the businesses, individual freelancers and employers. In our online market space, employers can hire people to work on different areas and technologies such as Website Development, Software development, Designing, data science, data entry, etc. 

Mission  

To create economic opportunities for talented and skilled people and also ensure employers find the right people for their work without much hassle. 

 

System Interface 

Apache will be used as web server. The user inputs data via the web server using HTML forms. The actual program that will perform the operations is written in PHP. 

User interface  

The new system shall provide a very intuitive and simple interface to the user and the administrator, so that the user can easily navigate through pages, view freelancers’ profiles, Create own profiles, search for Jobs and services etc.  

Hardware Interface  

Server side: The web application will be hosted on a web server which is listening on the web standard port.  

Client side:  Monitor screen – the software shall display information to the user via the monitor screen Mouse – the software shall interact with the movement of the mouse and the mouse buttons. The mouse shall activate areas for data input, command buttons and select options from menus. Keyboard – the software shall interact with the keystrokes of the keyboard. The keyboard will input data into the active area of the database. 

Software Interface 

Server side: An Apache web server will accept all requests from the client and forward it accordingly. A database will be hosted centrally using MySQL.  

Client side: An OS which is capable of running a modern web browser which supports JavaScript and HTML5. 

Communication Interfaces  

The HTPP or HTTPS protocol(s) will be used to facilitate communication between the client and server. 

Operations  

The product shall have operations to protect the database from being corrupted or accidentally altered during a system failure. 

Specific Requirements(Technical) 

External interface 

 Web Server: 

Apache will be used as web server:  

The user inputs data via the web server using HTML forms  

The web server executes the PHP as a module and PHP script retrieves the post data if available.  

The web server receives information back from the PHP script. 

The web server displays a HTML page as result to the end-user.  

 

Back-End Application  

The actual program that will perform the operations is written in PHP. All data will be stored in a database.  

MySQL Database 

It’s an open source MySQL database to store all data which communicates with the application on the server. 

Front End Application 

The front-End coding will be done with CSS (Bootstrap framework), HTML and JavaScript.  

 

 

 

 

 

 

 

 

Major Modules 

Freelancers: 

This module provides all the functionalities for freelancers and businesses (providing various services), which mainly covers maintaining their profiles, Uploading CVs, applying to posted jobs, etc. 

Profile types: 

Freelancers 

Agencies/businesses 

Customer/Employer: 

This module majorly covers the functions and actions the employers can do, which mainly covers maintaining their profiles, their interest areas, posting jobs or projects which require freelancers. Search and view profiles of freelancers. 

Administration Module: 

Administration related functionalities, Managing the entire application. Admin accesses to update delete and make changes to profiles of both freelancers and Employers.  

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

 

Important Pages for the website 

 

User Registration: 

User Credentials: Email, Username, Password, Age, Gender.  

 

User Login:  

Credentials: Email, Password.  

 

 Qualification: 

Credentials: Education, Highest level of Education, Skills, Experience, Resume, Area Of Interest.  

 

Browsing Page: 

Showing all Jobs and Internship. (Apply) 

Filter Options on the basis of 1) Interest 2) Skills 3) Location 4) Duration 5) Salary 6) Sector 

 

User Applications Page: 

Showing all the user applications and the no. of candidates applied for the position.  

Each Appication will show status: 1) Applied 2) InTouch 3) under Review 4) Selected 5) Not Selected  

 

Company Registration: 

With Name, Email, Address, Description, No. of Employees, Password, Others.  

Options 1) FreeLancing 2) Fulltime 3) Internship 

Dashboard for each Section.   

 

Company Login: 

With Email and Password 

 

Company Requirements: 

Displaying Source Talent Pages giving options to company to look for the talents in different sector.  

Company Will add: 

Separate Category for Freelancing, Interns and Fulltime.  

Duration of Project, No. of Employees required, Salary.  

 

Payment Gateway: 

Company will pay to the candidate through our Portal.  

 

Subscription Plans Page 

 

 

 

Initial Functional Requirements 

Global Talents Requirements Specification GT-2 

Target Release 

v1.0 

Epic 

https://globaltalents.atlassian.net/browse/GT-18 

Document Status 

DRAFT  

Document Owner 

Nilabdhi Majumdar 

Developers 

Krushna Raut Rakesh B. Amrutkar Sarang Ghode Manish Bhilare  

Documents 

 

BACKGROUND AND DETAILS 

Global Talents provides a web based freelancing platform where the we connect the businesses, individual freelancers and employers. In our online market space, employers can hire people to work on different areas and technologies such as Website Development, Software development, Designing, data science, data entry, etc. 

BENCHMARK WEBSITES 

UPWORK (https://www.upwork.com/) 

FREELANCER (https://www.freelancer.com/) 

# 

User Story Title 

User Story Description 

Priority 

Notes 

1 

Home page Login/Sin Up 

As a User I want an option to login or sign up from Home Page. 

Must Have 

 

 

Search Bar 

As a User I want a search bar with parameters or filters to set for the search 

 

Must Have 

 

2 

Home Button 

As a User I want to always have an option to Go back to Home page 

Must Have 

 

3 

Popular Services/Job Categories 

As a User I want to have an option to view popular freelancing services or Job categories postings and also trending/top skills directly on home page 

Should Have 

 

4 

Recent Job Listings 

As a User I want to have an option to view the recent job listings directly on home page with a button to view all Job Listings 

Good To Have 

 

5 

Most Featured Freelancers 

As a User I want to have an option to view the most featured  

Good To Have 

 

6 

Top Companies 

As a User I want to have an option to view top companies offering Jobs on the home page itself. 

Good To Have 

 

7 

How things work 

As a User I want to have an option to have a summarized view of the process of How the process of hiring and Job posting works.  

 

Must Have 

 

8 

Major Links On Home Page 

As a User I want to see the following links at the bottom of the home page: About Us, Terms & Services, Company Reviews, Contact Us, Contact Info, Browse Freelancers by Location. 

Must Have 

 

 

Global Talents Requirements Specification 

Target Release 

v1.0 

Epic 

Registration and user profile. 

Document Status 

DRAFT  

Document Owner 

Nilabdhi Majumdar 

Developers 

Krushna Raut Rakesh B. Amrutkar Sarang Ghode Manish Bhilare  

Documents 

 

 

BACKGROUND AND DETAILS 

Global Talents provides a web based freelancing platform where the we connect the businesses, individual freelancers and employers. In our online market space, employers can hire people to work on different areas and technologies such as Website Development, Software development, Designing, data science, data entry, etc. 

BENCHMARK WEBSITES 

UPWORK (https://www.upwork.com/) 

FREELANCER (https://www.freelancer.com/) 

 

 

 

 


 

 
