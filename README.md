# Software Engineer Portfolio

This document contains the portfolio of Jason Swift and showcases what I have worked on as an Associate Software Engineer. The purpose of this porfolio is to highlight my contributions.

## Table of Contents
  * [Introduction](#introduction)
  * [Some Projects of Mine](#some-projects-of-mine)
    * [Creating Custom Sonar Rules](#creating-custom-sonar-rules)
    * [Main Message Definition Screen](#main-message-definition-screen)
    * [Cascade Tool](#cascade-tool)
    * [AppHub Validation](#appHub-validation)
    * [Rocket Logic Toolbox](#rocket-logic-toolbox)
    
  * [Mentorship](#mentorship)
  * [Opportunities](#opportunities)
  * [Technical Excellence](#technical-excellence)
    * [Master My Craft](#master-my-craft)
    * [Problem Solving](#problem-solving)
   
# Introduction

I started as an Associate Software Engineer at Rocket Mortgage in Spring of 2020. My role on the Business Apllication Engineering team then and today is to provide support across AMP. I have 3 years of experience developing with OpenEdge on enterprise systems, and I am continuously broadening my knowledge of OpenEdge and other various tools and languages.

# Some Projects of Mine

Below are some noteworthy projects I've worked on in my current role as an Associate Software Engineer.  

## Creating Custom Sonar Rules
  *  (https://git.rockfin.com/AMP/custom-sonar-rules/pull/182) 
  *  (https://git.rockfin.com/AMP/custom-sonar-rules/pull/107)

Here I wrote a custom Sonar rule to warn if any rules were not followed. These rules include checking to see if the code is reading in unencrypted secrets and ensuring buffer name follows our coding standards. Impact the unencrypted secrets has is to prevent data leakeage in the database, ensuring that we as a business do not open our selves up to possible data risks by having the data encrypted. The rule for buffer names follows our coding standards, ensuring our programs are readable with a uniformed buffer styles, which allows every team to understand the program much easier.  The technologies used were Java, Maven, Progress and GitHub.

## AppHub Validation
  * Add Validation for Apphub

    *  (https://git.rockfin.com/AMP/ampgate/pull/13926)
    
Here this code validates that each item in codeowners is correlated to an Business Criticality, Status and Source Control URL. Additionally this update requires that new files belong to a capability and is a hard gate. This impacts the business to ensure all new programs that are pushed have a codeowners with the related fields filled out. By doing so the business can easily identify who owns a program, and quickly contact that team with any questions if they occur. The technologies used were Python and Bash.

## Main Message Definition Screen 
  * Add additional filter to Main Message Definition Screen 

    *  [2848350] 
    
Here this additional filter impacts the business by allowing team members to filter down the selection on the screen. The impact this screen has on the business is that it saves the team member time when finding the correct field. My contribution to this was the creation of the screen to suit the needs Property Qualifer Teams Tonya Seymour. The technology used was Progress 4GL.
    
## Cascade Tool
  *  [3088451]
  *  [3054208]
  *  [3068595]

This tool is used to update team members information across all loans updating permissions and security records. This impacts the business by allowing BA's to make mass updates without needing to be online after hours. The first screen I created was a mass status update which allowed the BA's to update name, email, fax and pager. Allowing our business to remnain current impacts the business by guarnatee the right information is available and easy to change. The next screen allows updates to occur during the day it loan amount is under 300, and overnight if its over. The impact this has is to ensure the update doesn't slow down the overall system during business hours. The third program I created was a program that sends out a email to the BA informing them of all user functions that were updated after the cascade was ran. This impacted the business by having it easier for the BA's to verify the updates have taken place. The technology used was Progress 4GL.
       
## Rocket Logic Toolbox
  *  (https://git.rockfin.com/BusinessApplicationEngineering/RL-Toolbox-UI) 
  *  (https://git.rockfin.com/BusinessApplicationEngineering/RL-Toolbox-BFF)

Here I have been currently working with my team connect the front end to the backend for Rocket Logicv Toolbox. The first story I have worked on is creating an API call to credit data orchestrator to get the verififed status. This impacts the business by allowing users to compare the value stored here with open amp to determine if the two are aligned. Another story I have worked on is SQS. SQS once called will resynce the verified staus of credit data orchestrator and Open Amp. The business impact of this story is easily sync Amp with SQS without having to manually delete and enter the information. The technology used so far are Typescript. 
  
# Mentorship
* In the past year I've had the opportunity to be mentored by three team members, all with different experience levels and exposure to AMP. Each team memeber had over 20 years of experience in coding and was able to share what they have learned over the years in an easy to understand way. Things I have learned in my mentorship is how create object in Amp.      
* I have shared the knowledge I gained in my mentorships with my team and others that are interested in programming. One such thing I shared with the team is how objects and classes are used in Amp.

# Opportunities

* **Mentorship** - I enjoy learning new approaches to imporve my code and sharing my knowledge. Over the last two years I have been able to learn from my mentorships from the Performance Engineering Team. I was than able to share what I learn with my fellow team members.

# Technical Excellence
## Master My Craft
  **Training**  - I continuously look for ways to improve myself and add value to Rocket Mortgage.  Below are some of my recent training endeavours.
  
  * Attended Agile Training. Agile training taught me the improtance of breaking down projectsd into smaller pieces, so it can be easily iterated over.
  * Team Learning Linkedin - Business Software And Tools. This Linkedin learning showcased tools for time managment for small projects.  
  * Team Learning Linkedin - Data Science. This learning reviewed how to clean data and apply data models.
  * Hack Week- Machine Learning with Don Ward. This training used Kaggle to learn machine learing for data science.
  * Hackathon Project Posture Monitor - This project captures your image and alerts you if you have bad posture. My contribution to the project was to connect the camera to the application, allowing us to capture pictures. Technologies used for this project was Python.
  * Sonar Rules With Ken Herring - This training provided further insight on how to create sonar rules using Visual Studio Code. 
  * Amazon Sage Maker Canvas with Jordan LaFramboise - This training showcased how machine learning models are developed by non engineers. Knowing this allows me to bridge the knowledge gap of what tools the business side has.
  * AWS Pipelines with Jordan LaFramboise - Provided hands-on experience in building near serverless real-time data processing pipelines on AWS, growing my overall knowledge base regarding data. 
  
## Problem Solving
On the Business Application Engineering Team I am often called on to research and find a solutions. One such example is the research for MyVault. The research of MyVault is crucial to identify programs that open us to security risks that need to be encrypted. A solution from the research I implemented was put into place a Sonar Rule that prevents this possible data leakage.
