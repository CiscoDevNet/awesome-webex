# Awesome Cisco Spark

A curated list of Cisco Spark resources for Developers, inspired by [awesome-go](https://github.com/avelino/awesome-go) and [awesome-python](https://github.com/vinta/awesome-python).


### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/CiscoDevNet/awesome-ciscospark/blob/master/CONTRIBUTING.md) first. Thanks to all contributors; you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!* 


### Contents

DISCLAIMER: Cisco does not make any commitments about the resources listed in this document, nor the accuracy of the third party resources and any content accessible via those links.


- [Bot frameworks](#bot-frameworks)
- [Client SDKs](#client-sdks)
- [Reference](#reference)
- [Samples](#samples)
- [Tools](#tools)


## Bot frameworks

*Libraries to code your own bots and integrations implementing Cisco Spark Webhooks and/or the OAuth Grant Flow.*

* [Cloud Integration Services](#cis) - priced services with trials (see Tools section)
* Javascript
     * [flint](https://github.com/nmarus/flint/commits/master) - bot SDK for NodeJS (by nmarus)
     * [hubot-sparkwebhook](https://github.com/marchfederico/hubot-sparkwebhook) - a Hubot adapter (by marchfederico)
     * [node-sparkbot](https://github.com/CiscoDevNet/node-sparkbot) - build Spark Bots and experiment Cisco Spark Webhooks (by ObjectIsAdvantag)


## Client SDKs

*Helper libraries to consume Cisco Spark APIs*

* Public RESTful API SDKs
    * Go
        * [go-cisco-spark](https://github.com/jbogarin/go-cisco-spark) - a Go client library (by jbogarin)
    * Java
        * [spark-java-sdk](https://github.com/ciscospark/spark-java-sdk) - a Java library for consuming RESTful APIs (by Cisco)
    * NodeJS
        * [node-sparky](https://github.com/nmarus/sparky) - a simple API wrapper for NodeJS (by nmarus)
        * [node-ciscospark](https://github.com/marchfederico/node-ciscospark) - a simple node module to work with the Spark APIs (by marchfederico)
    * Python
        * [pyCiscoSpark](https://github.com/brbester/pyCiscoSpark) - Python library (by brbester)
        * [cmlCiscoSparkSDK](https://github.com/cmlccie/cmlCiscoSparkSDK) - Pythonic classess and methods (by cmlccie)
    * Ruby
        * [cisco_spark-ruby](https://github.com/NGMarmaduke/cisco_spark-ruby) - Ruby client (by NGMarmaduke)
* Web & Mobile SDKs
    * [SDK for Javascript](https://github.com/ciscospark/spark-js-sdk) - a collection of node modules inspired from the Spark Web client's Legacy SDK (by Cisco)
    * [SDK for iOS](https://github.com/ciscospark/spark-ios-sdk) - iOS SDK written in swift (by Cisco)


## Reference

*Documentation and other resources maintained by Cisco Product teams*

* Learn
    * [blog](https://developer.ciscospark.com/blog-home.html) - samples and updates (by Spark for Developers)
    * [learnings labs](https://learninglabs.cisco.com/labs/tags/spark) - tutorials (by Cisco DevNet)
    * [security whitepaper](http://www.cisco.com/c/dam/en/us/solutions/collateral/collaboration/cloud-collaboration/cisco-spark-security-white-paper.pdf) - details the end-to-end secured service (by Cisco Spark)
* Support
    * [depot](https://depot.ciscospark.com/) - hub for integrations & bots (by Cisco)
    * [devsupport](https://developer.ciscospark.com/support.html) - 24/7 developer support community (by Spark for Developers)
    * [status page](https://status.ciscospark.com/) - service availability page for the Developer API (by Spark for Developers)
    

## Samples

*Inspiring code samples*

* Java
     * [Midori](https://github.com/midoricorp/jabbot/tree/master/bindings/jabbot-spark-binding) - an extensible chat robot with Spark binding (by midoricorp)
* Python
     * [Room Finder](https://github.com/Guismo1/roomfinder/tree/master/roomfinder_spark) - bot to a meeting room finder interfaced with Microsoft Exchange (by Guismo1)
     * [My Spark Hero](https://github.com/hpreston/myhero_spark) - vote for your favorite superhero, deploy as a docker container on Mantl.io (by hpreston)
* Ruby
     * [Fault Report](https://github.com/jfield44/TropoFaultReport) - Reporting System using Tropo IVR and Cisco Spark for efficient Fault Resolution (by jfield44)


## Tools

*Utilities to interact with the Cisco Spark API, without coding.*

* <a name="cis">Cloud Integration Services</a> - create integrations or assemble from pre-built modules (priced services with trials)
     * [Built.io](https://flow.built.io/#/library/cisco-spark/all) - pre-defined Spark templates (signin required)
     * [Gupshup](https://www.gupshup.io/developer/docs/bot-platform/guide/build-deploy-bot-on-cisco-spark) - how to build and deploy a Spark bot
     * [IFTTT](https://ifttt.com/cisco_spark/recipes) - Spark recipies
     * [Stamplay](https://stamplay.com/integrations/cisco%20spark) - integrate and automate Cisco Spark
     * [Zapier](https://zapier.com/zapbook/cisco-spark/) - recommended Spark zaps
* [interactive documentation](https://developer.ciscospark.com/quick-reference.html) - the reference API documentation (by Spark for Developers) 
* [postman-ciscospark](https://github.com/CiscoDevNet/postman-ciscospark) - scripted Postman collections to generate code and more (by CiscoDevNet)
* [sparkcli](https://github.com/tdeckers/sparkcli) - a command line interface (by tdeckers)



