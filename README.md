# The Pip-MPU library for RIOT

## Description

This repository contains the userland code that facilitates interaction
with Pip-MPU. It enables, among other things, the invocation of Pip-MPU
services for memory isolation and the transfer of execution flow, as
well as the configuration of a subset of hardware registers. This
library is included as an external package in the paravirtualized
version of RIOT.

## Limitations

The library currently supports only the hardware registers of the
DWM1001, which is equipped with an nRF52832 MCU and a Cortex-M4 CPU
based on the ARMv7-M architecture.

## Funding

This project is part of the TinyPART project funded by the MESRI-BMBF
German-French cybersecurity program under grant agreements
n°ANR-20-CYAL-0005 and 16KIS1395K.
