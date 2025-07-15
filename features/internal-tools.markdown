---
layout: marketing-feature
sitemap:
  exclude: 'no'

title: ChatterKB Internal Tools | KB-Level Tool Management System
hero:
  title: Internal Tools 
  description: ChatterKB implements a KB-level tool management system that allows for selective enabling of tools per knowledge base, while extending beyond internal tools using Zapier MCP integration.
  image: /assets/images/marketing/internal-tools-feature-hero.png
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"

features:
  section_title: Tool Management
  title: Customize Your AI Assistant's Capabilities
  items:
    - side: left
      title: KB-Level Tool Management
      description: Control which tools are available in each knowledge base through a simple settings interface, optimizing token usage and focusing capabilities.
      image: /assets/images/marketing/internal-tools-feature-step-1.png
      bullets:
        - Enable or disable specific tools based on your team's needs
        - Reduce token costs by only loading necessary tools
        - Customize AI capabilities for different knowledge base use cases
        - Clean tool architecture with UI generation capabilities
    - side: right
      title: Extended Tool Integration
      description: Connect your knowledge base to thousands of external tools and services through Zapier Model Context Protocol integration.
      image: /assets/images/marketing/internal-tools-feature-step-2.png
      bullets:
        - Seamlessly integrate with over 5,000 apps and services
        - Combine internal tools with Zapier's MCP offerings
        - Create custom workflows that leverage your knowledge base
   

faqs:
  title: Frequently Asked Questions
  items:
    - question: How do I enable or disable tools for my knowledge base?
      answer: You can manage tools directly from your knowledge base settings page. Navigate to your KB settings, select the "Tools" tab, and use the toggle switches to enable or disable specific tools. This gives you full control over which capabilities are available in each knowledge base.
    - question: Why would I want to disable certain tools?
      answer: Disabling unused tools provides several benefits. It reduces token costs by only loading necessary tools, simplifies the interface for users who don't need specialized capabilities, and can improve security by limiting access to certain functions when appropriate.
    - question: How does the Zapier MCP integration work?
      answer: ChatterKB extends beyond internal tools using Zapier Model Context Platform (MCP). When Zapier is connected, ChatterKB receives a merged tool list that combines internal tools with Zapier's MCP offerings. 
    - question: Are there any tools that can't be disabled?
      answer: No, but we suggest you keep at least kb_search_documents, kb_list_files, and kb_read_file.
    - question: Can I create custom tools for my knowledge base?
      answer: Currently, custom tool creation is not available directly through the user interface. However, you can extend functionality through the Zapier MCP integration, which allows you to connect to thousands of external services and create custom workflows that leverage your knowledge base.
    - question: How do I monitor tool usage and costs?
      answer: ChatterKB includes cost logging integration that tracks tool usage across your knowledge bases. You can view these metrics in your account dashboard to understand which tools are being used most frequently and optimize your token usage accordingly.e knowledge across different tools and platforms.


show_workflow_library: false

cta:
  title: "Enhance Your AI Assistant's Capabilities"
  description: "Configure the perfect toolset for each knowledge base and extend functionality through seamless integrations."
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10os0gxZrUbzNEIvQZUJqLWVeGM"

content_title: Available Tools

---

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
      <th scope="row"><i class="bi bi-search me-2"></i>Search Knowledge Base</th>
      <td>A tool to search the knowledge base for relevant information using natural language queries.</td>
      <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_search_documents</span>
      </td>
    </tr>
    <tr>
      <th scope="row"><i class="bi bi-robot me-2"></i>LLMO/GEO Metrics</th>
      <td>A tool to measure SEO impact in LLMs. Provides rank, mention count, and related links for each brand mentioned in the prompt.</td>
      <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>llmo</span>
      </td>
    </tr>
    <tr>
      <th scope="row"><i class="bi bi-robot me-2"></i>LLM Evaluate</th>
      <td>A tool to evaluate the sandboxed results from a specific LLM given a prompt. Just specify the LLM model, the prompt, and how you want to evaluate the results.</td>
      <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>llmo</span>
      </td>
    </tr>
    <tr>
      <th scope="row"><i class="bi bi-hash me-2"></i>Document Chunk Count</th>
      <td>Shows how many pieces a large document is split into.</td>
      <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_document_chunk_count</span>
      </td>
    </tr>
    <tr>
      <th scope="row"><i class="bi bi-file-text me-2"></i>Load Document Chunks</th>
      <td>Read selected parts of a large document.</td>
      <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_load_document_chunks</span>
      </td>
    </tr>
    <tr>
      <th scope="row"><i class="bi bi-youtube me-2"></i>YouTube Transcript</th>
      <td>Read selected parts of a large document.</td>
      <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>youtube_transcript</span>
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
      <td>A tool to update a specific section within a markdown file in the knowledge base, with options to overwrite, append, or replace content.</td>
      <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_update_file_section</span>
      </td>
    </tr>
    <tr>
      <th scope="row"><i class="bi bi-file-earmark-spreadsheet me-2"></i>Analyze Spreadsheet with Pandas</th>
      <td>Instantly analyze and gain insights from your spreadsheet data. This tool lets you run powerful data analysis scripts on your files, like CSVs and Excel sheets, directly within the knowledge base to uncover trends, summarize information, and answer complex questions.</td>
      <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_analyze_spreadsheet_with_pandas</span>
      </td>
    </tr>
    <tr>
      <th scope="row"><i class="bi bi-braces me-2"></i>Execute Python Code</th>
      <td>Unleash the power of code to solve problems on the fly. This tool can run Python scripts to perform calculations, automate tasks, or process text, giving you a flexible and powerful way to find answers and get work done.</td>
      <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>execute_python</span>
      </td>
    </tr>    
    <tr>
      <th scope="row"><i class="bi bi-code-square me-2"></i>Analyze JSON File</th>
      <td>Run Python code on a JSON file to quickly parse, summarize, and explore your data.</td>
      <td><span class="badge bg-secondary opacity-75"><i class="bi bi-key me-1"></i>kb_analyze_json_as_dict</span>
      </td>
    </tr>   
  </tbody>

</table>
</div>
