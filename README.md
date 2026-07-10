# n8n Workflows

A collection of automation workflows built with [n8n](https://n8n.io/), covering integrations, agents, data pipelines, and utility patterns.

## 📂 Repository Structure

| Folder | Description |
|---|---|
| `API-Iintegration-pipeline` | Workflow demonstrating how to connect and pull/push data between external APIs. |
| `customer-service-agent` | An AI-powered agent workflow for handling customer service queries and responses. |
| `debugging` | Example workflows and utilities used for troubleshooting and debugging n8n flows. |
| `feedback-agent` | Automated agent workflow for collecting, processing, and routing user feedback. |
| `feedback-pipeline` | A pipeline for aggregating and transforming feedback data end-to-end. |
| `report-generation-system` | Workflow that automatically compiles and generates reports from source data. |
| `sales-data-pipeline` | Pipeline for ingesting, cleaning, and processing sales data. |
| `sales-report-discord-bot` | Workflow that generates sales reports and delivers them via a Discord bot. |
| `split and aggregrate` | Demonstrates n8n's split and aggregate nodes for batch data processing. |
| `webhook` | Example workflows triggered via incoming webhooks. |

> 💡 Each folder contains an exported n8n workflow (JSON) that can be imported directly into your own n8n instance.

## 🚀 Getting Started

### Prerequisites
- An [n8n](https://n8n.io/) instance (self-hosted or [n8n Cloud](https://n8n.io/cloud/))
- Any relevant API keys / credentials required by the specific workflow you want to use (e.g., Discord bot token, sales data source, etc.)

### Importing a Workflow
1. Clone this repository:
   ```bash
   git clone https://github.com/Apoo3va/n8n-workflows.git
   ```
2. Open your n8n instance.
3. Go to **Workflows → Import from File** (or **Import from URL**).
4. Select the `.json` file from the relevant folder in this repo.
5. Configure the required credentials/nodes for that workflow.
6. Activate and run the workflow.

## 🛠️ Tech Stack
- [n8n](https://n8n.io/) — workflow automation tool
- Various third-party integrations depending on the workflow (APIs, Discord, etc.)

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome! Feel free to open an issue or submit a pull request.

## 👤 Author

**Apoorva** ([@Apoo3va](https://github.com/Apoo3va))
