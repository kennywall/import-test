---
layout: post
title: Amazon Load Balancer Port Configuration
url: http://kinlane.com/2010/06/28/amazon-load-balancer-port-configuration/
image: http://kinlane-productions.s3.amazonaws.com/amazon/load-balancer/Configure-Ports.PNG
---
{% include JB/setup %}
<p>
     When setting up your Amazon Load Balancer you need to configure ports and protocols that the load balancer will route traffic for. Traffic can be routed from any load balancer port to any port on your Amazon EC2 instances. By default, the load balancer is configured with a standard web server on port 80. It also comes with standard configurations for Apache Tomcat, Rails Server, Glassfish App Server and Secure HTTP Server.
</p>