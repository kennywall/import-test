---
layout: post
title: Amazon Web Servers
url: http://kinlane.com/2009/02/10/amazon-web-servers/
source: http://kinlane.com/2009/02/10/amazon-web-servers/
domain: kinlane.com
image: 
---
{% include JB/setup %}<p><!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <title></title>
  </head>
  <body>
    I really love the Amazon Web Services platform. It brings some really valuable tools to the table for deploying a companies infrastructure. However there are some areas that really can throw you
    for a loop. I create bundles and then ultimately AMIs from my core instances. It makes it so I can restore to last nights complete server if I want...with settings and all. I do individual
    bunlidng then AMI creation of instances all the time. Tonight I thought....oh I will go ahead and do all 10 instances at once. So about midnight all the bundles error out because of Amazon S3
    permissions. When all my instances come back up...they all work fine...except for SSL / HTTPS / Port 443. DOH!! I had to remove all certs and reinstall to get back online. What a pain.....but I
    recovered....and we learned another tidbit about living in the clouds Amazon style. 4:00 AM ...night.
  </body>
</html></p>
