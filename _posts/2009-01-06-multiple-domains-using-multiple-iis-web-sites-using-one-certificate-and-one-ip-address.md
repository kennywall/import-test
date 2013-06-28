---
layout: post
title: Multiple Domains using Multiple IIS Web Sites using One Certificate and One IP Address
url: http://apievangelist.com/2009/01/06/multiple-domains-using-multiple-iis-web-sites-using-one-certificate-and-one-ip-address/
source: http://apievangelist.com/2009/01/06/multiple-domains-using-multiple-iis-web-sites-using-one-certificate-and-one-ip-address/
domain: apievangelist.com
image: 
---
{% include JB/setup %}I haven't researched this one in a while, I am glad I had the chance to research for a new project.
I need to be able to setup many sites using a single domain. So each site will be a subdomain within this chose domain.
I have always used one web site on Windows Server because I would need multiple IP Addreses and SSL certificates. I had research the wildcard certificates a couple of times, but the multiple IP address need always trumped. IP Addresses aren't as cheap as they used to be. I remember paying $5.00 / month for a whole C Block.
So tonight I was researching and I came across Wildcard SSL Certificates from Digicert. They rock!! Their process is easy and smooth. I highly recommend them.
Then I saw as one of their features is you could do multiple sites with one IP Address on IIS 6.0. Something I have been asking for for a while.
Then I found this page on how to do it on IIS and Apache - http://www.sslshopper.com/article-how-to-configure-ssl-host-headers-in-iis-6.html
Good stuff....really enjoy the discovery and changes I find on a daily basis.