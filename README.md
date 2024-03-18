# SOC Entity Triage Workbook for Azure Sentinel
![Image Header](https://i.imgur.com/G0wn5vY.png)
## Overview
The SOC Entity Triage workbook is designed to enhance the triage process for security operation centers (SOCs) by providing a comprehensive and interactive analysis tool within Azure Sentinel. This workbook aims to streamline the investigation of entities such as IP addresses, hostnames, AD users, and email accounts, by presenting relevant security data and insights through a series of visualizations and queries. This workbook includes filters for separate workspaces within an environment that uses Azure Lighthouse to integrate multiple client environments in a single tenant.

## Features
- **Entity Analysis**: Analyze different entity types including private and public IP addresses, hostnames, AD users, and email accounts.
- **Interactive Visualizations**: Utilize KQL (Kusto Query Language) to query Azure Sentinel data and visualize the results in a user-friendly manner.
- **Quickly Pivot**: Utilizes query export, allowing you to open the query in a Log Analytics tab with the current parameters to dive into the logs.
- **Customizable Time Range**: Filter data within specific time frames to focus on the events relevant to your investigation.
- **Comprehensive Data Points**: Access detailed information on security alerts, sign-in logs, email triage, host triage, and more, tailored to the entity being investigated.
- **Client Filtering**: Automatically extracts available workspaces and provides filtering options.

## Getting Started

### Prerequisites
- Azure Sentinel environment setup.
- Permission to access and create workbooks within Azure Sentinel.

### Installation
1. Navigate to **Azure Sentinel** > **Workbooks** in the Azure portal.
2. Click on **+ Add workbook**.
3. Select the **Advanced editor** tab and paste the JSON configuration for the SOC Entity Triage workbook within the ARM template section.
4. Save the workbook to make it available in your Azure Sentinel environment.

### Usage
- Open the SOC Entity Triage workbook from the Azure Sentinel > Workbooks gallery.
- Select an entity type and specify the entity you wish to investigate.
- Use the interactive controls to filter by time range and other parameters relevant to your analysis.

![Workbook Preview](https://i.imgur.com/c3jfV01.png)

## Contributing
Your contributions are welcome! Please feel free to submit pull requests or open issues to improve the workbook or add new features.


