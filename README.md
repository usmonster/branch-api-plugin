# Jenkins Branch API Plugin

This plugin provides an API for multiple branch based projects. See also this [plugin's wiki page][wiki]

For generic information about how to use the Branch API plugin, please see [the user guide](docs/user.adoc)

If you are writing a plugin that implements this API, please see [the implementation guide](docs/implementation.adoc)
 
# Environment

The following build environment is required to build this plugin

* `java-1.7` and `maven-3.3.9`

# Build

To build the plugin locally:

    mvn clean verify

# Release

To release the plugin:

    mvn release:prepare release:perform -B

# Test local instance

To test in a local Jenkins instance

    mvn hpi:run

  [wiki]: http://wiki.jenkins-ci.org/display/JENKINS/Branch+API+Plugin
