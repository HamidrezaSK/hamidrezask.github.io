---
title: "Deduplication for Secondary Storage"
date: 2022-09-04
layout: post
---
Extended Bareos’s base backup process to support VDO module Deduplication, interfacing with VMware hypervisor.

The primary objective of this project was to establish a system for testing the backup speed of virtual machine data using Bareos over Fiber Channel. Additionally, the project aimed to enhance Bareos by integrating the deduplication process as a plugin, leveraging the VDO module in conjunction with Bareos's existing deduplication support.

![](/images/Bareos-setup.png)