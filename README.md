# Binance Java SDK

A clone of the (soon to be deprecated) Binance Java SDK, with some API updates and stale dependabot pull requests.
As this particular SDK is soon to be deprecated and replaced with [binance-futures-connector-java](https://github.com/binance/binance-futures-connector-java), it is uploaded for completion/archival purposes.


## Changes

- Updated topLongShortAccountRatio()
- Updated get24hrTickerPriceChange()
- Updated OpenInterest.java
- Stale dependabot pull requests
    - Updated fastjson to 2.0.24
    - Updated maven-javadoc-plugin to 3.5.0
    - Updated logback-classic to 1.4.5
    - Updated okhttp to 4.10.0
    - Updated maven-gpg-plugin to 3.0.1

### Maven configuration

Available on [Maven Central](http://search.maven.org/#search).

Install 1/2: Add this to pom.xml:

```xml
<dependency>
  <groupId>com.github.dermitza</groupId>
  <artifactId>binance-java-sdk</artifactId>
  <version>1.2.5</version>
</dependency>
```

Install 2/2: Run via command line

```xml
$ mvn install
```
*The SDK is compiled with Java8*

## Creators
[Yonathan Wolloch](https://github.com/yonathan95)

[Uri Bek](https://github.com/urib94)

[Omri Attal](https://github.com/omriattal)
