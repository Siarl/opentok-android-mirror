# opentok-android-mirror
Is a mirror for opentok-android-sdk packages. Used for private projects.

Currently contains the following versions:
- opentok-android-sdk-2.16.3
    - opentok-android-sdk-v3:3.1.3
- opentok-android-sdk-2.23.1

## Use

Add to your android/build.gradle:

```groovy
allprojects {
    repositories {
        /* other repos */
        maven { url 'https://github.com/Siarl/opentok-android-mirror/raw/main'}
    }
}
```

