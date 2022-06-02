# SqrLibrary

[![](https://jitpack.io/v/VadimSquorpikkor/sqrlibrary.svg)](https://jitpack.io/#VadimSquorpikkor/sqrlibrary)

Добавить в settinds.gradle "maven { url 'https://www.jitpack.io' }":
```
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        maven { url 'https://www.jitpack.io' }
    }
}
rootProject.name = "Jessica2"
include ':app'
```

Добавить в build.gradle:
```
dependencies {
    ...
    implementation 'com.github.VadimSquorpikkor:sqrlibrary:1.0.2'
}
```

## SaveLoad
Нестатический вариант. Ничего добавлять не надо. Нужно инициализировать.

## SaveLoadR
Экспериментальный вариант. С рефлексией. Ничего добавлять не надо

