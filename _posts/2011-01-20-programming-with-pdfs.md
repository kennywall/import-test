---
layout: post
title: "Programming with PDFs"
url: 'http://kinlane.com/2011/01/20/programming-with-pdfs/'
image: 'http://kinlane-productions.s3.amazonaws.com/mimeo/pdf-management/GPL-Ghostscript-Logo.png'
---

When it comes to developing for [Print][1] applications you need to be able to [programmatically manipulate images][2]. Currently with [Mimeo][3], ultimately everything needs to be in a PDF format before it gets sent to the Mimeo Connect [Cloud Print][4] [API][5]. [<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo/pdf-management/GPL-Ghostscript-Logo.png" alt="" width="197" height="206" align="right" />][6] Whether its a report, [book][1], magazine, [photo][1] or [poster][1] it will have to be PDF document at some point. Hopefully soon we will accept a wider range of formats. :)

I spent some time today looking to see what my options are when it comes to working with PDFs. Supporting and advocating the usage of [Open Source][7] projects is important to me, so I limited my search here. Another factor I consider is the overall stableness of the open source project.

I came across three separate projects to take care of 80% of my PDF manipulation needs:

  * **[GhostScript][8]** \- Ghostscript is an interpreter for the PostScript language. A PostScript interpreter usually takes as input a set of graphics commands. The output is usually a page bitmap which is then sent to an output device such as a printer or display. PostScript is embedded in many printers.
  * **[GhostWord**][9] \- GhostWord is an interface for the GhostScript above package, and enables you to create PDF documents from [Microsoft][10] Word, Excel or PowerPoint documents.
  * **[PDFSam**][11] \- pdfsam is an open source tool for managing pdf files. It's written in Java and it runs on every platform where a Java Virtual Machine is available.
[<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo/pdf-management/pdfsam_logo.png" alt="" align="right" />][11] These three open source tools are allowing me to convert and manipulate PDF documents as I need, and provide resources to my Print API developers. I will be digesting and providing documentation, how tos, and code samples helping developers become more efficient using PDF.

I am also going through the [GNU PDF Library][12], but have not had time to full digest and integrate into my [API strategy][13]. I will be posting more as my API developer support strategy comes together.

   [1]: http://www.kinlane.com/category/publishing/
   [2]: http://www.kinlane.com/2011/01/programming-with-images-using-imagemagick/
   [3]: http://www.mimeo.com
   [4]: http://www.kinlane.com/category/cloud-computing/cloud-print/
   [5]: http://www.apievangelist.com/
   [6]: http://pages.cs.wisc.edu/~ghost/doc/intro.htm
   [7]: http://www.kinlane.com/category/open-source/
   [8]: http://pages.cs.wisc.edu/~ghost/
   [9]: http://ghostword.sourceforge.net/
   [10]: http://www.kinlane.com/category/microsoft/
   [11]: http://www.pdfsam.org/mediawiki/index.php?title=Main_Page
   [12]: http://www.gnupdf.org/Library
   [13]: http://www.apievangelist.com
