---
layout: page
title: "monday.com MCP Server"
description: "Connect your monday.com data using Model Context Protocol."
order: 40
server_type: local

blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      align: start
      eyebrow: MCP Server
      title: monday.com MCP Server
      title_class: display-2 fw-bold mb-3
      subtitle: Connect your monday.com data using Model Context Protocol.
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
        url: /assets/images/marketing/monday-dot-com-mcp-server-hero.webp
        alt: monday.com MCP Server hero

  - type: section
    class: py-6 bg-body-secondary bg-opacity-25
    title: Connect monday.com in Three Steps
    subtitle: Install the monday.com MCP integration, configure the bridge, and start automating.
    matrix:
      row:
        columns:
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                image:
                  url: /assets/images/marketing/monday-dot-com-mcp-server-step-1.webp
                  alt: monday.com marketplace listing
              content:
                icon: bi-1-circle-fill
                title: Install the monday.com MCP App
                body: |
                  - Review monday.com's [MCP Server documentation](https://monday.com/w/mcp).
                  - Click **Connect your AI tools** to open the monday.com Marketplace.
                  - Install the app to your account and finish the marketplace prompts.
                  - In monday.com, open **Settings → Connections → Personal API token**.
                  - Generate a token and copy it for later use.
                buttons:
                  - text: Install MCP App for monday.com
                    url: https://monday.com/w/mcp
                    class: btn-outline-primary
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                code: |
                  {
                    "mcpServers": {
                      "monday-api-mcp": {
                        "command": "npx",
                        "args": ["@mondaydotcomorg/monday-api-mcp", "-t", "your_monday_api_token"]
                      }
                    }
                  }
                copy_label: Copy
                copied_label: Copied!
              content:
                icon: bi-2-circle-fill
                title: Configure the Local MCP Bridge
                body: |
                  - Launch the [Local MCP Bridge](/mcp-servers/local-mcp) after installation.
                  - Open `mcp-config.json` in your editor.
                  - Add the monday.com entry shown here.
                  - Replace `your_monday_api_token` with the personal token from step one.
                  - Save the file and restart the bridge.
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
                title: Verify and Start Building
                body: |
                  - Confirm the Local MCP Bridge console lists the monday.com tools.
                  - Add the bridge to your MCP servers inside ChatterKB.
                  - Begin syncing boards, logging updates, or pushing automations via monday.com.
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
      body: Unlock powerful automations through monday.com's MCP integration.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
---
