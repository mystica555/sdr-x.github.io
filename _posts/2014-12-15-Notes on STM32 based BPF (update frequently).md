---
date: 2014-11-02 12:00:00
layout: post
title: Notes on STM32 based BPF (update frequently)
thread: 2014121523
categories: STM32
tags:  STM32 BPF STM32F4DISCOVERY STM32F4-DISCOVERY
---

**0x00** All you need is a discovery board + a mini-usb cable to computer

**0x01** CN3 connected mode: computer -- USB cable -- onboard STLINK -- onboard STM MCU

**0x02** CN3 disconnected mode: computer --USB  cable -- onboard STLINK -- onboard CN2 -- offboard/other STM MCU

**0x03** CN3 disconnected mode is not for offboard USB-STLINK adapter programming discovery board via CN2! This mode turns discovery board to a BIG USB-STLINK adapter for you to develop your own or the third part STM MCU program!

