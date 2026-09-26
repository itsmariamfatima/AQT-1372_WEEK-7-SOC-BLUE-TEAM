# ASTRAQUANTUM TECH — Week 07 SOC / Blue Team Assessment

## 📌 Overview

This repository contains my **Week 07 SOC / Blue Team Assessment** completed as part of the **ASTRAQUANTUM TECH Summer of Cybersecurity 2026** program.

The assessment focused on practical Security Operations Center (SOC) activities, including **security monitoring, alert triage, log analysis, phishing investigation, incident timeline development, and incident response**.

## 🎯 Objectives

* Understand fundamental SOC operations
* Practice security alert triage and prioritisation
* Analyse security alerts and surrounding events
* Investigate phishing-related artifacts
* Develop an incident timeline
* Document evidence and investigation findings
* Understand when and why an alert should be escalated

## 🛠️ Tools & Platforms

* **TryHackMe — SOC Fundamentals**
* **TryHackMe — SOC L1 Alert Triage**
* **Blue Team Labs Online (BTLO) — Phishing Analysis**
* WHOIS / Reverse DNS
* URL2PNG
* Text Editor

## 🔍 Practical Work

### 1. SOC Fundamentals

Covered the role and purpose of a Security Operations Center, including:

* People, Process, and Technology
* SOC L1, L2, and L3 responsibilities
* SIEM and EDR
* Alert triage
* 5 Ws analysis

### 2. SOC L1 Alert Triage

Practiced:

* Reviewing security alerts
* Analysing alert properties
* Prioritising alerts
* Assigning alerts
* Updating alert status
* Investigating a **Potential Data Exfiltration** alert
* Making an escalation decision

### 3. Phishing Analysis

Investigated a phishing-related email and analysed:

* Email headers
* Originating IP address
* Suspicious URL
* WHOIS / reverse DNS information
* Associated webpage and email attachment

## 🚨 Alert Investigation

The selected alert was:

**Alert:** Potential Data Exfiltration
**Severity:** Critical
**Time:** March 21, 2025 at 13:30

The investigation included reviewing the alert details, surrounding security events, timestamps, severity, evidence, and analyst actions.

The alert was assigned to the L1 analyst and moved to **In Progress** for further investigation.

## 📋 Investigation Outcome

The alert required **escalation to SOC L2** because the available evidence was not sufficient to determine whether the activity represented genuine unauthorised data exfiltration or legitimate activity.

Further investigation would involve reviewing relevant SIEM/EDR logs, affected users and hosts, network connections, and data-transfer activity.

## 📚 Key Learning

This assessment helped me understand how SOC analysts:

* Monitor and investigate security alerts
* Analyse events using available evidence
* Correlate surrounding activity
* Document investigation findings
* Prioritise security alerts
* Escalate cases when additional investigation is required


