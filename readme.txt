Project title: Chunghwa online storage service


Description: 
The storage of important documents can be difficult at home. With in Taïwan a high percentage of humidity, the documents can be damaged. Our solution is designed to avoid loss or document damage by storing everything in Chunghwa and providing an easy access to the documents by a website.
The project is designed in UML and implemented in Java and HTML/CSS.

Team members:
We are team 4, our group members are as follows:
X1070076 / Jérôme Daulion / jdaulion@yahoo.fr
X1070077 / Elisa Gressier-Monnard / elisagm17@gmail.com
X1070078 / Karel Kedemos / kedemoskarel@gmail.com
X1070079 / Romain Moineau / romain.moineau1@gmail.com

Instructor: Dr. Hareesh, National Tsing Hua University.

The project is organized in the following folders:


1. Ideation 
As written in the description, the documents are stored at the post and immediately accessible by the internet. Each customer can have a list of certain documents they prefer to store at the post. The post would receive the document, see if it is on the list. If it’s not they would send the document to the customer. If it is, they would scan it and then store it and put the scan filed on the database.



2. Uml design
We did to UML design. One based on the service design and the other on the website design. The service design UML shows more precisely our ideation. The website design UML shows how the website works for a customer (access to documents and different functions we thought about on the website).


3. Final project presentation
Our final project was the occasion to put all together the knowledge we gathered during the semester. We chose Java because it was the nicest way we thought about to play around with the structure of our system, as shown in the video. Before making the website, with HTML and CSS, we also did sketches in order to know how the whole thing would work out at the end, and of course how it would look like. 


4. Demonstration video
The video of the java code is here to show a few examples of how to deal with the accounts management through a menu driven system.



5. Code
We used java for the menu driven system. You only have to execute the main, and then follow the instructions that are displayed on the console

We use HTML and CSS in our project
The goal was to create the beginning of a website.
First, there’s a login page (log.html.jinja2). As we didn’t use any database or php, there is only 1 ID-Password combination possible, checked with javascript.
Once, you’re logged the “control panel” page appears (home.html.jinja2). Here we split the page in 3 columns. The first one is related to the user and what documents he can access. This part uses basic HTML. The second column is where the documents appear. This part was more difficult because it needed to replace the picture in the center every time by the new one. It uses HTML and onclick method and a bit of javascript to display the picture properly. The third columns is about the actions the user can make. It’s only buttons and HTML/CSS. 
Finally, webapp.py is the file that allows someone to run the site.It defines the website paths.



6. Bugs and future improvements
Our main problem was that we did our work on two separate languages. The front-end is with HTML/CSS, whereas the back-end with Java. What would be better is to implement the Java part in PHP, and put the PHP to work with the HTML/CSS part to have a dynamic website. Moreover, the information were not stored into a database (because we didn’t link the 2 parts, we didn’t do this database). So after linking the two parts, this could be a crucial part for the project since it is a storage online project. 
Improvements concern the proposal of chinese language on the website since it is designed for Taïwanese post, the implementation of more features such as Ask the post to send a document to someone and maybe instead of having servers to store the documents, store them directly on the users’ devices (phones, computers, …).
