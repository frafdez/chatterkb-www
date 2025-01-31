---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

sitemap:
  exclude: 'yes'

layout: home
hero:
  title: Chat with your documents and share insights.
  description: Use AI to find insights in your documents and turn them into reports that you can share with your team and clients.
  offer:
    text: Get 20% off yearly plans
    url: "https://app.chatterkb.com/checkout/yearly"
  button:
    text: Get Started For Free
    url: "https://app.chatterkb.com/checkout/plans"
  link:
    text: Learn more
    url: "#features"
features:
  section_title: Features
  title: Upload. Chat. Pin.
  description: Turn Conversations into Actionable Insights—Effortlessly
  items:
    - icon: bi-upload
      title_highlight: Upload
      title_suffix: Your Files
      description: Simply upload your files to create a knowledge base you can chat with. No technical setup—just drag, drop, and let AI provide insights from your own data.
    - icon: bi-chat
      title_highlight: Chat
      title_suffix: with Your Data
      description: Engage in natural conversations with AI powered by your own files. Simply ask questions to get instant insights and answers directly from your personalized knowledge base.
    - icon: bi-pin-angle
      title_highlight: Pin
      title_suffix: and Share Important Insights
      description: Transform your conversations into visual tables and charts for a clearer understanding of your data. Pin these insights to a board you can share with your team or clients, making collaboration effortless.

additional_features:
  section_title: Additional Features
  title: More than just a chatbot
  description: Chat with your files, create dashboards, and more.
  items:
    - icon: bi-speedometer  
      col_type: col-md-6        
      title: Dynamic Dashboards
      description: Create dynamic dashboards to visualize your data and share with your team.
    - icon: bi-flag
      col_type: col-md-6
      title: Updating files updates reports
      description: Refresh your board with the latest data to provide the most accurate insights.
    - icon: bi-sliders
      col_type: col-md-6
      title: Customizable
      description: Customize your board with the tools you need to create the perfect visualizations.
    - icon: bi-share
      col_type: col-md-6
      title: Shareable
      description: Share your board with your team or clients to collaborate on the most important insights.

smbs:
  section_title: Benefits
  title: Here's How Our Platform Empowers You
  items:
    - title: "Upload your financial statements"
      tab_title: Finance
      description: Imagine uploading your quarterly financial statements and, within seconds, generating a comparative analysis of your revenue growth.
      style: left
      outline_class: border-warning border-opacity-50
      background_image: /assets/images/template/finance/tab-bg-1.svg
      foreground_image: /assets/images/template/finance/tab-g-1.png
      main_image: /assets/images/template/finance/tab.jpg
      points:
        - icon: bi-chat-fill
          color_class: text-primary
          title: Chat with your data
          description: "What was our total revenue growth in Q4 compared to Q3?"
        - icon: bi-graph-up-arrow
          color_class: text-success
          title: Instant insights
          description: Pin this chart to your 'Quarterly Financials' board and share it with stakeholders instantly.
    
    - title: Optimize Your E-commerce Operations
      tab_title: Ecommerce
      description: Imagine uploading your sales data and inventory levels, and within seconds, pinpointing which products are flying off the shelves but are low in stock.
      style: right
      outline_class: border-info border-opacity-50
      background_image: ./assets/images/template/ecommerce/tab-bg-1.svg
      foreground_image: ./assets/images/template/ecommerce/tab-g-1.png
      main_image: ./assets/images/template/ecommerce/tab.jpg
      points:
        - icon: bi-chat-fill
          color_class: text-primary
          outline_class: border-warning
          title: Chat with your data
          description: "Which products are low in stock but high in demand?"
        - icon: bi-currency-exchange
          color_class: text-success
          title: Instant insights
          description: Pin this table to your 'Restock Priorities' board and keep your procurement team in the loop.

    - title: Transform Marketing Data into Actionable Visuals Instantly
      tab_title: Marketing
      description: Imagine uploading your latest campaign data and instantly generating a comprehensive ROI analysis.
      style: left
      outline_class: border-success border-opacity-50
      background_image: ./assets/images/template/marketing/tab-bg-1.svg
      foreground_image: ./assets/images/template/marketing/tab-g-1.png
      main_image: ./assets/images/template/marketing/tab.jpg
      points:
        - icon: bi-chat-fill
          color_class: text-primary
          title: Chat with your data
          description: "Generate a chart comparing the ROI of all campaigns in the last six months."
        - icon: bi-currency-exchange
          color_class: text-success
          title: Instant insights
          description: Pin this chart to your 'Campaign Performance' board and impress your clients with real-time insights.

    - title: Elevate Your Startup's Project Management
      tab_title: Tech Startups
      description: Imagine uploading your project plans and timelines, and within seconds, gaining a clear overview of upcoming milestones and resource allocations.
      style: right
      outline_class: border-secondary border-opacity-50
      background_image: ./assets/images/template/tech/tab-bg-1.svg
    #   foreground_image: ./assets/images/template/tech/tab-g-1.png
      main_image: ./assets/images/template/tech/tab.jpg
      points:
        - icon: bi-chat-fill
          color_class: text-primary
          title: Chat with your data
          description: "What are the upcoming milestones for Project Alpha in the next two weeks?"
        - icon: bi-currency-exchange
          color_class: text-success
          title: Instant insights
          description: Pin this to your 'Project Alpha Dashboard' and keep your development team aligned and focused.

      
---
