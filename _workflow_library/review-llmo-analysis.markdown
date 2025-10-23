---
layout: page
title: "Review LLMO Analysis"
description: "Analyze and synthesize results from multi-model LLMO analysis to understand brand mention patterns and reasoning."
order: 50
blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      align: start
      eyebrow: Workflow
      title: Review LLMO Analysis
      title_class: display-2 fw-bold mb-3
      subtitle: Analyze and synthesize results from multi-model LLMO analysis to understand brand mention patterns and reasoning.
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
        This workflow analyzes the results from your LLMO/GEO Analysis to understand why certain brands are mentioned before others. You'll need to customize the brand names and logic to match what you're testing — replace "Brand A," "Brand B," and "Brand C" with your actual brand names or competitors you want to analyze.

        **Important:** This workflow requires previous LLMO analysis results in your knowledge base and the LLMO/GEO tool enabled in your KB settings.
    media:
      position: bottom
      class: col-lg-7
      title: Workflow Steps
      code: |
        Review LLMO Analysis

        Step 1 - 16:
        Create a step for each of these models:
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

        Logic must be part of the step: Generate a list of files in the KB filtered using model's name and scoped to the step. Do not include files with the name "llmo_results_".

        **IMPORTANT** The model mentioned in this step should not be used as the step's model. Use the default one instead. It is only to be used for the prompt in the step.

        Copy this to the step:
        For every file associated to the model:
        a) Use search_documents to find information about Brand A, Brand B, and Brand C. You are looking for reasons why Brand A and Brand B are mentioned before Brand C.  
        b) Store reasons in memory with a name/key like "reasoning_for_mention_{{name of the file}}" also, store it as an md file in the KB.  
        **Note**: Reason should be 2 - 3 sentences at most. Do not fabricate a reason. If unknown, save "Cannot determine reason." in the memory and file.
        **IMPORTANT** Keep the steps simple and scoped to the model for this step (e.g. for each file: search_documents, analyze results, save to file)

        Step 17:
        Copy this to the step: Review all of the reasons and create a report detailing why Brand A, and Brand B, are mentioned before Brand C. Store this to an md file called "detailed_report_reasoning.md"

        Step 18:
        Copy this to the step: Generate an executive summary by reviewing all of the reasons and create a report detailing why Brand A and Brand B are mentioned before Brand C. Store this to an md file called "executing_summary_reasoning.md"
      copy_label: Copy
      copied_label: Copied!

  - type: section
    class: py-6
    content:
      class: col-lg-10 mx-auto text-lg-start
      align: start
      title: Why This Workflow Works
      body: |
        - **Systematic Analysis** — Reviews results from each AI model individually to identify patterns and biases
        - **Document Search Integration** — Uses search_documents to find specific brand mentions and context
        - **Memory Management** — Stores reasoning for each file systematically to prevent data loss
        - **Consolidated Reporting** — Creates both detailed and executive summary reports for different audiences
        - **Customizable Logic** — Easily adaptable to different brand comparisons and analysis criteria
        - **Quality Control** — Prevents fabricated reasoning by explicitly handling unknown cases

        **Pro Tip:** Before running this workflow, replace "Brand A," "Brand B," and "Brand C" with your actual brand names. You can also modify the search logic to focus on specific aspects like pricing, features, or market positioning.

  - type: cta
    class: py-6 bg-primary bg-opacity-10
    content:
      align: start
      class: col-lg-6 text-lg-start
      title: Analyze Your LLMO Results
      body: Transform raw LLMO data into actionable insights with ChatterKB's intelligent analysis workflows.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book 15-Min Call
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
          icon: bi-calendar-event
---
