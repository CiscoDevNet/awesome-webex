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

* Javascript
     * [flint](https://github.com/nmarus/flint/commits/master) - bot SDK for NodeJS (by nmarus)
     * [hubot-sparkwebhook](https://github.com/marchfederico/hubot-sparkwebhook) - a Hubot adapter (by marchfederico)
     * [node-sparkbot](https://github.com/CiscoDevNet/node-sparkbot) - build bots in nodejs and experiment webhooks (by ObjectIsAdvantag)


## Client SDKs

*Helper libraries to consume Cisco Spark APIs*

* REST API SDKs
    * C#
        * [SparkDotNet](https://github.com/darrenparkinson/SparkDotNet) - an unofficial dotnet library for consuming RESTful APIs (by darrenparkinson)
    * Go
        * [go-cisco-spark](https://github.com/jbogarin/go-cisco-spark) - a Go client library (by jbogarin)
    * Java
        * [spark-java-sdk](https://github.com/ciscospark/spark-java-sdk) - a Java library for consuming RESTful APIs (by Cisco)
    * NodeJS
        * [sparkclient](https://github.com/marchfederico/node-sparkclient) - a simple node module (by marchfederico)
        * [sparky](https://github.com/nmarus/sparky) - a simple API wrapper for NodeJS (by nmarus)
    * Python
        * [ciscosparkapi](https://github.com/CiscoDevNet/ciscosparkapi) - Simple, lightweight, scalable Python API wrapper (by cmlccie)
        * [cmlCiscoSparkSDK](https://github.com/cmlccie/cmlCiscoSparkSDK) - Pythonic classess and methods (by cmlccie)
        * [pyCiscoSpark](https://github.com/brbester/pyCiscoSpark) - Python library (by brbester)        
    * Ruby
        * [cisco_spark-ruby](https://github.com/NGMarmaduke/cisco_spark-ruby) - Ruby client (by NGMarmaduke)
* Web & Mobile Spark SDKs
    * [SDK for iOS](https://github.com/ciscospark/spark-ios-sdk) - iOS SDK written in swift (by Cisco)
    * [SDK for Javascript](https://github.com/ciscospark/spark-js-sdk) - a collection of node modules inspired from the Spark Web client's Legacy SDK (by Cisco)


## Examples

*Basic to inspiring code samples in various languages*

* Java
     * [Midori](https://github.com/midoricorp/jabbot/tree/master/bindings/jabbot-spark-binding) - an extensible chat robot with Spark binding (by midoricorp)
* NodeJS
     * [email2spark](https://github.com/marchfederico/email2spark/blob/master/email2spark.js) - move an email thread to a room using Mailgun (by marchfederico)
     * [integration-sample](https://github.com/CiscoDevNet/spark-integration-sample) - an example of integration in nodejs (by ObjectIsAdvantag)
     * [sparkbot-samples](https://github.com/CiscoDevNet/node-sparkbot-samples) - examples of bots, leveraging the node-sparkbot framework (by ObjectIsAdvantag)
     * [sparkbotstarter](https://github.com/valgaze/sparkbotstarter) - starter kit for a simple bot leveraging flint (by valgaze)
     * [zbot](https://github.com/akalsey/zbot) - play Zork interactive game in Cisco Spark rooms or over SMS with Tropo (by akalsey)
* Python
     * [Blog companions](https://github.com/ciscospark/Spark-API-Demos) - simple scripts and bots as companions to the spark4devs blog (by Spark API support team)
     * [My Spark Hero](https://github.com/hpreston/myhero_spark) - vote for your favorite superhero, deploy as a docker container on Mantl.io (by hpreston)
     * [Room Finder](https://github.com/Guismo1/roomfinder/tree/master/roomfinder_spark) - bot to a meeting room finder interfaced with Microsoft Exchange (by Guismo1)
     * [Walkthrough](https://developer.ciscospark.com/blog/blog-details-8110.html) - quick walkthrough to build a simple bot (by JustinDupree)
* Ruby
     * [Fault Report](https://github.com/jfield44/TropoFaultReport) - Reporting System using Tropo IVR and Cisco Spark for efficient Fault Resolution (by jfield44)
* Swift
     * [Kitchen Sink](https://github.com/ciscospark/spark-ios-sdk-example) - developer friendly sample to showcase Spark iOS SDK features (by Spark for Developers)


## Integration services

*Cloud platforms and wiring engines to build Cisco Spark Apps with little to no coding*

* <a name="cis">Cloud Services</a> - create integrations or assemble from pre-built modules (priced services with trials)
     * [API.AI](https://docs.api.ai/docs/spark-integration) - create Spark bots with natural language understanding
     * [Built.io](https://flow.built.io/#/library/cisco-spark/all) - pre-defined Spark templates (signin required)
     * [Gupshup](https://www.gupshup.io/developer/docs/bot-platform/guide/build-deploy-bot-on-cisco-spark) - how to build and deploy a Spark bot
     * [IFTTT](https://ifttt.com/cisco_spark/recipes) - Spark recipies
     * [Stamplay](https://stamplay.com/integrations/cisco%20spark) - integrate and automate Cisco Spark
     * [Workato](https://www.workato.com/integrations/cisco_spark) - get more out of Cisco Spark by connecting it
     * [Zapier](https://zapier.com/zapbook/cisco-spark/) - recommended Spark zaps
* Wiring Engines
     * [node-red](https://github.com/nmarus/node-red-contrib-spark) - Node-RED nodes to integrate with the Cisco Spark API (by nmarus)


## Reference

*Developer resources maintained by Cisco Product teams*

* Learn
    * [API documentation](https://developer.ciscospark.com/quick-reference.html) - the reference documentation (by Spark for Developers)
    * [blog](https://developer.ciscospark.com/blog-home.html) - samples and updates (by Spark for Developers)
    * [learning track](https://learninglabs.cisco.com/tracks/collab-cloud) - learn to build bots and integration (by CiscoDevNet)
    * [security whitepaper](http://www.cisco.com/c/dam/en/us/solutions/collateral/collaboration/cloud-collaboration/cisco-spark-security-white-paper.pdf) - details the end-to-end secured service (by Cisco Spark)
    * [videos](https://www.youtube.com/playlist?list=PLF2B449AC79859DC5) - a YouTube playlist to discover how to setup and manage Cisco Spark (by Cisco)
* Share
    * [community of interest](https://developer.cisco.com/site/spark/) - share your passion for bots and integrations, learn from others (by CiscoDevNet)
    * [creations](https://developer.cisco.com/site/devnetcreations/) - inspire others by sharing your code (by CiscoDevNet)
    * [depot](https://depot.ciscospark.com/) - catalog for bots & integrations (by Cisco)
* Support
    * [devsupport](https://developer.ciscospark.com/support.html) - 24/7 developer support community (by Spark for Developers)
    * [geos](http://cs.co/geos) - quickly check where Cisco Spark is available (by Cisco)
    * [media test](https://mediatest.ciscospark.com/) - test your TCP/UDP network eligibility (by Cisco)
    * [status page](https://status.ciscospark.com/) - service availability page for the Developer API (by Spark for Developers)
    

## Tools

*Handy tools to browse or interact with the Cisco Spark REST API*

* [cisco-spark-swagger](https://github.com/nmarus/cisco-spark-swagger) - Swagger definition file for Cisco Spark API v1 (by nmarus)
* [interactive tool](https://developer.ciscospark.com/quick-reference.html) - toogle "Test mode" in the API documentation (by Spark for Developers) 
* [postman-ciscospark](https://github.com/CiscoDevNet/postman-ciscospark) - scripted Postman collections to generate code and more (by ObjectIsAdvantag)
* [sparkcli](https://github.com/tdeckers/sparkcli) - a command line interface (by tdeckers)




