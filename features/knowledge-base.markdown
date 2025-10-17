---
layout: page
sitemap:
  exclude: 'no'

title: Knowledge Base with Syncing

blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      title: Your Knowledge, Everywhere You Need It
      subtitle: Connect your existing tools and documents to ChatterKB without disrupting your workflow. No more scattered information or duplicate content management.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"
          class: btn-outline-secondary btn-lg
    media:
      class: col-lg-6
      position: end
      image:
        url: /assets/images/marketing/kb-feature-hero.png
        class: shadow-none

  - type: section
    class: py-6 bg-body-secondary bg-opacity-75
    title: Why Your Business Needs a Knowledge Base
    matrix:
      row:
        columns:
          - class: col-lg-6
            card:
              class: border-0 shadow-none h-100
              content:
                icon: bi-lightbulb-fill
                title: From Static Files to Living Knowledge
                body: |
                  Most teams have knowledge scattered across drives, emails, and personal notes. ChatterKB pulls it together into an interactive system that:

                  - Makes information findable when you need it
                  - Connects related ideas across different docs
                  - Preserves the “why” behind decisions and insights
                  - Grows smarter with every conversation
          - class: col-lg-6
            card:
              class: border-0 shadow-none h-100
              content:
                icon: bi-diagram-3-fill
                title: The Foundation for Everything Else
                body: |
                  Your knowledge base powers everything in ChatterKB:

                  - Chat with your knowledge to get instant answers
                  - [Build workflows](/features/workflows) that act on trusted information
                  - Create dashboards that stay current automatically
                  - Share insights without creating yet another document
          - class: col-lg-12
            card:
              class: border-0 shadow-none h-100
              content:
                icon: bi-people-fill
                title: Beyond Storage—Real Understanding
                body: |
                  ChatterKB reads and understands what’s in your files. Ask a question in plain English and it draws from PDFs, Google Drive docs, Notion pages, Slack conversations, and more—just like a well-informed teammate who has read everything.

  - type: section
    class: py-6 bg-body-secondary bg-opacity-25
    title: Connect Your Existing Knowledge Sources
    subtitle: Data Sources
    matrix:
      row:
        columns:
          - class: col-lg-12
            card:
              class: border-0 shadow
              media:
                class: col-lg-4
                position: start
                image:
                  url: /assets/images/marketing/kb-feature-step-1.png
              content:
                icon: bi-upload
                class: col-lg-8 text-lg-start
                title: Upload Your Own Files
                body: |
                  - Support for multiple file formats including PDF, Word, Excel, PowerPoint, and text files
                  - Batch upload capabilities for processing multiple documents at once
                  - Automatic content preparation for AI-powered search and chat
          - class: col-lg-6
            card:
              class: border-0 shadow h-100
              media:
                class: col-lg-6
                position: bottom
                image:
                  url: /assets/images/marketing/kb-feature-step-3.png
              content:
                icon: bi-google
                class: col-lg-6 text-lg-start
                title: Import from Google Drive
                body: |
                  - Authenticate with Google and choose exactly which files to sync
                  - Bring documents, spreadsheets, and presentations into your knowledge base
                  - Keep originals untouched while layering AI understanding on top
          - class: col-lg-6
            card:
              class: border-0 shadow h-100
              media:
                class: col-lg-6
                position: bottom
                image:
                  url: /assets/images/marketing/kb-feature-step-4.png
              content:
                icon: bi-slack
                class: col-lg-6 text-lg-start
                title: Capture Slack Conversations
                body: |
                  - Connect to Slack and import key channels with one click
                  - Preserve the decisions and discussions living in chat
                  - Turn informal conversations into searchable institutional knowledge
          - class: col-lg-6
            card:
              class: border-0 shadow
              media:
                class: col-lg-6
                position: bottom
                image:
                  url: /assets/images/marketing/kb-feature-step-2.png
              content:
                icon: bi-clipboard-check
                class: col-lg-6 text-lg-start
                title: Sync with Notion
                body: |
                  - Secure OAuth connection to your Notion workspace
                  - Import selected pages or entire sections
                  - Preserve your Notion structure while adding AI capabilities
          - class: col-lg-6
            card:
              class: border-0 shadow h-100
              media:
                class: col-lg-6
                position: bottom
                image:
                  url: /assets/images/marketing/kb-feature-step-5.png
              content:
                icon: bi-youtube
                class: col-lg-6 text-lg-start
                title: Analyze YouTube Content
                body: |
                  - Paste any video or playlist URL—no auth required
                  - Automatically extract and process transcripts
                  - Make video content searchable and actionable inside ChatterKB

  - type: faq
    class: py-6 bg-body-secondary bg-opacity-75
    content:
      align: start
      title: Frequently Asked Questions
      faqs:
        - question: Is syncing automatic or manual?
          answer: Syncing is currently manual by design. When content changes in your original sources you initiate the sync, giving you full control over when updates occur.
        - question: Will syncing create duplicate content?
          answer: No. ChatterKB creates a copy of your content for processing and AI access while leaving your originals untouched in Notion, Google Drive, Slack, or elsewhere.
        - question: What happens to my original files after syncing?
          answer: Originals stay exactly where they are. ChatterKB never modifies your source files—it only reads them and builds an AI-ready representation inside your knowledge base.
        - question: What file types are supported?
          answer: Common formats including Markdown, PDF, Word, Excel, PowerPoint, CSV, text files, and more. Notion imports retain headers, lists, tables, and embedded content.
        - question: How do I update synced content?
          answer: When the source changes, simply trigger another sync—either for a single file/page or an entire connection.
        - question: Can I control what gets synced?
          answer: Yes. Choose specific Notion pages, Google Drive files, or Slack channels to import so only relevant content enters your knowledge base.
        - question: Can I share synced content with my team?
          answer: Absolutely. Once data is in ChatterKB it's available to every teammate with access to that knowledge base, even if they lack permissions in the original tool.

  - type: cta
    class: py-7 bg-primary bg-opacity-10
    content:
      class: col-lg-6 text-lg-start
      title: Connect Your Knowledge Today
      body: Start bringing your scattered information together into one intelligent system.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
---
