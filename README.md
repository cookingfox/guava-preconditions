# Guava: Preconditions

Only the [Preconditions](src/main/java/com/google/common/base/Preconditions.java) class from
[Google Guava](https://github.com/google/guava) version 19.

## Download

[![Download](https://api.bintray.com/packages/cookingfox/maven/guava-preconditions/images/download.svg)](https://bintray.com/cookingfox/maven/guava-preconditions/_latestVersion)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.cookingfox/guava-preconditions/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.cookingfox/guava-preconditions)

The distribution is hosted on [Bintray](https://bintray.com/cookingfox/maven/guava-preconditions/view).
To include the package in your projects, you can add the jCenter repository.

### Gradle

Add jCenter to your `repositories` block (not necessary for Android - jCenter is the default
repository):

```groovy
repositories {
    jcenter()
}
```

and add the project to the `dependencies` block in your `build.gradle`:

```groovy
dependencies {
    compile 'com.cookingfox:guava-preconditions:0.1.4'
}
```

### Maven

Add jCenter to your repositories in `pom.xml` or `settings.xml`:

```xml
<repositories>
    <repository>
        <id>jcenter</id>
        <url>http://jcenter.bintray.com</url>
    </repository>
</repositories>
```

and add the project to the `dependencies` block in your `pom.xml`:

```xml
<dependency>
    <groupId>com.cookingfox</groupId>
    <artifactId>guava-preconditions</artifactId>
    <version>0.1.4</version>
</dependency>
```
