---
nav-title: "Overview"
title: "Metadata Overview"
description: "NativeScript Android Runtime Metadata Overview"
position: 0
---

# The Big Picture
TODO: Add picture here - e.g. from Sebastian's presentation

# What is Metadata
At its shortest, metadata is the mapping between the JavaScript and the Java/Android worlds. Besides a full list with all the available classes and methods, the metadata contains the [JNI](http://developer.android.com/training/articles/perf-jni.html) signature for each accessible method/field. It is pre-generated, in a binary format, and embedded in the application package (apk), storing the minimal required information thus providing small size and highly efficient read access. The generation process uses the Java's [Reflection Mechanism](http://en.wikipedia.org/wiki/Reflection_(computer_programming)) to iterate through all the publicly available types.

#See Also
* [Accessing APIs](./accessing-packages.md)
* [Generating Metadata](./generator.md)
