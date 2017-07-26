django-cups
===========

Django-based interface to CUPS

Imported from the original project at

http://code.google.com/p/django-cups/

created by Sébastien Ramage

forked by guhkun13 - July 26, 2017
Updated, adjustment all codes and guide to run on : 
 - python 2.7x; 
 - django 1.11.x
 - Ubuntu 16.04 (Xenial)
 - virtual environment 

1. For Ubuntu 16.04, install the cups library
  > apt install libcups2-dev ( or ) apt install libcups*

2. Create virtual environment
  > virtualenv virtualenv
  - start it : source virtualenv/bin/activate

3. Install all the requirements
  > pip install -r req.txt

#Note: I did not set the version of tools (ex:Django) in req.txt, so it will install the latest version. Be cautious.
