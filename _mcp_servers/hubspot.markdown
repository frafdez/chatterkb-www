---
layout: page
title: "HubSpot MCP Server"
description: "Connect your HubSpot data using Model Context Protocol."
order: 30
server_type: local

blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      align: start
      eyebrow: MCP Server
      title: HubSpot MCP Server
      title_class: display-2 fw-bold mb-3
      subtitle: Connect your HubSpot data using Model Context Protocol.
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
        url: /assets/images/marketing/hubspot-mcp-server-hero.jpg
        alt: HubSpot MCP Server hero

  - type: section
    class: py-6 bg-body-secondary bg-opacity-25
    title: Connect HubSpot with Three Quick Moves
    subtitle: Spin up HubSpot’s private app, register it with the bridge, and start automating.
    matrix:
      row:
        columns:
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                image:
                  url: /assets/images/marketing/hubspot-mcp-server-step-1.webp
                  alt: HubSpot private app setup
              content:
                icon: bi-1-circle-fill
                title: Set Up Your HubSpot Private App
                body: |
                  - Review HubSpot’s [MCP documentation](https://developers.hubspot.com/mcp) to understand scopes and setup.
                  - Watch the walkthrough video for creating a private app.
                  - Generate a private app access token and copy it securely.
                buttons:
                  - text: How To Setup HubSpot MCP
                    url: https://developers.hubspot.com/mcp
                    class: btn-outline-primary
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                code: |
                  {
                    "mcpServers": {
                      "hubspotApi": {
                        "command": "npx",
                        "args": ["-y", "@hubspot/mcp-server"],
                        "env": {
                          "HUBSPOT_ACCESS_TOKEN": "your-hubspot-access-token"
                        }
                      }
                    }
                  }
                copy_label: Copy
                copied_label: Copied!
              content:
                icon: bi-2-circle-fill
                title: Configure the Local MCP Bridge
                body: |
                  - Launch the [Local MCP Bridge](/mcp-servers/local-mcp) and open `mcp-config.json`.
                  - Add the HubSpot server definition.
                  - Replace `your-hubspot-access-token` with the private app token.
                  - Save the file and restart the bridge to apply changes.
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
                title: Confirm and Start Automating
                body: |
                  - Verify HubSpot appears in the Local MCP Bridge console.
                  - Add the bridge inside ChatterKB so your workspace can reach HubSpot tools.
                  - Begin syncing deals, logging activities, or generating insights from HubSpot data.
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
      body: Unlock powerful automations through HubSpot’s MCP integration.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
---
