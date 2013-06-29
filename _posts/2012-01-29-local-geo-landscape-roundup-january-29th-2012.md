---
layout: post
title: Local Geo Landscape Roundup January 29th 2012
url: http://kinlane.com/2012/01/29/local,-geo-landscape-roundup-january-29th,-2012/
image: https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-api-a.png
---
{% include JB/setup %}
<p>
     <strong>From the <a title="Foursquare Blog" href="http://blog.foursquare.com/">Foursquare</a> Blog</strong>
</p>
<ul class="mainlist">
     <li>
          <a href="http://feedproxy.google.com/~r/thefoursquareblog/~3/jcII8oagst4/">From Starbucks to Sports Authority find your favorite places, even in a new city!</a> - (01/27/2012) - Love Starbucks? On Starbucks foursquare pageyoull see a map with all the locations nearby, so you can pick the closest one to visit. Plus, when youre on aparticular Starbucks venue page, well show you the other closest options. The nearby map is now on hundreds of business pages, with more to come soon. Here are some places to try out! Look for the closest Zipcar locationsand get away for the weekend! Museum lovers, find all of MoMAs locationsin New York (if you’re in New York, zoom out to see them all! ). Local business love! See The Beanerys locationsin Oregon. If your gym has multiple locations, you can find the closest place to work out, even when youre travelling.
     </li>
     <li>
          <a href="http://feedproxy.google.com/~r/thefoursquareblog/~3/WvI_47M1uPk/">A police constable uses foursquare to check in with his community! #4sqFun</a> - (01/27/2012) - Scott Mills, whos also the Social Media Adviser for Crime Stoppers International, is encouraging officers everywhere to use foursquare to connect with their neighborhoods! Scott checks in when hes giving community talks, to let people know when and where hes on patrol, or to keep them posted on breaking crime scenes. People love to comment on Scotts check-ins, come say hi when hes nearby, and evenoust him as the Mayorof the police station headquarters! See one of his awesome presentations here.
     </li>
     <li>
          <a href="http://feedproxy.google.com/~r/thefoursquareblog/~3/NRlyijp9GNg/">Candidates and students check in to the Presidential Debate at USF! #CampusHighlight</a> - (01/25/2012) - University of South Floridahosted NBCs Republican Presidential Candidates Debate. Students, visitors, and even Newt Gingrich and Mitt Romney checked in on foursquare, with the first hundred people winning a free shirt! Want to keep up with the primaries? You can follow Newt Gingrich, Mitt Romney, and The White Houseon foursquare! If you’re interested in promoting your campus event on foursquare (for free! ), emailcampus@foursquare. com.
     </li>
     <li>
          <a href="http://feedproxy.google.com/~r/thefoursquareblog/~3/oEruaKkr27s/">Qu guay! Madrids city badge is here!</a> - (01/25/2012) - Follow the Madrileo listat foursquare. com/4sqcities and check in to five places on it to unlock the badge. Eat a churro for us!
     </li>
     <li>
          <a href="http://feedproxy.google.com/~r/thefoursquareblog/~3/70c4w6HPMX8/">Tell us why your hometown deserves a foursquare badge! #visitUS</a> - (01/24/2012) - Tuscaloosa! ) As part of President Obama’s announcement to boost tourism in the U. S. , the White Housecalled on folks around the country to share what makes their city or town a great place to visit. Well, we want to know too! Inspired by the #visitUS initiative, were putting out a call for foursquare lists with all the best spots in your city. We’ll pick the three most amazing ones and creating foursquare city badges for them! How to make a list for your town! 1. Create a list at foursquare. com/lists, and make sure it has your town and the #visitUS hashtag in the name. 2. Add 20-30 of your towns best places. Include a variety of spots, from restaurants and bars, to parks, monuments, and local businesses.
     </li>
     <li>
          <a href="http://feedproxy.google.com/~r/thefoursquareblog/~3/qywwqRn3PyU/">Hey LA, now its your turn to save $5 on every Restaurant Week meal!</a> - (01/23/2012) - New York Restaurant Week partnershipwith American Express, saving Cardmembers $5 on every lunch and dinner they have at over 300 New York eateries. Today, we’re excited to extend the same deal to hungry explorers in Los Angeles: Spend $21 hundreds of restaurants participating in dineLA’s Restaurant Week, and you’ll get a $5 credit back on your American Express statement. Redeeming your free money is just as easy as with past American Express specials:Check in at a Restaurant Week restaurant. Go to the Special screen and tap the Load to Card button (youll also be able to sync your card if you havent yet).
     </li>
