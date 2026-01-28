---
title: "Cisco Switch – Access Issue"
layout: single
permalink: /issues/cisco/switches/
classes: wide
toc: true
toc_label: "On this page"
toc_sticky: true
---

## Issue

After replacing the switch with the running configuration on a new switch,
ping did not work.

## What we saw
{: .notice--warning}

- Ping failed
- No SSH access

## Fix
{: .notice--success}

- Cleared ARP on the gateway → ping started working
- SSH still failed
- Cleared ARP on the peer switch → SSH started working
