What is this?
=============
lxml-xpath-tester is a simple django app that uses lxml to test your XPath 
queries.

It's designed to be rough, but robust, so don't expect it to be pretty.

Installation & dependencies
===========================
Make sure you have lxml and Django installed.

Then just clone this repository somewhere, and use Django's server to run it.

    mkdir xpath-tester
    cd xpath-tester
    hg clone https://bitbucket.org/mlissner/lxml-xpath-tester .
    ./manage.py runserver

That'll start Django's server. From there, just go to localhost:8000 in your
browser, and you'll be off and running.    


Contributions
======
Are welcome.


License
========
This is licensed under the permissive BSD license.


Screenshot
==========
Here's what it looks like right now:

<img src="https://bitbucket.org/mlissner/lxml-xpath-tester/raw/fcf9077c78fc/tester/static/screenshot.jpg" width="500">