</ul>
<p>
     <strong>From the <a title="Facebook Blog" href="http://developers.facebook.com/blog/feed">Facebook</a> Blog</strong>
</p>
<ul class="mainlist">
     <li>
          <a href="http://working.laneworks.net/gather/">iOS and Android: Single Sign-On Best Practices</a> - (01/26/2012) - Over a year ago, we introduced Single Sign-On (SSO) for Android and iOS. Today, more than 350 million active users currently access Facebook through their mobile devices. Users logged into the Facebook for iOS or Facebook for Android app can use the Login with Facebook button and, in one-click through a permissions dialog, login to your app. This saves users from typing in an e-mail address and password for apps that require registered users. Since the launch of SSO, developers implementing it in their apps have enjoyed increased user registrations and access to the Graph API to build in-app social experiences.
     </li>
     <li>
          <a href="http://working.laneworks.net/gather/">Platform Updates: Operation Developer Love</a> - (01/25/2012) - This week we announced how to implement flashHideCallback to support "wmode=window". We are also announcing the following changes:Getting SubscribedTo and Subscribers via Graph API We are now providing the ability of reading a user's subscribers and subscribees list via the Graph API. To access this information, your app is required to have the user_subscriptions permission for the user, and friends_subscriptions permission for their friends' info. Refer to the documentation for SubscribedTo and Subscribers for more details. To access a user's subscribers list, issue an HTTP GET request to the subscribers connection like the following:https://graph. facebook. com/USER_ID/subscribers? access_token=.
     </li>
     <li>
          <a href="http://working.laneworks.net/gather/">How-To: Implementing hideFlashCallback to support "wmode=window"</a> - (01/23/2012) - One of the Pro-Tips we mentioned late last year in our Games Tutorial to Developers creating Flash based Apps was to use wmode=opaque whenever possible. Setting wmode to any value other than "opaque" or "transparent" prevents any HTML content from being displayed at a higher z index than the Flash object. This results in Dialogs, Notifications and Ticker Flyouts being displayed under the Flash object and creates a pretty poor user experience on Canvas. As a result when Canvas Apps set wmode to "window" or "direct" Facebook automatically hides the Flash object when any Dialogs, Notifications or Ticker Flyouts are opened. To help improve the user experience we have recently introduced a new parameter for FB.
     </li>
</ul>
<p>
     <strong>Tweets from <a title="Factual" href="https://twitter.com/#!/factual">Factual</a></strong>
</p>
<blockquote>
     <strong>(01/25/2012)</strong> <a href="https://twitter.com/#!/factual/status/162320981560528897%3EWe%20just%20released%20our%20official%20Ruby%20driver.%20Give%20it%20a%20try%20&amp;%20let%20us%20know%20what%20you%20build:%20gem%20install%20factual-api%20http://t.co/OSRwTCvr%20#ruby%3C/a%3E%3Cbr%20/%3E%3Cstrong%3E(01/25/2012)%3C/strong%3E%20%3Ca%20href=">@kevinlouie Our apologies, we were experiencing some brief issues with our v2 API yesterday morning. It should be resolved now.</a><br />
     <strong>(01/23/2012)</strong> <a href="https://twitter.com/#!/factual/status/161533799065337856%3E@chrishanscom%20thanks!%3C/a%3E%3Cbr%20/%3E%3Cstrong%3E(01/23/2012)%3C/strong%3E%20%3Ca%20href=">Happy to release our official PHP driver. Accessing our 55 million global places is now easier than ever #php http://t.co/NmlWnvhf</a><br />
</blockquote>
<p>
     <strong>From the <a title="Factual Blog" href="http://blog.factual.com/">Factual</a> Blog</strong>
