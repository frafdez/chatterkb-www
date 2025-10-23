---
layout: page
title: "Airtable MCP Server"
description: "Connect your Airtable data using Model Context Protocol."
order: 50
server_type: local

blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      align: start
      eyebrow: MCP Server
      title: Airtable MCP Server
      title_class: display-2 fw-bold mb-3
      subtitle: Connect your Airtable data using Model Context Protocol.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
    media:
      class: col-lg-6 text-center
      position: end
      image:
        url: /assets/images/marketing/airtable-mcp-server-hero.png
        alt: Airtable MCP Server hero

  - type: section
    class: py-6 bg-body-secondary bg-opacity-25
    title: Get Connected In Minutes
    subtitle: Bring Airtable into your automations with three quick steps.
    matrix:
      row:
        columns:
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                image:
                  url: /assets/images/marketing/airtable-mcp-server-step-1.png
                  alt: Airtable MCP setup
              content:
                icon: bi-1-circle-fill
                title: Install the Airtable Integration
                body: |
                  - Review the [Airtable MCP documentation](https://airtable.com/developers/web/api/introduction).
                  - Visit the Airtable Developer Hub and sign in to your account.
                  - Open **Account Settings** from the profile menu.
                  - In the **Developer** tab choose **Personal access tokens**.
                  - Create a new token, scope it for the bases you need, then copy it somewhere safe.
                buttons:
                  - text: Create Your Personal Access Token
                    url: https://airtable.com/create/tokens
                    class: btn-outline-primary
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                code: |
                  {
                    "mcpServers": {
                      "airtable": {
                        "command": "npx",
                        "args": ["-y", "airtable-mcp-server"],
                        "env": {
                          "AIRTABLE_API_KEY": "your_airtable_token"
                        }
                      }
                    }
                  }
                copy_label: Copy
                copied_label: Copied!
              content:
                icon: bi-2-circle-fill
                title: Update Your Local MCP Bridge
                body: |
                  - Launch the [Local MCP Bridge](/mcp-servers/local-mcp) after installing it.
                  - Open `mcp-config.json` in your editor of choice.
                  - Add the Airtable server entry shown here.
                  - Replace `your_airtable_token` with the personal access token from step one.
                  - Save the file and relaunch the bridge.
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                image:
                  url: /assets/images/marketing/local-mcp-hero.png
                  alt: Local MCP bridge console
              content:
                icon: bi-3-circle-fill
                title: Confirm the Connection
                body: |
                  - Watch the Local MCP Bridge console to confirm Airtable loads successfully.
                  - Add the bridge inside ChatterKB so your workspace can reach it.
                  - Start querying tables, syncing data, or triggering automations with Airtable.
                buttons:
                  - text: Learn about Local MCP Bridge...
                    url: /mcp-servers/local-mcp
                    class: btn-outline-secondary

  - type: cta
    class: py-6 bg-primary bg-opacity-10
    content:
      align: start
      class: col-lg-6 text-lg-start
      title: Connect Using MCP Today
      body: Unlock powerful database insights through Airtable MCP integration.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
---
