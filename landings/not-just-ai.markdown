---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: landings/side-by-side
image: ./assets/images/ckb-card-kb.png

hero:
  title: "Chat with YOUR Knowledge, Not Just AI's"
  description: "Unlike ChatGPT, ChatterKB focuses on YOUR private documents and expertise. Get accurate, source-cited answers based on your content—without hallucinations or public data leaks."
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
  title: "Beyond ChatGPT: Your Private AI Knowledge Platform"
  for_teams:
    title: "For Teams: Private Document Intelligence"
    tagline: "Turn YOUR confidential documents into searchable insights."
    description: "Unlike general AI chatbots, ChatterKB works exclusively with your private documents, extracting key insights with pinpoint citations and zero hallucinations."
    key_benefit: "Get accurate, source-cited answers from your own documents—not from the public internet."
    icon: bi-file-earmark-text
    image: /assets/images/template/content/team-dashboard.webp
    cta:
      text: Start Analyzing Now
      url:  "https://app.chatterkb.com/auth/signup"
  for_creators:
    title: "For Creators: Your AI Knowledge Twin"
    tagline: "Let AI respond with YOUR expertise, not generic answers."
    description: "Transform your content into an interactive knowledge base that answers questions using only your verified material—maintaining your unique voice and expertise."
    key_benefit: "Scale your audience reach while ensuring every answer reflects your authentic knowledge."
    icon: bi-people
    image: /assets/images/template/content/creator-kb.webp
    cta:
      text: Build Your Knowledge Base
      url:  "https://app.chatterkb.com/auth/signup"

problems:
  section_title: "Benefits"
  title: "Why ChatterKB Instead of Generic AI"
  description: "Unlike ChatGPT, which draws from public data, ChatterKB is purpose-built for your private information and specific use cases."
  bifurcated: true
  for_teams:
    title: "For Teams"
    benefits:
      - title: "Private & Secure Analysis"
        description: "Your sensitive documents never train a public AI—keeping your competitive intelligence truly confidential."
        icon: "bi-shield-lock"
      - title: "Source-Cited Answers"
        description: "Every insight comes with exact citations to source documents—no more AI hallucinations or fabricated facts."
        icon: "bi-check-circle"
      - title: "Extract Hidden Connections"
        description: "Reveal patterns across multiple documents that even careful human analysis would miss."
        icon: "bi-diagram-3"
      - title: "Reportable & Auditable"
        description: "Create stakeholder-ready reports with every insight traceable to source—critical for compliance and governance."
        icon: "bi-graph-up-arrow"
    image: /assets/images/template/content/team-benefits.webp
  for_creators:
    title: "For Creators"
    benefits:
      - title: "Your Knowledge, Not AI's"
        description: "Visitors get answers drawn exclusively from your content—not generic AI that might contradict your expertise."
        icon: "bi-clock"
      - title: "24/7 Engagement Without Burnout"
        description: "Scale personal interactions without constant DMs—freeing you from answering the same questions repeatedly."
        icon: "bi-clock"
      - title: "Audience Intelligence Dashboard"
        description: "Discover exactly what your audience is most curious about through real question analytics."
        icon: "bi-lightbulb"
      - title: "Premium Knowledge Monetization"
        description: "Create tiered access to your expertise, turning your knowledge base into a sustainable revenue stream."
        icon: "bi-cash-coin"
    image: /assets/images/template/content/creator-benefits.webp

how_it_works:
  section_title: How It Works
  title: "Beyond Chatbots: Your Knowledge, Organized & Accessible"
  description: "ChatterKB works exclusively with your documents and content—not public data or generic responses."
  for_teams:
    title: "For Teams"
    steps:
      - title: "Upload Securely"
        description: "Add private documents with enterprise-grade encryption."
        icon: bi-upload
      - title: "Ask Specifically"
        description: "Get exact answers with page & paragraph citations."
        icon: bi-chat-dots
      - title: "Capture & Organize"
        description: "Save key insights into structured collections."
        icon: bi-pin-angle
      - title: "Collaborate Securely"
        description: "Share findings within your permission boundaries."
        icon: bi-share
    image: /assets/images/template/content/team-workflow.webp
  for_creators:
    title: "For Creators"
    steps:
      - title: "Import Your Content"
        description: "Add articles, videos, newsletters, or course material."
        icon: bi-upload
      - title: "Train on Your Voice"
        description: "Ensure responses match your authentic style and expertise."
        icon: bi-palette
      - title: "Publish & Promote"
        description: "Share your interactive knowledge base with your audience."
        icon: bi-link-45deg
      - title: "Scale Your Reach"
        description: "Engage with thousands simultaneously while maintaining your unique voice."
        icon: bi-chat-dots
    image: /assets/images/template/content/creator-workflow.webp

# video:
#   url: "https://chatterkb.s3.us-east-1.amazonaws.com/chatterkb-hero-video.m4v"
#   type: "html5"
#   poster: /assets/images/template/content/hero-app-video.webp
#   container_class: "pb-5 px-4"

features:
  section_title: Features
  title: "Private AI For Your Specific Needs"
  description: "ChatterKB focuses exclusively on your documents—not public data like ChatGPT"
  items:
    - icon: bi-chat-dots
      title_highlight: Contextual
      title_suffix: Document Intelligence
      description: "Ask questions about your specific documents and get precise answers with exact source citations—not generic AI responses."
      image: /assets/images/template/content/feature-chat.webp
    - icon: bi-pin-angle
      title_highlight: Knowledge
      title_suffix: Organization
      description: "Build structured collections of insights that transform scattered information into coherent, shareable knowledge repositories."
      image: /assets/images/template/content/feature-pin.webp
    - icon: bi-share
      title_highlight: Private
      title_suffix: "& Secure"
      description: "Your documents and knowledge remain your property and never train public AI models—ensuring true data sovereignty."
      image: /assets/images/template/content/feature-share.webp

integrations:
  section_title: Integrations
  title: "Connect Your Private Content Sources"
  description: "Import your knowledge directly from the tools you already use—securely and privately."
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
  title: "Private AI Knowledge, Affordably Priced"
  description: "Value-driven plans for both teams and creators, starting at $0. No credit card required."
  plans:
    - name: "Free"
      description: "For individuals exploring private AI knowledge"
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
      description: "For serious knowledge management"
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
  title: "Turn YOUR Knowledge into Interactive Intelligence"
  description: "Stop relying on generic AI answers. Start leveraging your own expertise and documents."
  button:
    text: "Get Started Free"
    url: "https://app.chatterkb.com/auth/signup"
---