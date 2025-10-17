---
layout: page
title: "Zapier MCP Integration"
description: "Connect your knowledge base to thousands of external tools and services through Zapier’s Model Context Protocol integration."
order: 10
server_type: remote

blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      align: start
      eyebrow: MCP Integration
      title: Zapier MCP Integration
      title_class: display-2 fw-bold mb-3
      subtitle: Connect ChatterKB to thousands of applications via Zapier’s Model Context Platform (MCP).
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
        url: /assets/images/marketing/mcp-feature-hero.png
        alt: Zapier MCP Integration hero

  - type: section
    class: py-6 bg-body-secondary bg-opacity-25
    title: Link Zapier MCP to ChatterKB
    subtitle: Spin up a server inside Zapier, capture the Streamable HTTP endpoint, and add it to your workspace.
    matrix:
      row:
        columns:
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                image:
                  url: /assets/images/marketing/internal-tools-feature-step-2.png
                  alt: Zapier MCP dashboard
              content:
                icon: bi-1-circle-fill
                title: Create Your Zapier MCP Server
                body: |
                  - Visit the Zapier MCP site and sign in with your Zapier account.
                  - Create a server and select the apps you want to expose through MCP.
                  - Save your configuration so Zapier provisions the server instance.
                buttons:
                  - text: Visit Zapier MCP
                    url: https://mcp.zapier.com
                    class: btn-outline-primary
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                image:
                  url: /assets/images/marketing/zapier-mcp-server-step-2.webp
                  alt: Zapier MCP connect tab
              content:
                icon: bi-2-circle-fill
                title: Copy the Streamable HTTP URL
                body: |
                  - Open the **Connect** tab of your Zapier MCP server.
                  - Ensure **Streamable HTTP** transport is enabled.
                  - Locate the **Connect with the server-specific URL** section and copy the URL.
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                image:
                  url: /assets/images/marketing/zapier-mcp-server-step-3.webp
                  alt: Adding Zapier MCP server inside ChatterKB
              content:
                icon: bi-3-circle-fill
                title: Add the Server to ChatterKB
                body: |
                  - In your knowledge base, open **Settings → MCP**.
                  - Click **Add Server**, provide a name, and paste the Zapier MCP URL.
                  - Save the server to unlock Zapier’s 5,000+ apps directly inside your automations.

  - type: section
    class: py-5
    body: |
      ChatterKB seamlessly integrates with Zapier’s Model Context Platform, combining your internal knowledge with Zapier’s 5,000+ app ecosystem so you can automate complex workflows without writing code.

  - type: cta
    class: py-6 bg-primary bg-opacity-10
    content:
      align: start
      class: col-lg-6 text-lg-start
      title: Connect Zapier Today
      body: Unlock powerful automations through Zapier MCP integration.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
---
