---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: side-by-side
image: ./assets/images/ckb-card-kb.png

hero:
  title: "Unlock the Power of Your Knowledge with AI"
  description: "Chat with your documents, extract insights, and share your expertise interactively—all in one seamless platform."
  split_screen:
    left_image: /assets/images/template/content/team-chat-document.webp
    left_label: For Teams
    right_image: /assets/images/template/content/creator-knowledge-base.webp
    right_label: For Creators
  button:
    text: Get Started Free
    url:  "https://app.chatterkb.com/auth/signup"
  link:
    text: Learn more
    url: "#features-overview"

features_overview:
  section_title: Overview
  title: "Two Powerful Solutions in One Platform"
  for_teams:
    title: "For Teams: Turn Documents into Actionable Reports"
    tagline: "Analyze, collaborate, and share—faster than ever."
    description: "Upload your docs, chat to uncover insights, and generate real-time reports your team can act on."
    key_benefit: "Cut analysis time in half and keep everyone aligned."
    icon: bi-file-earmark-text
    image: /assets/images/template/content/team-dashboard.webp
    cta:
      text: Start Analyzing Now
      url:  "https://app.chatterkb.com/auth/signup"
  for_creators:
    title: "For Creators: Share Your Knowledge Interactively"
    tagline: "Engage your audience 24/7 with AI."
    description: "Turn your content into an interactive knowledge base where followers ask questions and explore insights."
    key_benefit: "Boost engagement and monetize your expertise."
    icon: bi-people
    image: /assets/images/template/content/creator-kb.webp
    cta:
      text: Build Your Knowledge Base
      url:  "https://app.chatterkb.com/auth/signup"

problems:
  section_title: "Benefits"
  title: "Why You'll Love It"
  description: "Tailored solutions for both teams analyzing documents and creators sharing knowledge."
  bifurcated: true
  for_teams:
    title: "For Teams"
    benefits:
      - title: "Cut Analysis Time in Half"
        description: "Extract insights from lengthy documents in minutes instead of hours."
        icon: "bi-clock-history"
      - title: "Uncover Hidden Connections"
        description: "Discover relationships between documents that manual review might miss."
        icon: "bi-diagram-3"
      - title: "Collaborate Seamlessly"
        description: "Share insights and reports with your team in real-time."
        icon: "bi-people"
      - title: "Make Data-Driven Decisions"
        description: "Turn document insights into actionable business intelligence."
        icon: "bi-graph-up-arrow"
    image: /assets/images/template/content/team-benefits.webp
  for_creators:
    title: "For Creators"
    benefits:
      - title: "Answer Questions 24/7"
        description: "Let your audience find answers without waiting for a reply—freeing you from repetitive messages."
        icon: "bi-clock"
      - title: "Boost Engagement"
        description: "Transform casual subscribers into active participants who keep coming back for more."
        icon: "bi-hand-thumbs-up"
      - title: "Gain Audience Insights"
        description: "See what people are really asking about, so you can tailor future content to their biggest needs."
        icon: "bi-lightbulb"
      - title: "Monetize Your Expertise"
        description: "Offer premium access or subscription tiers, turning your knowledge base into a revenue stream."
        icon: "bi-cash-coin"
    image: /assets/images/template/content/creator-benefits.webp

how_it_works:
  section_title: How It Works
  title: "Your Knowledge, Powered by AI—In 4 Simple Steps"
  description: "Getting started is easy, whether you're a team analyzing documents or a creator sharing expertise."
  for_teams:
    title: "For Teams"
    steps:
      - title: "Upload"
        description: "Drag and drop your documents."
        icon: bi-upload
      - title: "Chat"
        description: "Ask questions and get instant answers."
        icon: bi-chat-dots
      - title: "Pin"
        description: "Highlight key insights for reports."
        icon: bi-pin-angle
      - title: "Share"
        description: "Collaborate with real-time updates."
        icon: bi-share
    image: /assets/images/template/content/team-workflow.webp
  for_creators:
    title: "For Creators"
    steps:
      - title: "Upload"
        description: "Add your articles, videos, or notes."
        icon: bi-upload
      - title: "Customize"
        description: "Tailor the look and feel."
        icon: bi-palette
      - title: "Share"
        description: "Send a link to your audience."
        icon: bi-link-45deg
      - title: "Engage" 
        description: "Answer questions via AI, anytime."
        icon: bi-chat-dots
    image: /assets/images/template/content/creator-workflow.webp

# video:
#   url: "https://chatterkb.s3.us-east-1.amazonaws.com/chatterkb-hero-video.m4v"
#   type: "html5"
#   poster: /assets/images/template/content/hero-app-video.webp
#   container_class: "pb-5 px-4"

features:
  section_title: Features
  title: "Powerful Features for Teams and Creators"
  description: "Everything you need to analyze documents and share knowledge effectively"
  items:
    - icon: bi-chat-dots
      title_highlight: Chat
      title_suffix: with Your Data
      description: "Ask questions in plain language and get instant, accurate answers based on your documents."
      image: /assets/images/template/content/feature-chat.webp
    - icon: bi-pin-angle
      title_highlight: Pin
      title_suffix: Important Insights
      description: "Save key findings and organize them into shareable dashboards and reports."
      image: /assets/images/template/content/feature-pin.webp
    - icon: bi-share
      title_highlight: Share
      title_suffix: Knowledge Seamlessly
      description: "Collaborate with your team or audience through interactive knowledge bases."
      image: /assets/images/template/content/feature-share.webp

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
# testimonials:
#   section_title: Testimonials
#   title: "Trusted by Teams and Creators Like You"
#   items:
#     - name: "Sarah T."
#       title: "Project Manager"
#       quote: "ChatterKB turned our 50-page reports into actionable insights in minutes. It's a game-changer."
#       type: "team"
#       image: /assets/images/template/testimonials/user1.webp
#     - name: "Mark R."
#       title: "Content Creator"
#       quote: "My subscribers love asking questions on my knowledge base. Engagement is up 40%!"
#       type: "creator"
#       image: /assets/images/template/testimonials/user2.webp
#   logos:
#     title: "Integrates with your favorite tools"
#     items:
#       - name: "Slack"
#         image: /assets/images/template/logos/slack.svg
#       - name: "Google Drive"
#         image: /assets/images/template/logos/google-drive.svg
#       - name: "Notion"
#         image: /assets/images/template/logos/notion.svg
#       - name: "Microsoft Teams"
#         image: /assets/images/template/logos/ms-teams.svg

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
  title: "Ready to Transform Your Knowledge?"
  description: "Join thousands of teams and creators using ChatterKB today."
  button:
    text: "Get Started Free"
    url: "https://app.chatterkb.com/auth/signup"

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
---