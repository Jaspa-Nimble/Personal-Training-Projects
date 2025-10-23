# Exercise 01 — (Conceptual) Trojan: Gain Access to Target System
**Status:** Draft

> **Safety reminder:** This page describes the learning goals and analysis approach only. It does **not** provide code or step-by-step instructions to create malware.

## Overview (non-actionable)
Short conceptual description of what a trojan is, common infection vectors, and defense mechanisms.

## Learning objectives
- Identify how trojans typically achieve persistence and privilege escalation (conceptual).
- Recognize defensive signatures and behavioral indicators that suggest trojan activity.
- Understand legal and ethical boundaries when studying trojans.

## Pre-requisites
- Basic familiarity with Windows/Linux internals
- Understanding of processes, services, and persistence concepts

## Lab environment (policy note)
- **Only** perform controlled analysis in an isolated lab environment. Do not test on production networks or third-party systems.

## Tools (high-level, non-actionable)
- Static analysis tools (e.g., disassembler) — used to read binaries conceptually.
- Dynamic analysis sandbox — used to observe behavior in controlled environment.
*(Do not include or publish real samples in this public repo.)*

## Tasks / Worksheet (example)
1. Define expected behavior of the sample (conceptual).  
2. List possible indicators to look for in logs (file paths, network endpoints, abnormal processes).  
3. Describe mitigation steps a defender would take (isolate host, collect memory image, block C2 domains).

## Deliverables
- `exercise-01-report.md` — Observed indicators, timeline, recommended detection rules, mitigation checklist.