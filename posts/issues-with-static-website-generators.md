---
title: Issues with Static Website generators
author: Philippe Bodart
banner: /img/uploads/images1.jpg
shortdesc: "The missing link in building, managing and updating a Static website using the JAM Stack"
cmsUserSlug: ""
date: 2016-05-03T00:00:00+08:00
categories: null
---

There has been a lot of talk recently on the rebirth of Static websites, for lack of a better word. Static websites have been around for quite a while, but have been gradually replaced by database driven websites and content management systems. The likes of Wordpress, Joomla, Drupal and a ton of others come to mind. Five to six years ago that seemed the way to - you store all your data in a relational database and you serve all the content from a web server. The dot's are connected via a user interface to administer and manage all the content and users from of your web assets. 
Tablets and smartphones were not around in large quantities, browser capabilities were minimal and security and speed were not high on the agenda. Open source projects like Linux, Apache, MySQL and PHP were the drivers of a solid development community around those technologies. 

But the success of database driven websites has created real issues that are hard to overcome. The model was not really scaleable - with a couple of simultaneous users, no worries. With hundreds of users, the server would go down eventually. 
With numerous plugins and patches, the model became highly vulnerable to Service attacks and denial of service.
Webservers and databases need to be maintained and updated, a costly and complex exercise.
The need of ever better and speedier user experience on now smartphones and tablets further stretches the model to where it becomes questionable if a database driven website is really the answer for websites in 2016 and beyond.

## Over the last years we have seen the rise of Static Website generators 
There are plenty of them around, like Jekyll, Roots, Hugo, Middleman just to name a few. They are great tools to use, as the use HTML, CSS and Javascript as main language. So no need for PHP knowledge, database and web server knowledge and no need to use plugins to put your site up. Without the need of a database, web server and a multitude of plugins, the websites build with these frameworks are fast, reliable and scaleable. Add an open source SSL certificate to it, put it on a CDN (Content Delivery Network) and you are done. Cost of building and maintenance is substantially lower then with a database driven website. It scales without additional resources, it is as fast for one visitor as it is for thousands of visitors. 

What is the missing link - a simple browser based User Interface to update the content of a website. At WebriQ we have solved this by automating content updates through a Github workflow that automatically creates a new build for your website each time the Github repository is changed. It allows you to dynamically change the content from a website on a desktop, tablet and even on a smartphone in case of urgency. 
You can view a [DEMO](http://demo.webriq.com) and you can manage the site on [ADMIN](http://demo.webriq.com/admin) - login with user demo@webriq.com and password demo!@#1234. Enjoy the ride.