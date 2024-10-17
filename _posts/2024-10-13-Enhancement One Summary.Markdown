---
layout: post
title: Enhancement One Summary
date: 2024-10-10 09:30:00 -0400
---

This artifact was completed in CS340: Client Server Development. The client was the Austin Animal Center and they were looking to create a database to store all of the data they were, at the time, managing on an excel sheet. The database would be managed through a dashboard and the client required sorting and filtering functions for the table being displayed as well as some kind of system to filter the entire database by several different criteria. I included a dynamic pie chart that would update based on the results displayed in the table. Lastly, each animal had coordinates that would put a pin on the geographic location feature when selected in the table. <br>

![Dashboard Zoomed Out](/images/DashboardFull.png) <br><br>

Looking closer at the dashboard, you can see the inclusion of radio buttons for filtering the different types of working dogs from the table. 

![Dashboard Zoomed In](/images/DashboardZoomed.png) <br>

The main purpose of this enhancement was to rewrite the original Grazioso-Salvare Dashboard project in Java. I won't go into too much detail about the database here because that is the main topic of Enhancement Three, but a lot of the reworking and structure of the program is centered around working with the database.<br>

The first shot below is a snippet from the Python version, and the second is from the Java version.<br>

![Python Database Shot](/images/PythonDBshot.png)<br><br> ------------------------------------------------------------------------------------------------------
![Java Database Shot](/images/JavaDBshot.png)<br>

Rather than having just one screen in which the user would sort and filter from, I wanted to create an application with different screens that would handle working with the data. I also wanted to add the rest of the CRUD functionality not present in the orignal app. This meant allowing users to add, edit, and delete entries instaed of just reading them. 

 ![Dashboard Screen](/images/newDashboard.png)<br>

Rewriting this program in Java gave me an opportunity to be creative while also meeting the client's requirements. I feel that this new layout has a much neater appearance and makes it easy for users to accomplish what they need to intuitively.