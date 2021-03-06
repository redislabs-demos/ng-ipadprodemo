# A Simple Demo Application 

... which is entirely developed on the iPad Pro.

It all started a few weeks ago when I decide to buy an iPad Pro (11 inches). The motivation was not to use it as a development machine. My current role requires to draw some diagrams and to explain stuff a bit more visually. So the iPad Pro seemed to be a nice device for such a purpose.

Being a techie, I wondered a bit which kind of development can be done on it and I started to install some tools for experimenting with them:

* Working Copy: A Git client
* Pythonista: A Python IDE
* StaSh: A shell for Pythonista which allows you to use packages via 'pip'
* Blink: A CLI with an SSH client
* VNC Viewer: Access the screen of your computer (which is running a VNC server)
* Duet: Use your iPad as a second screen for your Mac

It all went a bit "crazy" when I went to my barber to get my beard cut. Now my Turkish barber is a very good one which means that he is very busy (seems this is a pattern across all industries - let it be IT-specialists or barbers). So I had to wait for about 2 hours to get a shave. As I already expected some waiting time, I took my iPad Pro with me (for i.e. reading a book). Holding it in my hands, I was then thinking why not trying to drive this 'How to develop on this device?' idea forward. But which kind of application should I develop? So one of the thoughts was to be able to demonstrate Redis (https://redis.io/) itself on the iPad. Wouldn't it be cool to

* Just connect a small device with a Pen to a big screen (i.e. projector via USB-C, screen sharing)
* Explain some concepts by just drawing like on a whiteboard
* Demonstrate some Redis basics by being connected to a Redis Cloud instance (You can get a 30MB database for free here: https://redislabs.com/redis-enterprise/essentials/)

? 

Given the fact that I invested some time to write this article, my opinion is clearly: "Yes, it would be cool!".  However, if you are still wondering "Why the hell should I want to develop on an iPad Pro?" then I guess the answer is: "Because you can!" ;-) So this is more a fun project, whereby it might be a good basic example for:

* Understanding some Redis basics
* Using a very popular Redis Python client (https://github.com/andymccurdy/redis-py)
* Understanding some Jinja2 (http://jinja.pocoo.org/docs/2.10/) HTML templating basics
* Learning how to use some Flask basics (http://flask.pocoo.org/) for building a simple web application

So have fun!

## How to run the Application

The following python packages should be installed:

* redis
* Flask

The application will read the configuration from a file which is called 'config.py'. You will need to create copy the 'config_example.py' file to 'config.py'. Then you can set the following configuration paramters:

* host
* port
* password


## Screenshots

Here finally a screenshot of the application which is running in a browser on my iPad:

* App in Safari:

<img src="https://raw.github.com/nosqlgeek/ng-ipadprodemo/master/screenshot/Database_Info.jpg" width="400"></img>

<img src="https://raw.github.com/nosqlgeek/ng-ipadprodemo/master/screenshot/Exec2.jpg" width="400"></img>

* Pythonista IDE:

<img src="https://raw.github.com/nosqlgeek/ng-ipadprodemo/master/screenshot/IDE.jpg" width="400"></img>
