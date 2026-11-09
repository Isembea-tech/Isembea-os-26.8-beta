# ISEMBEA OS 26.8 Beta

**Innovation Forward.**

ISEMBEA OS 26.8 Beta is an experimental, browser-based operating-system interface built with HTML, CSS, and JavaScript. It explores an OS-style desktop experience that can run in a modern web browser.

> **Status:** Beta / Experimental  
> **Platform:** Web  
> **Runtime:** Browser  
> **Architecture:** Web

## Features

- OS-inspired desktop interface and app navigation
- English interface by default, with Thai language support
- Dark and light appearance settings
- Appearance customization through Theme Studio
- Built-in apps, including Clock, Notes, Calendar, Weather, Files, Search, and Settings
- System Monitor and Diagnostics
- Notification Engine
- ISEMBEA Terminal with `ishell 1.0`
- Linux-inspired terminal commands, including `fastfetch`
- Local browser storage for supported settings and app data
- ISEMBEA AI connection settings for configuring an AI provider

## Getting Started

1. Download `ISEMBEA_OS_26_8_Beta.html`.
2. Open the HTML file using a modern browser.
3. Wait for the interface to load.
4. Open apps from the desktop or app launcher.

No separate installation is required for the basic browser experience.

## Terminal

Open **Terminal** and try:

```text
help
fastfetch
about
uname
whoami
date
ls
pwd
```

The terminal is a browser-based virtual command environment. Its filesystem and system information are simulated. It is **not** a native Linux shell and does not run on a Linux kernel.

## Data and Storage

ISEMBEA OS stores supported preferences and application data in the browser's local storage. Data is associated with the browser and origin being used. Clearing browser site data may remove locally stored settings or data.

## AI Connection

The AI connection panel provides configuration options for connecting an AI provider. Availability depends on the provider configuration and any required backend or API access. The core OS interface does not mean that an AI model is running locally on the device.

## Beta Testing

This release is intended for testing. Please check the interface and apps, then report reproducible issues with:

- The browser and device you used
- The steps that caused the issue
- What you expected to happen
- What actually happened
- A screenshot, if useful

Please avoid including passwords, private API keys, or other sensitive information in bug reports.

## Known Limitations

- This is a web-based OS experience, not a standalone operating system, Android ROM, or Linux distribution.
- Browser capabilities and storage limits may vary by device and browser.
- Some integrations may require an internet connection or external service configuration.
- The terminal is simulated and cannot execute arbitrary native system commands.

## Project

**Project:** ISEMBEA OS  
**Version:** 26.8 Beta  
**Shell interface:** ishell 1.0  
**Runtime:** Web Runtime  
**Slogan:** Innovation Forward.

---

*Thank you for testing ISEMBEA OS 26.8 Beta. Your feedback helps improve the project.*
