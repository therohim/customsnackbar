SbackBar - A Beautiful Snackbar Library for Android Kotlin
========================

## Introduction
This library is build on top of Snackbar 

Usage
-----

This library allows you to use :
```kotlin
//Success Snackbar
SnackBar.success(findViewById(android.R.id.content), "Successfully SnackBar :)", SnackBar.LENGTH_LONG).show()

//Info Snackbar
SnackBar.info(findViewById(android.R.id.content), "Info SnackBar :)", SnackBar.LENGTH_LONG).show()

//Warning Snackbar
SnackBar.warning(findViewById(android.R.id.content), "Warning SnackBar :)", SnackBar.LENGTH_LONG).show()

//Error Snackbar
SnackBar.error(findViewById(android.R.id.content), "Error SnackBar :)", SnackBar.LENGTH_LONG).show()
```

## Setup

Currently available via [JitPack][1].

To use it, add the jitpack maven repository to your `build.gradle` file:
```gradle
repositories {
  ...
  maven { url 'https://jitpack.io' }
  ...
}
```
and add the dependency:
```gradle
dependencies {
  ...
  implementation 'com.github.gaddarkumar7447:CustomSnackBar:1.0.0'
  ...
}
```