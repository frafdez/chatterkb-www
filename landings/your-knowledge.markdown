---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: landings/side-by-side
image: ./assets/images/ckb-card-kb.png

hero:
  title: "Your Knowledge, Your Audience, Your Way"
  description: "Keep sensitive business data private or engage your audience 24/7. Unlike ChatGPT, ChatterKB is built around YOUR expertise."
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
  title: "Smart Solutions for Your Knowledge Needs"
  for_teams:
    title: "For Teams: Private Knowledge Hubs"
    tagline: "Keep business information secure, accessible, and actionable."
    description: "Store your research, competitive analysis, and campaign data in a private, searchable hub that delivers exact insights when you need them—without exposing your data to public AI models."
    key_benefit: "Make faster decisions with confidential data that stays private and secure."
    icon: bi-file-earmark-text
    image: /assets/images/template/content/team-dashboard.webp
    cta:
      text: Start Your Knowledge Hub
      url:  "https://app.chatterkb.com/auth/signup"
  for_creators:
    title: "For Creators: Expand Your Reach"
    tagline: "Engage your audience while you sleep, create, or focus on growth."
    description: "Turn your content and expertise into an interactive knowledge base that engages your audience 24/7—answering questions in your authentic voice while you work on what matters most."
    key_benefit: "Scale your impact without scaling your time commitment."
    icon: bi-people
    image: /assets/images/template/content/creator-kb.webp
    cta:
      text: Grow Your Audience
      url:  "https://app.chatterkb.com/auth/signup"

problems:
  section_title: "Benefits"
  title: "Two Solutions, One Powerful Platform"
  description: "ChatterKB delivers specialized value for both privacy-focused teams and audience-building creators."
  bifurcated: true
  for_teams:
    title: "For Teams"
    benefits:
      - title: "Keep Sensitive Data Private"
        description: "Your business intelligence never trains public AI models—maintaining your competitive edge and data security."
        icon: "bi-shield-lock"
      - title: "Find Exact Information Fast"
        description: "Every insight comes with precise citations to source—no more hunting through endless files or spreadsheets."
        icon: "bi-check-circle"
      - title: "Uncover Hidden Insights"
        description: "Connect dots across campaigns, research, and analytics that would be missed by manual review."
        icon: "bi-diagram-3"
      - title: "Build Reportable Intelligence"
        description: "Create presentation-ready decks with verifiable data that leadership and clients can trust."
        icon: "bi-graph-up-arrow"
    image: /assets/images/template/content/team-benefits.webp
  for_creators:
    title: "For Creators"
    benefits:
      - title: "Scale Your Audience Reach"
        description: "Engage thousands simultaneously with interactive content that feels personal to each follower."
        icon: "bi-megaphone"
      - title: "Eliminate Repetitive Questions"
        description: "Let your knowledge base handle common queries while you focus on creating premium content."
        icon: "bi-clock"
      - title: "Discover What Your Audience Wants"
        description: "See exactly what questions your followers are asking to guide your content strategy."
        icon: "bi-lightbulb"
      - title: "Monetize Your Expertise"
        description: "Create premium tiers of access to your knowledge base, transforming expertise into revenue."
        icon: "bi-cash-coin"
    image: /assets/images/template/content/creator-benefits.webp

how_it_works:
  section_title: How It Works
  title: "Easy Setup for Both Privacy & Publicity"
  description: "Whether you're protecting business insights or amplifying your voice, getting started is simple."
  for_teams:
    title: "For Teams"
    steps:
      - title: "Upload Your Documents"
        description: "Add reports, campaigns, and research with enterprise security."
        icon: bi-upload
      - title: "Ask Natural Questions"
        description: "Get precise answers with exact page & paragraph references."
        icon: bi-chat-dots
      - title: "Save Key Insights"
        description: "Pin findings to create shareable dashboards and reports."
        icon: bi-pin-angle
      - title: "Share Selectively"
        description: "Control exactly who sees what within your organization."
        icon: bi-share
    image: /assets/images/template/content/team-workflow.webp
  for_creators:
    title: "For Creators"
    steps:
      - title: "Add Your Content"
        description: "Import your blog posts, videos, newsletters, or courses."
        icon: bi-upload
      - title: "Define Your Voice"
        description: "Customize how your AI responds to maintain your authentic tone."
        icon: bi-palette
      - title: "Share With Your Audience"
        description: "Give followers a link to interact with your knowledge base."
        icon: bi-link-45deg
      - title: "Grow While You Create"
        description: "Analyze questions to guide content while your AI handles engagement."
        icon: bi-chat-dots
    image: /assets/images/template/content/creator-workflow.webp

# video:
#   url: "https://chatterkb.s3.us-east-1.amazonaws.com/chatterkb-hero-video.m4v"
#   type: "html5"
#   poster: /assets/images/template/content/hero-app-video.webp
#   container_class: "pb-5 px-4"

features:
  section_title: Features
  title: "Versatile Tools for Different Goals"
  description: "Whether you need privacy or publicity, ChatterKB adapts to your specific needs"
  items:
    - icon: bi-chat-dots
      title_highlight: Smart
      title_suffix: Knowledge Assistant
      description: "Get clear, accurate answers about your content with source citations—whether you're researching internally or engaging externally."
      image: /assets/images/template/content/feature-chat.webp
    - icon: bi-pin-angle
      title_highlight: Insight
      title_suffix: Collections
      description: "Organize key findings into structured dashboards that transform scattered information into actionable intelligence."
      image: /assets/images/template/content/feature-pin.webp
    - icon: bi-share
      title_highlight: Flexible
      title_suffix: Sharing
      description: "Keep knowledge private for business use or publish it widely for audience engagement—you control the visibility."
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
  # cta:
  #   text: "See All Integrations"
  #   url: "https://app.chatterkb.com/integrations"

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
  title: "Affordable Plans for Growth & Engagement"
  description: "Whether you're just starting out or running an established business, we have options that scale with your needs."
  plans:
    - name: "Free"
      description: "For individuals getting started"
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
      description: "For serious content creators and businesses"
      price: "$20"
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
  title: "Transform Your Knowledge Into Impact"
  description: "Whether you need to protect business insights or amplify your voice, ChatterKB is your solution."
  button:
    text: "Get Started Free"
    url: "https://app.chatterkb.com/auth/signup"
---