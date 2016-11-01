# LoganSquareProGuardRules
ProGuard rules for LoganSquare shipped as an AAR!

[![Build Status](https://travis-ci.org/Commit451/LoganSquareProGuardRules.svg?branch=master)](https://travis-ci.org/Commit451/LoganSquareProGuardRules) [![](https://jitpack.io/v/Commit451/LoganSquareProGuardRules.svg)](https://jitpack.io/#Commit451/LoganSquareProGuardRules)

# Gradle Dependency

Add this in your root `build.gradle` file (**not** your module `build.gradle` file):

```gradle
allprojects {
	repositories {
		...
		maven { url "https://jitpack.io" }
	}
}
```

Then, add the library to your project `build.gradle`
```gradle
dependencies {
    compile 'com.github.Commit451:LoganSquareProGuardRules:1.3.6.0'
}
```

# Source
BlueLine Labs kindly provides the appropriate ProGuard rules on the [LoganSquare site](https://github.com/bluelinelabs/LoganSquare#proguard)

# Thanks
Thanks to BlueLine Labs for the awesomeness that is LoganSquare, and to [Artem](https://github.com/artem-zinnatullin) for the idea of making this a library


License
--------

    Copyright 2016 Commit 451
    Copyright 2015 BlueLine Labs, Inc.

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
