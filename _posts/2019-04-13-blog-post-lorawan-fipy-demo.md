---
title: 'LoRaWAN Demo'
date: 2019-04-13
permalink: /posts/2019/04/blog-post-lorawan-fipy-demo/
tags:
  - LoRaWAN
  - Demo
---

This is a sample blog post. Lorem ipsum I can't remember the rest of lorem ipsum and don't have an internet connection right now. Testing testing testing this blog post. Blog posts are cool.

A LoRaWAN-based Internet of Things (IoT) demo is created at the Advanced Networks Research Group (ANRG), University of Liverpool.

## Overview
A light sensing and control IoT system is created as a case study. The LoRa end device is consisted of FiPy (with LoRa function) and Pysense (expansion board) with light sensors. A LoRa end device A will sense the light and transmit it to the application server. When the luminous intensity is smaller than a threshold, it will send a control signal to the LoRa end device B and turn its LED to green, emulating a control signal to a switch.

## Key Features
* Regular uplink transmission
* Manual downlink transmission (confirmed or unconfirmed)
* Automatic downlink transmission (determined by the threshold)

## Setup
* Hardware
  * End device: FiPy + Pysense
  * Gateway: Raspberry Pi + RAK831, an instruction can be found at https://www.thethingsnetwork.org/docs/gateways/rak831/
* Software
  * TTN to host the gateway and applications
  * Python SDK
  * Micropython for the FiPy
  
<br />
<img align="center" width="1000" src="{{ site.url }}/images/lorawan/LoRaWAN-setup.jpg" alt="...">
<br />

## Graphical User Interface
<br />
<img align="center" width="1000" src="{{ site.url }}/images/lorawan/gui_lorawan.png" alt="...">
<br />
 