</p>
<ul class="mainlist">
     <li>
          <a href="http://feedproxy.google.com/~r/factualblog/~3/Dc9QJo8JbGo/factual-ruby-driver">Factual Ruby Driver</a> - (01/25/2012) - Ruby driver for our API. The driver supports Factual’s API features, including Crosswalk, Resolve, and geo location functionality around the Factual Places API. We put a priority on making this driver easy to use, and designed it “The Ruby Way”. It lets you focus on building your Factual queries and using the results in Ruby. It handles details like OAuth and url encoding, so you don’t have to. The driver and its associated gems are hosted at Rubygems. org. Install the driver as a gem in your project as follows:$ gem install factual-api Once you have the driver installed in your Ruby project, here’s how you create an authenticated handle to Factual:require 'factual'factual = Factual.
     </li>
     <li>
          <a href="http://feedproxy.google.com/~r/factualblog/~3/Iv-_Jsdknr4/startup-weekend-san-jose-2012">Startup Weekend San Jose Developer Contest</a> - (01/25/2012) - We’re proud to announce that we are sponsoring this year’s Startup Weekend San Jose. At Factual, we’re big fans of Startup Weekend and their mission toinspire, educate, and empower individuals, teams and communities. We also love empowering developers to do amazing things with data faster and easier than ever before. To help one lucky team achieve their startup dreams, we will be awarding Free Accelerated Access to the Factual API for one year, plus $500 in Amazon Gift Cards to the Startup Weekend San Jose team that makes best use of the Factual API. What: Startup Weekend San Jose When:January 27 – 29, 2012 Where:2903 Bunker Hill Ln. , Santa Clara, CA, 95054 Details:http://sanjose.
     </li>
     <li>
          <a href="http://feedproxy.google.com/~r/factualblog/~3/tvXWZeUL-Kk/factual-php-driver">Factual PHP Driver</a> - (01/23/2012) - We are pleased to report the availability of the official PHP driver for the Factual API. This driver wraps our Read, Crosswalk, Resolve, and Schema APIs, providing five-line access to our 55 million global places and other structured data. ExamplesGetting Started: First, get an API key from Factual. Add your oauth key and secret to the constructor:require_once('Factual.
     </li>
</ul>
<p>
     <strong>From the <a title="InfoChimps" href="http://blog.infochimps.com/">InfoChimps</a> Blog</strong>
</p>
<ul class="mainlist">
     <li>
          <a href="http://feedproxy.google.com/~r/infochimps-blog/~3/-TmtaakvJzM/">Fixies and Hipsters are Correlated?</a> - (01/27/2012) - Depending on who you are, the sight of a gorgeously simple yet eclectic fixed gear bicycle may make your mouth water or may fill you with ire. Perhaps if you feel the former, you are the current owner of several pairs of skinny jeans, a pearl snap vintage shirt and ironic glasses. In other words, you are a hipster. According to the folks on Quora, fixed gear bicycles (or fixies) are considered to be a strong indicator of hipsterness. The folks at Priceonomics blog, as part of their effort to build a comprehensive bicycle pricing guide, have measured what kinds of used bicycles people sell and the quantity sold in cities across the US. To find where the hipsters live, they mined their database of 1.
     </li>
     <li>
          <a href="http://feedproxy.google.com/~r/infochimps-blog/~3/IyUYtJtiIkg/">The Best Pie Chart Ever</a> - (01/26/2012) - Thanks, ilovecharts.
     </li>
     <li>
          <a href="http://feedproxy.google.com/~r/infochimps-blog/~3/q3IXbXRuaSk/">How long does it take for a cockroach to die?</a> - (01/25/2012) - Earlier this week, YouTube revealed that users are uploading one hour of video every second to the site. It’s quite the amazing milestone, not only speaking to YouTube’s massive success, but also the mind-boggling rate at which we are producing data. Furthermore,it was revealed that the average YouTube visitor spends an average of 15 minutes a day on the site, accounting for a total of 4 billion video views per day. It can be overwhelming for most to understand the sheer size of these numbers, so to help put things into perspective, YouTube has created One Hour Per Second.
     </li>
     <li>
          <a href="http://feedproxy.google.com/~r/infochimps-blog/~3/UfbJ5p_dysk/">Economic Outlook: Mostly Typical</a> - (01/24/2012) - Using major macroeconomic indicators, Russell Investments has created a dashboard to capture a snapshot of the state of our economy. It’s updated on the 22nd of each month with data from Bloomberg. You can click through the “Historical Details” links to read more about each indicator and its see its changes over time. Check out the legend below for complete details on how to read the chart. So, what does this dashboard tell us about the current state of our economy? For starters, we are growing at a modest 1. 8%. As youcan see from the chart, most indicators are well within “typical” range and even mortgagedelinquenciesand corporate debt are slowly coming down.
     </li>
</ul>
<p>
     <strong>Tweets from <a title="InfoChimps" href="https://twitter.com/#!/infochimps">InfoChimps</a></strong>
</p>
<blockquote>
     <strong>(01/27/2012)</strong> <a href="https://twitter.com/#!/infochimps/status/162990504114524161%3EFixies%20and%20Hipsters%20are%E2%80%A6%20Correlated?%20http://t.co/el4k8dBA%3C/a%3E%3Cbr%20/%3E%3Cstrong%3E(01/26/2012)%3C/strong%3E%20%3Ca%20href=">The Best Pie Chart Ever http://t.co/YDjiT0k9</a><br />
     <strong>(01/26/2012)</strong> <a href="https://twitter.com/#!/infochimps/status/162587610043265024%3E@livehappy8%20Hey%20Nicole%20-%20looks%20like%20that's%20actually%20our%20friends%20at%20@mailchimp's%20logo.%20)%3C">@denzil_correa Which API are you using? We can have the engineers take a look ASAP.</a><br />
     <strong>(01/25/2012)</strong> <a href="https://twitter.com/#!/infochimps/status/162245966907445248%3EHow%20long%20does%20it%20take%20for%20a%20cockroach%20to%20die?%20http://t.co/Ho3EzgVv%3C/a%3E%3Cbr%20/%3E%3Cstrong%3E(01/24/2012)%3C/strong%3E%20%3Ca%20href=">@jonalmond2 No, we're not planning a move anytime soon and for future reference, Twitter cold calling is lame. :)</a><br />
     <strong>(01/24/2012)</strong> <a href="https://twitter.com/#!/infochimps/status/161905938385747968%3EEconomic%20Outlook:%20Mostly%20Typical%20http://t.co/xtrvwraS%3C/a%3E%3Cbr%20/%3E%3Cstrong%3E(01/23/2012)%3C/strong%3E%20%3Ca%20href=">@carterrabasa Check out our Foursquare Places API... http://t.co/RGDogpm1</a><br />
     <strong>(01/23/2012)</strong> <a href="https://twitter.com/#!/infochimps/status/161575261941399552%3ERT%20@mckquarterly%20US%20households%20Debt%20has%20fallen%20by%20$584%20billion;%20or%204%%20in%20absolute%20terms.%20http">4 Ways Small Businesses Can Build a Great Culture : Managing :: American Express OPEN Forum http://t.co/G77CQ6Sk via @OpenForum</a><br />
     <strong>(01/26/2012)</strong> <a href="https://twitter.com/#!/Infogroup/status/162573525348122624%3E10%20Tech%20Trends%20Defining%20the%20Future%20of%20Small%20Business%20http://t.co/dmrNgmdm%20via%20@entmagazine%3C/a%3E%3Cbr%20/%3E%3Cstrong%3E(01/26/2012)%3C/strong%3E%20%3Ca%20href=">One Sure-fire Way to Be a Better Leader : Lifestyle :: American Express OPEN Forum http://t.co/AgvEAQtE via @OpenForum</a><br />
     <strong>(01/25/2012)</strong> <a href="https://twitter.com/#!/Infogroup/status/162245203451850753%3E10%20Lessons%20in%20Marketing%20Brilliance%20|%20Slideshow%20|%20http://t.co/ZNGJyavt%20http://t.co/u9ZaLatg%20via%20@entmagazine%3C/a%3E%3Cbr%20/%3E%3Cstrong%3E(01/25/2012)%3C/strong%3E%20%3Ca%20href=">Turning Customers Into Fans and Followers : Marketing :: American Express OPEN Forum http://t.co/HJBWLi3m via @OpenForum</a><br />
     <strong>(01/25/2012)</strong> <a href="https://twitter.com/#!/Infogroup/status/162235472523956224%3E28%20Essential%20Facebook%20Timeline%20Resources%20http://t.co/dhWNjvte%20via%20@mashable%3C/a%3E%3Cbr%20/%3E%3Cstrong%3E(01/25/2012)%3C/strong%3E%20%3Ca%20href=">#alamw12 - Big THANKS to all our friends we saw in Dallas</a><br />
     <strong>(01/24/2012)</strong> <a href="https://twitter.com/#!/Infogroup/status/161859845253906432%3EThe%20One%20Great%20Thing%20that%20Every%20Great%20Leader%20Does%20-%20Forbes%20http://t.co/xX4llEBU%3C/a%3E%3Cbr%20/%3E%3Cstrong%3E(01/24/2012)%3C/strong%3E%20%3Ca%20href=">11 Vital Mobile Apps for Entrepreneurs http://t.co/sTm8DABT via @mashable</a><br />
     <strong>(01/24/2012)</strong> <a href="https://twitter.com/#!/Infogroup/status/161827755938426881%3E6%20Ways%20Nonprofits%20Can%20Use%20Facebook%20Covers%20to%20Promote%20Online%20Fundraising%20http://t.co/Hfz7FezQ%3C/a%3E%3Cbr%20/%3E%3Cstrong%3E(01/24/2012)%3C/strong%3E%20%3Ca%20href=">Reduce Customer Service Expenses Using Twitter and Facebook : Managing :: American Express OPEN Forum http://t.co/UaBCiHNN via @OpenForum</a><br />
     <strong>(01/23/2012)</strong> <a href="https://twitter.com/#!/Infogroup/status/161574779797774336%3EConsumers%20Want%20Online%20Video%20Ads%20No%20More%20Than%2015%20Seconds%20Long%20http://t.co/JhYd111p%20via%20@mashable%3C/a%3E%3Cbr%20/%3E%3Cstrong%3E(01/23/2012)%3C/strong%3E%20%3Ca%20href=">Starting today, we will be adding @TheDailyTrigger tweets to our feed. For infomation about iSell check out this link http://t.co/olN5UKNr</a><br />
     <strong>(01/23/2012)</strong> <a href="https://twitter.com/#!/Infogroup/status/161539805342203904%3E9%20Best%20Practices%20for%20Social%20Networking%20in%20the%20Workplace%20http://t.co/7zx011Ik%20via%20@mashbusiness%20@mashable%3C/a%3E%3Cbr%20/%3E%3Cstrong%3E(01/23/2012)%3C/strong%3E%20%3Ca%20href=">#alamw12 #referenceusa/Booth1855 sponsors the ALTAFF gala Authors Tea, Monday, January 23rd http://t.co/FeZcLWrQ…</a><br />
     <strong>(01/23/2012)</strong> <a href="https://twitter.com/#!/Infogroup/status/161468763902984192%3EHow%20Running%20a%20Small%20Business%20Has%20Changed%20:%20Lifestyle%20::%20American%20Express%20OPEN%20Forum%20http://t.co/3uXhU5Oy%20via%20@OpenForum%3C/a%3E%3Cbr%20/%3E%3C/blockquote%3E%3Cstrong%3EProcessing%20Twitter%20for%20Acxiom%3C/strong%3E%3Cbr%20/%3E%3Cblockquote%3E%3Cstrong%3E(01/24/2012)%3C/strong%3E%20%3Ca%20href=">Thinking about switching #email platforms? Some key criteria to think about before you do: http://t.co/RstNFHGo via @MediaPost</a><br />
     <strong>(01/23/2012)</strong> <a href="https://twitter.com/#!/Acxiom/status/161591293452099584%3ERT%20@timsuther%20Predictions%20For%202012%20Data%20Is%20Everywhere!%20http">Loci 2011: Gib Olander http://t.co/mP9ytx6b via @mblumenthal</a><br />
     <strong>(01/25/2012)</strong> <a href="https://twitter.com/#!/localeze/status/162278621556387840%3EA%20Business%20Listing%20Is%20Your%20Online%20Anchor%20(Five%20Rules%20for%20Ensuring%20Stability)%20http://t.co/G9EycJKA%20via%20@marketingprofs%3C/a%3E%3Cbr%20/%3E%3C/blockquote%3E%3Cstrong%3EProcessing%20Twitter%20for%20HyperPublic%3C/strong%3E%3Cbr%20/%3E%3Cblockquote%3E%3C/blockquote%3E%3Cp%3E%3Cstrong%3EFrom%20the%20%3Ca%20title=">HyperPublic</a> Blog
</blockquote>