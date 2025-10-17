---
layout: page
title: "Notion MCP Server"
description: "Connect your Notion pages using Model Context Protocol."
order: 20
server_type: local

blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      align: start
      eyebrow: MCP Server
      title: Notion MCP Server
      title_class: display-2 fw-bold mb-3
      subtitle: Connect your Notion pages using Model Context Protocol.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"
          class: btn-outline-secondary btn-lg
    media:
      class: col-lg-6 text-center
      position: end
      image:
        url: /assets/images/marketing/notion-mcp-server-herp.png
        alt: Notion MCP Server hero

  - type: section
    class: py-6 bg-body-secondary bg-opacity-25
    title: Get Connected In Minutes
    subtitle: Bring Notion into your automations with three quick steps.
    matrix:
      row:
        columns:
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                image:
                  url: /assets/images/marketing/notion-mcp-server-github.jpg
                  alt: Notion MCP setup
              content:
                icon: bi-1-circle-fill
                title: Create Your Notion Integration
                body: |
                  - Visit the [Notion MCP Server documentation](https://github.com/makenotion/notion-mcp-server#readme) to review requirements.
                  - In Notion, create a new internal integration and copy the generated secret.
                  - Share the pages or databases your integration needs to access.
                buttons:
                  - text: Create a Notion Integration
                    url: https://www.notion.so/profile/integrations
                    class: btn-outline-primary
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                code: |
                  {
                    "mcpServers": {
                      "notionApi": {
                        "command": "npx",
                        "args": ["-y", "@notionhq/notion-mcp-server"],
                        "env": {
                          "OPENAPI_MCP_HEADERS": "{\"Authorization\": \"Bearer ntn_****\", \"Notion-Version\": \"2022-06-28\" }"
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
                  - Open your `mcp-config.json` file and add the Notion server entry.
                  - Replace `ntn_****` with the integration secret you just created.
                  - Save the configuration and relaunch the Local MCP Bridge.
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                image:
                  url: /assets/images/marketing/local-mcp-hero.png
                  alt: Local MCP bridge
              content:
                icon: bi-3-circle-fill
                title: Confirm The Connection
                body: |
                  - Watch the Local MCP Bridge console to verify Notion loads successfully.
                  - Add the bridge to your MCP server list inside ChatterKB.
                  - Start querying pages, summarising docs, or capturing new records straight from your automations.
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
      body: Unlock powerful automations through Notion's MCP integration.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"
          class: btn-outline-secondary btn-lg
---
