# PyJobs-WebScraper [![Build Status](https://travis-ci.org/Sim4n6/PyJobs-WebScraper.svg?branch=master)](https://travis-ci.org/Sim4n6/PyJobs-WebScraper)
A simple python job offers web scraper using *beautifulsoup4* and *requests* modules in *python3*. 


App functionnalities : 
--------
 - The app web scrapes from www.python.org/jobs offers board based on location.
 - It web scrapes from www.afpy.org/posts/emplois offers.
 - It uses Requests module for handling a simple HTTP get of URLs content.
 - It uses beautifulsoup4 module for parsing html content.


INSTALL
----
 Clone the repository from github : 

    $ git clone https://github.com/Sim4n6/PyJobs-WebScraper.git PyJobs-WebScraper
    $ cd PyJobs-WebScraper

Create a virtual environnement on linux : 

    $ python3 -m venv venv
    $ source venv/bin/activate
    
Create a virtual environnement on windows :

    $ python3 -m venv venv
    $ venv\Scripts\activate.bat
    
Install the necessary packages: 
    
    $ pip3 install -r requirements.txt
   
Run
---
On linux or Windows :

    $ python3 PyJobs-WebScraper.py
    
TEST
----
On linux or Windows :
  
    $ python3 main_tests.py
    
    
Code coverage
----

On Windows for terminal report :

     $ coverage run --omit .\venv\* PyJobs-WebScraper.py 
     $ coverage report -m 

On Windows for html report : 
 
     > coverage run --omit .\venv\* PyJobs-WebScraper.py 
     > coverage html 

Then visit htmlcov/index.html in your browser
