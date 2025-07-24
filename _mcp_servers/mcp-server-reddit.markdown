---
layout: marketing-feature
sitemap:
  exclude: 'no'
order: 50
server_type: local

title: MCP Server Reddit
description: "Connect to Reddit using Model Context Protocol."

hero:
  title: mcp-server-reddit
  description: Connect to Reddit using Model Context Protocol.
  image: /assets/images/marketing/mcp-server-reddit-hero.png
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"

features:
  section_title: Local MCP Bridge
  title: Connecting to Reddit
  items:
    - side: left
      title: Register an App with Reddit
      description: Visit Reddit's developer portal and register an app
      image: /assets/images/marketing/mcp-server-reddit-step-1.webp
      bullets:
        - Click on the button to visit the apps page
        - Create an app and copy the app's **id** and **secret**
      button:
        text: Create a Reddit App
        url: https://www.reddit.com/prefs/apps

    - side: right
      title: Install the server using Python
      description: Ensure that you have Python installed and run this command
      code: |
        pip install mcp-server-reddit


    - side: left
      title: Update Your Local MCP Bridge
      description: You'll need to add an entry into the mcp-config.json file
      code: |
        {
          "mcpServers": {
            "mcp-server-reddit": {
              "description": "A Reddit MCP Server",
              "command": "/Users/my-login/opt/anaconda3/envs/test-mcp-4/bin/python",
              "args": [
                "-m",
                "mcp_server_reddit"
              ],
              "envs": {
                "REDDIT_CLIENT_ID": "123***",
                "REDDIT_CLIENT_SECRET": "123***"
              }
            }
          }
        }
      bullets:
        - Run the [MCP Bridge](/mcp-servers/local-mcp)
        - Locate the config file
        - |
          Replace the values with the values provided by Reddit when creating the app
          - **REDDIT_CLIENT_ID**
          - **REDDIT_CLIENT_SECRET**
        - |
         **IMPORTANT**: *You may need to specify the full path to your Python file as shown in the example*
      
    - side: right
      title: Restart the Local MCP Bridge
      description: Once the MCP Bridge loads, you'll see Reddit and its tools listed in the window
      image: "/assets/images/marketing/local-mcp-hero.png"
      bullets:
        - Remember to add your Local MCP Bridge to the list of MCP Servers in your knowledge base
      button:
        text: Learn about Local MCP Bridge...
        url: /mcp-servers/local-mcp




show_workflow_library: false

cta:
  title: Connect Using MCP Today
  description: Unlock powerful automations through Reddit's MCP integration.
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10os0gxZrUbzNEIvQZUJqLWVeGM"
---

This MCP server is a community server available at [PyPi.org](https://pypi.org/project/mcp-server-reddit) called mcp-server-reddit and developed by Hawstein. You can review the code at [https://github.com/Hawstein/mcp-server-reddit](https://github.com/Hawstein/mcp-server-reddit)