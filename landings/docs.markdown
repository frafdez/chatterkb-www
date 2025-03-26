---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: landings/ad
sitemap:
  exclude: 'yes'

hero:
  title: Turn your documents into actionable reports
  description: Chat with your documents to find hidden insights and turn them into reports that you can share with your team and clients.
  # image: /assets/images/template/content/hero-app-screen.webp
  # image_left: /assets/images/template/content/hero-frame-left.webp
  video:
    url: "https://chatterkb.s3.us-east-1.amazonaws.com/chatterkb-hero-video.m4v"
    type: "html5"
    poster:  /assets/images/template/content/hero-app-video.webp

  container_class: "pb-5 px-4"
  offer:
    text: Get 20% off yearly plans
    url: "https://app.chatterkb.com/checkout/yearly"
  button:
    text: Try It For Free
    url: "https://app.chatterkb.com/auth/signup"
  link:
    text: Learn more
    url: "#problems"

problems:
  section_title: "Problems"
  items:
    - section_title: "Work Automation"
      title: "Wasting Time on Manual Work"
      description: "Sifting through countless documents to find what matters is tedious and time-consuming. Every hour spent scrolling is an hour not spent acting on insights."
      image: /assets/images/template/content/manual-work.jpg
      side: left
    - section_title: "Data Clarity"
      title: "Overwhelmed by Information Overload"
      description: "From reports to presentations, the sheer volume of information makes it easy to miss critical details, slowing down decision-making and impacting results."
      image: ./assets/images/template/content/information-overload.jpg
      side: right
    - section_title: "Simplified Collaboration"
      title: "Collaboration Bottlenecks"
      description: "Sharing insights with your team often involves multiple tools, confusing email chains, and endless revisions – not to mention wasted effort recreating reports."
      image: ./assets/images/template/content/collaboration-bottlenecks.jpg
      side: left

solution:
  title: "Finally, a Smarter Way to Handle Your Documents"
  description: "Use AI to find insights in your documents and turn them into reports that you can share with your team and clients."
  button:
    text: Try It For Free
    url: "https://app.chatterkb.com/auth/signup"

# video:
#   url: "https://chatterkb.s3.us-east-1.amazonaws.com/chatterkb-hero-video.m4v"
#   type: "html5"
#   poster:  /assets/images/template/content/hero-app-video.webp
#   container_class: "pb-5 px-4"

features:
  section_title: Features
  title: Upload. Chat. Pin.
  description: Turn Conversations into Actionable Insights—Effortlessly
  items:
    - icon: bi-upload
      title_highlight: Upload
      title_suffix: Your Files
      description: Simply upload your files to create a knowledge base you can chat with. No technical setup—just drag, drop, and let AI provide insights from your own data. 
      image: /assets/images/template/content/feature-1.webp
    - icon: bi-chat
      title_highlight: Chat
      title_suffix: with Your Data
      description: Engage in natural conversations with AI powered by your own files. Simply ask questions to get instant insights and answers directly from your personalized knowledge base.
      image: /assets/images/template/content/feature-2b.webp
    - icon: bi-pin-angle
      title_highlight: Pin
      title_suffix: and Share Important Insights
      description: Transform your conversations into visual tables and charts for a clearer understanding of your data. Pin these insights to a board you can share with your team or clients, making collaboration effortless.
      image: /assets/images/template/content/feature-3.webp
