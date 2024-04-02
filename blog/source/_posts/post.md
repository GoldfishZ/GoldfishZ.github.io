---
title: About Me
---

**Welcome to GoldfishZ's homepage! This is an introduction about me that covers some basic personal information about me.**

<!-- <center> This is me </center> -->

<!-- ![pic](/images/image1.jpg) -->

## Basic Information

<div style="width: 40%; float: left; margin-top: 50px;">

<i class="fas fa-user"></i> **Name**: 张润今（Zhang Runjin）

<i class="fas fa-birthday-cake"></i> **Birthday**: 2002.11

<i class="fas fa-mars"></i> **Gender**: Male

<i class="fas fa-phone"></i> **Telephone**: 18320878083

<i class="fas fa-envelope"></i> **Email**: 2366385033@qq.com

<i class="fab fa-github"></i> **Github**: https://github.com/GoldfishZ

<i class="fas fa-school"></i> **Department**: Department of Computer Science & Technology

<i class="fas fa-book-open"></i> **Major**: Computer Science & Technology

<i class="fas fa-home"></i> **Hometown**: Meizhou,Guangdong

<i class="fas fa-home"></i> **Birthplace**: Shenzhen,Guangdong

<i class="fas fa-user-graduate"></i> **Education**: Undergraduate, Zhejiang University

<i class="fas fa-graduation-cap"></i> **GPA**: 3.86/4(86.2/100)

<i class="fas fa-language"></i> **IELTS**: 7.0(8.0/7.5/6.5/6.5)

</div>
<div style="width: 50%; float: right;">
  <img src="/images/image1.jpg" alt="pic" style="width: 100%;">
</div>
<div style="clear: both;"></div>

## Projects

**Below I will describe some of the projects I completed during my college years. The introductions in this blog are rough introductions, for more details please go to the respective blogs.**

<div style="border: 1px solid black; padding: 10px; margin-bottom: 10px;">

### IOT device manage system

**Solo Work**

<i class="fas fa-calendar"></i> 2023-2024 winter

<div style="width: 50%; float: right; padding: 10px;">
The goal of this project is to develop an IoT device management platform that can receive data sent by designated IoT terminal simulators, achieve user registration and login functions, and fill in necessary information and verify it during user registration. After logging in, users can create or modify device information, including necessary information such as device ID, device name, device type, etc. At the same time, the platform should also be able to provide a query and statistics interface for device reported data, a map interface to 
</div>
<div style="width: 48%; float: left; padding: 10px;">
  <img src="/images/iot.png" alt="pic" style="width: 100%;">
</div>
<div style="clear: both;"></div>
display device information, distinguish normal and alarm information, etc. Historical data of some device types can be displayed as historical trajectories. The homepage should be able to provide statistical information, and display it in a graphical format.

#### Technology stack usage

- Front-end: Based on React, using javascript as programming language
- Back-end: Based on Java Springboot, use JDBC to connect to the database(mysql).
- Front-end & Back-end Connection: Via Cross-Domain
- Server: The open source server mosquitto was used, and a subscription side was implemented in python to bind the port

#### Highlights

- The whole project is implemented based on B/S architecture
- The scope of coverage is extremely broad, and the entire project needs to be covered from front-end and back-end to servers and other content
</div>

<div style="border: 1px solid black; padding: 10px; margin-bottom: 10px;">

### Football Tactic Visualization

**Group Work.Complete in a group of two**

<i class="fas fa-calendar"></i> 2023-2024 winter

<div style="width: 40%; float: left; padding: 10px;">
In this project, the group selected the 2017-18 season of the English Premier League as the research object. We designed a data mining algorithm to analyze game data, designed effective visual elements to present the tactics adopted by the team in the game, analyzed and evaluated the performance of athletes in the game, and ultimately implemented a visual analysis system for football game tactics. Through the use of various visual elements, engineering provides clear and intuitive tactical images for data users.
</div>
<div style="width: 50%; float: right; padding: 10px;">
  <img src="/images/vis.png" alt="pic" style="width: 100%;">
</div>
<div style="clear: both;"></div>

#### Technology Stack Usage

- Front-end: Based on React, using javascript as programming language
- Back-end: Using python

#### Highlights

- This project is a laboratory project that participated in the VIS group of Zhejiang University, and the work was completed under the guidance of the engineering
- Referenced paper《Automatic discovery of tactics in spatio-temporal soccer match data》,The algorithm is reproduced.
- A variety of different data representations are used in the front-end, and a variety of visualization elements are represented in a detailed and comprehensive manner.
</div>

<div style="border: 1px solid black; padding: 10px; margin-bottom: 10px;">

### Tetris

**Group Work.Complete in a group of three**

<i class="fas fa-calendar"></i> 2023 summer

