---
layout: card-template/blocks
sitemap:
  exclude: 'no'

title: Local MCP
container: xxl

blocks:
  - type: hero
    class: py-6
    position: end
    content:
      class: col-lg-6 text-lg-start
      title: Local MCP
      subtitle: Run your MCP servers on your local machine with ChatterKB's Local MCP Bridge
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"
          class: btn-outline-secondary btn-lg
          icon: bi-calendar
    media:
      class: col-lg-6
      position: end
      image:
        url: "/assets/images/marketing/local-mcp-hero.png"
        class: shadow-lg rounded-4

  - type: section
    class: py-6 bg-body-secondary bg-opacity-50
    title: Local MCP Sent to Your Browser
    subtitle: Four quick steps to connect your desktop tools and start chatting.
    matrix:
      row:
        columns:
          - class: col-lg-12
            card:
              class: border-0 shadow
              media:
                class: col-lg-8
                position: start
                image:
                  url: /assets/images/marketing/local-mcp-step-1.png
              content:
                class: col-lg-4 p-lg-2 text-lg-start
                icon: bi-1-circle-fill
                title: Download the Bridge
                subtitle: Visit your knowledge base settings to grab the installer
                body: |
                  - Click **Download MCP Bridge**
                  - Unzip the files to any folder
                  - Double-click the Mac or Windows app to launch it
                buttons:
                  - text: Download MCP Bridge
                    url: https://chatterkb.s3.us-east-1.amazonaws.com/ckb-mcp-bridge.zip
                    class: btn-outline-primary
                    icon: bi-download
          - class: col-lg-12
            card:
              class: border-0 shadow
              media:
                class: col-lg-8
                position: end
                image:
                  url: /assets/images/marketing/local-mcp-step-2.png
              content:
                class: col-lg-4 p-lg-2 text-lg-start
                icon: bi-2-circle-fill
                title: Add Your MCP Servers
                subtitle: Works with Claude, Cursor, and other desktop clients
                body: |
                  - The bridge opens a config page for your MCP servers
                  - Click **Save and Apply** to connect automatically
          - class: col-lg-12
            card:
              class: border-0 shadow
              media:
                class: col-lg-8
                position: start
                image:
                  url: /assets/images/marketing/local-mcp-step-3.png
              content:
                class: col-lg-4 p-lg-2 text-lg-start
                icon: bi-3-circle-fill
                title: Add the URL to ChatterKB
                subtitle: Surface internal tools directly in every conversation
                body: |
                  - Copy the local MCP URL from the bridge
                  - Paste it into ChatterKB and click **Add**
          - class: col-lg-12
            card:
              class: border-0 shadow
              media:
                class: col-lg-7
                position: end
                image:
                  url: /assets/images/marketing/local-mcp-step-4.png
              content:
                class: col-lg-5 p-lg-2 text-lg-start
                icon: bi-4-circle-fill
                title: Start a New Chat
                subtitle: Local MCP appears as soon as the connection is live
                body: |
                  - Launch a new thread and choose **Local MCP**
                  - Try “List your tools” to confirm everything is ready
                  - Keep the bridge tab open so your connection stays active

  - type: cta
    class: py-5 bg-primary bg-opacity-10
    content:
      class: col-lg-8 mx-auto
      align: left
      title: Connect Your Local MCP Servers Today
      body: Unlock powerful automations using MCP integrations.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
          icon: bi-calendar
---
