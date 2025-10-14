---
layout: feature
sitemap:
  exclude: 'no'
order: 40
server_type: local

description: "Connect your Google Analytics data using Model Context Protocol."
title: Google Analytics MCP Server
hero:
  title: Google Analytics MCP Server
  description: Connect your Google Analytics data using Model Context Protocol.
  image: /assets/images/marketing/ga4-mcp-server-hero.webp
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"

features:
  section_title: Local MCP Bridge
  title: Connecting to Google Analytics (GA4)
  items:
    - side: left
      title: Setting Up Your Google Analytics (GA4)
      description: To get started, you'll need to create service accounts with Google Cloud Console.
      image: /assets/images/marketing/ga4-mcp-server-step-1.png # Placeholder image
      bullets:
        - Visit [Google Cloud Console](https://console.cloud.google.com/) and create an account
        - In the search bar (at the top of the page), type **API Library** and select the **Library** item
        - Then, in the **Search for APIs & Services**, search for **Google Analytics**
        - Next, locate and enable both...
          - **Google Analytics Admin API**
          - **Google Analytics Data API**
        - Then, go back to the search bar (it may be hidden and look like a <i class="bi bi-search"></i>)
        - Search for **Service Accounts**
        - Create a service account by following the steps
        - Assign either **Owner** or **Viewer** as its **Role**
        - You'll notice that the service account has an email address. Jot it down.
        - When done, select the account and scroll to the right to find the **Actions** column
        - Click on **Manage Keys**
        - Click on the **Add key** button
        - Select JSON and create it. This will download a file that you will need later.
        - Now, visit Google Analytics and add the email of the service account as an authorized user.
        - Phew! You're now set up with your credentials
      button:
        text: Visit Google Cloud Console
        url: https://console.cloud.google.com/
    - side: right
      title: Update Your Local MCP Bridge
      description: You'll need to add an entry into the mcp-config.json file.
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
      bullets:
        - Run the [MCP Bridge](/mcp-servers/local-mcp)
        - Locate the config file
        - Add the entry for Google Analytics. You'll need to replace *PATH_TO_ADC_JSON* with the path to the JSON file that you previously downloaded.
      
    - side: left
      title: Restart the Local MCP Bridge
      description: Once the MCP Bridge loads, you'll see Google Analytics and its tools listed in the window.
      image: "/assets/images/marketing/local-mcp-hero.png"
      bullets:
        - Remember to add your Local MCP Bridge to the list of MCP Servers in your knowledge base.
      button:
        text: Learn about Local MCP Bridge...
        url: /mcp-servers/local-mcp

show_workflow_library: false

cta:
  title: Connect Using MCP Today
  description: Unlock powerful analytics insights through Google Analytics MCP integration.
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
---
