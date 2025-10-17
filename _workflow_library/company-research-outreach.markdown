---
layout: page
title: "Company Research and Outreach"
description: "Automated company research to qualify leads and prepare targeted outreach"
order: 30
blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      align: start
      eyebrow: Workflow
      title: Company Research and Outreach
      title_class: display-2 fw-bold mb-3
      subtitle: Automated company research to qualify leads and prepare targeted outreach.
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
        This workflow focuses on automatically researching and qualifying companies as potential leads by gathering critical business information from the web. It systematically identifies company details, creates structured records, and analyzes potential pain points and expected outcomes based on industry and business model. The workflow helps sales teams quickly determine if a company is a viable prospect and prepare targeted outreach materials aligned with their specific needs.

        **Instructions**
        - Add the following file to your Knowledge Base: **[company-research-outreach.md](/assets/files/company-research-outreach.md)**
        - Upload at least one document with the **features and benefits** of your company's product or service to your Knowledge Base.
        - Replace **YOUR COMPANY NAME HERE** with your company's name as mentioned in your document(s).
    media:
      position: bottom
      class: col-lg-7
      title: Workflow Steps
      code: |
        Company Research and Outreach

        Overview

        This workflow focuses on filling in missing information about a company in order to determine if it should be considered a viable lead. By automatically gathering and organizing key business details, it helps qualify prospects and prepare customized outreach materials.

        Workflow Steps

        Step 1: Company Identification
        Ask: "Please provide the name of a company and its location?"

        Step 2: Initial Web Research
        Search the web for information about the company, including:
        - Address
        - Website URL
        - Company Size
        - Industry
        - Services
        - Business Model
        - Contact Information
        Do not visit any site, just store the results.

        Step 3: Detailed Information Extraction
        Base on the search results from the previous step, investigate each result and attempt to capture the following information from each webpage:
        - Location (City/State)
        - Address (Full mailing address)
        - Website URL
        - Company Size (Provide a number, can be a ballpark)
        - Industry
        - Services
        - Business Model
        - Primary Contact (should be a specific person)
        - Primary Contact Email
        - Phone

        Step 4: Pain Point Analysis
        If you have information about the company's industry, business model, or services:
        a. Check the KB for information about the benefits and features of our company (YOUR COMPANY NAME HERE)
        b. Based on the company's industry, business model, and services, give me a list of the pain points with desired outcomes in their voice, going deep and make them polarizing.
        c. Create a file called pain-points-{{name of company with dashes}}.md and save the Pain Points for the company.
        Otherwise, skip this step and mark the Pain Points as "Unknown".

        Step 5: Data Consolidation
        Append the information from the previous steps to the company-research-outreach.md file. Without adding the column headers, append the data to the markdown table in this order (Pain Points should contain the name of the file if Pain Points exist):
        | Company Name | Location | Address | Website URL | Company Size | Industry | Agency Type | Services | Business Model | Pain Points | Primary Contact Name | Primary Contact Email | Phone |
      copy_label: Copy
      copied_label: Copied!

  - type: section
    class: py-6
    content:
      class: col-lg-10 mx-auto text-lg-start
      align: start
      title: Why This Workflow Works
      body: |
        - **Automated Discovery** — Find complete company information without hours of manual research
        - **Pain Point Identification** — Automatically detect prospect challenges based on industry and model
        - **Contact Acquisition** — Locate decision-maker information for direct outreach
        - **Lead Qualification** — Quickly determine if companies are a good fit for your solutions
        - **Scalable Outreach** — Build structured databases of prospects with targeting information

        **Pro Tip:** Run this workflow on a list of companies from the same industry to quickly build a targeted outreach campaign with industry-specific pain points.

  - type: cta
    class: py-6 bg-primary bg-opacity-10
    content:
      align: start
      class: col-lg-6 text-lg-start
      title: Automate Your Lead Research
      body: Stop manually hunting for prospect information. ChatterKB's Company Research workflow helps you build qualified lead lists with targeted pain points in minutes, not hours.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book 15-Min Call
          url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"
          class: btn-outline-secondary btn-lg
          icon: bi-calendar-event
---
