android-tank
============
[![Build Status](https://travis-ci.org/panzerfahrer/android-tank.svg?branch=master)](https://travis-ci.org/panzerfahrer/android-tank) [![Release](https://img.shields.io/github/tag/panzerfahrer/android-tank.svg?label=maven)](https://jitpack.io/#panzerfahrer/android-tank/v1.0.1)


A collection of Android related implementations that I find valuable.


And here comes a tank:

```
      ___
     |"""\--=
     (____)
  
```


Contents
=========

* [Content](library/src/main/java/de/slowpoke/androidtank/content)
 - [Crypto](library/src/main/java/de/slowpoke/androidtank/content/Crypto.java): Collection of cryptography en-/decryption utilities
 - [Persistable](library/src/main/java/de/slowpoke/androidtank/content/Persistable.java): De-/Serialization using the `Parcelable` way
* [Graphics](library/src/main/java/de/slowpoke/androidtank/graphics)
 - [PathParcelable](library/src/main/java/de/slowpoke/androidtank/graphics/PathParcelable.java): a `android.graphics.Path` that implements `Parcelable`
* [Drawable](library/src/main/java/de/slowpoke/androidtank/graphics/drawable)
 - [CircleCutOutColorDrawable](library/src/main/java/de/slowpoke/androidtank/graphics/drawable/CircleCutOutColorDrawable.java): a `Drawable` that draws a color and leaves out a definable circle
 - [ColorTintDrawable](library/src/main/java/de/slowpoke/androidtank/graphics/drawable/ColorTintDrawable.java): a `Drawable` that applies a color tint to another drawable
 - [RotatedDrawable](library/src/main/java/de/slowpoke/androidtank/graphics/drawable/RotatedDrawable.java): a `Drawable` that can be programmatically rotated
  

Usage
======

    repositories {
        maven { url "https://jitpack.io" }
    }
    
    dependencies {
        compile 'com.github.panzerfahrer:android-tank:v1.0.1'
    }

License
=======

```
  Copyright 2015 Brian Hoffmann, slowpoke.de

  Licensed under the Apache License, Version 2.0 (the "License");
  you may not use this file except in compliance with the License.
  You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0
 
  Unless required by applicable law or agreed to in writing, software
  distributed under the License is distributed on an "AS IS" BASIS,
  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
  See the License for the specific language governing permissions and
  limitations under the License.
```
