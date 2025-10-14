---
layout: feature
sitemap:
  exclude: 'no'
order: 40
server_type: local

description: "Connect your monday.com data using Model Context Protocol."
title: monday.com MCP Server
hero:
  title: monday.com MCP Server
  description: Connect your monday.com data using Model Context Protocol.
  image: /assets/images/marketing/monday-dot-com-mcp-server-hero.webp
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"

features:
  section_title: Local MCP Bridge
  title: Connecting to monday.com
  items:
    - side: left
      title: Setting Up Your monday.com Integration
      description: To get started, you'll need to install the monday mcp app from the monday.com Marketplace.
      image: /assets/images/marketing/monday-dot-com-mcp-server-step-1.webp # Placeholder image
      bullets:
        - Learn more about monday.com's MCP Server from their [documentation](https://monday.com/w/mcp)
        - Click on the button on the site (**Connect your AI tools**), which will take you to the **monday.com Marketplace**
        - Install the app to your account
        - Then, go to your monday.com **Settings** and find the **Connections** menu
        - There you'll find a page called **Personal API token**
        - Generate the token and copy it
      button:
        text: Install MCP App for monday.com
        url: https://monday.com/w/mcp
    - side: right
      title: Update Your Local MCP Bridge
      description: You'll need to add an entry into the mcp-config.json file.
      code: |
        {
            "mcpServers": {
                    "monday-api-mcp": {
                    "command": "npx",
                    "args": [
                        "@mondaydotcomorg/monday-api-mcp",
                        "-t",
                        "your_monday_api_token"
                    ]
                }
            }
        }
      bullets:
        - Run the [MCP Bridge](/mcp-servers/local-mcp)
        - Locate the config file
        - Add the entry for monday.com (remember to replace *your_monday_api_token* with the **Personal API token** from the previous step)
      
    - side: left
      title: Restart the Local MCP Bridge
      description: Once the MCP Bridge loads, you'll see monday.com and its tools listed in the window.
      image: "/assets/images/marketing/local-mcp-hero.png"
      bullets:
        - Remember to add your Local MCP Bridge to the list of MCP Servers in your knowledge base.
      button:
        text: Learn about Local MCP Bridge...
        url: /mcp-servers/local-mcp

show_workflow_library: false

cta:
  title: Connect Using MCP Today
  description: Unlock powerful automations through monday.com's future MCP integration.
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
---
