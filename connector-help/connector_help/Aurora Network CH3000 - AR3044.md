---
uid: Connector_help_Aurora_Network_CH3000_-_AR3044
---

# Aurora Network CH3000 - AR3044

This driver shows information about the status and alarms of the AR3044 modules. It also allows configuration of the alarms, optical receivers and RF receivers. It displays the information of the receivers as stand alone parameters to make it more readable.

## About

About the AR3044 Quad Gain Analog Return Receiver module.

Note:

- This driver is automatically generated by driver Aurora Network CH3000 range 1.0.0.10

Ranges of the driver

| **Driver Range** | **Description** | **DCF Integration** | **Cassandra Compliant** |
|------------------|-----------------|---------------------|-------------------------|
| 1.0.0.x          | Initial version | No                  | Yes                     |

### Supported firmware versions

| **Driver Range** | **Device Firmware Version** |
|------------------|-----------------------------|
| 1.0.0.x          | 1.16                        |

## Installation and configuration

### Creation

This driver is used by DVE child elements that are **automatically created** by the driver [Aurora Network CH3000](xref:Connector_help_Aurora_Network_CH3000), from version 1.0.0.1 onwards.

## Usage

### General

Provides general information about the AR3044L module. Shows the **Type**, **Model**, **Firmware**, **Revision**, **Serial Number**, **Module Up Time** and other general status parameters.

### Alarms

Provides alarm information about the AR3044L module current and history. Including **12V Out of Range**, **5V Out of Range**, **3.3V Out of Range**, **Fan Not Operational**, and **Board High Temperature**.

### Detailed Alarms

Provides detailed alarm information about the AR3044L module including the four receivers. Shows voltage input sates, fan state, board temp state, Rx input power state for each receiver and RF output state for each receiver.

### Alarms Configuration

Allows to configure the alarm mask and severity. Allows to configure alarms masks and severities.

### Receiver

Provides receiver status and counters information. shows a table with information for each receiver with **Rx Input Power**, **AB Switch Count**, **AB Switch Stable Period**, **AB Switch Status** and **RF Output Status**.

### Configuration

Allows to configure the module receivers. Configures **RF Test Point, Rx Inputs Wavelengths, Inputs Attenuation, Inputs Max, Inputs** **Min, AB Switch Threshold, Reset Counters, Expected Inputs, ALC Control, Auto Squelch, Switch Control and Input Level.**

### States

Provides status information about the module.