---
layout: post
title: "Microsoft Sentinel Setup"
categories: misc
---

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.


![Sentinel 01](/assets/sentinel-setup-01.png)
![[sentinel-setup-02.png]]
![[sentinel-setup-03.png]]
![[sentinel-setup-04.png]]

Make sure to pick the same region. This will make connectivity faster between devices.

![[sentinel-setup-05.png]]
![[sentinel-setup-06.png]]
![[sentinel-setup-07.png]]
![[sentinel-setup-08.png]]
![[sentinel-setup-09.png]]
No vm is connected so i'll need a data connector to connect the vm event data to the siem 



![[sentinel-setup-10.png]]
Go to the Sentinel Page -> select TestLogAnalytics -> go to Data Connectors > Click on "More content at Content hub"

![[sentinel-rule-05.png]]
Find the "Windows Security Events" and Install it![[sentinel-setup-12.png]]
Return to the data connectors page and refresh to see the new Connectors. 

Click on "Windows Security Events via AMA" -> Open connector page

![[sentinel-setup-13.png]]
![[sentinel-setup-14.png]]
![[sentinel-setup-15.png]]

Press create 
![[sentinel-rule-01.png]]
# Creating a rule

![[sentinel-rule-02.png]]

![[sentinel-rule-03.png]]

![[sentinel-rule-04.png]]

![[sentinel-rule-06.png]]

![[sentinel-rule-07.png]]
