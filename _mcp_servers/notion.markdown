---
layout: marketing-feature
sitemap:
  exclude: 'no'
order: 1
description: "Connect your Notion pages using Model Context Protocol."
title: Notion MCP Server
hero:
  title: Notion MCP Server
  description: Connect your Notion pages using Model Context Protocol.
  image: /assets/images/marketing/notion-mcp-server-herp.png
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"

features:
  section_title: Local MCP Bridge
  title: Connecting to Notion
  items:
    - side: left
      title: Setting Up Your Notion Integration
      description: The first thing to do is to set up your integration
      image: /assets/images/marketing/notion-mcp-server-github.jpg
      bullets:
        - Visit [Notion MCP Server](https://github.com/makenotion/notion-mcp-server#readme) on GitHub for details
        - Then create your Notion Integration by clicking on the button below
      button:
        text: Create a Notion Integration
        url: https://www.notion.so/profile/integrations
    - side: right
      title: Update Your Local MCP Bridge
      description: You'll need to add an entry into the mcp-config.json file
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
      bullets:
        - Run the [MCP Bridge](/mcp-servers/local-mcp)
        - Locate the config file
        - Add the entry for Notion (remember to replace the ntn***)
      
    - side: left
      title: Restart the Local MCP Bridge
      description: Once the MCP Bridge loads, you'll see Notion and its tools listed in the window
      image: "/assets/images/marketing/local-mcp-hero.png"
      bullets:
        - Remember to add your Local MCP Bridge to the list of MCP Servers in your knowledge base
      button:
        text: Learn about Local MCP Bridge...
        url: /mcp-servers/local-mcp




show_workflow_library: false

cta:
  title: Connect Using MCP Today
  description: Unlock powerful automations through Notion's MCP integration.
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10os0gxZrUbzNEIvQZUJqLWVeGM"
---