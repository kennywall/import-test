---
layout: post
title: Google Wave Embed
url: http://apievangelist.com/2009/12/18/google-wave-embed/
source: http://apievangelist.com/2009/12/18/google-wave-embed/
domain: apievangelist.com
image: http://kinlane-productions.s3.amazonaws.com/google-wave_embed/Wave-CMS-Editor.jpg
---
{% include JB/setup %}I was playing with Google Wave tonight. I am curious to see how I can use it. I keep thinking about using Google Wave as a content management system (CMS).
I am starting with the basics. First I started a new wave and filled it with some dummy content.

Then using the Google Wave Embed API I can quickly grab the Wave ID and embed it in a web page using a simple little JavaScript that creates and manipulates a Google Wave Embed Panel.
&lt;script src="embed.js" type="text/javascript"&gt;&lt;/script&gt;
&lt;script type="text/javascript"&gt;
function initialize() {
var wavePanel = new WavePanel('http://wave.google.com/a/wavesandbox.com/');
wavePanel.loadWave('wavesandbox.com!w+Fe5fw2vJA');
var conf = new WavePanel.UIConfig();
conf.setBgcolor("#ffffff");
conf.setFont("arial");
conf.setFontSize("10px");
conf.setToolbarEnabled(0);
wavePanel.setUIConfigObject(conf);
wavePanel.init(document.getElementById('waveframe'));
wavePanel.setEditMode(0);
}
&lt;/script&gt;
This means I could easily create a dynamic web site that would pull from some sort of dynamic sitemap that has the site outline with corresponding Google Wave ID. The Wave would handle all the user edit permissions.
Then using the sitemap you could create some sort of graphical look for the site that built the menu, submenus, and bread crumbs on the fly.
You could easily create an administrative tool that would allow a webmaster to create new sections, pages and it would automatically create new waves, and setup user permissions from Google Wave contacts.
Right now Google has wave embed limited to the Google Wave Sandbox. So its hard to tell what the public will see.

This is just one page, however I can see the potential. You can basically crowd source the management of a web site across many different people using Google Wave.
I still have some public and user editing isuess on the embed page to figure out. I will also create some sort of web site registry tool that will build the site map and handle organizing all the waves.
