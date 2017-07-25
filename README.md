## OpenWeatherMap-Java-Library

**You need an APPID to use the OpenWeatherMap API. Head on over to their [website](http://openweathermap.org/) if you don't already have one.**


## Setting up

#### Step 1. Add the JitPack repository to your root ```build.gradle```.

``` java
allprojects {
  repositories {
    ...
    maven { url 'https://jitpack.io' }
  }
}
```

#### Step 2 : Download via ```Gradle```:

``` compile 'com.github.KwabenBerko:OpenWeatherMap-Android-Library:v1.0.0'```

**Note: Remember to include the INTERNET permission to your manifest file**

## Features

### Current Weather
#### Get current weather by:

1.City Name

2.City ID

3.Geographic Coordinates

4.Zip Code
