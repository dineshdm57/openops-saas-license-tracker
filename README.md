# OpenOps – SaaS License Tracker Workflows

Ready-to-use, editable OpenOps workflows to **track unused SaaS licenses** automatically.  
No code. No manual checks.

---

## What This Does

These workflows help you:

- Track users who haven’t used their SaaS license (Jira, Zoom, Miro, etc.)
- Check every month
- Alert your team in Slack
- Avoid paying for unused seats

---

## Included Files

| File                    | What It Does                        |
|-------------------------|--------------------------------------|
| `jira-workflow.json`    | Tracks inactive Jira users           |
| `multi-tool-workflow.json` | Tracks inactive users in Jira, Zoom, and Miro |

---

## Fully Editable & Extendable

These workflows are **fully editable** inside OpenOps.  
You can adapt them to **any SaaS tool with an API** — including:

- Slack
- Confluence
- Figma
- Asana
- Notion
- Salesforce  
...or any other system that supports user activity tracking via API.

You just need:
- The API endpoint for that tool
- The correct authentication (token, basic auth, etc.)

---

## How to Use in OpenOps

1. Open **OpenOps**
2. Go to **Workflows**
3. Click **Import**
4. Upload `jira-workflow.json` or `multi-tool-workflow.json`
5. Update the steps:
   - Add your API connections (Jira, Slack, Zoom, Miro)
   - Select your Slack channel
6. Click **Publish**

That’s it. The workflow will now check usage and notify your team monthly.

---

## How It Works

1. **Schedule** – Triggers once a month
2. **Get Users** – Connects to SaaS tool and pulls active user data
3. **Filter** – Flags users with no activity
4. **Slack** – Sends message with list of unused licenses

---

## Tip

Not using all 3 tools?  
Clone the multi-tool workflow and delete the sections you don’t need.  
You can also add new tools by copying and adjusting the same logic.

---

## Requirements

- OpenOps account
- API access to the tools you’re tracking
- Slack connection (for alerts)

