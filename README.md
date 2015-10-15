# Gradle Utils

[![Build Status](https://travis-ci.org/boazj/gradle-utils.svg?branch=master)](https://travis-ci.org/boazj/gradle-utils)
[![Coverage Status](https://coveralls.io/repos/boazj/gradle-utils/badge.svg?branch=master&service=github)](https://coveralls.io/github/boazj/gradle-utils?branch=master)

Provides various utility methods and capabilities applicable both in Gradle scripts and plugins.

## Usage


To build the project execute the following command from the clone directory
```shell
./gradlew clean build install
```

To apply the plugin in your build add the following to the build script
```gradle

buildscript {
	repositories {
		jcenter()
	}
	dependencies {
		classpath 'com.boazj.gradle:gradle-utils:0.1.0'
	}
}
```