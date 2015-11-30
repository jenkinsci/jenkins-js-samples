# jenkins-js Sample Plugins

This repository provides some sample Jenkins Plugins, showing how to use [jenkins-js-builder] to build
Jenkins plugins that support a richer UI through the use of Modularized JavaScript.

The repository contains step-by-step example plugins, starting with <a href="../../tree/master/step-01-basic">step-01-basic</a>,
which is just a simple Jenkins plugin that contains no JavaScript at all, working up through steps 02 and 03 etc,
incrementally adding more JavaScript "features". 

## Step-by-step Plugins

1. <b><a href="../../tree/master/step-01-basic">step-01-basic</a></b>: A very basic Jenkins plugin with no JavaScript.
1. <b><a href="../../tree/master/step-02-nodeify">step-02-nodeify</a></b>: Update <a href="../../tree/master/step-01-basic">step-01-basic</a> to add a very simple jQuery based JavaScript App bundle (jQuery bundled).
1. <b><a href="../../tree/master/step-03-more-npm-packs">step-03-more-npm-packs</a></b>: Update <a href="../../tree/master/step-02-nodeify">step-02-nodeify</a> to use Twitter Bootstrap instead of jQuery and to also use Moment.js (Bootstrap and Moment.js bundled).
1. <b><a href="../../tree/master/step-04-externalize-libs">step-04-externalize-libs</a></b>: Update <a href="../../tree/master/step-03-more-npm-packs">step-03-more-npm-packs</a> to slim down the the App bundle by externalizing Bootstrap and Moment.js (Bootstrap and Moment.js NOT bundled).
1. <b><a href="../../tree/master/step-05-namespaced-css">step-05-namespaced-css</a></b>: Update <a href="../../tree/master/step-04-externalize-libs">step-04-externalize-libs</a> to use the default namespaced CSS.

[jenkins-js-modules]: https://github.com/jenkinsci/js-modules
[jenkins-js-builder]: https://github.com/jenkinsci/js-builder
[jenkins-js-libs]: https://github.com/jenkinsci/js-libs
[jenkins-js-test]: https://github.com/jenkinsci/js-test
