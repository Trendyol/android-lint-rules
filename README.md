
Lint Rules for Android.
==========

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Android Lint Rules includes several rules for Android platform.

# Contents: #
* Background Vector : Detect vectors used for background
* Hardcoded Value : Detect hardcoded values used for dimension

# Installation
 - To implement **Android Lint Rules** to your Android project via Gradle, you need to add JitPack repository to your root build.gradle.
```gradle
allprojects {
    repositories {
        ...
        maven { url 'https://jitpack.io' }
    }
}
```
 - After adding JitPack repository, you can add **Android Lint Rules** dependency to your app level build.gradle.
```gradle
dependencies {
    implementation 'com.github.Trendyol:android-lint-rules:1.0.1"
}
```

# TODO

#### Custom Lints
- [ ] Vector drawables for TextView Drawable attributes as an Error
- [ ] Use custom LifecyclerOwner with LiveData as a Warning
- [ ] Encapsulate the LiveData which is store data on ViewModels as a Warning 
- [ ] Hardcoded colors for support theme as an Error
- [ ] Resource names (https://github.com/Trendyol/android-guidelines/) as a Warning 
- [ ] Prefix check for multi module projects as an Error

#### IDE Default Lints
- [ ] Spesift return type explicitly as a Warning
- [ ] Line length as a Warning
- [ ] Limit lines of method as a Warning
- [ ] Method names length as a Warning

License
--------
    Copyright 2019 Trendyol.com

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
