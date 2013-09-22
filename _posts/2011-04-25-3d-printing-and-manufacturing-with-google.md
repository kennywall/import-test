---
layout: post
title: "3D Printing and Manufacturing with Google"
url: 'http://kinlane.com/2011/04/25/3d-printing-and-manufacturing-with-google/'
image: 'http://kinlane-productions.s3.amazonaws.com/3D-Printing/3D-Nylon-Bike.jpg'
---

<img class="c1" src="http://kinlane-productions.s3.amazonaws.com/3D-Printing/3D-Nylon-Bike.jpg" alt="" width="250" align="right" />I'm watching the future of manufacturing and printing unfold slowly in front of us. I'm paying attention to 3D printing solutions evolving from companies like [Shapeways][1], [MakerBot][2], [Materialise][3], [ZCorp][4], and [Objet][5].

At the same time I'm involved with the rollout of [Google Cloud Print Services Interface][6], an API for managing printing to any printer over the Internet.

I'm using [Google Docs as a publishing platform][7], integrating Google Cloud Print with the [Mimeo Connect API][8] and evolving whats possible with commercial cloud printing.

Google has added [support for many more native file formats in Google Docs][9]. Now all they need to do is add support for common 3D printing file formats:

  * .[stl][10] \- STL is a file format native to the stereolithography CAD software created by 3D Systems.
  * .[iges][11] \- The Initial Graphics Exchange Specification (IGES) (pronounced eye-jess) defines a neutral data format that allows the digital exchange of information among Computer-aided design (CAD) systems.
  * .[obj][12] \- OBJ (or .OBJ) is a geometry definition file format first developed by Wavefront Technologies for its Advanced Visualizer animation package. The file format is open and has been adopted by other 3D graphics application vendors. For the most part it is a universally accepted format.
  * .[3ds][13] \- 3DS is one of the file formats used by the Autodesk 3ds Max 3D modeling, animation and rendering software.
To support 3D printing file formats I'm sure they will have to introduce a new app to the Google Apps suite or evolve Google Drawings.

Google Drawings only supports importing of .wmf files and exporting of .jpg, .pdf, .png, and .svg formats.

I'm working on some modifications to the Google Cloud Print capabilities definition via .ppd or .xps for commericial cloud printing, I think we could also bend this definition to support 3D printing and mnufacturing.

We have a ways to go, but I see the future of cloud 3D printing and manufacturing unfold in front of us with 3-D printing and cloud printing.

   [1]: http://www.shapeways.com/ (Shapeways)
   [2]: http://www.makerbot.com/ (Makerbot)
   [3]: http://www.materialise.com/ (Materialise)
   [4]: http://www.zcorp.com/ (ZCorp)
   [5]: http://www.objet.com/ (Object)
   [6]: http://www.kinlane.com/2011/02/google-cloud-print-proxy-cloud-printer/ (Google Cloud Print Services Interface)
   [7]: http://www.kinlane.com/2011/02/google-docs-as-a-publishing-platform/ (Google Docs as a Publishing Platform)
   [8]: http://developer.mimeo.com (Mimeo Connect API)
   [9]: http://www.kinlane.com/2011/02/google-docs-file-formats-viewer-web-and-api/ (Support for many more native file formats in Google Docs)
   [10]: http://en.wikipedia.org/wiki/STL_(file_format) (.stl file format)
   [11]: http://en.wikipedia.org/wiki/IGES (.iges file format)
   [12]: http://en.wikipedia.org/wiki/Wavefront_.obj_file (.obj file format)
   [13]: http://en.wikipedia.org/wiki/.3ds (.3ds file format)
