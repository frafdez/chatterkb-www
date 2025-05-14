---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home-video

sitemap:
  exclude: 'yes'

# Page content follows below
hero:
  title: "Your Creative Brain, Supercharged by AI"
  description: "Turn scattered decks, docs, and threads into instant answers, reports, and dashboards. All from one chat. Ask questions. Pin insights. Automate your workflows."
  video:
    url: "https://chatterkb.s3.us-east-1.amazonaws.com/chatterkb-hero-video.m4v"
    type: "html5"
    poster: "/assets/images/template/content/hero-app-video.webp"
  container_class: "pb-5 px-4"
  offer:
    text: "Get 20% off yearly plans"
    url: "https://app.chatterkb.com/checkout/yearly"
  button:
    text: "Get Started for Free"
    url: "https://app.chatterkb.com/checkout/plans"
  link:
    text: "See how it works"
    url: "#problems"

problems:
  section_title: "Why ChatterKB"
  items:
    - section_title: "Manual Work"
      title: "Still digging through docs?"
      description: "From Slack to Sheets to Slides, your team's best insights are lost in the noise. Finding what matters shouldn't take hours."
      image: "/assets/images/template/content/manual-work.jpg"
      side: "left"
    - section_title: "Information Overload"
      title: "Too much data, too little clarity"
      description: "Marketing reports. Campaign results. Strategy docs. They're everywhere but rarely where you need them when you need them."
      image: "/assets/images/template/content/information-overload.jpg"
      side: "right"
    - section_title: "Collaboration Gaps"
      title: "Insights stuck in silos"
      description: "Even when you find something great, sharing it means screenshots, email threads, or another tool. Let AI do the organizing."
      image: "/assets/images/template/content/collaboration-bottlenecks.jpg"
      side: "left"

solution:
  title: "Ask. Analyze. Act. All in One Chat."
  description: "Upload your files. Ask questions. Pin what matters. Share it instantly. Soon, you'll be able to generate workflows from plain language, turning insights into action automatically."
  button:
    text: "Try ChatterKB Free"
    url: "https://app.chatterkb.com/checkout/plans"

# video:
#   url: "https://chatterkb.s3.us-east-1.amazonaws.com/chatterkb-hero-video.m4v"
#   type: "html5"
#   poster: "/assets/images/template/content/hero-app-video.webp"
#   container_class: "pb-5 px-4"

features:
  section_title: "Features"
  title: "Upload. Chat. Pin. Share."
  description: "Everything you need to go from knowledge to action, faster than ever."
  items:
    - icon: "bi-upload"
      title_highlight: "Upload"
      title_suffix: "your docs"
      description: "Drag and drop any doc or slide deck. Connect Google Drive, Notion, Slack, or YouTube transcripts. ChatterKB builds your AI-ready knowledge base."
      image: "/assets/images/template/content/feature-1.webp"
    - icon: "bi-chat"
      title_highlight: "Ask"
      title_suffix: "in plain English"
      description: "Don't search, just ask. Find insights, write summaries, or get answers from your files in seconds. Like ChatGPT, but trained on your stuff."
      image: "/assets/images/template/content/feature-2b.webp"
    - icon: "bi-pin-angle"
      title_highlight: "Pin"
      title_suffix: "to dashboards"
      description: "Turn answers into visuals. Pin tables, scorecards, or writeups to team dashboards you can share or make public-facing in one click."
      image: "/assets/images/template/content/feature-3.webp"

