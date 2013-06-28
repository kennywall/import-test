---
layout: post
title: Amazon Load Balancer - Port Configuration
url: http://kinlane.com/2010/06/28/amazon-load-balancer-port-configuration/
source: http://kinlane.com/2010/06/28/amazon-load-balancer-port-configuration/
domain: kinlane.com
image: http://kinlane-productions.s3.amazonaws.com/amazon/load-balancer/Configure-Ports.PNG
---
{% include JB/setup %}<p><!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
    "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <title></title>
  </head>
  <body>
    <p style="text-align: left;">
      When setting up your Amazon Load Balancer you need to configure ports and protocols that the load balancer will route traffic for. <img class="aligncenter" title=
      "AWS Load Balancer - Configure Ports" src="http://kinlane-productions.s3.amazonaws.com/amazon/load-balancer/Configure-Ports.PNG" alt="" width="550" align="center" />
    </p>
    <p style="text-align: left;">
      Traffic can be routed from any load balancer port to any port on your Amazon EC2 instances. By default, the load balancer is configured with a standard web server on port 80.
    </p>
    <p style="text-align: left;">
      It also comes with standard configurations for Apache Tomcat, Rails Server, Glassfish App Server and Secure HTTP Server.
    </p>
  </body>
</html></p>
