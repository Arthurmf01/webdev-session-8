---
title: Continuous integration
author: Pepe García
---

# Plan for today

##

- Continuous integration
- anything else

# What?

##

Continuous integration is the process of merging all contributor's
code in order to avoid integration problems.

## Benefits

Continuous integration gives us some **guarantees** when accepting new
code within our project.

# How?

## CI services

There are a lot different CI systems out there.  Some of the most
famous are:

- https://travis-ci.com
- https://jenkins.io
- https://circleci.com

## How?

What we normally do is make the CI system run tests whenever new code
wants to be merged.

## How?

<ul>
  <li><span class="fragment fade-in">create tests for your project</span></li>
  <li><span class="fragment fade-in">add CI integration in Github</span></li>
  <li><span class="fragment fade-in">You're done :)</span></li>
</ul>

## Example

Let's use [https://github.com/mcsbt-2019-web-and-mobile/ci-example-1](https://github.com/mcsbt-2019-web-and-mobile/ci-example-1) as
an example.

You can see the travis-ci build in here:
[https://travis-ci.com/mcsbt-2019-web-and-mobile/ci-example-1](https://travis-ci.com/mcsbt-2019-web-and-mobile/ci-example-1)

# Exercise

go to
[https://github.com/mcsbt-2019-web-and-mobile/ci-exercise-1](https://github.com/mcsbt-2019-web-and-mobile/ci-exercise-1). Fork
it and follow the instructions in the README :)


# Relation with Continuous deployment

##

Continuous deployment is a technique similar to continuous integration
that consists on deploying code several times a day, normally after
continuous integration passes.
