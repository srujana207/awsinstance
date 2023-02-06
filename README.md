We are going to deal with how to access CLI of a Linux server/system. So tag along as we go through a little history as well. 

There are mainly two ways (that we are going to discuss) for accessing the terminal : 

-Your PC/System has Linux OS such as Ubuntu, CentOS, etc.
-Your PC/System doesn't have Linux OS but has Mac/Windows OS
Let's talk about these ways in detail:

-You use Linux OS 
Easier option because you don't have to do anything much other than to open CLI (Command-Line Interface) and write the commands.

-You don't have Linux but have Mac/Windows OS 
You can easily use the cloud platforms (here, we will be dealing with AWS) to create an instance, which is is a virtual server/system. One can set up and configure the operating system (here, Linux) and applications (here, CLI) that run on your instance. It's just a few clicks away, quick, hassle free, secure and pay as you go option. A gist of why companies are migrating to cloud platforms (which is a discussion for another day).

How to "Create an AWS EC2 instance"?

-Login to your AWS account (Don't forget your password!). If you are a beginner, a free tier for a year is available, sign up. There are numerous services AWS provides.
-Go to EC2 --> Launch instances. You will be taken to the "Launch an instance" page for filling the details.
-Choose name, Ex) Example Instance; server type from AMI (Amazon Machine Image contains virtual copies of operating system, application server, and applications required to launch the instance), here, Ubuntu; key pair if already existing, otherwise create one by clicking on "Create new key pair" in type "RSA" and file format as ".ppk" and checkbox the 3 boxes in "Network Settings" for accessing the IP address in web browser. (NOTE: Only mentioning the editing options as the others remain untouched.) 
-Now, "Launch instance". You have successfully launched the instance.
-Instance created successfully
-Once the instance is running and the status checks are done, "Connect" to instance. Go to "EC2 instance connect". 
-Click on connect to access the instance
-A console will be launched giving you access to the CLI of Ubuntu server/system.

We have come to the end of the article. This is an attempt in simplifying numerous and enormous subjects. Hence, bear with my efforts. Feel free to comment any mistakes and suggestions.

And definitely don't forget to terminate your instances when not in use.
Toodaloo!

The above article can be found at the following link : https://srujanakoya.blogspot.com/2023/01/basic-linux-commands-i-why-and-what.html



