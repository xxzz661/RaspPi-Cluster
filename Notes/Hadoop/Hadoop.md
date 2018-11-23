# Hadoop

## Overview

## Hadoop Streaming

Hadoop provides a streaming API which supports any programming language that can read from the standard input *stdin* and write to the standard output *stdout*. The Hadoop streaming API uses standard Linux streams as the interface between Hadoop and the program.  Thus, input data is passed via the *stdin* to a map function, which processes it line by line and writes to the *stdout*.  Input to the reduce function is *stdin* (which is guaranteed to be sorted by key by Hadoop) and the results are output to *stdout*.

* Hadoop provides an API to MapReduce that allows you to write your map and reduce functions in languages other than Java!
* Hadoop Streaming use Unix standard streams as the interface between Hadoop and your program, so you can use any language that can read standard input and write to standard output to write your MapReduce program.

## Book

Hadoop - The Definitive Guide

## Links

### Getting Started

macOS installation guide

* [How to install Hadoop|Spark on macOS High Sierra](http://hanslen.me/2018/01/19/How-to-install-Hadoop-on-macOS-High-Sierra/)
* [Slide - Install Apache Hadoop on Mac OS Sierra](https://www.slideshare.net/SunilkumarMohanty3/install-apache-hadoop-on-mac-os-sierra-76275019)

### Sandbox

* [Hortonworks Sandbox](https://hortonworks.com/products/sandbox/) - The Sandbox is a straightforward, pre-configured, learning environment that contains the latest developments from Apache Hadoop, specifically the Hortonworks Data Platform (HDP).
    * [Sandbox Deployment and Install Guide](https://hortonworks.com/tutorial/sandbox-deployment-and-install-guide/)