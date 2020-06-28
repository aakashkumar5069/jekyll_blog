---
layout: post 
title: "Images not loading in Jekyll (Updated-2020)"
description: "Jekyll Issue solved for Jekyll blog.After going through numerous blogs and stackoverflow,this code was solved by looking into the source-code issues."
author: "Kumar Aakash"
coverImg: "post-bg.jpg"
---

 <h1>Images not loading issue in Jekyll (Updated-2020)</h1>

After going through numerous blogs and stackoverflow,I was disappointed on the technical documents concerning this issue.Everywhere it was written resolved but to no avail.Finally after attempting almost all the solutions provided on the **INTERNET**,I switched on to the Hit and Trial Method and tried to solve the issue  a logical way.

Whenever you face such an issue,please ue the Inspect element tool of Chrome.Additionally hover over the space and **right click to open the image in new page** to see the link where the server is directing.Generally you would find that the server is directing to a url (Github folder) which does not exit.  

In my case : The issue was siteurl.It was taking the wrong siteurl and therefore redirecting me to a different url (Github folder) altogether.If you have defined a siteurl in config.yml,Kindly go through the Documentation and solve the problem. 

![Test image]({{ site.baseurl }}/assets/images/IoT-2.jpg)

Additionally you can also go through some resources I used.

<a href="https://stackoverflow.com/questions/28820917/jekyll-on-github-pages-not-displaying-images-and-has-broken-links">Stackoverflow</a>