additional_features:
  section_title: Additional Features
  title: More than just a chatbot
  description: Convert your files into smart, interactive knowledge bases—enabling seamless chat, real-time dashboards, and so much more.
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
    - title: Transform Marketing Data into Actionable Visuals Instantly
      tab_title: Marketing
      description: Imagine uploading your latest campaign data and instantly generating a comprehensive ROI analysis.
      style: left
      outline_class: border-success border-opacity-50
      background_image: /assets/images/template/marketing/tab-bg-1.svg
      # foreground_image: /assets/images/template/marketing/tab-g-1.png
      main_image: /assets/images/template/marketing/tab.jpg
      points:
        - icon: bi-chat-fill
          color_class: text-primary
          title: Chat with your data
          description: "Generate a chart comparing the ROI of all campaigns in the last six months."
        - icon: bi-clipboard-data-fill
          color_class: text-success
          title: Instant insights
          description: Pin this chart to your 'Campaign Performance' board and impress your clients with real-time insights.


    - title: Optimize Your E-commerce Operations
      tab_title: Ecommerce
      description: Imagine uploading your sales data and inventory levels, and within seconds, pinpointing which products are flying off the shelves but are low in stock.
      style: right
      outline_class: border-info border-opacity-50
      background_image: ./assets/images/template/ecommerce/tab-bg-1.svg
      # foreground_image: ./assets/images/template/ecommerce/tab-g-1.png
      main_image: ./assets/images/template/ecommerce/tab.jpg
      points:
        - icon: bi-chat-fill
          color_class: text-primary
          outline_class: border-warning
          title: Chat with your data
          description: "Which products are low in stock but high in demand?"
        - icon: bi-credit-card-2-back-fill
          color_class: text-success
          title: Instant insights
          description: Pin this table to your 'Restock Priorities' board and keep your procurement team in the loop.

    - title: Upload your financial statements
      tab_title: Finance
      description: Imagine uploading your quarterly financial statements and, within seconds, generating a comparative analysis of your revenue growth.
      style: left
      outline_class: border-warning border-opacity-50
      background_image: ./assets/images/template/finance/tab-bg-1.svg
      # foreground_image: ./assets/images/template/finance/tab-g-1.png
      main_image: ./assets/images/template/finance/tab.jpg
      points:
        - icon: bi-chat-fill
          color_class: text-primary
          title: Chat with your data
          description: "What was our total revenue growth in Q4 compared to Q3?"
        - icon: bi-graph-up-arrow
          color_class: text-success
          title: Instant insights
          description: Pin this chart to your 'Quarterly Financials' board and share it with stakeholders instantly.
    

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
        - icon: bi-code-square
          color_class: text-success
          title: Instant insights
          description: Pin this to your 'Project Alpha Dashboard' and keep your development team aligned and focused.

integrations:
  section_title: Integrations
  title: "Connect Your Existing Content"
  description: "Seamlessly import from the platforms where your knowledge already lives."
  logos:
    items:
      - name: "Notion"
        image: /assets/images/template/logos/notion.png
        description: "Import your Notion pages and databases directly into ChatterKB."
      - name: "Google Drive"
        image: /assets/images/template/logos/google-drive.png
        description: "Connect your Google Docs, Sheets, and Slides for instant knowledge extraction."
      - name: "More Coming Soon"
        image: /assets/images/template/logos/coming-soon.svg
        description: "We're constantly adding new integrations to make your workflow smoother."

models:
  section_title: AI Models
  title: "Powered by Leading AI Models"
  description: "ChatterKB leverages state-of-the-art language models to deliver accurate, nuanced responses to your questions."
  items:
    - name: "LLama 3.3"
      image: /assets/images/template/logos/llama.png
      description: "Meta's advanced open-source large language model, optimized for performance and efficiency."
      capabilities:
        - "Exceptional reasoning capabilities"
        - "Efficient knowledge retrieval"
        - "Optimized for document analysis"
        - "Open-source foundation"
    - name: "Claude 3.7 Sonnet"
      image: /assets/images/template/logos/claude.png
      description: "Anthropic's powerful AI assistant known for its helpfulness, harmlessness, and honesty."
      capabilities:
        - "Superior contextual understanding"
        - "Nuanced response generation"
        - "Advanced reasoning abilities"
        - "Designed for safety and reliability"

pricing_teaser:
  section_title: Pricing
  title: "Start Free, Scale as You Grow"
  description: "Plans for teams and creators, starting at $0. No credit card required."
  plans:
    - name: "Free"
      description: "For individuals just getting started"
      price: "$0"
      features:
        - "Up to 30 monthly chats"
        - "1 knowledge base"
        - "Subscribe to Creator KBs"
      button:
        text: "Get Started"
        url: "https://app.chatterkb.com/auth/signup"
      highlighted: false
    - name: "Plus"  
      description: "For serious teams and creators"
      price: "$30"
      billing_period: "per month"
      features:
        - "Up to 1000 monthly chats"
        - "3 knowledge bases"
        - "1 GB of storage"
        - "Custom branding"
        - "Analytics dashboard (coming soon)"
        - "Public or Private KBs"
      button:
        text: "Upgrade to Pro"
        url: "https://app.chatterkb.com/checkout/plans"
      highlighted: true
  cta:
    text: "View all pricing options"
    url: "https://app.chatterkb.com/checkout/plans"

cta:
  title: Start Chatting with Your Data Now
  description: Sign up for a free account today — no credit card required.
  button:
    text: Get Started for Free
    url: "https://app.chatterkb.com/auth/signup"
---
