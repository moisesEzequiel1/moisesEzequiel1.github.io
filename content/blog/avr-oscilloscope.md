---
title: "AVR Oscilloscope"
date: 2025-10-20
description: "Functional oscilloscope built with an ATmega328p microcontroller."
tags: ["AVR", "oscilloscope", "embedded", "electronics"]
categories: ["Projects"]
draft: false
---

A functional **oscilloscope** built from scratch using an **ATmega328p** (Arduino Uno).  
This project demonstrates **signal acquisition**, **ADC sampling**, and **data visualization** via serial plotting on PC.

<!--more-->

## Overview

This project reads analog signals using the 10-bit ADC from the AVR microcontroller and sends sampled data via UART for visualization.  
The display software on the PC reconstructs the waveform in real time.

### Key features
- Up to 5 kHz sample rate  
- Adjustable time base  
- Trigger synchronization  
- USB serial communication  

### Repository
👉 [GitHub – Oscilloscope Using ATmega328p](https://github.com/moisesEzequiel1/Oscilloscope-Using-Atemga328p-)
