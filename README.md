Searchsploit
============

A command line tool to search a local exploit-db repository.


What you'll need to do
======================

Make sure you edit the file so the csvpath variable reflects the path pointing to the csv file. That variable is there so that no matter what your install of exploit-db looks like path wise it should be trivial to get the script to work.

Place searchsploit somewhere in your path (or alternatively perhaps where your exploit-db .csv lives) and mark the file executable.


Now what?
=========

Calling the script with no argumets will print out it's usage/syntax.


To-Do
=====
- Automatically populate csvpath by figuring out if the system is a run-of-the-mill pentesting disto
- Perhaps figure out a way to make it a bit more clever so if the user isn't pervy to the csv value order the script will still return meaningful results
