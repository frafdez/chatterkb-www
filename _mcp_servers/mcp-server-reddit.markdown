---
layout: page
title: "Reddit MCP Server"
description: "Connect to Reddit using the community-driven mcp-server-reddit project."
order: 50
server_type: local

blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      align: start
      eyebrow: MCP Server
      title: Reddit MCP Server
      title_class: display-1 fw-bold mb-3
      subtitle: Connect to Reddit using the community-developed `mcp-server-reddit`.
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
        url: /assets/images/marketing/mcp-server-reddit-hero.png
        alt: Reddit MCP Server hero

  - type: section
    class: py-6 bg-body-secondary bg-opacity-25
    title: Connect Reddit in Four Steps
    subtitle: Register a Reddit app, install the community server, add it to the bridge, and start exploring subreddits.
    matrix:
      row:
        columns:
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                image:
                  url: /assets/images/marketing/mcp-server-reddit-step-1.webp
                  alt: Reddit developer app setup
              content:
                icon: bi-1-circle-fill
                title: Register a Reddit Application
                body: |
                  - Visit Reddit’s developer portal and sign in.
                  - Click **Create App** and choose the script option.
                  - Copy the generated client **ID** and **secret** for later.
                buttons:
                  - text: Create a Reddit App
                    url: https://www.reddit.com/prefs/apps
                    class: btn-outline-primary
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                code: |
                  pip install mcp-server-reddit
                copy_label: Copy
                copied_label: Copied!
              content:
                icon: bi-2-circle-fill
                title: Install the Community Server
                body: |
                  - Ensure Python is installed in the environment that runs the Local MCP Bridge.
                  - Install the community package from PyPI using the command shown.
                  - Confirm the module imports successfully by running `python -m mcp_server_reddit --help`.
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                code: |
                  {
                    "mcpServers": {
                      "mcp-server-reddit": {
                        "description": "A Reddit MCP Server",
                        "command": "/full/path/to/python",
                        "args": ["-m", "mcp_server_reddit"],
                        "envs": {
                          "REDDIT_CLIENT_ID": "your_client_id",
                          "REDDIT_CLIENT_SECRET": "your_client_secret"
                        }
                      }
                    }
                  }
                copy_label: Copy
                copied_label: Copied!
              content:
                icon: bi-3-circle-fill
                title: Configure the Local MCP Bridge
                body: |
                  - Launch the [Local MCP Bridge](/mcp-servers/local-mcp) and open `mcp-config.json`.
                  - Add the Reddit server entry exactly as shown.
                  - Replace `/full/path/to/python` with the interpreter that has the package installed.
                  - Substitute `your_client_id` and `your_client_secret` with the values from the Reddit app.
          - class: col-lg-12
            card:
              class: border-0 shadow-sm h-100
              media:
                position: end
                image:
                  url: /assets/images/marketing/local-mcp-hero.png
                  alt: Local MCP bridge console
              content:
                icon: bi-4-circle-fill
                title: Restart and Verify
                body: |
                  - Restart the Local MCP Bridge and confirm Reddit appears in the console output.
                  - Add the bridge inside ChatterKB to expose Reddit tools to your workspace.
                  - Start searching subreddits, fetching posts, or triggering workflows that rely on Reddit data.
                buttons:
                  - text: Learn about Local MCP Bridge...
                    url: /mcp-servers/local-mcp
                    class: btn-outline-secondary

  - type: section
    class: py-5
    body: |
      The `mcp-server-reddit` project is an open-source community server created by Hawstein. Explore the code on [GitHub](https://github.com/Hawstein/mcp-server-reddit) or install the latest release from [PyPI](https://pypi.org/project/mcp-server-reddit) to contribute improvements.

  - type: cta
    class: py-6 bg-primary bg-opacity-10
    content:
      align: start
      class: col-lg-6 text-lg-start
      title: Connect Using MCP Today
      body: Unlock powerful automations through Reddit’s MCP integration.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
---
