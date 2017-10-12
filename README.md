# Awesome Cisco Spark

A curated list of Cisco Spark resources for Developers, inspired by [awesome-go](https://github.com/avelino/awesome-go) and [awesome-python](https://github.com/vinta/awesome-python).


### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/CiscoDevNet/awesome-ciscospark/blob/master/CONTRIBUTING.md) first. Thanks to all contributors; you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*


### Contents

DISCLAIMER: Cisco does not make any commitments about the resources listed in this document, nor the accuracy of the third party resources and any content accessible via those links.


- [Bot frameworks](#bot-frameworks)
- [Client SDKs](#client-sdks)
- [Examples](#examples)
- [Integration Services](#integration-services)
- [Reference](#reference)
- [Tools](#tools)


## Bot frameworks

*Libraries to code your own bots and integrations implementing Cisco Spark Webhooks and/or the OAuth Grant Flow.*

* Java
     * [odl-sparkbot](https://github.com/CiscoDevNet/odl-sparkbot) - An SDK for developing clients and bots on top of the OpenDaylight platform (by jmedved).
* Javascript
     * [Botkit](https://github.com/howdyai/botkit/blob/master/docs/readme-ciscospark.md) - Build conversational bots that can live on multiple platforms (by Howdy.ai).
     * [bot-connector](https://github.com/RecastAI/bot-connector/wiki/Channel-Cisco) - Connect your bot to multiple messaging channels (by Recast.ai).
     * [flint](https://github.com/flint-bot/flint) - Bot SDK for NodeJS (by nmarus).
     * [hubot-spark](https://github.com/tonybaloney/hubot-spark) - A Hubot integration for Cisco Spark (by tonybaloney).
     * [hubot-sparkwebhook](https://github.com/marchfederico/hubot-sparkwebhook) - A Hubot adapter (by marchfederico).
     * [node-sparkbot](https://github.com/CiscoDevNet/node-sparkbot) - Build bots in nodejs and experiment webhooks (by ObjectIsAdvantag).
* PHP
     * [botman](https://github.com/botman/driver-cisco-spark) - Driver to connect Cisco Spark with BotMan (by mpociot).
* Python
     * [err-backend-cisco-spark](https://github.com/panholt/err-backend-cisco-spark) - An errbot backend for Cisco Spark (by panholt).


## Client SDKs

*Helper libraries to consume Cisco Spark APIs*

* REST API SDKs
    * C#
        * [SparkDotNet](https://github.com/darrenparkinson/SparkDotNet) - An unofficial dotnet library for consuming RESTful APIs (by darrenparkinson).
    * Go
        * [go-cisco-spark](https://github.com/jbogarin/go-cisco-spark) - A Go client library (by jbogarin).
    * Haskell
        * [cisco-spark-api](https://github.com/nshimaza/cisco-spark-api) - A Haskell bindings (by nshimaza).
    * Java
        * [spark-java-sdk](https://github.com/ciscospark/spark-java-sdk) - A Java library for consuming RESTful APIs (by Cisco).
    * NodeJS
        * [sparkclient](https://github.com/marchfederico/node-sparkclient) - A simple node module (by marchfederico).
        * [sparky](https://github.com/flint-bot/sparky) - A simple API wrapper for NodeJS (by nmarus).
    * Python
        * [ciscosparkapi](https://github.com/CiscoDevNet/ciscosparkapi) - Simple, lightweight, scalable Python API wrapper (by cmlccie).
        * [pyCiscoSpark](https://github.com/brbester/pyCiscoSpark) - Python library (by brbester).
    * Ruby
        * [cisco_spark-ruby](https://github.com/NGMarmaduke/cisco_spark-ruby) - Ruby client (by NGMarmaduke).
* Web & Mobile Spark SDKs
    * [SDK for iOS](https://github.com/ciscospark/spark-ios-sdk) - iOS SDK written in swift (by Cisco).
    * [SDK for Javascript](https://github.com/ciscospark/spark-js-sdk) - A collection of node modules inspired from the Spark Web client's Legacy SDK (by Cisco).


## Examples

*Basic to inspiring code samples in various languages*

* Java
     * [Midori](https://github.com/midoricorp/jabbot/tree/master/bindings/jabbot-spark-binding) - An extensible chat robot with Spark binding (by midoricorp).
     * [QuizBot](https://github.com/LucaCalabrese/codemotion-spark-bot) - Answer a technology quiz, get scored (by LucaCalabrese).
* NodeJS
     * [Botkit samples](https://github.com/CiscoDevNet/botkit-ciscospark-samples) - Conversational bot samples built with Botkit (by ObjectIsAdvantag).
     * [ciscospark-jira](https://github.com/promptworks/ciscospark-jira) - JIRA bot built with Botkit (by patricksmith).
     * [ciscospark-websocket-events](https://github.com/marchfederico/ciscospark-websocket-events) - An unsupported hack to get events thru Spark's native websocket (by marchfederico).
     * [email2spark](https://github.com/marchfederico/email2spark/blob/master/email2spark.js) - Move an email thread to a room using Mailgun (by marchfederico).
     * [integration-sample](https://github.com/CiscoDevNet/spark-integration-sample) - An example of integration in nodejs (by ObjectIsAdvantag).
     * [spark-botkit-salesforce](https://github.com/asynchrony-ringo/spark-botkit-salesforce) - SalesForce bot built with Botkit (by asynchrony-ringo).
     * [spark-botkit-servicenow](https://github.com/asynchrony-ringo/spark-botkit-servicenow) - ServiceNow bot built with Botkit (by asynchrony-ringo).
     * [sparkbot-samples](https://github.com/CiscoDevNet/node-sparkbot-samples) - Examples of bots, leveraging the node-sparkbot framework (by ObjectIsAdvantag).
     * [sparkbotstarter](https://github.com/valgaze/sparkbotstarter) - Starter kit for a simple bot leveraging flint (by valgaze).
     * [zbot](https://github.com/akalsey/zbot) - Play Zork interactive game in Cisco Spark rooms (by akalsey).
* PHP
     * [botman-spark-demo](https://github.com/mpociot/botman-spark-demo) - Shows how to use BotMan in combination with Cisco Spark (by mpociot).
* Python
     * [Blog companions](https://github.com/ciscospark/Spark-API-Demos) - Simple scripts and bots as companions to the spark4devs blog (by Spark API support team).
     * [ciscosparkapi bots](https://github.com/CiscoDevNet/ciscosparkapi/tree/master/examples) - Flask, webpy and pyramid bot examples (by cmlccie).
     * [My Spark Hero](https://github.com/hpreston/myhero_spark) - Vote for your favorite superhero, deploy as a docker container on Mantl.io (by hpreston).
     * [Room Finder](https://github.com/Guismo1/roomfinder/tree/master/roomfinder_spark) - Bot to a meeting room finder interfaced with Microsoft Exchange (by Guismo1).
     * [Walkthrough](https://developer.ciscospark.com/blog/blog-details-8110.html) - Quick walkthrough to build a simple bot (by JustinDupree).
* Ruby
     * [Fault Report](https://github.com/jfield44/TropoFaultReport) - Reporting System using Tropo and Cisco Spark for efficient Fault Resolution (by jfield44).
* Swift
     * [Kitchen Sink](https://github.com/ciscospark/spark-ios-sdk-example) - Developer friendly sample to showcase Spark iOS SDK features (by Spark for Developers).
     * [Spark iOS SDK Wrapper](https://github.com/jfield44/SparkSDKWrapper) - Wrapper library offering a drop in voice and video calling component (by jfield44).


## Integration services

*Cloud platforms and wiring engines to build Cisco Spark Apps with little to no coding*

* <a name="cis">Cloud Services</a> - Create integrations or assemble from pre-built modules (priced services with trials)
     * [API.AI](https://docs.api.ai/docs/spark-integration) - Create Spark bots with natural language understanding.
     * [Built.io](https://flow.built.io/#/library/cisco-spark/all) - Pre-defined Spark templates (signin required).
     * [Gupshup](https://www.gupshup.io/developer/docs/bot-platform/guide/build-deploy-bot-on-cisco-spark) - How to build and deploy a Spark bot.
     * [IFTTT](https://ifttt.com/cisco_spark/recipes) - Spark recipies.
     * [Recast](https://botconnector.recast.ai/integrations) - Collaborative platform to build, train, deploy and monitor bots.
     * [Stamplay](https://stamplay.com/integrations/cisco%20spark) - Integrate and automate Cisco Spark.
     * [Workato](https://www.workato.com/integrations/cisco_spark) - Get more out of Cisco Spark by connecting it.
     * [Zapier](https://zapier.com/zapbook/cisco-spark/) - Recommended Spark zaps.
* Wiring Engines
     * [node-red](https://github.com/cumberlandgroup/node-red-contrib-spark) - Node-RED nodes to integrate with the Cisco Spark API (by nmarus).


## Reference

*Resources maintained by Cisco Product teams and Developer Communities*

* Developer Spaces
    * [Botkit devs](https://eurl.io/#SyNZuomKx) - The Botkit developer community Space.
    * [Flint devs](https://eurl.io/#rkwLEq4fZ) - The node-flint developer community Space.
    * [Python Spark devs](https://eurl.io/#HkMxO-_9-) - The Python developer community Space.
    * [#spark4dev](https://developer.ciscospark.com/support.html) - Get help from Spark DevSupport and other community members (by Cisco).
* Learn
    * [API documentation](https://developer.ciscospark.com/quick-reference.html) - The reference documentation (by Spark for Developers).
    * [Spark4Devs blog](https://developer.ciscospark.com/blog-home.html) - Samples and API updates (by Spark for Developers).
    * [DevNet learning track](https://learninglabs.cisco.com/tracks/collab-cloud) - Learn to build bots and integration (by CiscoDevNet).
    * [Rate limiting](https://developer.ciscospark.com/blog/blog-details-8193.html) - Explains 429 & Retry-After HTTP header (by Spark for Developers). 
    * [security whitepaper](http://www.cisco.com/c/dam/en/us/solutions/collateral/collaboration/cloud-collaboration/cisco-spark-security-white-paper.pdf) - Details the end-to-end secured service (by Cisco).
    * [videos](https://www.youtube.com/playlist?list=PLF2B449AC79859DC5) - A YouTube playlist to discover how to setup and manage Cisco Spark (by Cisco).
    * [What's new and next](http://cs.co/spark-new-next) - Latest PDF covering Cisco Cloud Collaboration updates (by Cisco).
* Share
    * [ambassadors](https://ambassador.ciscospark.com/about/) - A worldwide network of professionals (by Cisco).
    * [community of interest](https://developer.cisco.com/site/spark/) - Share your passion for bots and integrations, learn from others (by CiscoDevNet).
    * [creations](https://developer.cisco.com/site/devnetcreations/) - Inspire others by sharing your code (by CiscoDevNet).
    * [depot](https://depot.ciscospark.com/) - Catalog for bots & integrations (by Cisco).
    * [partner program](help.webex.com/docs/DOC-5364) - Get Started as a Cisco Spark Partner (by Cisco).
* Support
    * [devsupport](https://developer.ciscospark.com/support.html) - 24/7 developer support community (by Spark for Developers).
    * [geos](http://cs.co/geos) - Quickly check where Cisco Spark is available (by Cisco).
    * [media test](https://mediatest.ciscospark.com/) - Test your TCP/UDP network eligibility (by Cisco).
    * [status page](https://status.ciscospark.com/) - Service availability page for the Developer API (by Cisco).


## Tools

*Handy tools to browse or interact with the Cisco Spark REST API*

* [generator-spark-bot](https://github.com/brh55/generator-spark-bot) - A yeoman generator that scaffolds out a bot with usability and simplicity in mind (by brh55).
* [interactive tool](https://developer.ciscospark.com/quick-reference.html) - Toogle "Test mode" in the API documentation (by Spark for Developers).
* [postman-ciscospark](https://github.com/CiscoDevNet/postman-ciscospark) - Scripted Postman collections to generate code and more (by ObjectIsAdvantag).
* [sparkcli](https://github.com/tdeckers/sparkcli) - A command line interface (by tdeckers).
* [spark-messages](https://github.com/brh55/spark-messages) - A collection of helpers to ensure consistent formatting of markdown messages (by brh55).
* [Spark-Space-Archive](https://github.com/DJF3/Spark-Space-Archive) - Archive messages to a single HTML file (by DJF3).
* [swagger-cisco-spark](https://github.com/cumberlandgroup/swagger-cisco-spark) - Swagger definition file for Cisco Spark API v1 (by nmarus).
* [whproxy](https://github.com/sgrimee/whproxy) - Proxy incoming webhooks to established websockets (by sgrimee).
