---
layout: marketing-feature
sitemap:
  exclude: 'no'
order: 2
description: "Connect your HubSpot data using Model Context Protocol."
title: HubSpot MCP Server
hero:
  title: HubSpot MCP Server
  description: Connect your HubSpot data using Model Context Protocol.
  image: /assets/images/marketing/hubspot-mcp-server-hero.jpg
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"

features:
  section_title: Local MCP Bridge
  title: Connecting to HubSpot
  items:
    - side: left
      title: Setting Up Your HubSpot Integration
      description: To get started, you'll need to set up a private app in your HubSpot account.
      image: /assets/images/marketing/hubspot-mcp-server-step-1.webp # Placeholder image
      bullets:
        - Learn more about HubSpot's MCP Server from their [documentation](https://developers.hubspot.com/mcp)
        - Click on the button and **watch the video** for instructions on how to setup the app
      button:
        text: How To Setup HubSpot MCP
        url: https://developers.hubspot.com/mcp
    - side: right
      title: Update Your Local MCP Bridge
      description: You'll need to add an entry into the mcp-config.json file.
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
      bullets:
        - Run the [MCP Bridge](/mcp-servers/local-mcp)
        - Locate the config file
        - Add the entry for HubSpot (remember to replace your access token)
      
    - side: left
      title: Restart the Local MCP Bridge
      description: Once the MCP Bridge loads, you'll see HubSpot and its tools listed in the window.
      image: "/assets/images/marketing/local-mcp-hero.png"
      bullets:
        - Remember to add your Local MCP Bridge to the list of MCP Servers in your knowledge base.
      button:
        text: Learn about Local MCP Bridge...
        url: /mcp-servers/local-mcp

show_workflow_library: false

cta:
  title: Connect Using MCP Today
  description: Unlock powerful automations through HubSpot's future MCP integration.
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10os0gxZrUbzNEIvQZUJqLWVeGM"
---