---
layout: post
title: Managing Print Files with Box net
url: http://kinlane.com/2011/04/30/3509/
image: http://kinlane-productions.s3.amazonaws.com/cloud-storage/Box-logo-new.jpg
---
{% include JB/setup %}

One such platform that I've identified as a Mimeo.com partner platform is Box.net.
Box.net provides a complete cloud storage platform, with a powerful developer platform and application directory called OpenBox.
Mimeo.com provides commercial web to print services, and with Mimeo Connect Cloud Print API you can integrate print file management from Box.net
*** Heads up!! This requires basic understanding of box.net and programming with PHP ***
To do this I sign up for a Box.net developers account and add new OpenBox application:

	Give Application Name and Description
	Assign a description page for the application that tells about my printer.

An important part of this application is a callback URL for when users first add the Box.net application. This has to be a page you host that handles the Box.net oAuth, which gives this print file manager access to a users account.
Another important part of each application are whats called service actions.  Service actions which will show up for any user who adds this application to their Box.net account from OpenBox.
For my Open Box Application I create a new service action:  

	Give Application Service Action a title like, Send Print File toMimeo
	Choose which document extensions my print file manager supports, PDF for now
	Enter a callback function which Box.net will send user when printing document
	Enter callback parameters such as URL, Title, Extension of Box.net file to be printed.

Save your service action, fill out any other relevant parts of your application and hit save as well.
This creates your application at Box.net.
Now you need put together the code that integrates Box.net with your Mimeo.com account using the Mimeo Connect Cloud Print API.
First you need the OAuth piece of code described above, you can download this at Github.  It requires the following files:

	box_config.php
	boxlibphp5.php
	class.curl.php
	index.php

This will allow your print file manager to OAuth with Box.net.
Now you need the actual code that lets you pull the file being passed by Box.net and print uses Mimeo.com.
Here is a sample code file for doing this:

The above code sample demonstrates how to build a print file manager using Box.net cloud storage and Mimeo Connect Cloud Print API.
Any company can use  Box.net to manage their print files, and allow commercial printing using Mimeo.com
You can dowload a complete library of PHP code samples for integrating Box.net with Mimeo.com at Github.