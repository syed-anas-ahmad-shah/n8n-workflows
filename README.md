# n8n workflows

Ready-to-import n8n workflows, each in its own folder with a README, the workflow JSON and a picture of the canvas.

| Workflow | What it does |
|---|---|
| [Invoice Inbox](invoice-inbox/) | Watches Gmail for PDF invoices, reads the fields with AI, asks for approval in Slack on large amounts, logs to Google Sheets, labels the email and alerts Slack when payment is due soon |
| [Research Report Generator](research-report/) | Work in progress: runs research tasks on a topic, saves a draft report to Supabase, retries on low confidence and asks for email approval |

## How to use one

1. Open a workflow folder and read its README (what you need, setup steps).
2. In n8n, create a new workflow and choose **Import from file**, then pick the folder's `workflow.json`.
3. Connect your own credentials. No credentials or private IDs are included in any file here.

## License

MIT, see [LICENSE](LICENSE).