<div style="width: 45%; float: right; padding: 10px; margin-top: 35px;">
This project is an implementation of the classic game Tetris. Designed as a relatively short-term endeavor, our aim is to enhance user experience by creating a more aesthetically pleasing UI. Employing the MVVM (Model-View-ViewModel) architecture, we structured the development to ensure clear separation of concerns and facilitate easier maintenance and testing. Our collaborative development process took place on GitLab, allowing for seamless integration and version control.
</div>
<div style="width: 45%; float: left; padding: 10px;">
  <img src="/images/tetris.png" alt="pic" style="width: 100%;">
</div>
<div style="clear: both;"></div>

#### Technology Stack Usage

- Language: C++
- Tools: Qt Creator

#### Highlights

- The whole project is based on the MVVM architecture, which is divided into the Model layer, the View layer and the ViewModel layer
- The whole project strictly uses git synchronization and integration, and synchronization is carried out on gitlab
</div>

<div style="border: 1px solid black; padding: 10px; margin-bottom: 10px;">

### Minisql

**Group Work.Complete in a group of three**

<i class="fas fa-calendar"></i> 2023 summer

<div style="width: 50%; float: left; padding: 10px; margin-top: 35px;">
The miniSQL database management system completed in this project refers to the MySQL database, allowing users to input statements that comply with SQL syntax specifications through a character interface, achieving functions such as data insertion, querying, updating, and deletion in the database, database mode creation and modification, and data access control. MiniSQL implements the functions of database data definition, data manipulation, data control, and data abstraction.
This project is mainly divided into five modules: the Buffer Pool Replacer is responsible for tracking the usage of data pages in the Buffer Pool and deciding which data page to replace when there are no free pages in the Buffer Pool. The Record module is mainly used to process inserted tuples, and the Index module is mainly responsible for managing indexes. The Catalog module is mainly responsible for contacting the relevant information of tables and indexes in the top-level and data pages. The Executor module is mainly responsible for the top-level and front-end operations. It requires the ability to read the commands input by the user on the terminal, parse them into commands that the system can execute, and perform database operations to return results
</div>
<div style="width: 45%; float: right; padding: 10px;">
  <img src="/images/minisql.png" alt="pic" style="width: 100%;">
</div>
<div style="clear: both;"></div>

#### Techonlogy Stack Usage

- Language: C++
- Environment: Linux
- Development Approach: Vscode + WSL

#### Highlights

- Use github for synchronous development
- The engineering framework is rewritten with reference to the CMU-15445 BusTub framework, which is relatively mature
</div>

## Publications

<div style="width: 50%; float: left; padding: 10px; margin-top: 35px;">
<strong style="font-size: 2em;">Team-Scouter: Simulative Visual Analytics of Soccer Player Scouting</strong>
<br>
Anqi Cao , Xiao Xie , <strong>Runjin Zhang</strong> , Yuxin Tian , Mu Fan , Hui Zhang , Yingcai Wu

March 31,2024

</div>
<div style="width: 50%; float: right; padding: 10px;">
  <img src="/images/publication.png" alt="pic" style="width: 100%;">
</div>
<div style="clear: both;"></div>

<div style="width: 15%; float: left; padding: 10px; margin-right: 20px; text-align: left;">
</div>

<div style="width: 15%; float: left; padding: 10px; margin-right: 20px; text-align: left;">
<p><strong>Type </strong></p>
<p><strong>Publication</strong></p>
<p><strong>Date</strong></p>
</div>

<div style="width: 65%; float: left; padding: 10px; text-align: left;">
<p>Journal Article</p>
<p>IEEE Transactions on Visualization and Computer Graphics (IEEE VIS 2024)</p>
<p>March 2024</p>
</div>
<div style="clear: both;"></div>

## Awards

- <i class="fas fa-award"></i> **Zhejiang University Scholarship-Third Prize**
- <i class="fas fa-award"></i> **Academic Excellence Award**

## Hobbies

### Football

- Fan of Manchester United
- Usually play as a Striker
- Guangzhou is the most successful team in China

Football is one of my favourite sports and I have been participating in this sport since primary school. Not only do I love to play football, but I also love to watch it and have participated in many football matches. I have put my passion for football into my research and have done two projects related to football and have gained a lot.

<img src="/images/football.jpg" alt="pic" style="width: 100%;">

### Basketball

- Fan of Los Angeles Lakers
- Fan of LeBron James
- Play as guard usually
- Support China's basketball juggernaut —— Guangdong.

Basketball is a sport I play regularly, and likewise, I was introduced to him in primary schools. Compared to football, basketball requires less court and number of participants, so many times I spend more time playing basketball than football.
Unfortunately, I didn't get the photos that satisfied me <i class="fas fa-face-sad-cry"></i>
