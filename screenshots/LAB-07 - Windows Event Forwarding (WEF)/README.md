# LAB-07 – Windows Event Forwarding (WEF)

## Overview

This lab focused on implementing centralized Windows event collection using Windows Event Forwarding (WEF). Security events generated on Windows systems were forwarded to a central Windows Event Collector (WEC) server for aggregation and monitoring.

## Objectives

* Configure Windows Event Forwarding (WEF)
* Configure Windows Event Collector (WEC)
* Enable WinRM communication
* Create event subscriptions
* Centralize Windows Security Event collection

## Technologies Used

* Windows Server
* Windows Event Forwarding (WEF)
* Windows Event Collector (WEC)
* WinRM
* Active Directory
* Windows Security Logs

## Tasks Performed

### 1. WinRM Configuration

Configured Windows Remote Management (WinRM) to support event forwarding communication.

### 2. Windows Event Collector Setup

Configured the Windows Event Collector service to receive forwarded events.

### 3. Event Subscription Creation

Created event subscriptions for centralized collection of Windows Security Logs.

### 4. Client Configuration

Configured domain-joined systems as forwarding clients.

### 5. Event Validation

Verified successful forwarding and collection of security events.

## Key Skills Demonstrated

* Windows Event Forwarding
* Windows Event Collector Administration
* WinRM Configuration
* Security Log Collection
* Centralized Event Monitoring

## Outcome

Successfully implemented centralized Windows Security Event collection using Windows Event Forwarding, providing the foundation for SIEM integration and enterprise security monitoring.

Author: Muhammad Wajahat

Role: Security Operations Portfolio | SOC Analyst Candidate