additional_features:
  section_title: "Coming Soon: Workflows"
  title: "Your Knowledge, on Autopilot"
  description: "Automate your most common knowledge tasks by simply writing them in plain language. No nodes. No code. Just intent -> action."
  items:
    - icon: "bi-lightning-charge"
      col_type: "col-md-6"
      title: "Natural language automation"
      description: "Say what you want done: 'Write a content brief using last month's data' and watch the steps generate in real-time."
    - icon: "bi-journal-code"
      col_type: "col-md-6"
      title: "Reproducible workflows"
      description: "Save workflows for recurring tasks like campaign reviews, client reports, and competitor analysis."
    - icon: "bi-box-arrow-down"
      col_type: "col-md-6"
      title: "Plug into your process"
      description: "Trigger workflows from new files, new campaigns, or new Slack threads. Connect to external apps via API or Zapier."
    - icon: "bi-graph-up"
      col_type: "col-md-6"
      title: "Actionable + measurable"
      description: "Each workflow step is tracked. Soon, you'll be able to see what's working and what's getting stuck right from your dashboard."

smbs:
  section_title: "Who It's For"
  title: "ChatterKB Works Across Teams"
  items:
    - title: "Make Your Marketing Click"
      tab_title: "Marketing"
      description: "Launch a knowledge base with campaign assets, brand voice, and reports. Generate insights instantly, pin your best performing ideas, and share them with your team or clients."
      style: "left"
      outline_class: "border-success border-opacity-50"
      background_image: "/assets/images/template/marketing/tab-bg-1.svg"
      main_image: "/assets/images/template/marketing/tab.jpg"
      points:
        - icon: "bi-bullseye"
          color_class: "text-primary"
          title: "Analyze creative performance"
          description: "What's the best-performing copy variation for our ad set last week?"
        - icon: "bi-pie-chart-fill"
          color_class: "text-success"
          title: "Build shareable dashboards"
          description: "Turn chat into charts, pin to a 'Client Results' board, and keep everyone aligned."

    - title: "Stay On Top of Your Store"
      tab_title: "Ecommerce"
      description: "Turn your inventory, sales, and marketing data into a living dashboard that answers questions and alerts your team when action is needed."
      style: "right"
      outline_class: "border-info border-opacity-50"
      background_image: "/assets/images/template/ecommerce/tab-bg-1.svg"
      main_image: "/assets/images/template/ecommerce/tab.jpg"
      points:
        - icon: "bi-bar-chart-steps"
          color_class: "text-primary"
          title: "Product insights"
          description: "Which SKUs are low on stock but trending in sales?"
        - icon: "bi-share-fill"
          color_class: "text-success"
          title: "Share it with ops"
          description: "Pin to your 'Reorder Board' and send a Slack alert to the buyer team."

    - title: "Financial Clarity, Fast"
      tab_title: "Finance"
      description: "Upload your statements and get instant comparisons, trend graphs, and variance analysis. Chat with your financials, not just your accountant."
      style: "left"
      outline_class: "border-warning border-opacity-50"
      background_image: "/assets/images/template/finance/tab-bg-1.svg"
      main_image: "/assets/images/template/finance/tab.jpg"
      points:
        - icon: "bi-bar-chart-fill"
          color_class: "text-primary"
          title: "Ask questions directly"
          description: "How did our Q4 EBITDA compare to last year?"
        - icon: "bi-journal-arrow-up"
          color_class: "text-success"
          title: "Create visual reports"
          description: "Pin to the CFO board and export as a client report in seconds."

    - title: "Empower Your Product Team"
      tab_title: "Tech Startups"
      description: "From user interviews to roadmap decks, let your team ask questions, surface insights, and automate reporting. All from one chat-based hub."
      style: "right"
      outline_class: "border-secondary border-opacity-50"
      background_image: "/assets/images/template/tech/tab-bg-1.svg"
      main_image: "/assets/images/template/tech/tab.jpg"
      points:
        - icon: "bi-terminal"
          color_class: "text-primary"
          title: "Get instant clarity"
          description: "What features did users mention most often in feedback this week?"
        - icon: "bi-kanban"
          color_class: "text-success"
          title: "Keep teams aligned"
          description: "Pin to the 'Feedback Radar' and use it in sprint planning."

cta:
  title: "Stop Searching. Start Chatting with Your Knowledge."
  description: "Sign up for a free account. No credit card, no setup, no noise."
  button:
    text: "Get Started Free"
    url: "https://app.chatterkb.com/checkout/plans"
---
