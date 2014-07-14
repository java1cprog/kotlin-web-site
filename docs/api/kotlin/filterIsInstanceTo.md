---
layout: api
title: filterIsInstanceTo
---
[stdlib](../index.html) / [kotlin](index.html) / [filterIsInstanceTo](filterIsInstanceTo.html)

# filterIsInstanceTo
Appends all elements that are instances of specified class to the given *destination*
```
public fun <T, C : C, R : R> Stream<T>.filterIsInstanceTo(destination: C, klass: Class<R>): C
public fun <T, C : C, R : R> Iterable<T>.filterIsInstanceTo(destination: C, klass: Class<R>): C
public fun <T, C : C, R : R> Array<T>.filterIsInstanceTo(destination: C, klass: Class<R>): C
```