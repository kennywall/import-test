---
layout: post
title: Internet Explorer 9 HTML 5 Support
url: http://kinlane.com/2010/06/27/internet-explorer-9-html-5-support/
image: http://kinlane-productions.s3.amazonaws.com/InternetExplorer.jpg
---
{% include JB/setup %}
<p>
     <img class="alignnone c1" title="Internet Explorer" src="http://kinlane-productions.s3.amazonaws.com/InternetExplorer.jpg"  width="200" align="right" /><a href="http://ie.microsoft.com/testdrive/info/ReleaseNotes/Default.html" target="_blank">Microsoft recently released some new additions to their Windows Internet Explorer Platform</a>, aka. Internet Explorer 9.
</p>

<p>
     They are working hard to support more of the HTML5 standard.
</p>

<p>
     <strong>Features Available (</strong>Blue are New Releases)
</p>
<ul class="mainlist">
     <li>
          Canvas - In the latest Platform Preview we support all Canvas element APIs and most Canvas 2D Context APIs and attributes.
     </li>
     <li>
          &lt;video&gt; - MP4 H.264 playback support, using hardware or software decoding and support for WebM software is not included in this release
     </li>
     <li>
          &lt;audio&gt; - MP3 and AAC audio support
     </li>
     <li>
          window.msPerformance - This API is being worked in partnership with members of the W3C and is subject to change
     </li>
     <li>IE9 User Agent String
     </li>
     <li>getElementsByClassName
     </li>
     <li>characterSet
     </li>
     <li>
          HTML5-conformant whitespace handling
     </li>
     <li>CSS3
          <ul class="mainlist">
               <li>Media Queries
               </li>
               <li>Selectors (entire module and ::selection)
               </li>
               <li>Namespaces (all except attribute selectors)
               </li>
               <li>
                    Backgrounds &amp; Borders
               </li>
               <li>Color (rgba(), opacity)
               </li>
               <li>
                    Values &amp; Units
               </li>
          </ul>
     </li>
     <li>
          Web font formats
     </li>
     <li>HTML5 Events
     </li>
     <li>
          DOM Style
     </li>
     <li>
          DOM Core
     </li>
     <li>DOM Traversal
     </li>
     <li>DOM Range
     </li>
     <li>DOM L2 Events (complete)
     </li>
     <li>DOM L3 Events (complete)
     </li>
     <li>HTML5 Selection
     </li>
     <li>
          XHTML Documents - The XHTML mime-type of application/xhtml+xml is now listed in the Accept header of outgoing requests
     </li>
     <li>
          Generic XML Improvements (text/xml and application/xml)
     </li>
     <li>
          Generic XML documents render contained SVG and XHTML content
     </li>
     <li>
          XSLT via &lt;?xml-stylesheet � ?&gt;
     </li>
     <li>SVG
     </li>
     <li>ICC v2 and v4 color profiles are supported on images
     </li>
</ul>
<p>
     <strong>Features Partially Implemented</strong> <strong>(</strong>Blue are New Releases)
</p>
<ul class="mainlist">
     <li>
          Canvas
          <ul class="mainlist">
               <li>
                    globalCompositeOperation - The latest Platform Preview does not include support for the globalCompositeOperation attribute.
               </li>
               <li>
                    DOM Exceptions - The latest Platform Preview does not include support for Canvas 2D Context DOM Exceptions.
               </li>
               <li>
                    drawFocusRing() - The latest Platform Preview does not include support for the drawFocusRing() Focus management API.
               </li>
          </ul>
     </li>
     <li>
          CSS3 Fonts - font-size-adjust and advanced font features are not supported
     </li>
     <li>DataURI - Support in script source
     </li>
</ul>
<p>
     Looks like they are trying to get up to speed with other browsers in the HTML 5 support game. I will take some time to compare against the HTML core specs to see how they are doing overall.
</p>