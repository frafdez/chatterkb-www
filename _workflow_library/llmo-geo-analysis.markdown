---
layout: page
title: "LLMO/GEO Analysis"
description: "Compare how different AI models rank and analyze topics across 16 leading language models simultaneously."
order: 40
blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      align: start
      eyebrow: Workflow
      title: LLMO/GEO Analysis
      title_class: display-2 fw-bold mb-3
      subtitle: Compare how different AI models rank and analyze topics across 16 leading language models simultaneously.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Learn About Workflows
          url: "/features/workflows/"
          class: btn-outline-secondary btn-lg
    media:
      class: col-lg-6 text-center
      position: end
      image:
        url: /assets/images/marketing/workflow-diagram.png
        alt: Workflow diagram

  - type: section
    class: py-6 bg-body-secondary bg-opacity-50
    content:
      class: col-lg-5 text-lg-start
      align: start
      title: Workflow Overview
      body: |
        This workflow is a bit more involved than the others, but it's still easy to follow and showcases the incredible control you have over complex, multi-step processes. You'll run the same prompt across 16 different AI models and automatically compile the results into a comprehensive analysis table.

        **Important:** Before running this workflow, make sure to enable the LLMO/GEO tool in your knowledge base settings.
    media:
      position: bottom
      class: col-lg-7
      title: Workflow Steps
      code: |
        LLMO/GEO Analysis

        Step 1:
        Specifically state: "Ask the user for a prompt."

        Step 2:
        Generate a unique id using the prompt and formatted as snake case and store it in memory in a key called "unique_id_for_run".

        Step 3:
        Create a file named 'llmo_results_{{unique_id_for_run}}.md' with the following table structure:
        | Rank | Name | Mention Count | Associated Keywords | Related Links | Model |
        | ---- | ---- | ------------- | ------------------- | ------------- | ----- |
        **IMPORTANT** Mention this in the step: YOU **MUST** replace {{unique_id_for_run}} with the value found in memory for "unique_id_for_run".

        Step 4 - 20
        For each of the following models:
        - Claude Sonnet 4
        - Claude 3.7 Sonnet
        - Claude 3.5 Sonnet V2
        - Claude 3.5 Haiku
        - DeepSeek-R1
        - Meta Llama 3.3 70B
        - Google Gemini 2.5 Pro
        - Google Gemini 2.5 Flash
        - Grok 3
        - Grok 3 Mini
        - Perplexity Sonar Pro
        - Perplexity Sonar
        - OpenAI GPT-4.1
        - OpenAI GPT-4o
        - OpenAI o4-mini
        - Amazon Nova Pro

        Do the following:
        a. Call the LLMO tool with the prompt from Step 1 with the model.
        b. Store the entire results from the tool in a file using a name like {{model_name}}_{{unique_id_for_run}}.md'
        c. Specifically mention in Step: Add the statistics table (without the header) from the LLMO results as new rows in the 'llmo_results_{{unique_id_for_run}}.md' table.
        - Ensure that you add one column, at the end of the row, that includes the model name. Each row **must** contain values (even if blank) for Rank, Name, Mention Count, Associated Keywords, Related Links (where applicable), and Model (**IMPORTANT** do **not** include headers).
        - Example content format:
        | 1 | Skechers | 1 | Memory Foam Insoles, comfort for all-day wear | | Claude Sonnet 4 |
        - Use kb_write_file to append to the end of the file. IMPORTANT: You must use the default model for the steps. The model mentioned here is only for the llmo tool call.
        - **IMPORTANT** Mention this in the step: YOU **MUST** replace {{unique_id_for_run}} with the value found in memory for "unique_id_for_run".

        Step 21
        Display that you have finished the process.
      copy_label: Copy
      copied_label: Copied!

  - type: section
    class: py-6
    content:
      class: col-lg-10 mx-auto text-lg-start
      align: start
      title: Why This Workflow Works
      body: |
        - **Comprehensive Model Coverage** — Tests your prompt against 16 different AI models to reveal biases and variations in responses
        - **Automated Data Collection** — Eliminates the manual work of running the same prompt across multiple models
        - **Structured Output** — Automatically formats results into a comparative table for easy analysis
        - **Unique Session Tracking** — Each analysis gets its own unique identifier to prevent data mixing
        - **Detailed Logging** — Saves individual model responses for deeper investigation
        - **Scalable Analysis** — Perfect for market research, competitive analysis, or AI model evaluation

        **Pro Tip:** This workflow is perfect for understanding how different AI models interpret the same business question, helping you choose the right model for specific tasks or identify consensus vs. outlier responses.

  - type: cta
    class: py-6 bg-primary bg-opacity-10
    content:
      align: start
      class: col-lg-6 text-lg-start
      title: Run Multi-Model Analysis
      body: See how different AI models interpret the same prompt with ChatterKB's advanced workflow automation.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book 15-Min Call
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
          icon: bi-calendar-event
---
