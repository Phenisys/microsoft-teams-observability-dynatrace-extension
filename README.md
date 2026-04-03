[![Download Latest](https://img.shields.io/badge/Download-Latest-brightgreen?logo=download)](https://github.com/Phenisys/dynatrace-extension-teams-observability-agent/releases/latest)
[![All Releases](https://img.shields.io/badge/Releases-All-blue?logo=github)](https://github.com/Phenisys/dynatrace-extension-teams-observability-agent/releases)
[![Documentation](https://img.shields.io/badge/Documentation-Online-blueviolet?logo=gitbook)](https://phenisys.github.io/microsoft-teams-observability-documentation/collector/extension/)
[![Microsoft Teams Observability](https://img.shields.io/badge/Microsoft_Teams_Observability-Agent-blue)](https://github.com/Phenisys/microsoft-teams-observability)


# Microsoft Teams Observability Agent — Dynatrace Extension

The **Microsoft Teams Observability Agent Dynatrace Extension** enables the collection of Microsoft Teams observability data directly into **Dynatrace**.

It is designed to run as a Dynatrace extension and feed Microsoft Teams telemetry into the Dynatrace platform, making it possible to monitor collaboration experience, analyze call quality, detect degradations, and support operational troubleshooting workflows.

This extension is intended to be used together with the [**Microsoft Teams Observability Dynatrace Application**](https://github.com/Phenisys/microsoft-teams-observability-dynatrace-app), which provides ready-to-use dashboards and visualizations for the collected data.

---

## Downloads

To obtain the extension:

- **Latest release (recommended)** — see release notes and package: [here](https://github.com/Phenisys/dynatrace-extension-teams-observability-agent/releases/latest)

- **All releases** — browse all available versions: [here](https://github.com/Phenisys/dynatrace-extension-teams-observability-agent/releases)

---

## Overview

The extension collects Microsoft Teams observability data and makes it available in Dynatrace for monitoring and investigation purposes.

Typical usage includes:

- Monitoring Microsoft Teams call quality and collaboration experience
- Supporting service desk and operations teams during incident triage
- Correlating Teams degradations with broader platform, network, or Microsoft incidents
- Enabling analysis across users, calls, locations, and published service issues

---

## Documentation

Full documentation for the extension is available here:

- **Extension documentation**: [Microsoft Teams Observability Extension](https://phenisys.github.io/microsoft-teams-observability-documentation/collector/extension/)
- **Installation guide**: [Installation](https://phenisys.github.io/microsoft-teams-observability-documentation/collector/extension/installation/)
- **Migration guide**: [Migration](https://phenisys.github.io/microsoft-teams-observability-documentation/collector/extension/migration/)

---

## Installation

Installation and configuration steps are documented in the dedicated guide:

- [Install the Dynatrace Extension](https://phenisys.github.io/microsoft-teams-observability-documentation/collector/extension/installation/)

For migration scenarios between extension versions, see:

- [Migration guide](https://phenisys.github.io/microsoft-teams-observability-documentation/collector/extension/migration/)

---

## Usage

Once installed and configured in Dynatrace, the extension continuously collects Teams-related observability data and forwards it into the platform.

The collected data can then be explored through the dedicated Dynatrace application:

- [**Microsoft Teams Observability Dynatrace Application**](https://github.com/Phenisys/microsoft-teams-observability-dynatrace-app)

Together, the components provide a complete end-to-end solution:

1. **The Dynatrace Extension** collects and sends Microsoft Teams observability data
2. **The Dynatrace Application** provides dashboards, investigations, and analysis views in Dynatrace

---

## Related Components

### Dynatrace Application

Ready-to-use dashboards and investigation views for Microsoft Teams observability:

- https://github.com/Phenisys/microsoft-teams-observability-dynatrace-app

### Teams Observability Agent

Core Microsoft Teams observability project:

- https://github.com/Phenisys/microsoft-teams-observability

---

## Additional Information

Issues and feature requests can be submitted by opening a GitHub Issue.
