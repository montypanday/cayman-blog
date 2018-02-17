---
title: My journey as the Team Lead
layout: post
author: "Monty Panday"
---

This post describes my journey as the Team Leader for Team 10 during T2 and T3, 2017.

I am a final year student at Deakin University studying Bachelor of Information Technology and will be graduating in July 2018. I recently completed two interesting units, SIT 374 - Project Design and SIT 302 - Project Delivery.

## My Capabilities
As the team lead, I was responsible for the overall success of the project. I played a major role in deciding the project architecture, languages and delivered to the team both as the lead programmer and team leader. Please find below the list summarizing my achievements in this project: -
- Experience writing WEB API's. Built a .NET CORE WEB API which utilizes both Box and Google Drive SDK's to integrate both platforms into the application.
- Experience building Single Page Applications using ReactJs. Contributed significantly in the UI development. Wrote code for all events, react lifecycle events and fetching data from API.
- Handled all client communications, discussed ideas, provided updates, responded to suggestions and implemented them.
- Guided my team members so they can contribute to the project using their skills, help them learn new skills, assigned tasks and ensured that project completes on time by overcoming all hurdles.

## Project Assets
The code is in a private repository managed by me. If anyone wants access to the repository, they can use the Contact form to send me an email.

The application is hosted on Azure and is available at [https://docchain.azurewebsites.net](https://docchain.azurewebsites.net).

The Swagger documentation for the API is available at [https://docchain.azurewebsites.net/swagger](https://docchain.azurewebsites.net/swagger)

Please feel free to try the application. It uses external authentication using **Oauth 2.0**. You can log in using your Box or Google Drive account, see all your files and folders, select any file, embed its hash onto the blockchain. You can later come back and check if the file has changed or not.

# Assertion

## Introduction
The Team built an application that allows users to login with their Box or Google Drive account, manage their files and use our BlockChain Infrastructure to verify the integrity of their files.

It is a Single Page Application built using ReactJs with a .NET CORE WEB API as backend. Currently, it also uses a MSSQL database for logging user actions.

Our client [LINCD](https://www.lincd.co/) provides BlockChain infrastructure as a service. This application is built as proof of concept for client's idea that BlockChain can be used for document integrity verification. In future, the application will be used by lawyers and accountants.

By the end of sprint 4, we successfully completed the project to client expectations. The team presented the project at the showcase which was a unique experience in itself.

## My contribution to the project

**I was the lead programmer in the team for all the four sprints. By the end of the sprint 4, I built the WEB API on my own, introduced encrypted cookies, wrote Swagger documentation, wrote all code related to Box and Google Drive, made sure that all actions like uploads, downloads, file/folder renames/deletions/sharing etc. actually work without errors. I wrote most of the ReactJs code, refactored it again and again to improve performance and speed.**

**I also handled all communications with the client and use to send weekly updates in the form of videos which you will find below. As the team lead, I also managed internal team communication, flow of ideas, helped my team mates in resolving errors and learning about how the project works.**

![My Contributions to repository](/images/github_monty.png)

**The response received regarding weekly video updates**

![Client liked videos](/images/videos_good_email_client.png)


**Client liked the UI, Swagger Documentation, cookie encryption, API and other features**

![Client liked videos](/images/email_2.png)


**Team Feedback on SparkPlus**

![Team Feedback for me](/images/1.png)

![Team Feedback for me](/images/2.png)


![Team Feedback for me](/images/3.png)

![Team Feedback for me](/images/4.png)

![Team Feedback for me](/images/5.png)

**Client Feedback**

![Client Feedback](/images/6.png)

![Client Feedback](/images/7.png)

**Swagger Documentation**

![Client Feedback](/images/8.png)  

**App Performance Insights**
![Health](/images/9.png)  



At the start of the project, the architecture, languages and implementation of the project was not fixed. My first task was to figure out the best options and propose a solution to the client that was feasible. I had the choice of using either Angular or ReactJs for building the UI. I tried and studied both languages and decided to use ReactJs because of its simplicity, support and component based architecture. I also proposed two backend solutions using Node.js(Express) and .NET Core. We used .NET Core because of client suggestions as their codebase follows the .NET architecture.

I proposed the idea to built the application for existing cloud storage users than setting up a new storage platform because that would have diverted the team away from the core features of the application.

The project was aimed to built a file storage product and the requirements didn't specify that the application should incorporate support for Box, Google Drive or any other platform. However, the project name was Box.com meets blockchain. This made me think it should be able to work for Box users. This was later confirmed with the client when I proposed a solution and discussed and defined project requirements which were earlier "vague" as my supervisor said.

It is to be noted that at that point of time, did not have any previous experience with ReactJs or .NET Core or writing API's. The same situation was with the other team members. I had to find a solution so that the team could finish the project fulfilling all major project requirements.

The solution I found was to use React components from Box in our application to incorporate support for Box. These components are available [here](https://www.npmjs.com/package/box-ui-elements).


## Summary
I received a very good response from my feedback. When the supervisor said that the team have performed much better than what was expected from us, I realised my efforts as the team leader successfully yielded results. I learnt lot of discipline specific skills + new programming language ( ReactJs ) + project management skills which will definitely help me in future. Also, working with our supervisor Prof. Leonard Hoon was a unique experience. I am grateful for his support and attention. He is one of the best mentors I ever had.
