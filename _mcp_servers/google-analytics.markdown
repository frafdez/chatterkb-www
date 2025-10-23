---
layout: page
title: "Google Analytics MCP Server"
description: "Connect your Google Analytics data using Model Context Protocol."
order: 40
server_type: local

blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      align: start
      eyebrow: MCP Server
      title: Google Analytics MCP Server
      title_class: display-2 fw-bold mb-3
      subtitle: Connect your Google Analytics 4 properties using Model Context Protocol.
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
        url: /assets/images/marketing/ga4-mcp-server-hero.webp
        alt: Google Analytics MCP Server hero

  - type: section
    class: py-6 bg-body-secondary bg-opacity-25
    title: Connect Google Analytics (GA4) in Three Steps
    subtitle: Create service account credentials, configure the bridge, and verify the connection.
    matrix:
      row:
        columns:
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                image:
                  url: /assets/images/marketing/ga4-mcp-server-step-1.png
                  alt: Google Cloud Console setup
              content:
                icon: bi-1-circle-fill
                title: Prepare Google Cloud Credentials
                body: |
                  - Visit the [Google Cloud Console](https://console.cloud.google.com/) and sign in.
                  - Enable both **Google Analytics Admin API** and **Google Analytics Data API**.
                  - Search for **Service Accounts** and create a new one with Owner or Viewer role.
                  - Generate a JSON key file and note the service account email.
                  - Add the service account email as an authorized user inside Google Analytics.
                buttons:
                  - text: Open Google Cloud Console
                    url: https://console.cloud.google.com/
                    class: btn-outline-primary
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                code: |
                  {
                    "mcpServers": {
                      "analytics-mcp": {
                        "command": "pipx",
                        "args": [
                          "run",
                          "--spec",
                          "git+https://github.com/googleanalytics/google-analytics-mcp.git",
                          "google-analytics-mcp"
                        ],
                        "env": {
                          "GOOGLE_APPLICATION_CREDENTIALS": "PATH_TO_ADC_JSON"
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
                  - Launch the [Local MCP Bridge](/mcp-servers/local-mcp) after installation.
                  - Open `mcp-config.json` and add the Google Analytics server entry.
                  - Update `PATH_TO_ADC_JSON` to point to the JSON key you downloaded.
                  - Save the file and restart the bridge to reload servers.
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
                title: Verify Analytics Access
                body: |
                  - Confirm the Local MCP Bridge console lists Google Analytics tools.
                  - Add the bridge to your MCP servers inside ChatterKB.
                  - Start exploring GA4 metrics, dimensions, and reports from your knowledge base.
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
      body: Unlock powerful analytics insights through Google Analytics MCP integration.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
---
