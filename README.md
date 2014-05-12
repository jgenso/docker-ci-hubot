docker-ci-hubot
===============

Runs Hubot for continuous integration using Jenkins as CI server, all inside a docker container.


#### Supported Environment Variables

* HUBOT_JENKINS_AUTH -- jenkins authentication in the form of ```username:password```
* HUBOT_JENKINS_URL -- URL to jenkins
* HUBOT_HIPCHAT_JID -- JID for the hipchat user
* HUBOT_HIPCHAT_PASSWORD -- password for the hpichat user
* HUBOT_HIPCHAT_ROOMS -- set the room(s) to join.  Uses the JID of the room, ie. xxx@conf.hipchat.com



