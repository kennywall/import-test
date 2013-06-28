---
layout: post
title: Programming with PDFs
url: http://apievangelist.com/2011/01/20/programming-with-pdfs/
source: http://apievangelist.com/2011/01/20/programming-with-pdfs/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/mimeo/pdf-management/GPL-Ghostscript-Logo.png
---
{% include JB/setup %}<p>When it comes to developing for Print applications you need to be able to programmatically manipulate images.  Currently with Mimeo, ultimately everything needs to be in a PDF format before it gets sent to the Mimeo Connect Cloud Print API.

Whether its a report, book, magazine, photo or poster it will have to be PDF document at some point.  Hopefully soon we will accept a wider range of formats. :)
I spent some time today looking to see what my options are when it comes to working with PDFs.  Supporting and advocating the usage of Open Source projects is important to me, so I limited my search here. Another factor I consider is the overall stableness of the open source project.
I came across three separate projects to take care of 80% of my PDF manipulation needs:

	GhostScript - Ghostscript is an interpreter for the PostScript language. A PostScript interpreter usually takes as input a set of graphics commands. The output is usually a page bitmap which is then sent to an output device such as a printer or display. PostScript is embedded in many printers.
	GhostWord - GhostWord is an interface for the GhostScript above package, and enables you to create PDF documents from Microsoft Word, Excel or PowerPoint documents.
	PDFSam - pdfsam is an open source tool for managing pdf files. It's written in Java and it runs on every platform where a Java Virtual Machine is available.

 These three open source tools are allowing me to convert and manipulate PDF documents as I need, and provide resources to my Print API developers. I will be digesting and providing documentation, how tos, and code samples helping developers become more efficient using PDF.
I am also going through the GNU PDF Library, but have not had time to full digest and integrate into my API strategy.  I will be posting more as my API developer support strategy comes together.</p>
<center><p><a href="http://apievangelist.com/2011/01/20/programming-with-pdfs/" style='padding:25px; font-sze:18px; font-weight: bold;'>Read Full Story</a></p></center>
