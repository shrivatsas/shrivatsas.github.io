---
layout: post
title:  "Test Doubles"
date:   2021-07-31 11:34:32 +0530
categories: Software Testing
---

A test double is a generic (meta) term used for objects or procedures that look and behave like their release-intended counterparts, but are actually simplified versions that reduce the complexity and facilitate testing. [Wikipedia](https://en.wikipedia.org/wiki/Test_double)

System under test (SUT) 

We replace a component on which the SUT depends with a "test-specific equivalent."

Type of test doubles,

Dummy
A Dummy is the simplest type of test double. They get passed in to fulfill a parameter requirement.

Stub
A stub is an object that provides (canned) hardcoded values to method calls. It always returns the same output regardless of the input.

Spy
A spy allows us to verify what functions were called, with what arguments, when, and how often.

Fake
A Fake is an object that has a concrete implementation that works similar to the actual implementation. It is a simplified version of production code.

Mock
The behaviour of the mocked interface can be changed dynamically based on scenarios. Also allows to verify calls, arguments, when and how often.
