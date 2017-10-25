---
layout: essay
type: essay
title: I have no idea how this works
date: 2017-10-24
labels:
  - Meteor
---
<h2>What's Meteor</h2>

[Meteor](https://en.wikipedia.org/wiki/Meteor_(web_framework)) is a free web framework which allows developers to produce applications for the web. It supports MongoDB, which allows the user to create and manage databases.

<h2>Meteor is slow!</h2>
To get an introduction to Meteor, I went through [these](http://courses.ics.hawaii.edu/ics314f17/modules/meteor-1/) tutorials. One thing I noticed is how long it takes to start up and build an application. On my MacBookPro, it takes about 20+ seconds to do the initial build. Once the application is set up, starting it up to run takes another 15-30 seconds. Once everything is all set up, Meteor will update on its own as I make edits to the code. The changes happen live, and the webpage will refresh automatically. This turned out to be a very convenieant feature, as it allows me to make small changes, without having to restart and rerun the program.

<h2>And it's confusing!</h2>

I watched Professor Philip Johnson's [screencasts](http://courses.ics.hawaii.edu/ics314f17/modules/meteor-2/) which explain step-by-step how to create a basic web application. In the application, the user can input contact information, and it will show up on a table in the home page. After watching a screencast I would tried to recreate a portion of it on my own.

Professor Johnson's screenscasts held my hand, while I blindly stumbled through Meteor. Even while following the instructions, I ran into errors. More often than not, the error was forgetting an import statement in one of the client, or server side files. Troubleshooting was difficult because the console won't display errors for forgetting to import a file. Instead, nothing will display or work properly in the web application. I was never sure where exactly a file needed to be imported because I hardly understood any of the code that I was importing!

When the error was something more serious than an import statement, that's when I found myself in trouble. I was being introduced to several Meteor and Schema concepts without a formal explanation. It was difficult to identify what the different errors meant. One particular error I ran into was

```
No such function: fieldError
```

I had no idea whether or not this was a Meteor, Schema, or a self-defined function. I eventually found that it was a helper function I needed to define under Meteor Templates. I had copy-pasted code from something similar to what I needed, and was making edits to the file to match the code I saw in the screencast. I deleted some lines I shouldn't have, which sent me on a long hunt. I was not sure what a Template Function was, nor when those functions were actually called. My ignorance to how Meteor works cost me a lot of time. One line code fixes would take 10-30 minutes to figure out.

<h2>But I guess it's alright</h2>

Meteor seems like a great tool for helping developers build apps for the web because it does a lot of the dirty work. But it is not friendly to beginners. It has a huge learning barrier that is not easy to cross alone. I still don't understand how a lot of the working parts come together to create the web application. However, one of the benefits of using a framework is that I don't have to understand the nitty-gritty details. I just need to remember my import statements, and know when not to mess with code that looks important.
