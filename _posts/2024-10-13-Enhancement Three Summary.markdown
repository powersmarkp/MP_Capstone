---
layout: post
title:  "Enhancement Three Summary"
date:   2024-10-08 12:00:00 -0400
---

Enhancement Three pertained to database improvements, so I chose to revisit the newly reprogrammed dashboard app from Enhancement One, now written in Java. 

To begin, I set up my server with WampServer. I used WampServer because even though other services like XAMPP would have sufficed, I wanted the extra security that WAMP offers.<br><br>

<img src="/images/wampClip.png" style="display:block; margin-left: auto; margin-right:auto" alt="WAMP clip"><br>

I then simplified the creation of my databases by using phpMyAdmin. This eliminated the need to write a lot of code to create the database from within my program. <br><br>

<img src="/images/phpMyAdminClip.png" style="display:block; margin-left: auto; margin-right:auto" alt="phpMyAdmin Clip"><br>

Now I have to be humble and admit that I had some issues from this point on. I had never worked with Intellij Idea before this course started, but I was having no problem learning the software and building my program. Then it came to displaying the table of animal data on the dashboard's main screen. I understood what I needed to do, but I constantly found myself struggling with getting the right data types to build my table. I tried learning about table modules, both default and abstract, and I tried many other techniques to convert the animal data on the database to something the program could use to produce the table. In the end, the only way I could figure out how to display the table was to read in the data from the CSV file provided with the original assignment. <br>

![file path CSV](/images/animalCSV.png)<br>

Many of the other feature of the app work and interact with the database using methods tied to mySQL queries. For example, users are able to add entries to the database, as well as edit them and delete them. <br> 


<img src="/images/addEntryClip.png" style="display:block; margin-right: auto" alt="Add Entry Clip">
<img src="/images/editEntryClip.png" style="display:block; margin-left:auto" alt="Edit Entry clip"><br>

However, without being able to update the table with data changes from the database, users will not be able to see the changes they make reflected in the table on the dashboard. I am still working to fix the problem and am confident that I will have it resolved within the next week.<br>