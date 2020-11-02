---
title: "Java Throwable"
date: 2020-10-22T10:50:17+08:00
draft: false
tags: ["notes", "technology", "programming", "java", "github", "basic"]
categories: ["Notes"]
authors:
- "pseudoyu"
---

# Java Basics

## Throwable

![java_throwable](https://raw.githubusercontent.com/pseudoyu/image_hosting/master/hugo_images/java_throwable.svg)

### Error
(JVM can't handle with)
- VirtualMachineError
	- StackOverFlowError
	- OutOfMemoryError
- AWTError

### Exception
(Can be deal with by program)
- IOException
	- EOFException
	- FileNotFoundException
- RuntimeException
	- ArrithmeticException
	- MissingResourceException
	- ClassNotFoundException
	- NullPointerException
	- IllegalArgumentException
	- ArrayIndexOutOfBoundsException
	- UnknownTypeException

### Basic syntax
- try-catch
- throw
- throws
- finally