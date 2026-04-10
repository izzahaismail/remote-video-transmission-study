# Remote Video Transmission Technical Study over Low Bandwidth Networks
A technical study of low bandwidth video transmission over constrained network links, including stream stability, throughput and latency observations.

## Overview
This project explores the challenges of transmitting live video over low-bandwidth and high-latency networks.

The goal was to evaluate how different video configurations affect stream stability, latency and playback quality under constrained network conditions.

## Objectives
- Assess live video transmission feasibility over constrained links
- Evaluate bitrate and frame rate impact on stream stability
- Monitor latency and throughput behaviour
- Identify suitable settings for reliable field deployment

## Test Setup
The test environment consisted of:
- IP camera video source
- Video encoding / playback software
- Satellite terminal / constrained uplink
- Local routing equipment (for selected scenarios)
- Packet analysis tools

Tools used:
- VLC / OBS Studio
- Wireshark
- IP camera web interface

## Test Scenarios

### Scenario 1: Direct constrained uplink connection
- Camera connected directly to constrained uplink
- Low resolution / moderate bitrate

### Scenario 2: Routed network setup
- Camera routed through intermediate device
- Higher bitrate profile tested

### Scenario 3: Optimised low-bitrate profile
- Reduced bitrate and frame rate
- Stability-focused configuration

## Key Findings
- Higher bitrate settings introduced increased packet retransmissions and occasional stream freezing
- Reduced bitrate and lower frame rates improved playback stability
- Direct uplink connection reduced network complexity and improved consistency
- Constrained links require careful balancing of quality and reliability

## Lessons Learned
- Real-time video over constrained links requires conservative encoding settings
- Network routing devices can introduce additional latency and instability
- Packet-level analysis is critical for diagnosing stream issues
- Practical field deployment requires both technical optimisation and operational planning

## Skills Demonstrated
- Network performance testing
- Video stream troubleshooting
- Packet analysis
- System optimisation under constraints
- Technical reporting

## Disclaimer
This repository presents a simplified and anonymised technical study for portfolio purposes. Sensitive operational details, configurations and deployment-specific information have been excluded.
