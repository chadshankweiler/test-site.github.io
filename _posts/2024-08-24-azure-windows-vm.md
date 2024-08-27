---
layout: post
title: "Azure Windows 11 Setup"
categories: misc
---

This post is a continuation of https://google.com


![Sentinel 01](/assets/sentinel-setup-01.png)
![test](/assets/sentinel-setup-02.png)
![test](/assets/sentinel-setup-03.png)
![test](/assets/sentinel-setup-04.png)

Make sure to pick the same region. This will make connectivity faster between devices.

![test](/assets/sentinel-setup-05.png)
![test](/assets/sentinel-setup-06.png)
![test](/assets/sentinel-setup-07.png)
![test](/assets/sentinel-setup-08.png)
![test](/assets/sentinel-setup-09.png)
No vm is connected so i'll need a data connector to connect the vm event data to the siem 



![test](/assets/sentinel-setup-10.png)
Go to the Sentinel Page -> select TestLogAnalytics -> go to Data Connectors > Click on "More content at Content hub"

![test](/assets/sentinel-rule-05.png)
Find the "Windows Security Events" and Install it
![test](/assets/sentinel-setup-12.png)
Return to the data connectors page and refresh to see the new Connectors. 

Click on "Windows Security Events via AMA" -> Open connector page

![test](/assets/sentinel-setup-13.png)
![test](/assets/sentinel-setup-14.png)
![test](/assets/sentinel-setup-15.png)

Press create 
![test](/assets/sentinel-rule-01.png)
# Creating a rule

![test](/assets/sentinel-rule-02.png)

![test](/assets/sentinel-rule-03.png)

![test](/assets/sentinel-rule-04.png)

![test](/assets/sentinel-rule-06.png)

![test](/assets/sentinel-rule-07.png)
