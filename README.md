# Kotlin Kit
Kotlin for android essentials

#Setup

**First of all add a jitpack repository in your project's build.gradle**
```
repositories {
    maven { url "https://jitpack.io" }
}
```    

**There are couple modules available:**

Core methods only, no other 3rd party libraries included
```
dependencies {
    compile 'com.github.Schibsted-Tech-Polska.kotlin-kit:core:1.0.19'
}
```

[JodaTime](http://www.joda.org/joda-time/) extension
```
dependencies {
    compile 'com.github.Schibsted-Tech-Polska.kotlin-kit:jodatime:1.0.19'
}
```
