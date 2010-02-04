---
layout: post
title: gtd with gmail
categories:
- gtd
- google
---

After reading David Allen's [Getting Things Done](http://www.davidco.com/), I
have tried a couple of methods for keeping my actions list going and
distractions out of my head.  My main qualifications for a method are:
* editable most places (anywhere with an internet connection)
* viewable everywhere (with some device I already own)
* easy to enter new items

Although I do not have a smartphone with everywhere internet access, I do have
a Nokia [N800](http://nokiahowto.com/find-products/phones/nokia-n800-r5) which
I carry with me along with a phone.  Although this situation is not ideal, it
is nice having a general purpose linux computer in your pocket.

### ikog
Looking for console based GTD programs, I ran across a neat little python
script called [ikog](http://www.henspace.co.uk/ikog/).  Keeping this list
program on my N800 let me have complete access to my todo list anywhere, but
editing it was a little difficult.  I would usually ssh into the tablet and
work on my list remotely, but this became a pain.  Although a great little
program, I needed something else.

### gmail
Looking for another way, I found this
[whitepaper](http://saw.themurdaughs.com/gtd-with-gmail-whitepaper/) on GTD
using [Gmail](http://mail.google.com/).  Since I use Gmail all the time, this
seemed perfect.

In general, my workflow looks like this.
* When a new task that I need to take care of/look into comes up, I compose an email to *me* with the message, followed by *eom* (end of message, which keeps Gmail from complaining about no contents)
* A filter has been made that catches anything from me with *eom* in the message and marks the message as read and tags it with *GTD*
* Once it is time to process my inbox, I go through
 * completing tasks that are short enough
 * labeling tasks that are part of a project with the appropriate project tag
 * mark next actions with the *Actions* tag
 * mark things to look at eventually with the *Someday* tag
 * tag the message with a context (*@errand*, *@work*, *@home*,etc.)
* After that, it is just a matter of looking through my *Actions* list to determine what needs to be done, and periodically checking the projects and *Someday* tags for things to add to *Actions*
* If a reminder is needed later, add an item to Google Calendar to send an email at a certain time, which is also filtered to be marked as read and tagged *GTD*
* When a task is complete, delete the message
* When a project is complete, delete the appropriate project tag

There are lots of ways to do this, but this workflow has helped me greatly.  I can add tasks anywhere there is an internet connection, and I can check my *Actions* folder on my N800's mail client to download all the todos I have up in the air.
