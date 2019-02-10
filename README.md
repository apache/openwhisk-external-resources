# Awesome Apache OpenWhisk [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [<img src="https://raw.githubusercontent.com/openwhisk/openwhisk/master/docs/images/whisk_icon_full_color_with_tm_100x100-300dpi.png" width="100" align="right" alt="openwhisk">](https://github.com/openwhisk/openwhisk)

> Awesome [Apache OpenWhisk](https://github.com/apache/incubator-openwhisk) resources and tips.

*Apache OpenWhisk is a cloud-first distributed event-based programming service. It provides a programming model to upload event handlers to a cloud service, and register the handlers to respond to various events.*

*Learn more at [http://openwhisk.org](http://openwhisk.org) or try it on [IBM Cloud Functions](https://console.bluemix.net/openwhisk/).*

## Contents

- [Tutorials](#tutorials)
- [Sample Applications](#sample-applications)
- [Articles](#articles)
- [Books](#books)
- [Media](#media)
- [Runtimes](#runtimes)
- [Feed Providers](#feed-providers)
- [Utilities](#utilities)
- [Support](#support)


## Articles

*Articles, tutorials and blogs on building serverless applications using Apache OpenWhisk.*
- [Uncovering the magic: How serverless platforms really work!](https://medium.com/openwhisk/uncovering-the-magic-how-serverless-platforms-really-work-3cb127b05f71) - A step by step guide through the inner guts of OpenWhisk.
- [How to make serverless platforms blazing fast!](https://medium.com/openwhisk/squeezing-the-milliseconds-how-to-make-serverless-platforms-blazing-fast-aea0e9951bd0) - How OpenWhisk makes executing actions so fast...
- [OpenWhisk Planner Bot](https://developer.ibm.com/open/2016/05/13/openwhisk-planner-bot/) - Plan your conference schedule with a serverless recommendation bot
- [Exploring OpenWhisk's REST API](https://amanoblog.wordpress.com/2016/03/03/ibm-bluemix-openwhisk-rest-api/) - Details on the platform API for OpenWhisk.
- [Building an MQTT Feed Provider](http://jamesthom.as/blog/2016/06/15/openwhisk-and-mqtt/) - Walking through adding a new Feed Provider for IoT integration.
- [NPM Modules in OpenWhisk](http://jamesthom.as/blog/2016/11/28/npm-modules-in-openwhisk/) - Using NPM modules in OpenWhisk Actions.
- [Python Packages in OpenWhisk](http://jamesthom.as/blog/2017/04/27/python-packages-in-openwhisk/) - Using external Python libraries in OpenWhisk
- [Docker Actions in OpenWhisk](http://jamesthom.as/blog/2017/01/16/openwhisk-docker-actions/) - Running custom runtimes on OpenWhisk with Docker.
- [Using Go with OpenWhisk](http://jamesthom.as/blog/2017/01/17/openwhisk-and-go/) - Running Go binaries on OpenWhisk
- [SMS Bot](http://jamesthom.as/blog/2017/03/20/smsbot/) - SMS Bot with Twilio and Slack 
- [Databases Updates And Actions](https://lornajane.net/posts/2018/react-to-database-changes-with-openwhisk-actions) - React to Database Changes with OpenWhisk Actions
- [Serverless PHP Webhooks](https://lornajane.net/posts/2018/handle-webhooks-with-serverless-php) - Handle Webhooks with Serverless PHP on OpenWhisk
- [Package Parameters](https://lornajane.net/posts/2017/package-parameters-in-openwhisk) - Storing package parameters for actions
- [Serverless Search Engine](https://www.raymondcamden.com/2017/05/02/building-your-own-serverless-search-engine-with-openwhisk) - Building Your Own Serverless Search Engine with OpenWhisk
- [Uploading Files to an OpenWhisk Action](https://www.raymondcamden.com/2017/06/09/uploading-files-to-an-openwhisk-action) - Handling form uploads in actions
- [JSON Web Tokens and OpenWhisk](https://www.raymondcamden.com/2017/12/22/using-json-web-tokens-with-openwhisk) - Securing OpenWhisk actions with JWTs.
- [Deploying OpenWhisk on Kubernetes](https://medium.com/openwhisk/deploying-openwhisk-on-kubernetes-3f55f781fbab) - Starting OpenWhisk on Minikube.
- [Starting OpenWhisk in Sixty Seconds](https://medium.com/openwhisk/starting-openwhisk-in-sixty-seconds-9288bfb4863d) - Using Docker Compose to start OW locally.
- [Facebook Chat Bots with OpenWhisk](https://medium.com/openwhisk/facebook-chatbots-with-openwhisk-84eb2bf02d9b) - Creating chat bots on serverless platforms.
- [Getting Started with Serverless PHP](https://akrabat.com/getting-started-with-serverless-php/) - Introduction to PHP runtime on OpenWhisk.
- [OpenWhisk Alexa Skills](https://akrabat.com/creating-an-openwhisk-alexa-skill/) - Creating Alexa skills with Swift on OpenWhisk

## Sample Applications

*Sample open-source projects built using the OpenWhisk platform*

- [openwhisk-emoting](https://github.com/IBM-Cloud/openwhisk-emoting) - Capture audience feedback with a serverless app 😄 😡
- [alexa-skill-watson-conversaion](https://github.com/IBM/alexa-skill-watson-conversation) - Alexa Skill using OpenWhisk, IBM Watson Assistant and Weather Channel Data
- [keynuker](https://github.com/tleyden/keynuker) - nuke AWS keys accidentally leaked to Github
- [skylink](https://github.com/IBM-Bluemix/skylink) - Connect and control a DJI drone aircraft over the Internet with OpenWhisk.
- [BluePic](https://github.com/IBM-Swift/BluePic) - Photo sharing application for iOS using Swift Actions for the backend.
- [Conference Plan Bot](https://github.com/krook/owplan) - Conference planning bot built using serverless functions.
- [Project OpenFridge](https://github.com/krook/openfridge) - Improving customer service with IoT and event-driven computing.
- [Project OpenChecks](https://github.com/krook/openchecks) - Processes the deposit of checks to a bank account with object storage and OCR.
- [openwhisk-slackapp](https://github.com/IBM-Bluemix/openwhisk-slackapp) - Serverless Slack app built with Slack Events API and OpenWhisk.
- [openwhisk-visionapp](https://github.com/IBM-Bluemix/openwhisk-visionapp) - Image tagging and face detection iOS app built with OpenWhisk.
- [openwhisk-darkvision](https://github.com/IBM-Cloud/openwhisk-darkvisionapp) - Discover dark data in videos with IBM Watson and IBM Cloud Functions
- [openwhisk-jq](https://github.com/ibmets/openwhisk-jq) - OpenWhisk Action wrapping the JQ command-line utility for JSON filtering.
- [Personality Analysis](https://github.com/iwinoto/openwhisk-demo-personalityanalysis) - Analysing political speeches using IBM Watson.
- [smsbot](https://github.com/ibmets/smsbot) - SMS Bot for Slack using Twilio and OpenWhisk 
- [alexa-project-name-generator](https://github.com/lornajane/alexa-project-codename) - Alexa skill to generate a codename for your next project 

## Books

- [Developing Serverless Applications, A Practical Introduction with Apache OpenWhisk](https://www.oreilly.com/programming/free/developing-serverless-applications.csp) - free ebook

## Media

*Podcasts, videos, presentations and other content about Apache OpenWhisk.*

### Videos

- [Automating Actions](https://www.youtube.com/watch?v=4jRigiMpZF4) - Using Triggers with Actions.
- [OpenWhisk YouTube Channel](https://www.youtube.com/channel/UCbzgShnQk8F43NKsvEYA1SA/videos) - All OpenWhisk-related videos.
- [Building Slack Bots with OpenWhisk](https://www.youtube.com/playlist?list=PL0UyhC0D6KABYPvGroXcIeE-4x_yEbdB4) - Using OpenWhisk to build a Weather Slack Bot.
- [Project OpenFridge](https://www.youtube.com/watch?v=0Sl4rWZYo8w) - Improving customer service with IoT and event-driven computing.
- [Build a cloud native app with Apache OpenWhisk](https://developer.ibm.com/tv/build-a-cloud-native-app-with-apache-openwhisk/) - An overview of serverless architectures, introduction to the OpenWhisk programming model, and deployment of an OpenWhisk application on IBM Bluemix.
- [Getting Started With Apache OpenWhisk](https://www.youtube.com/watch?v=0kbFghAtvm0) - Learn how to create your first Serverless application with Apache OpenWhisk.
- [Working With OpenWhisk - Part 1](https://www.youtube.com/watch?v=RHzQf5eoAwc) - Getting started with OpenWhisk videos series.
- [Working with OpenWhisk - Part 2](https://www.youtube.com/watch?v=lujECfCPiGM) - Asynchronous Actions
- [Working With OpenWhisk - Part 3](https://www.youtube.com/watch?v=PFZDvvT7oX0) - Handling Errors

### Presentations

- [Event-driven and Serverless Computing with OpenWhisk](https://www.youtube.com/watch?v=rVGFll1sRY4) - Video from Serverless Conf London 2016 by Andreas Nauerz & Michael Behrendt
- [OpenWhisk Under the Hood](https://www.youtube.com/watch?v=S-fY1exdbao) - Video from Serverless Conf London 2016 by Stephen Fink
- [Lightning talk introducing serverless architectures and OpenWhisk](http://www.slideshare.net/DanielKrook/cloud-native-architectures-with-an-open-source-event-driven-serverless-platform) - IBM keynote at CloudNativeCon + KubeCon 2016. [Video](https://www.youtube.com/watch?v=C3PPmlUkarY) also available.
- [Tech Talk about OpenWhisk](https://developer.ibm.com/open/events/dw-open-tech-talk-openwhisk/) - Detailed look at this new open source platform from Stephen Fink.
- [The Future Of Cloud Programming](https://www.youtube.com/watch?v=sV7W-eK2x5U) - IBM Bluemix OpenWhisk Talk @ Codemotion 2016, Amsterdam
- [Serverless Applications with Cloud Foundry and OpenWhisk](https://www.youtube.com/watch?v=kydt6JgW6_8) - Video from Cloud Foundry Summit 2016.
- [Microservices Without Servers](http://jamesthom.as/blog/2016/09/08/microservices-without-servers/) - Slides, demo videos and sample code from conference talk on building serverless applications with OpenWhisk.
- [OpenWhisk - A platform for cloud native, serverless, event driven apps](http://www.slideshare.net/DanielKrook/openwhisk-a-platform-for-cloud-native-serverless-event-driven-apps) - Presentation from Cloud Native Day Toronto. [Video](https://www.youtube.com/watch?v=sYRiTZ47Cao) also available.
- [The Serverless Paradigm, OpenWhisk and FIWARE](http://www.slideshare.net/AlexGlikson/the-serverless-paradigm-openwhisk-and-fiware) - Presentation at the [FIWARE Summit](https://www.fiware.org/summit/) by Alex Glikson (video [here](https://www.youtube.com/watch?v=_JT63orNAsE)).
- [Serverless Swift with OpenWhisk](https://www.youtube.com/watch?v=VkpVJ3pNYEM&index=5&list=PL0UyhC0D6KAC05qdWzQC1vTSlVXzm9o9s&t=0s) - Using Swift on OpenWhisk to build APIs
- [Official OpenWhisk Slides](http://www.slideshare.net/OpenWhisk) - Presentation decks from OpenWhisk team.

### Podcasts

- [What Makes IBM OpenWhisk Different? Openness](http://thenewstack.io/exploring-pros-cons-serverless-computing-ibm-openwhisk/) - The New Stack podcast with Andreas Nauerz and Michael Behrendt.
- [The Cloudcast #252](http://www.thecloudcast.net/2016/05/the-cloudcast-252-understanding-ibm.html) - Interview with OpenWhisk team about the future of serverless computing.
- [InfoQ Interview](https://www.infoq.com/news/2016/04/bluemix-ibm-interconnect) - Q&A with Michael Behrendt on IBM's Event-driven Programming Service.
- [#vSurround: Are Serverless Architectures Ready for Primetime?](https://www.youtube.com/watch?v=_Q9Q4L3IdIY) - Roundtable discussion with Daniel Krook (IBM), Adam Johnson (IOpipe), David Wells (Serverless), and Ryan Scott Brown (Red Hat) about serverless definitions, use cases, and what's to come in 2017.
- [The FaaS and the Furious](https://gb.ivoox.com/en/ep-37-the-faas-and-the-furious-audios-mp3_rf_20040411_1.html) - Serverless Architecture with Apache OpenWhisk description

## Workshops

*Tutorials and other material to help you learn OpenWhisk*

- [Apache OpenWhisk Workshop](https://github.com/jthomas/openwhisk-workshops) - Complete bootcamp workshop on learning how to use OpenWhisk.
- [openwhisk-workshop](https://www.npmjs.com/package/openwhisk-workshop) - Command-line utility to introduce the concepts behind the platform using NodeSchool toolchain.

## Runtimes

*Links to samples, libraries and projects for running Actions using different languages*.

### Platform Runtimes

- [JavaScript](https://github.com/apache/incubator-openwhisk/blob/master/docs/actions-node.md) - OpenWhisk runtime for Node.js (v6 & v8).
- [Java](https://github.com/apache/incubator-openwhisk/blob/master/docs/actions-java.md) - OpenWhisk runtime for Java 8.
- [Python](https://github.com/apache/incubator-openwhisk/blob/master/docs/actions-python.md) - OpenWhisk runtime for Python 2.7 & 3
- [Swift](https://github.com/apache/incubator-openwhisk/blob/master/docs/actions-swift.md) - OpenWhisk runtime for Swift 3 & 4.
- [Docker](https://github.com/apache/incubator-openwhisk/blob/master/docs/actions-docker.md) - OpenWhisk runtime for Docker Actions using SDK.
- [PHP](https://github.com/apache/incubator-openwhisk/blob/master/docs/actions-php.md) - OpenWhisk runtime for PHP 7.2 and 7.1
- [Go](https://github.com/apache/incubator-openwhisk/blob/master/docs/actions-go.md) - OpenWhisk runtime for Go lang.
- [Ruby](https://github.com/apache/incubator-openwhisk/blob/master/docs/actions-ruby.md) - OpenWhisk runtime for Ruby lang.

### Community Examples

- [Scala](https://developer.ibm.com/openwhisk/2016/07/26/openwhisk-actions-scala/) - Example article with Github code for running OpenWhisk Actions in Scala.
- [Haskell](https://github.com/rainbyte/openwhisk-wrapper) - Haskell-based OpenWhisk services
- [Docker Examples](https://github.com/gekola/openwhisk_docker_samples) - Run Clojure, Erlang, Ruby and Rust Actions on OpenWhisk using Docker.
- [Rust](http://jamesthom.as/blog/2017/01/18/openwhisk-and-rust/) - Blog post and library for building Rust language Actions.
- [COBOL](https://github.com/morecobol/cobol.run) - Run serverless COBOL programs on OpenWhisk 
- [QBASIC](https://psuter.net/2018/07/15/serverless-qbasic) - QBASIC on OpenWhisk
- [Kotlin](https://github.com/ibm-functions/runtime-kotlin) - IBM Functions (OpenWhisk) runtime for Kotlin Actions 
- [Prolog](https://github.com/NaohiroTamura/openwhisk-runtime-prolog) - OpenWhisk Runtimes for SWI Prolog
- [Ballerina](https://github.com/imesh/openwhisk-runtime-ballerina) - Apache OpenWhisk runtime for Ballerina 
- [Blue Cloud Mirror](https://github.com/IBM/blue-cloud-mirror) -  Fun game built with Vue.js, TensorFlow and IBM technologies

## Feed Providers

*Examples of integrating OpenWhisk with external event sources.*

- [openwhisk-package-imap](https://github.com/tareqmamari/openwhisk-package-imap) - OpenWhisk Package to expose IMAP emails as a trigger feed.
- [openwhisk-package-template](https://github.com/openwhisk/openwhisk-package-template) - This is a template to be use when creating new packages for OpenWhisk.
- [openwhisk-package-iot](https://github.com/tareqmamari/openwhisk-package-iot) - Package including all actions and feeds of Watson IoT Platform.
- [openwhisk-mqtt-feed](https://github.com/jthomas/openwhisk_mqtt_feed) - MQTT package for OpenWhisk, provides a topic subscriber feed.
- [openwhisk-package-mqtt-watson](https://github.com/krook/openwhisk-package-mqtt-watson) - OpenWhisk MQTT Package for Watson IoT service.
- [amqp-wsk-feed](https://github.com/cliffjansen/amqp-wsk-feed) -  AMQP package for OpenWhisk 
- [jms-feed-provider](https://github.com/kameshsampath/jms-feed-provider) - JMS Feed Provider 
- [AWS OpenWhisk integration](https://github.com/projectodd/openwhisk-package-aws) - Package to integrate Amazon Web Services (AWS) with OpenWhisk 

## Utilities

*Tools and utilities to help you be more productive with OpenWhisk*

- [swagger-openwhisk](https://github.com/jeroiraz/swagger-openwhisk) - Generate a fully functional whisk package and actions from a swagger specification
- [openwhisk-webpack](https://github.com/IBM-Bluemix/openwhisk-webpack) - Demonstration of using Webpack to bundle OpenWhisk Actions.
- [openwhisk-es6-action](https://github.com/ddragosd/openwhisk-es6-action) - Sample project showing how to bundle ECMAScript6 actions including unit tests and code coverage.
- [hubot-ibmcloud-openwhisk](https://github.com/ibm-cloud-solutions/hubot-ibmcloud-openwhisk) - Hubot scripts for OpenWhisk.
- [node-red-node-openwhisk](https://www.npmjs.com/package/node-red-node-openwhisk) - Node-RED nodes for interacting with OpenWhisk platform.
- [openwhisk-vscode](https://github.com/openwhisk/openwhisk-vscode) - Plugin for Visual Studio Code to provide OpenWhisk commands.
- [openwhisk-apiapp](https://github.com/l2fprod/openwhisk-apiapp) - Proxies calls to OpenWhisk Actions using NGINX to enables CORS
- [openwhisk-canirequire](https://github.com/l2fprod/openwhisk-canirequire) - Find out which NPM modules can be used in OpenWhisk.
- [openwhisk-metrics](https://github.com/jthomas/openwhisk-metrics) - Node.js library to collect serverless application metrics from OpenWhisk actions 
- [Jupyter Notebooks integration](https://gist.github.com/parente/bd0b71f15ba0b97139e5) - Jupyter Notebooks as OpenWhisk Actions
- [logstash-input-openwhisk](https://github.com/jthomas/logstash-input-openwhisk) - Logstash plugin to drain OpenWhisk logs to Elastic Search.
- [wab (whisk activation browser)](https://github.com/psuter/wab) - A terminal-mode browser for inspecting OpenWhisk activations.

### Client Libraries

- [Node.js](https://github.com/openwhisk/openwhisk-client-js) - JavaScript client library for the OpenWhisk platform.

## Support

*Got stuck with Apache OpenWhisk? Find help here…*

- [GitHub Issues for OpenWhisk](https://github.com/openwhisk/openwhisk/issues).
- [Stack Overflow #openwhisk](http://stackoverflow.com/questions/tagged/openwhisk).
- [Slack Group #openwhisk](http://slack.openwhisk.org/).
- Twitter [@openwhisk](https://twitter.com/openwhisk)
