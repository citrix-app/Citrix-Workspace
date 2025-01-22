# Download and install Citrix Workspace app


- [Download Citrix Workspace](#download-citrix-workspace)
- [Install Citrix Workspace](#download-citrix-workspace)
- [System Requirements](#system-requirements)
- [Configuration](#configuration)
- [Troubleshooting](#troubleshooting)
- [Changelog](#changelog)
- [Key Features](#key-features)

## Download Citrix Workspace

Citrix Workspace 2409.10 is the latest stable version

*   Release number: 2409.10
*   Release date: Jan 16, 2025

| Platform | Type             | Download                                                                                                                                                                                                                             |
| -------- | ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Windows  | Standard Installer   | [64-bit version](https://www.citrix.com/platform/citrix-workspace-app.html) [ARM64 version](https://www.citrix.com/platform/citrix-workspace-app.html)                                                                                          |
|          | System Installer | [64-bit version](https://www.citrix.com/platform/citrix-workspace-app.html) [ARM64 version](https://www.citrix.com/platform/citrix-workspace-app.html)                                                                                        |
|          | .zip             | [64-bit version](https://www.citrix.com/platform/citrix-workspace-app.html) [ARM64 version](https://www.citrix.com/platform/citrix-workspace-app.html)                                                                                          |
| macOS    | .zip             | [Universal](https://go.microsoft.com/fwlink/?linkid=2298050) [Intel Chip](https://go.microsoft.com/fwlink/?linkid=2298103) [Apple Silicon](https://go.microsoft.com/fwlink/?linkid=2297727) |  


## System Requirements

For smooth installation and optimal performance, ensure the following requirements are met:

- **Operating System:** Supports Windows 11 24H2 and newer versions.
- **.NET Framework:** Requires .NET Desktop Runtime 8.0 or higher.
- **Supported Browsers:** Fully compatible with modern Chromium-based browsers.
- **Hardware Requirements:** Works seamlessly on PCs, tablets, and thin clients. Hardware must meet Citrix’s recommended CPU, RAM, and storage specifications.

## Configuration

To optimize performance and usability of Citrix Workspace App, configure the following:

- **Beacon Tests:**  
    Verify Citrix network service connectivity using the built-in Configuration Checker. Beacon Tests ensure a reliable and robust user experience during Citrix sessions.
    
- **USB Connection Memory:**  
    Automatically reconnect manually configured USB devices in future virtual sessions, simplifying device management and saving time.
    
- **Store Configuration:**  
    Administrators can set user-friendly store names and control user modifications, maintaining consistency in organizational settings.
    
- **Power Management:**  
    Prevent endpoint devices from entering sleep mode during active sessions with Power Management policies, ensuring uninterrupted workflows and enhanced productivity.
    
- **Advanced Customization Options:**  
    Administrators can tailor session preferences, virtual channel behavior, and display configurations, providing flexibility for diverse environments.
    

For detailed configuration instructions, visit the [Citrix Workspace Configuration Guide](https://docs.citrix.com/en-us/citrix-workspace-app/configure-access.html).

## Troubleshooting

Citrix Workspace App includes robust troubleshooting tools and strategies to address common issues:

- **Authentication Failures:**
    
    - Resolve Single Sign-On (SSO) or Kerberos issues by verifying domain credentials and Active Directory integration.
    - Consult authentication logs for persistent issues.
- **Network Issues:**
    
    - Use the Connection Strength Indicator for real-time network performance metrics.
    - For advanced diagnostics, complement Citrix tools with third-party network monitoring solutions.
- **Device Compatibility:**
    
    - Confirm that USB peripherals, webcams, and audio devices are supported by your Citrix Workspace App version. Keep device drivers updated for compatibility.
    - Refer to Citrix documentation for a list of supported devices.
- **Logs and Reports:**
    
    - Utilize detailed session activity, network, and device usage logs for in-depth analysis and effective troubleshooting.
- **Session Disconnects:**
    
    - Investigate network policies, endpoint configurations, and server-side session limits.
    - Enable reconnection policies to minimize disruptions during temporary connectivity losses.

For advanced troubleshooting, refer to the [Citrix Workspace Troubleshooting Page](https://docs.citrix.com/en-us/citrix-workspace-app/troubleshoot.html).

## Changelog

#### Version 2409 (Latest Release)

- **New Features:**
    
    - Full support for Windows 11 24H2, ensuring compatibility with the latest OS features.
    - Advanced energy-saving enhancements and refined beacon checks for improved network reliability.
    - Default activation of TLS 1.3 for secure communication protocols.
    - Enhanced virtual desktop resizing and launching for a flicker-free experience.
- **Bug Fixes:**
    
    - Resolved authentication failures linked to Workspace Environment Management tools.
    - Addressed UI inconsistencies in published resources display.
    - Fixed USB reconnection delays causing session disconnects.
    - Improved error reporting for troubleshooting virtual desktop launches.

#### Previous Versions

- **Version 2405:**
    
    - Added SSO support for ARM64-based devices.
    - Introduced enhanced system logs and improved beacon checker utility.
    - Upgraded Microsoft Teams audio/video performance in virtual sessions.
    - Integrated MJPEG webcam support for better image quality.
    - Enhanced Desktop Viewer toolbar customization.
- **Version 2403:**
    
    - Implemented sustainability features for hybrid launches.
    - Improved domain pass-through authentication.
    - Upgraded compatibility with the latest Chromium Embedded Framework versions.
    - Introduced new administrative controls for app protection and security policies.
    - Simplified Microsoft Teams VDI plugin installation.

## Key Features

Citrix Workspace App for Windows includes features to boost productivity, security, and user experience:

- **Single Sign-On Support:**  
    Simplifies authentication with SSO using domain credentials or Kerberos, ensuring seamless and secure logins.
    
- **Microsoft Teams Optimization:**  
    Enhanced audio, video, and collaboration tools ensure smooth virtual meeting experiences.
    
- **Improved Desktop Launch Experience:**  
    Offers flicker-free transitions and seamless resizing of virtual desktops.
    
- **TLS 1.3 Support:**  
    Strengthens security by adopting the latest TLS protocol.
    
- **SOCKS5 Proxy Support:**  
    Ensures secure and reliable data transport within enterprise networks.
    
- **Customizable Desktop Viewer Toolbar:**  
    Allows users to personalize tools and features for improved efficiency.
