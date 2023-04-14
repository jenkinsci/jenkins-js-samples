# ❗ This repository is unmaintained and end of life!
<h2>
    The samples do no longer comply with the standards and requirements in Jenkins. <br>
    If you are looking for up-to-date samples and documentation how to use JS in plugins, please consult the <a href="https://jenkins.io">Jenkins documentation</a>.
</h2>

# jenkins-js Sample Plugins

This repository provides some sample Jenkins Plugins, showing how to use [jenkins-js-builder] to build
Jenkins plugins that support a richer UI through the use of Modularized JavaScript.


## Step-by-step Plugins

The repository contains step-by-step example plugins, starting with <a href="../../tree/master/step-01-basic">step-01-basic</a>,
which is just a simple Jenkins plugin that contains no JavaScript at all, working up through steps 02 and 03 etc,
incrementally adding more JavaScript "features". 

| Name | Description |
| :-----| :------------|
| <b><a href="../../tree/master/step-01-basic">step-01-basic</a></b> | A very basic Jenkins plugin with no JavaScript.
| <b><a href="../../tree/master/step-02-nodeify">step-02-nodeify</a></b> | Update <a href="../../tree/master/step-01-basic">step-01-basic</a> to add a very simple jQuery based JavaScript App bundle (jQuery bundled).|
| <b><a href="../../tree/master/step-03-more-npm-packs">step-03-more-npm-packs</a></b> | Update <a href="../../tree/master/step-02-nodeify">step-02-nodeify</a> to use Twitter Bootstrap instead of jQuery and to also use Moment.js (Bootstrap and Moment.js bundled). |
| <b><a href="../../tree/master/step-04-externalize-libs">step-04-externalize-libs</a></b> | Update <a href="../../tree/master/step-03-more-npm-packs">step-03-more-npm-packs</a> to slim down the the App bundle by externalizing Bootstrap and Moment.js (Bootstrap and Moment.js NOT bundled). |
| <b><a href="../../tree/master/step-05-namespaced-css">step-05-namespaced-css</a></b> | Update <a href="../../tree/master/step-04-externalize-libs">step-04-externalize-libs</a> to use bootstrap's default namespaced CSS. |
| <b><a href="../../tree/master/step-06-handlebars-templates">step-06-handlebars-templates</a></b> | Update <a href="../../tree/master/step-04-externalize-libs">step-04-externalize-libs</a> to use Handlebars Templates. |
| <b><a href="../../tree/master/step-07-jsdom-tests">step-07-jsdom-tests</a></b> | How to add unit tests using [jsdom] and [Jasmine]. |
| <b><a href="../../tree/master/step-08-zombie-tests">step-08-zombie-tests</a></b> | How to add integration tests using [Zombie] and [Jasmine]. |

[jenkins-js-modules]: https://github.com/jenkinsci/js-modules
[jenkins-js-builder]: https://github.com/jenkinsci/js-builder
[jenkins-js-libs]: https://github.com/jenkinsci/js-libs
[jenkins-js-test]: https://github.com/jenkinsci/js-test
[Jasmine]: http://jasmine.github.io/
[jsdom]: https://github.com/tmpvar/jsdom
[Zombie]: http://zombie.js.org/
