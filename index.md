---
layout: default
title: Bond's Development Site
---

# Updates

## September 2019

Completed the development of my ESP32-Cam application. This is firmware for those ESP32-Cam modules you can get from China.

I contributed a patch to control the flash LED on some modules and it was accepted by Espressif for inclusion in their face recognition demo (ESP-WHO)

## October 2019

I'm upgrading my C++ skills. Part of this effort involves converting my MQTT client server library from Object Pascal to C++

## November 2019

Currently working on developing my C++ MQTT library on my private GOGS servere [https://git.bondkeevil.ca](https://git.bondkeevil.ca)

This project uses the TCP library that I am developing on GitHub.

## December 2019 

I've got the TCP library done and the MQTT library client is running but still too buggy for release. Since this project is more for my own educational purposes I've been slowed down by some experiments in Gitlab and CI/CD. I have ordered an off lease Dell PowerEdge 710 with 4x2TB SAS storage and 24 GB of RAM to further develop these skills. I think I will install XCP-ng (a fork of Xen Server) and partition the hardware into multiple virtual servers. One of those servers will be a Gitlab server and I will run Docker images to test software locally. I have decided to suspend development on the MQTT stuff until I can get my CI/CD system up and running.

# Repository List

## C++ Projects

[https://github.com/bkeevil/tcp](A TCP client/server library for Linux that supports SSL. The library uses the EPoll mechanism to respond to OS events in a single thread.)
