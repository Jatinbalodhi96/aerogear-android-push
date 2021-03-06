# AeroGear Android Push [![Build Status](https://travis-ci.org/aerogear/aerogear-android-push.png)](https://travis-ci.org/aerogear/aerogear-android-push)

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.jboss.aerogear/aerogear-android-push/badge.svg?style=flat-square)](https://maven-badges.herokuapp.com/maven-central/org.jboss.aerogear/aerogear-android-push/)
[![Javadocs](http://www.javadoc.io/badge/org.jboss.aerogear/aerogear-android-push.svg?color=blue)](http://www.javadoc.io/doc/org.jboss.aerogear/aerogear-android-push)


AeroGear's Android libraries were built as jar and aar packages using [Maven](http://maven.apache.org/) and the [android-maven-plugin](https://github.com/jayway/maven-android-plugin). The project follows the standard Maven layout so it can be imported directly into most IDEs as a Maven project.

## Push

AeroGear for Android provides support for integrating with push. Currently only using Google’s Cloud Messaging (GCM) with the [AeroGear UnifiedPush Server](https://github.com/aerogear/aerogear-unifiedpush-server) is supported, but we are planning to add support for Mozilla’s Simple Push, MQTT, and standalone GCM soon.

|                 | Project Info  |
| --------------- | ------------- |
| License:        | Apache License, Version 2.0  |
| Build:          | Maven  |
| Documentation:  | http://aerogear.org/docs/guides/aerogear-android/  |
| Issue tracker:  | https://issues.jboss.org/browse/AGDROID  |
| Mailing lists:  | [aerogear-users](http://aerogear-users.1116366.n5.nabble.com/) ([subscribe](https://lists.jboss.org/mailman/listinfo/aerogear-users))  |
|                 | [aerogear-dev](http://aerogear-dev.1069024.n5.nabble.com/) ([subscribe](https://lists.jboss.org/mailman/listinfo/aerogear-dev))  |

## Building

Please take a look at the [step by step guide](http://aerogear.org/docs/guides/aerogear-android/how-to-build-aerogear-android/) on our website.

*The following dependencies are required to build this project:*

* [aerogear-android-core](http://github.com/aerogear/aerogear-android-core) 
* [aerogear-android-pipe](http://github.com/aerogear/aerogear-android-pipe) 

## Usage

There are two supported ways of developing apps using AeroGear for Android: Android Studio and Maven.

### Android Studio

Add to your application's `build.gradle` file

```
dependencies {
    compile 'com.google.android.gms:play-services:+'
    compile 'org.jboss.aerogear:aerogear-android-push:2.2.1'
}
```

### Maven

Include the following dependencies in your project's `pom.xml`

```
<dependency>
  <groupId>org.jboss.aerogear</groupId>
  <artifactId>aerogear-android-push</artifactId>
  <version>2.2.1</version>
  <scope>provided</scope>
  <type>jar</type>
</dependency>

<dependency>
  <groupId>org.jboss.aerogear</groupId>
  <artifactId>aerogear-android-push</artifactId>
  <version>2.2.1</version>
  <type>aar</type>
</dependency>
```

## Documentation

For more details about the current release, please consult [our documentation](http://aerogear.org/docs/guides/aerogear-android/).

## Demo apps

Take a look in our demo apps

* [AeroGear Push HelloWorld](https://github.com/jboss-mobile/unified-push-helloworld/tree/master/android)
* [AeroGear Push Quickstarts](https://github.com/jboss-mobile/unified-push-quickstarts/tree/master/client/contacts-mobile-android-client)

## Development

If you would like to help develop AeroGear you can join our [developer's mailing list](https://lists.jboss.org/mailman/listinfo/aerogear-dev), join #aerogear on Freenode, or shout at us on Twitter @aerogears.

Also takes some time and skim the [contributor guide](http://aerogear.org/docs/guides/Contributing/)

## Questions?

Join our [user mailing list](https://lists.jboss.org/mailman/listinfo/aerogear-users) for any questions or help! We really hope you enjoy app development with AeroGear!

## Found a bug?

If you found a bug please create a ticket for us on [Jira](https://issues.jboss.org/browse/AGDROID) with some steps to reproduce it.

