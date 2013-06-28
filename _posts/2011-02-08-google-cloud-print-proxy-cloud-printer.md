---
layout: post
title: Google Cloud Print Proxy (Cloud Printer)
url: http://kinlane.com/2011/02/08/google-cloud-print-proxy-cloud-printer/
image: http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg
---
{% include JB/setup %}
<p>
     <a href="http://mimeo.com/"><img class="c1" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" /></a>I have some working code for a <a href="http://www.kinlane.com/2011/02/introduction-to-the-google-cloud-print-services-interface/" target="_blank">Google Cloud Print Proxy</a>. It is currently written in PHP and uses the <a href="http://framework.zend.com/" target="_blank">Zend framework</a>. I have written specific blog posts for each service endpoint, and to finish up I wanted to do a complete walk-through. First I authenticate against a users Google Account with <a href="http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html" target="_blank">Google ClientLogin API</a>. Then using the <a href="http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html" target="_blank">Google Cloud Print Services Interface</a>:
</p>
<ul class="mainlist">
     <li>
          <a href="http://www.google.com/cloudprint/interface/" target="_blank">http://www.google.com/cloudprint/interface/</a>
     </li>
</ul>
<p>
     I can make calls to the following end points to manage printers:
</p>
<ul class="mainlist">
     <li>
          <a href="http://www.kinlane.com/2011/02/google-cloud-print-register/" target="_blank">/register</a>
     </li>
     <li>
          <a href="http://www.kinlane.com/2011/02/google-cloud-print-list/" target="_blank">/list</a>
     </li>
     <li>
          <a href="http://www.kinlane.com/2011/02/google-cloud-print-update/" target="_blank">/update</a>
     </li>
     <li>
          <a href="http://www.kinlane.com/2011/02/google-cloud-print-delete/" target="_blank">/delete</a>
     </li>
</ul>
<p>
     I can make calls to the following end points to manage cloud print jobs:
</p>
<ul class="mainlist">
     <li>
          <a href="http://www.kinlane.com/2011/02/2822/" target="_blank">/fetch</a>
     </li>
     <li>
          <a href="http://www.kinlane.com/2011/02/google-cloud-print-control/" target="_blank">/control</a>
     </li>
</ul>
<p>
     You can receive print job notifications via persistent XMPP connection:
</p>
<ul class="mainlist">
     <li>
          <a title="XMPP Print Job Notifications" href="http://www.kinlane.com/2011/02/google-cloud-print-xmpp-print-job-notifications/">XMPP Print Job Notifications</a>
     </li>
</ul>
<p>
     If you want to download the sample code for my Google Cloud Print Proxy work, you can download in the following formats:
</p>
<ul class="mainlist">
     <li>
          <a href="https://github.com/mimeoconnect/Google-Cloud-Print-Proxy#readme" target="_blank">git - Github</a>
     </li>
     <li>
          <a href="http://code.google.com/p/google-cloud-print-proxy/" target="_blank">svn - Google Code</a>
     </li>
</ul>
<p>
     If you have any thoughts or ideas for an innovative Cloud Print Proxy, let me know. <a href="http://www.mimeo.com/"><img class="c2" src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print-mimeo.png" alt="" width="500" align="center" /></a>   <strong>UPDATE 2/28/2011 -</strong> I have finished the first prototype for the <a title="XMPP Print Job Notification Service" href="http://www.kinlane.com/2011/02/google-cloud-print-xmpp-print-job-notifications/">XMPP print job notification service</a>. This is critical piece to eliminate constant polling of /fetch service.
</p>
<h6 class="zemanta-related-title c3">
     Related articles
</h6>
<ul class="zemanta-article-ul">
     <li class="zemanta-article-ul-li">
          <a href="http://www.readwriteweb.com/archives/cloud_print_coming_soon_to_google_docs.php">Cloud Print "Coming Soon" to Google Docs</a> (readwriteweb.com)
     </li>
     <li class="zemanta-article-ul-li">
          <a href="http://go.theregister.com/feed/www.theregister.co.uk/2010/12/08/google_cloud_print/">Google sees printing in the cloud</a> (go.theregister.com)
     </li>
     <li class="zemanta-article-ul-li">
          <a href="http://downloadsquad.switched.com/2010/12/07/google-cloud-print-is-now-available/">Google Cloud Print is now available</a> (downloadsquad.switched.com)
     </li>
</ul>