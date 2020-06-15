# my_mini_cloud

Note: for bettere understanding read my my_mini_cloud.pdf document provided in this repository.
My Mini Cloud
Objective:
This is my mini cloud project, under docker training, in guidance of Mr. Vimal Dagga sir, world record holder, and IIEC-RISE community. In this project I want to give some, small-small cloud services, like viewing exe file through the world wide web/browser, lunching the new Operating System (OS) as per demand, showing beautiful image galleries and many e gifts on website. 
All these services will be available for clients and can be easily access through the internet from anywhere.

Prerequisites:
1.	Docker/k8s
2.	RHEL 8.0
3.	Httpd/apache web server
4.	Mysql
5.	Visual studio 2019 for making required applications (optional, web application asp.net)
6.	Basic knowledge in html5, css, php, js for developing webpages.
7.	A public domain or use ngrok tunnel (optional)
Installation and setup
Note: Installation and setup of above tools, must be done before proceeding himself for reference visit here, 
Build Steps:
1)	Install Docker C-E 18.0.3 or latest version on your operating system, in my case I am using redhat on vm ware. And then pull some required docker images like
a)	Httpd server
b)	Linux os in my case ubuntu, centos 8
c)	Sql data base

2)	Run httpd image and required images on docker using docker command (docker run -dit –name=myserver httpd) or you can run it with pating for outside connectivity (docker run -dit -p 8089:80   httpd)

3)	Or you Can configure your public ip address with Name Server (DNS) or use ngrok tunnel for some hour connectivity towards the public world. In my case I am using ngrok tunnel tool.

4)	You can similarly run other images by replacing images name, and check your server connection by connecting from browser.

5)	Make web pages or website, for giving some of the services to the client, and will easy for using for them. Make a dedicated home page where there will be options for some services and links on other pages in home page, like below. And cp all pages in httpd server in folder /var/www/html/, because webserver only read the pages in this folder. 

Here I am using manually now but can use it automatically using Jenkins, but it will later.

 
 
My services Introduction:
 

1.	Now here, I am giving one of the my service called, E_Galley, now for using this service you have to click on E_Gallery button appearing on homepage, and for accessing that webpage you have to use 

my ip address, which is http://a3eb29cce2c1.ngrok.io/mycloud/ you can also read some description below about that service, what are there? How can access that ? etc.

 

2.	You can use my second service called, E_Gifts, this is an exe file or software/win form application made in .net frame work. I mean using c# in visual studio 2019. Now here we all know it is impossible to open any exe file on web browser, so how can I made it possible 

So for that there are some options available on the internet like using chrome pulgins IE tab, and others. But I am using here, my linux os, and all application will be on it, and I also mde this os such like, here you can run windows application and linux application too.
 
3.	You can use also my third service, called use os online. In this you can use some the os like, redhat 7/8 (centos 7/8), ubuntu, Debian, linux in their respective version and you can use any program from anywhere. If you do any activities, like file downloading, and if you close it then, if you again try to access it, then don’t worry your all data will be save in my local storage/ persistent storage in docker, so that if you re start your os then you will get back your all data and files. You can use launch multiple os with no any problem, but for that I have to use minikube, that is container management tool of google. But now I am considering initially I have no more clients so used docker only for this.

4.	Now again, you can use my fourth program called Code_On_Cloud. In this service mainly I have installed some of known complier in redhat os, e.g 

So, the technical guys can write their python program and save it there using some basic linux commands, and also can access from anywhere from any time of there program files.
i)	Python 3.0
ii)	Java


5.	This is my last service, here I have given storage as a service, so that client can store their photos, videos, and files, and can also access from anywhere and any time. Or given some Face Recognition or other service based on it or nlp etc but this will be In future.

So, after all these are my services at initial level, but slowly-slowly I want to implement it in great a project. And in future I will also work with MlOps guys, for launching python based services, so would like to take help of Harvinder Singh deewan in future.
Setup and installation process of services
   	
Conclusion:
This is my initial level project mainly on docker. But in future I am going to do a great setup using most power tools for automation as well as management, and monitoring purposes like, Jenkins, k8s, Prometheus, Grafana, …. Etc.
If any mistakes done are here, please write in comment and suggest me for doing that with best approach.
I would like to very thanks Mr. Vimal Daga Sir, for his best way of explaining right education under the training of docker by IIEC RISE 1.0 community and Preeti Maa’m she, given me a chance to prove myself. Share and like it if you really find great efforts here.
 
