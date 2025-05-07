# n8n-templates

A chill collection of my favorite n8n automation. Ready to import, remix, and run 🤖 🚀

---

## 📂 What's Inside

This repo is just a flat collection of `.json` files-each one an exported n8n workflow. No nested folders, no surprises. Grab any file you like and import it straight into your n8n instance.

---

## 🛠️ Prerequisites

- **n8n** installed (self-hosted or Desktop App).  
- Node.js ≥ v14 if you’re running n8n locally.  
- Basic familiarity with n8n’s UI (credentials, triggers, nodes).

---

## 🔄 Importing Workflows

### Via the UI

- In your n8n dashboard, click Workflows in the side menu.
- Hit the Import button (top right).
- Navigate to your cloned folder and select any .json file.
- Click Import → voilà, your flow appears.
- Toggle Activate if you want it to run on its trigger.

### Via CLI

```console
n8n import:workflow --input=./any-workflow.json
```

---

#### Happy automating! ✨
