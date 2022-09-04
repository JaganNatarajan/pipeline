---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# Purpose of this documentation
{: .no_toc }

The purpose of this documentation is to install, configure and build a Z DevOps pipeline. The tools that would installed / configured are

<details open markdown="block">
  {: .text-delta }
- TOC
{:toc}
</details>

## Rocket Git for z/OS

Rocket Software's port of GIT SCM for z/OS. One key step in the enterprise DevOps solution for z/OS is to migrate the source control from the legacy source control tools to the latest ones. One option would be to align the mainframe with the enterprise wide source control tools. The most popular one in this space is GIT.

Rocket's GIT for z/OS runs on the Unix System Services (USS) on the z/OS

## IBM Dependency Based Build (DBB)

Traditionally, mainframe source control tools also were also used as the build & deploy tools. This severly restricted the number of test environments that were available for testing. With agile and parallel developments, the need for test environments increased - calling for a standalone build and deploy processes.

IBM Dependency Based Build (DBB), is a build module for mainframe application that runs on the USS on z/OS and comes with a groovy based build framework - zAppBuild

## Jenkins

The most popular Continous Integration (CI) orchestrator on the distributed environments is used to orchestrate the pipeline for the mainframes.

There are two components to Jenkins - the server, that runs on a Linux hardware and talks to an agent on USS

## IBM Developer for Z (IDZ)

Developers are moving from mainframe ISPF screens to modern IDEs for development. One of the modern IDE for the mainframe is the IBM Developer for Z (IDZ).

## Buildframe work - zAppBuild

## Rational License Key Manager

## Urban Code Deploy (UCD)

Urban Code Deploy (UCD) is one of the most popular deploy tools in the market. UCD is used to deploy mainframe components on z/OS

---
```
Document v1.0 
3 Sep 2022 
``` 