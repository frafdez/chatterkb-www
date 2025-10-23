---
layout: page
sitemap:
  exclude: 'no'

title: ChatterKB Internal Tools | KB-Level Tool Management System

blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      title: Internal Tools
      subtitle: ChatterKB implements a KB-level tool management system that allows for selective enabling of tools per knowledge base, while extending beyond internal tools using Zapier MCP integration.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
    media:
      class: col-lg-6
      position: end
      image:
        url: /assets/images/marketing/internal-tools-feature-hero.png
        class: shadow-lg

  - type: section
    class: py-6 bg-body-secondary bg-opacity-25
    title: Customize Your AI Assistant's Capabilities
    subtitle: Tool Management
    matrix:
      row:
        columns:
          - class: col-lg-12
            card:
              class: border-0 shadow
              media:
                class: col-lg-6
                position: start
                image:
                  url: /assets/images/marketing/internal-tools-feature-step-1.png
              content:
                class: col-lg-6 text-lg-start
                title: KB-Level Tool Management
                body: |
                  Control which tools are available in each knowledge base through a simple settings interface, optimizing token usage and focusing capabilities.

                  - Enable or disable specific tools based on your team's needs
                  - Reduce token costs by only loading necessary tools
                  - Customize AI capabilities for different knowledge base use cases
                  - Clean tool architecture with UI generation capabilities
          - class: col-lg-12
            card:
              class: border-0 shadow
              media:
                class: col-lg-6
                position: end
                image:
                  url: /assets/images/marketing/internal-tools-feature-step-2.png
              content:
                class: col-lg-6 text-lg-start
                title: Extended Tool Integration
                body: |
                  Connect your knowledge base to thousands of external tools and services through Zapier Model Context Protocol integration.

                  - Seamlessly integrate with over 5,000 apps and services
                  - Combine internal tools with Zapier's MCP offerings
                  - Create custom workflows that leverage your knowledge base

  - type: section
    class: py-6
    content:
      align: start
      title: Internal Tool Directory
      body: |
        Your workflows and chats are powered by a suite of specialized tools that enhance what LLMs can do. These tools handle everything from document analysis to web interactions, making your AI assistant truly capable.

        Below is a complete list of our internal tools. When building workflows, you can reference these tools by their descriptive names or use their exact function IDs for precise control.

        <div class="table-responsive">
        <table class="table table-striped">
        <thead>
            <tr>
              <th scope="col" width="340px">Name</th>
              <th scope="col">Description</th>
              <th scope="col">ID</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <th scope="row"><i class="bi bi-files me-2"></i>List Knowledge Base Files</th>
              <td>A tool to browse and list files stored in the knowledge base.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_list_files</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-robot me-2"></i>LLM Chat</th>
              <td>Start a chat with an LLM over your knowledge base, with contextual memory and file recall from the knowledge base.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_chat_llm</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-search me-2"></i>Search Knowledge Base Documents</th>
              <td>Search the knowledge base for relevant documents.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_search_documents</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-file-earmark-arrow-down me-2"></i>Download Knowledge Base File</th>
              <td>Download a file from a knowledge base through the API.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_download_file</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-cloud-arrow-up me-2"></i>Upload Knowledge Base File</th>
              <td>A tool to upload a file from the user to a knowledge base through the API.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_upload_file</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-person-lines-fill me-2"></i>Summarize a Call or Conversation</th>
              <td>Use this tool to summarize meetings, calls, chats, or any communication by pasting the transcript or interaction details. You choose the summary style that fits your needs—include participants, action items, and next steps to create polished, shareable notes in seconds.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>summary</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-building-check me-2"></i>Stakeholder Call and Company Summary</th>
              <td>Quickly capture the key talking points, business context, and action notes from a stakeholder call or company briefing. You’ll receive an executive-style summary ready for leadership updates or follow-up activities.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>stakeholder_summary</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-mic-fill me-2"></i>Podcast Summary</th>
              <td>Create a concise and engaging summary of a podcast episode, capturing the main themes, memorable quotes, and key takeaways so you can share or review insights faster.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>podcast_summary</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-camera-video me-2"></i>Video Summary</th>
              <td>Generate a clear summary of any video, highlighting the major topics, arguments, or moments. Perfect for saving time reviewing training, webinars, or YouTube content.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>video_summary</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-body-text me-2"></i>Summarize a Transcript</th>
              <td>Turn long transcripts into actionable summaries that capture speakers, decisions, and follow-ups. Whether it’s a deposition, interview, or meeting, you’ll have a clean recap in moments.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>transcript_summary</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-map me-2"></i>Generate Location Summary</th>
              <td>Build a location profile that includes detailed descriptions, nearby points of interest, and local highlights. Ideal for trip planning, field research, or briefing documents.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>location_summary</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-house-door me-2"></i>Property Listing Summary</th>
              <td>Create a polished property summary from raw listing information. Highlight amenities, neighborhood strengths, and unique selling points for faster real estate decisions.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>home_summary</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-hospital me-2"></i>Doctor or Facility Summary</th>
              <td>Generate a comprehensive summary of a doctor or medical facility, including specialties, background, and helpful patient-facing details. Perfect for care coordination or health research.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>doctor_summary</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-compass me-2"></i>Destinations Summary</th>
              <td>Turn travel research into a structured summary that covers attractions, logistics, and tips in one go. Great for travel planning or relocation briefings.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>travel_summary</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-puzzle me-2"></i>Key Takeaways</th>
              <td>Extract the most important points from any text, whether it’s a report, article, or large document. Ideal for quick reviews and stakeholder briefings.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>key_takeaways</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-lightbulb me-2"></i>Insight Summary</th>
              <td>Surface deeper patterns, opportunities, and strategic insights from any document or dataset. Helps teams make informed decisions faster.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>insight_summary</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-person-video3 me-2"></i>Persona Summary</th>
              <td>Generate a persona profile that summarizes traits, behaviors, and needs—perfect for marketing, product research, or user experience projects.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>persona_summary</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-people-fill me-2"></i>Audience Summary</th>
              <td>Create a high-level audience overview that outlines motivations, preferences, and communication style. Useful for campaign planning and stakeholder alignment.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>audience_summary</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-people me-2"></i>Direct Message</th>
              <td>Send a direct message within a conversation to provide updates or follow-ups.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>app_send_message</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-bell me-2"></i>Notify Team</th>
              <td>Notify your team with timely updates or quick results from a conversation or workflow.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>app_notify_team</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-gear-fill me-2"></i>Run Workflow</th>
              <td>Trigger a workflow using any saved workflow library entry or custom automation to support your task.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>app_run_workflow</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-check2-square me-2"></i>Review Insight</th>
              <td>Review a saved insight or knowledge base note for validation or further action.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_review_insight</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-clipboard2-check me-2"></i>Save Insight</th>
              <td>Instantly save important discoveries or reasoning steps into the knowledge base for later reference or sharing.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_save_insight</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-lightning-charge me-2"></i>Pin Insight to Board</th>
              <td>Pin key moments and insights discovered during a chat to a board, so that they can be organized, edited, shared, or turned into reports at any time.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_pin_insight_to_board</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-save me-2"></i>Create or Update report</th>
              <td>Quickly save an insight to a new or existing report. This makes it easy to organize your findings, add context, and build comprehensive summaries over time without losing important discoveries.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_save_insight_to_collection</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-chat-text me-2"></i>Review Insight Related to a Chat</th>
              <td>Look up saved insights for context or reuse in future work.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>app_review_insight_chat_context</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-share me-2"></i>Share Knowledge Base File</th>
              <td>Share a knowledge base file with other users or external visitors via the share link tool.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_share_file</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-box-arrow-up-right me-2"></i>Upload External File</th>
              <td>Upload a file from a provided URL directly into the knowledge base.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_upload_file_from_url</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-scissors me-2"></i>Generate Document Snippets</th>
              <td>Generates excerpts from documents to reveal insights or summaries.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_document_snippets</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-stars me-2"></i>Sparkle Questions</th>
              <td>Generate thought-provoking questions or suggestions related to your query.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_generate_sparkle_questions</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-list-check me-2"></i>Knowledge Base Info</th>
              <td>Fetch metadata and configuration details about the knowledge base.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_info</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-gear me-2"></i>Tool Configuration</th>
              <td>List the status of tools enabled or disabled in the knowledge base.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_tool_configurations</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-globe me-2"></i>Web Search</th>
              <td>A tool to search the web for real-time information on any topic.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>web_search</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-magnet me-2"></i>Web Parser</th>
              <td>A tool to parse a webpage and extract its content, including text, links, and metadata.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>web_parser</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-file-earmark-plus me-2"></i>Write Knowledge Base File</th>
              <td>A tool to write content to a markdown file in the knowledge base. Supports appending to existing files or overwriting them.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_write_file</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-file-earmark-text me-2"></i>Read Knowledge Base File</th>
              <td>A tool to read the full content of a markdown file from the knowledge base.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_read_file</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-pencil-fill me-2"></i>Update Knowledge Base File Section</th>
              <td>Update a specific section within a markdown file, with options to overwrite, append, or replace content.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_update_file_section</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-file-earmark-spreadsheet me-2"></i>Analyze Spreadsheet with Pandas</th>
              <td>Run data analysis scripts on CSVs and Excel files directly within the knowledge base to uncover trends and answer complex questions.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_analyze_spreadsheet_with_pandas</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-braces me-2"></i>Execute Python Code</th>
              <td>Run Python scripts to perform calculations, automate tasks, or process text—giving you a flexible and powerful way to get work done.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>execute_python</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-code-square me-2"></i>Analyze JSON File</th>
              <td>Parse, summarize, and explore JSON data with Python.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_analyze_json_as_dict</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-pin-angle-fill me-2"></i>Pin a Chat to a Board</th>
              <td>Pin a chat to a board to keep it easily accessible.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>app_pin_chat</span>
              </td>
            </tr>
            <tr>
              <th scope="row"><i class="bi bi-grid-3x3-gap me-2"></i>Create Board</th>
              <td>Create a new board to organize chats.</td>
              <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>app_create_board</span>
              </td>
            </tr>
          </tbody>
        </table>
        </div>

  - type: faq
    class: py-6 bg-body-secondary bg-opacity-25
    content:
      align: start
      title: Frequently Asked Questions
      faqs:
        - question: How do I enable or disable tools for my knowledge base?
          answer: You can manage tools directly from your knowledge base settings page. Navigate to your KB settings, select the "Tools" tab, and use the toggle switches to enable or disable specific tools. This gives you full control over which capabilities are available in each knowledge base.
        - question: Why would I want to disable certain tools?
          answer: Disabling unused tools provides several benefits. It reduces token costs by only loading necessary tools, simplifies the interface for users who don't need specialized capabilities, and can improve security by limiting access to certain functions when appropriate.
        - question: How does the Zapier MCP integration work?
          answer: ChatterKB extends beyond internal tools using Zapier Model Context Protocol (MCP). When Zapier is connected, ChatterKB receives a merged tool list that combines internal tools with Zapier's MCP offerings.
        - question: Are there any tools that can't be disabled?
          answer: We recommend keeping kb_search_documents, kb_list_files, and kb_read_file enabled for core knowledge base functionality, but you have control over the entire toolset.
        - question: Can I create custom tools for my knowledge base?
          answer: Custom tool creation is not yet available directly in the UI. You can extend functionality through Zapier MCP, which connects you to thousands of external services and lets you build custom workflows.
        - question: How do I monitor tool usage and costs?
          answer: ChatterKB includes cost logging integration that tracks tool usage across your knowledge bases. Review these metrics in your account dashboard to understand which tools are used most frequently and optimize token spend.

  - type: cta
    class: py-5 bg-primary bg-opacity-10
    content:
      class: col-lg-8 mx-auto
      align: left
      title: Enhance Your AI Assistant's Capabilities
      body: Configure the perfect toolset for each knowledge base and extend functionality through seamless integrations.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book a Demo
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
---
