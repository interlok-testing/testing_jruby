# JRuby Testing


[![GitHub tag](https://img.shields.io/github/tag/interlok-testing/testing_jruby.svg)](https://github.com/interlok-testing/testing_jruby/tags)
[![license](https://img.shields.io/github/license/interlok-testing/testing_jruby.svg)](https://github.com/interlok-testing/testing_jruby/blob/develop/LICENSE)
[![Actions Status](https://github.com/interlok-testing/testing_jruby/actions/workflows/gradle-publish.yml/badge.svg)](https://github.com/interlok-testing/testing_jruby/actions)

## What it does

This project demonstrates with a working example of the JRuby optional component. It
consists of a single channel and workflow that triggers when a GET request is sent to
http://localhost:8081/jruby1. 

The <jruby-scripting-service> is used to call a Ruby script when handling a message
(myjsonpath.rb) and on different lifecycle events (lifecycle.rb)

## Getting started

The config is using a variables.properties to configure:
```
workingDir=(Absolute path of the working directory)
jrubyHome=(Absolute path of the jruby installation)
```