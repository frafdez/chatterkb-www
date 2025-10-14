---
layout: feature
sitemap:
  exclude: 'no'
order: 50
server_type: local

description: "Connect your Airtable data using Model Context Protocol."
title: Airtable MCP Server
hero:
  title: Airtable MCP Server
  description: Connect your Airtable data using Model Context Protocol.
  image: /assets/images/marketing/airtable-mcp-server-hero.png
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"

features:
  section_title: Local MCP Bridge
  title: Connecting to Airtable
  items:
    - side: left
      title: Setting Up Your Airtable Integration
      description: To get started, you'll need to create a personal access token in your Airtable account.
      image: /assets/images/marketing/airtable-mcp-server-step-1.png # Placeholder image
      bullets:
        - Visit [Airtable Developer Hub](https://airtable.com/developers/web/api/introduction) and sign in to your account
        - Navigate to your **Account Settings** by clicking on your profile picture
        - Go to the **Developer** tab in the left sidebar
        - Click on **Personal access tokens**
        - Click **Create new token** button
        - Give your token a descriptive name (e.g., "MCP Integration")
        - Select the scopes you need (typically **data.records:read** and **data.records:write**)
        - Choose the specific bases you want to grant access to
        - Click **Create token** and copy the generated token immediately
        - Store this token securely as you won't be able to see it again
      button:
        text: Create Your Personal Access Token
        url: https://airtable.com/create/tokens
    - side: right
      title: Update Your Local MCP Bridge
      description: You'll need to add an entry into the mcp-config.json file.
      code: |
        {
          "mcpServers": {
            "airtable": {
            "command": "npx",
            "args": [
                "-y",
                "airtable-mcp-server"
            ],
            "env": {
                "AIRTABLE_API_KEY": "your_airtable_token"
            }
          }
        }
      bullets:
        - Run the [MCP Bridge](/mcp-servers/local-mcp)
        - Locate the config file
        - Add the entry for Airtable. You'll need to replace *your_airtable_token* with the personal access token you created in the previous step.
      
    - side: left
      title: Restart the Local MCP Bridge
      description: Once the MCP Bridge loads, you'll see Airtable and its tools listed in the window.
      image: "/assets/images/marketing/local-mcp-hero.png"
      bullets:
        - Remember to add your Local MCP Bridge to the list of MCP Servers in your knowledge base.
      button:
        text: Learn about Local MCP Bridge...
        url: /mcp-servers/local-mcp

show_workflow_library: false

cta:
  title: Connect Using MCP Today
  description: Unlock powerful database insights through Airtable MCP integration.
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"
--- 