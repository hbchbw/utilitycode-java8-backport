# jimagehash-java8-backport

[![License](https://img.shields.io/github/license/hbchbw/utilitycode-java8-backport.svg)](LICENSE)
[![Maven Central](https://img.shields.io/maven-central/v/io.github.hbchbw/utilitycode-java8-backport.svg)](https://search.maven.org/search?q=g:io.github.hbchbw%20AND%20a:utilitycode-java8-backport)

> A Java 8 compatible backport of **UtilityCode**, a selection of java utility methods.

---

## 📌 Introduction
This project is a **Java 8 compatible backport** of the [UtilityCode](https://github.com/KilianB/UtilityCode) library.

- ✅ Runs on **JDK 1.8**
- ✅ Drop-in compatible where possible with the original UtilityCode API
- ✅ Removes or adapts Java 11+ specific APIs
- ⚠️ Some features requiring newer Java APIs have been modified or removed

**Original description:**
> Selection of java utility methods.

---

## 📦 Installation

If you publish to **Maven Central** under your own coordinates:

### Maven
```xml
<dependency>
    <groupId>io.github.hbchbw</groupId>
    <artifactId>utilitycode-java8-backport</artifactId>
    <version>1.0.0</version>
</dependency>