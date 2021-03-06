# AndroidAnnotations plugin for Gradle

This plugin configures a [Gradle](http://gradle.org) project to add [AndroidAnnotations](http://androidannotations.org) to the build process.

## Installation

```
buildscript {
    repositories {
        mavenCentral()
    }

    def gradleAndroidAnnotationsPluginVersion = '0.3.0'

    dependencies {
        classpath "net.ealden.gradle.plugins:gradle-androidannotations-plugin:$gradleAndroidAnnotationsPluginVersion"
    }
}

apply plugin: 'androidannotations'
apply plugin: 'idea'

androidAnnotationsVersion = '2.2'
```

[![Built on DEV@cloud](http://web-static-cloudfront.s3.amazonaws.com/images/badges/BuiltOnDEV.png)](https://gradle-androidannotations-plugin.ci.cloudbees.com)

