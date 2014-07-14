---
layout: api
title: throws
---
[stdlib](../../index.html) / [kotlin](../index.html) / [throws](index.html)

# throws
This annotation indicates what exceptions should be declared by a function when compiled to a JVM method
```
public class throws
```
## Description
```
public class throws
```
Example:
throws(javaClass<IOException>())
fun readFile(name: String): String {...}
will be translated to
String readFile(String name) throws IOException {...}

## Members
| Name | Summary |
|------|---------|
|[*.init*](_init_.html)|This annotation indicates what exceptions should be declared by a function when compiled to a JVM method<br>&nbsp;&nbsp;`public throws(exceptionClasses: Array<Class<Throwable>>)`<br>|
|[exceptionClasses](exceptionClasses.html)|&nbsp;&nbsp;`val exceptionClasses: Array<Class<Throwable>>`<br>|