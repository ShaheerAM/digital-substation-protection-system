# Digital Substation Protection & Monitoring System

## Overview

This project is a low-voltage embedded protection and monitoring prototype designed to simulate core transmission substation protection and control functions used in modern power systems.

The system monitors current conditions in real time, detects abnormal operating states such as overcurrent faults, and isolates the load using relay-based trip logic controlled by an ESP32 microcontroller. A SCADA-style monitoring interface was designed to provide live telemetry, breaker status visualization, and fault event logging.

## Features

* Real-time current monitoring
* Overcurrent fault detection
* Relay-based fault isolation
* Embedded protection logic using ESP32
* SCADA-style monitoring interface
* Event and fault logging
* Protection logic architecture diagrams

## Technologies

* ESP32 Microcontroller
* ACS712 Current Sensor
* Relay Module
* Embedded C/C++
* Python / Node-RED Dashboard
* Power System Protection Concepts

## Engineering Concepts Demonstrated

* Power system protection
* Protection relay logic
* Fault isolation
* Control systems
* Embedded monitoring systems
* Transmission substation operations
* Real-time telemetry

## Safety Notice

This project is designed exclusively for low-voltage DC operation and does not interface with mains power.
