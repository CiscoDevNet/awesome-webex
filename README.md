# Awesome Webex [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of [Cisco Webex](https://www.webex.com) resources for developers, inspired by [awesome-go](https://github.com/avelino/awesome-go) and [awesome-python](https://github.com/vinta/awesome-python).

> Currently gathers resources **only for [Webex Teams](https://www.webex.com/products/teams/)** (formerly Cisco Spark) as documented at [Webex for Developers](https://developer.webex.com).<br/>
> Looking for developer resources for **[Webex Meetings](https://www.webex.com/products/meetings/)**? check the [Getting Started guide for Webex Meetings](https://developer.cisco.com/site/webex-developer/develop-test/getting-started/).<br/>
> Interested in **[Webex Devices](https://www.webex.com/products/devices/index.html)** programmability? check the [Room Devices dev center](http://cs.co/roomdevices/).


### Contributing

Please take a quick gander at the [Contribution guidelines](./CONTRIBUTING.md) first. Thanks to all contributors; you rock!

If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!


### Contents

DISCLAIMER: Cisco does not make any commitments about the resources listed in this document, nor the accuracy of the third party resources and any content accessible via the links below.


- [Bot frameworks](#bot-frameworks)
- [Clients SDKs](#client-sdks)
   - [REST API](#rest-api-clients)
   - [Advanced APIs](#advanced-apis)
- [Code samples](#code-samples)
   - [REST API samples](#rest-api-samples)
   - [Bot samples](#bot-samples)
   - [Mobile samples](#mobile-samples)
   - [Web SDK & Widgets samples](#web-sdk--widgets-samples)
- [Integration Services](#integration-services)
- [Reference](#reference)
- [Tools](#tools)


## Bot frameworks

*Libraries to code your own bots and integrations implementing Webhooks and/or the OAuth Grant Flow.*

* Java
    * [odl-sparkbot](https://github.com/CiscoDevNet/odl-sparkbot) - An SDK for developing clients and bots on top of the OpenDaylight platform (by jmedved).
* Javascript
    * [Botkit](https://github.com/howdyai/botkit/blob/master/docs/readme-ciscospark.md) - Build conversational bots that can live on multiple platforms (by Howdy.ai).
    * [bot-connector](https://github.com/RecastAI/bot-connector/wiki/Channel-Cisco) - Connect your bot to multiple messaging channels (by Recast.ai).
    * [flint](https://github.com/flint-bot/flint) - Bot SDK for Node.js (by nmarus).
    * [hubot-spark](https://github.com/tonybaloney/hubot-spark) - A Hubot integration (by tonybaloney).
    * [hubot-sparkwebhook](https://github.com/marchfederico/hubot-sparkwebhook) - A Hubot adapter (by marchfederico).
    * [node-sparkbot](https://github.com/CiscoDevNet/node-sparkbot) - Build bots in Node.js and experiment webhooks (by ObjectIsAdvantag).
* Perl
    * [cisco_spark-perl](https://github.com/akalinux/cisco_spark-perl) - Asynchronous Bot and HTTP Client Library for Perl (by akalinux).
* PHP
    * [botman](https://github.com/botman/driver-cisco-spark) - Driver to connect with BotMan (by mpociot).
* Python
    * [err-backend-cisco-spark](https://github.com/panholt/err-backend-cisco-spark) - An errbot backend (by panholt).


## Client SDKs

### REST API clients

* C#
    * [SparkDotNet](https://github.com/darrenparkinson/SparkDotNet) - An unofficial dotnet library for consuming the RESTful APIs (by darrenparkinson).
* Go
    * [go-cisco-spark](https://github.com/jbogarin/go-cisco-spark) - A Go client library (by jbogarin).
* Haskell
    * [webex-teams-api](https://github.com/nshimaza/webex-teams-api) - A Haskell binding (by nshimaza).
* Java
    * [spark-java-sdk](https://github.com/webex/spark-java-sdk) - A Java library for consuming the RESTful APIs (by Cisco Webex).
* Node.js
    * [ciscospark](https://github.com/webex/spark-js-sdk#nodejs) - A collection of Node.js modules targeting our REST API (by Cisco Webex).
    * [sparkclient](https://github.com/marchfederico/node-sparkclient) - A simple Node.js module (by marchfederico).
    * [sparky](https://github.com/flint-bot/sparky) - A simple API wrapper for Node.js (by nmarus).
* Perl
    * [cisco_spark-perl](https://github.com/akalinux/cisco_spark-perl) - Asynchronous Bot and HTTP Client Library (by akalinux).
* PHP
    * [SparkBundle](https://github.com/CiscoVE/SparkBundle) - Symfony bundle (by CiscoVE).
* Python
    * [aiociscospark](https://github.com/andriyko/aiociscospark) - Python 3 asynchronous API client (by andriyko).
    * [ciscosparkapi](https://github.com/CiscoDevNet/ciscosparkapi) - Simple, lightweight, scalable Python API wrapper (by cmlccie).
    * [pyCiscoSpark](https://github.com/brbester/pyCiscoSpark) - Python library (by brbester).
    * [spark-python-sdk](https://github.com/Bassintag551/spark-python-sdk) - Python module for consuming the RESTful APIs (by Bassintag551).
* Ruby
    * [cisco_spark-ruby](https://github.com/NGMarmaduke/cisco_spark-ruby) - Ruby client (by NGMarmaduke).
    * [ciscospark-ruby](https://github.com/Cloverhound/ciscospark-ruby) - REST kit for Ruby (by chadstachowicz).

### Advanced APIs

* [SDK for Android](https://github.com/webex/spark-android-sdk) - Integrate messaging and calling in your Android apps (by Cisco Webex).
* [SDK for Browsers](https://github.com/webex/spark-js-sdk#browsers) - Integrate calling into your client-side Javascript applications (by Cisco Webex).
* [SDK for iOS](https://github.com/webex/spark-ios-sdk) - Integrate messaging and calling in your iOS apps (by Cisco Webex).
* [Widgets](https://github.com/webex/react-ciscospark) - React components that mimic the Web user experience (by Cisco Webex).


## Code samples

### REST API samples

* Node.js
    * [integration-sample](https://github.com/CiscoDevNet/spark-integration-sample) - Creating a server-side OAuth integration (by ObjectIsAdvantag).
    * [node-sparky-samples](https://github.com/CiscoDevNet/node-sparky-samples) - Client samples with node-sparky (by ObjectIsAdvantag).
    * [spark-messages](https://github.com/brh55/spark-messages) - A collection of helpers to ensure consistent formatting of markdown messages (by brh55).
* Python
    * [Blog companions](https://github.com/webex/Spark-API-Demos) - Simple scripts and bots (by Webex Developer support).
* Ruby
    * [Fault Report](https://github.com/jfield44/TropoFaultReport) - Reporting dystem for efficient Fault Resolution (by jfield44).

### Bot samples

* Java
    * [Midori](https://github.com/midoricorp/jabbot/tree/master/bindings/jabbot-spark-binding) - An extensible chat robot platform (by midoricorp).
    * [QuizBot](https://github.com/LucaCalabrese/codemotion-spark-bot) - Answer a technology quiz, get scored (by LucaCalabrese).
* Node.js
    * [email2spark](https://github.com/marchfederico/email2spark/blob/master/email2spark.js) - Move an email thread to a space using Mailgun (by marchfederico).
    * [generator-spark-bot](https://github.com/brh55/generator-spark-bot) - A yeoman generator that scaffolds out a bot with usability and simplicity in mind (by brh55).
    * [sparkbot-samples](https://github.com/CiscoDevNet/node-sparkbot-samples) - Examples of bots, leveraging the node-sparkbot framework (by ObjectIsAdvantag).
    * [sparkbotstarter](https://github.com/valgaze/sparkbotstarter) - Starter kit for a simple bot leveraging flint (by valgaze).
    * [zbot](https://github.com/akalsey/zbot) - Play the Zork interactive game in spaces (by akalsey).
* Node.js (Botkit)
    * [botkit samples](https://github.com/CiscoDevNet/botkit-ciscospark-samples) - Conversational bot samples built with Botkit (by ObjectIsAdvantag).
    * [botkit-template](https://github.com/CiscoDevNet/botkit-template) - Best practices to bootstrap a Botkit project (by ObjectIsAdvantag).
    * [ciscospark-jira](https://github.com/promptworks/ciscospark-jira) - Jira bot built with Botkit (by patricksmith).
    * [spark-botkit-salesforce](https://github.com/asynchrony-ringo/spark-botkit-salesforce) - SalesForce bot built with Botkit (by asynchrony-ringo).
    * [spark-botkit-servicenow](https://github.com/asynchrony-ringo/spark-botkit-servicenow) - ServiceNow bot built with Botkit (by asynchrony-ringo).
* PHP
    * [botman-spark-demo](https://github.com/mpociot/botman-spark-demo) - Use BotMan in combination with Webex Teams (by mpociot).
* Python
    * [ciscosparkapi bots](https://github.com/CiscoDevNet/ciscosparkapi/tree/master/examples) - Flask, webpy and pyramid bot examples (by cmlccie).
    * [My Hero](https://github.com/hpreston/myhero_spark) - Vote for your favorite superhero, deploy as a docker container on Mantl.io (by hpreston).
    * [Room Finder](https://github.com/Guismo1/roomfinder/tree/master/roomfinder_spark) - Bot to a meeting room finder interfaced with Microsoft Exchange (by Guismo1).
    * [Walkthrough](https://developer.webex.com/blog/blog-details-8110.html) - Quick walkthrough to build a simple bot (by JustinDupree).

### Mobile samples

* Android
    * [Kitchen Sink](https://github.com/webex/spark-android-sdk-example) - Developer friendly sample to showcase the Android SDK features (by Cisco Webex).
    * [Goggles](https://github.com/promptworks/spark-goggles) - ‘You See What I See’ remote expert app for augmented reality headsets (by Promptworks).
* iOS
    * [Buddies](https://github.com/webex/spark-ios-sdk-example-buddies) - Application which combines message/call in a UI (by Cisco Webex).
    * [iOS SDK Wrapper](https://github.com/jfield44/SparkSDKWrapper) - Wrapper library offering a drop in voice and video calling component (by jfield44).
    * [Kitchen Sink](https://github.com/webex/spark-ios-sdk-example) - Developer friendly sample to showcase the iOS SDK features (by Cisco Webex).
    * [Notification Server](https://github.com/webex/spark-ios-sdk-example-push-notification-server) - Receive Incoming Call Notifications using Apple Push Notification Service (by Cisco Webex).
    
### Web SDK & Widgets samples

* SDK for Browsers
    * [call samples](https://developer.webex.com/sdk-for-browsers.html#samples) - Offical samples of the Browser SDK in action (by Cisco Webex).
* Widgets
    * [custom-menu](https://github.com/adamweeks/spark-widget-custom-menu) - Creating custom activities (by adamweeks).
    * [oauth-example](https://github.com/adamweeks/spark-widget-oauth-example) - Widget OAuth example with the Javascript SDK (by adamweeks).
    * [webdialer](https://github.com/achhabra2/webdialer) - Test calls and overlay an existing Web site (by achhabra2).
    * [widget-samples](https://github.com/CiscoDevNet/widget-samples) - Examples for the Space and Recents widgets (by ObjectIsAdvantag).


## Integration services

*Cloud platforms and wiring engines to build applications with little to no coding*

* <a name="cis">Cloud Services</a> - Create integrations or assemble from pre-built modules (priced services with trials)
    * [API.AI](https://docs.api.ai/docs/spark-integration) - Create Teams bots with natural language understanding.
    * [Built.io](https://flow.built.io/#/library/cisco-spark/all) - Pre-defined Teams templates (signin required).
    * [Gupshup](https://www.gupshup.io/developer/docs/bot-platform/guide/build-deploy-bot-on-cisco-spark) - How to build and deploy a Teams bot.
    * [IFTTT](https://ifttt.com/cisco_spark/recipes) - Webex Teams recipies.
    * [Recast](https://botconnector.recast.ai/integrations) - Collaborative platform to build, train, deploy and monitor bots.
    * [Stamplay](https://stamplay.com/integrations/cisco%20spark) - Integrate and automate Webex Teams.
    * [Workato](https://www.workato.com/integrations/cisco_spark) - Get more out of Webex Teams by connecting it.
    * [Zapier](https://zapier.com/zapbook/cisco-spark/) - Recommended zaps for Webex Teams.
* Wiring Engines
    * [node-red](https://github.com/cumberlandgroup/node-red-contrib-spark) - Node-RED Node.js binding to Webex Teams (by nmarus).


## Reference

*Resources maintained by Cisco Product teams and Developer Communities*

* Developer Community Spaces
    * [Botkit devs](https://eurl.io/#SyNZuomKx) - The Botkit developer community space.
    * [Flint devs](https://eurl.io/#rkwLEq4fZ) - The node-flint developer community space.
    * [Python devs](https://eurl.io/#HkMxO-_9-) - The Python developer community space.
    * [#webex4devs](https://developer.webex.com/support.html) - Get help from developer support and community (by Webex for Developers).
* Learn
    * [API documentation](https://developer.webex.com/quick-reference.html) - The reference documentation (by Webex for Developers).
    * [Blog](https://developer.webex.com/blog-home.html) - Samples and API updates (by Webex for Developers).
    * [Learning track](https://learninglabs.cisco.com/tracks/collab-cloud) - Learn the REST API, build bots, embed Video Calls (by CiscoDevNet).
    * [Rate limiting](https://developer.webex.com/blog/blog-details-8193.html) - Explains 429 & Retry-After HTTP header (by Webex for Developers). 
    * [Videos](https://www.youtube.com/playlist?list=PLF2B449AC79859DC5) - A YouTube playlist to discover how to setup and manage Webex Teams (by Cisco).
    * [What's new and coming](https://collaborationhelp.cisco.com/article/en-us/8dmbcr) - New and upcoming features for Webex Teams (by Cisco).
* Security
    * [Firewall traversal](https://www.cisco.com/c/dam/en/us/td/docs/voice_ip_comm/cloudCollaboration/spark/whitepapers/cisco-spark-firewall-traversal-white-paper.pdf) - Whitepaper about deployment requirements (by Cisco).
    * [Network requirements](https://collaborationhelp.cisco.com/article/en-us/WBX264) - For firewall and web security administrators (by Cisco).
    * [Privacy Data Sheet](https://www.cisco.com/c/dam/en_us/about/doing_business/trust-center/docs/cisco-webex-teams-privacy-data-sheet.pdf) - Describes how "personal data" are processed (by Cisco).
    * [Security FAQs](https://www.cisco.com/c/dam/en/us/td/docs/voice_ip_comm/cloudCollaboration/spark/esp/Cisco-Spark-Security-Frequently-Asked-Questions.pdf) - Tech Ops and Security FAQs (by Cisco).
    * [Security whitepaper](http://www.cisco.com/c/dam/en/us/solutions/collateral/collaboration/cloud-collaboration/cisco-spark-security-white-paper.pdf) - Details the end-to-end secured service (by Cisco).
* Share
    * [ambassadors](https://ambassador.webex.com/about/) - A worldwide network of professionals (by Cisco).
    * [app hub](https://apphub.webex.com/) - Catalog for bots & integrations (by Cisco).
    * [community of interest](https://developer.cisco.com/site/spark/) - Share your passion for bots and integrations, learn from others (by CiscoDevNet).
    * [creations](https://developer.cisco.com/site/devnetcreations/) - Inspire others by sharing your code (by CiscoDevNet).
    * [partner program](help.webex.com/docs/DOC-5364) - Get Started as a Webex Partner (by Cisco).
* Support
    * [devsupport](https://developer.webex.com/support.html) - 24/7 developer support community (by Webex for Developers).
    * [geos](http://cs.co/geos) - Quickly check where Webex Teams is available (by Cisco Webex).
    * [media test](https://mediatest.ciscospark.com/) - Test your TCP/UDP network eligibility (by Cisco Webex).
    * [release notes](https://collaborationhelp.cisco.com/article/en-us/mqkve8) - Improvements and fixes for Webex Teams applications (by Cisco).
    * [status page](https://status.ciscospark.com/) - Service availability page for the APIs (by Cisco Webex).


## Tools

*Handy tools to browse or interact with the APIs*

* [interactive documentation](https://developer.webex.com/quick-reference.html) - Toogle "Test mode" in the API documentation (by Webex for Developers).
* [postman-ciscospark](https://github.com/CiscoDevNet/postman-ciscospark) - Scripted Postman collections to generate code and more (by ObjectIsAdvantag).
* [sparkcli](https://github.com/tdeckers/sparkcli) - A command line interface (by tdeckers).
* [sparkguest](https://github.com/ObjectIsAdvantag/sparkguest) - CLI to generate persistent Guest tokens (by ObjectIsAdvantag).
* [spark-space-archive](https://github.com/DJF3/Spark-Space-Archive) - Archive messages to a single HTML file (by DJF3).
* [swagger-cisco-spark](https://github.com/cumberlandgroup/swagger-cisco-spark) - Swagger definition file for the REST API v1 (by nmarus).
* [websocket-events](https://github.com/marchfederico/ciscospark-websocket-events) - An unsupported hack to get events thru a native websocket (by marchfederico).
* [whproxy](https://github.com/sgrimee/whproxy) - Proxy incoming webhooks to established websockets (by sgrimee).
