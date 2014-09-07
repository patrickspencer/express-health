express-health
==============

express-health is a small, hobby, web application for keeping track of doctor-patient records
built with node.js and MongoDB. This project is for instructional purposes right now.

The starting point for this project is [this tutorial](http://cwbuecheler.com/web/tutorials/2013/node-express-mongo/).

Install
-------
First, [download and install node.js](http://nodejs.org/download/)
Then download the zip folder of express-health somewhere on your computer. In the
command line, navigate to the folder you downloaded the package from and run
the command `npm install`. You should see a bunch of text telling you that
packages are being installed.

Next, [download and install MongoDB](http://docs.mongodb.org/manual/installation/).

Running on computer
-------------------

All the commands are done on the command line. We assume the location of the
express-health application is `~/express-health` on a Mac or Linux system. It
could be `c:/express-health` on Windows.

First start mongo: `mongod --dbpath ~/express-health/db/data`. Then change
directories to the app folder `cd ~/express-health/db/data` and start the
MongoDB shell by typing `mongo`. Then jj

directory to `~/express-health/db/data` and type `mongo` and then type `use express-health-db`.
While in folder for the application in the command line type `npm start`.

Dependencies
-----------
* Node 0.10.31
* Express 4.8.6
* MongoDB 2.6.4

License
-------

This project is released under the MIT License. See the file LICENSE for more info.
