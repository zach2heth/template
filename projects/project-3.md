---
layout: project
type: project
image: images/D1.png
title: Account Database
permalink: projects/database
date: 2016
labels:
  - C
  - C++
summary: A program for storing and manipulating simple account records
---

<img class="ui image" src="{{ site.baseurl }}/images/D1.png">

This was an assignment for ICS 212, a C and C++ programming class.
It is a small database where a user can add records and store them for later retrieval. The records are objects that are stored in double linked list. The records can be modified and deleted. When the program closes, the records are stored in a text file, that upon starting up again, should automatically load into the database as record objects. Originaly the project was done in C, but the professor's assignment was to recreate the same project in C++. The majority of the problems I discuss are ones I faced while coding it in C. 

The first part completed was the user-interface. I had to take in user input and reprompt the user if there was an invalid input. The difficult part was thinking of what was unacceptable for specific prompts, and how to catch them. For example, when it asks for an account number, I had to make sure that it would not take in letters. There are some unresolved issues with the buffer. With the account number, if the user inputs numbers followed by letters, it will store the numbers and use the remaining letters for the name attribute. It's not supposed to accept negative numbers either, but it does.

<img class="ui image" src="{{ site.baseurl }}/images/D2.png">

Next I did the functions for adding, deleting, and modifying records. This was one of the most challenging parts of the project because there are several cases that I had to identify and consider. There are several pointers that change when adding and deleting records due to the linked list structure. 

The final part was reading from and writing records to a text file. Reading from a file was also a challenge because there was an indefinite number of records that needed to be added, and some records have more lines in them (due to the address) than others. 

Source code [here](https://github.com/zach2heth/Account212).

