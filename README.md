# btcreate3

[![CircleCI](https://circleci.com/gh/pantheon-systems/example-drops-8-composer.svg?style=svg)](https://circleci.com/gh/pantheon-ci-bot/btcreate3) [![Pantheon btcreate3](https://img.shields.io/badge/pantheon-btcreate3-yellow.svg)](https://dashboard.pantheon.io/sites/abc9236b-b35f-4042-bf83-dfba94f9ada1#dev/code) [![Dev Site btcreate3](https://img.shields.io/badge/site-btcreate3-blue.svg)](http://dev-btcreate3.pantheonsite.io/)

## IMPORTANT NOTE

At the time of creation, the Pantheon site being used for testing did not have multidev capability. The test suites were therefore configured to run all tests against the dev environment. If the test site is later given multidev capabilities, you must [visit the CircleCI environment variable configuration page](https://circleci.com/gh/pantheon-ci-bot/btcreate3) and delete the environment variable `TERMINUS_ENV`. If you do this, then the test suite will create a new multidev environment for every pull request that is tested.