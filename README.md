# Android Dimens

[![](https://jitpack.io/v/ali-sardari/dimens.svg)](https://jitpack.io/#ali-sardari/dimens)

Step 1. Add the JitPack repository to your build file. Add it in your root build.gradle at the end of repositories:

```groovy
allprojects {
        repositories {
            ...
            maven { url "https://jitpack.io" }
        }
    }
```

Step 2. Add the dependency
```groovy
dependencies {
    implementation 'com.github.ali-sardari:dimens:2.0.0'
}
```

### Usage

```xml
<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:padding="@dimen/_10sdp"
    android:text="Hello World!"
    android:textSize="@dimen/_20ssp" />
```