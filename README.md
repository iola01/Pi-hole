# Pi-hole DNS Ad Blocker - Home Lab Project

This repository documents my first DNS server setup using **Pi-hole**, running on a Raspberry Pi. The goal is to experiment with local DNS filtering, block unwanted content across my home network, and gain hands-on experience with DNS management and network privacy.

## Project Overview

Pi-hole acts as a local DNS server and network-wide ad blocker. It filters DNS requests and blocks domains based on large blocklists I’ve configured, currently handling around **200,000** known ad, tracker, and malicious domains.

The system is running 24/7 and handles DNS for all my home devices. I'm using upstream DNS resolvers from **Quad9**, with caching and blacklist rules managed locally.

## Why I'm Building This

This project is part of my personal learning journey into:

- Home networking
- DNS-level filtering and security
- Raspberry Pi and Linux system management
- Building a privacy-focused local infrastructure

## Current Status

- ✅ Live and stable
- ✅ Blocking around 15% of all queries
- ✅ Handling DNS for multiple devices
- ✅ Actively being monitored and improved

## Block Plan

I’m currently using:

- Multiple community-maintained blocklists (ads, trackers, malware)
- Custom blacklist and whitelist entries
- Future plans to optimize filtering without breaking legitimate services

## Future Improvements

- Integrate with Grafana for visual dashboards
- Add encrypted DNS (DoH or DoT)
- Combine with pfSense firewall in my home network
- Fine-tune blocklists for better balance between privacy and usability

## Notes

This setup is a work in progress and part of my broader interest in privacy, system administration, and home lab design. I plan to keep improving and learning as I go.

