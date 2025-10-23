---
layout: page
title: "Create Friendly Company Names"
description: "Convert formal company names into memorable, conversational alternatives for better engagement and personalized communication"
order: 35
blocks:
  - type: hero
    class: py-6
    content:
      class: col-lg-6 text-lg-start
      align: start
      eyebrow: Workflow
      title: Create Friendly Company Names
      title_class: display-2 fw-bold mb-3
      subtitle: Convert formal company names into memorable, conversational alternatives for better engagement and personalized communication.
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
        This workflow automatically transforms formal company names into concise, conversational alternatives that are more relatable in everyday business communications. By creating standardized "friendly" versions of company names, your team can maintain consistent branding references across all touchpoints while removing special characters and unnecessary legal designations. This approach personalizes client communications, improves readability in reports, and helps maintain a more conversational tone in customer-facing materials.

        **Instructions**
        - Prepare a CSV file containing company contact information with columns for: First Name, Last Name, Title, Company, Email
        - Upload your file when prompted by the workflow
    media:
      position: bottom
      class: col-lg-7
      title: Workflow Steps
      code: |
        Create Friendly Company Names

        Overview

        This workflow converts formal company names into simplified, conversational alternatives by intelligently extracting the most recognizable parts while removing special characters, legal designations, and unnecessary modifiers.

        Workflow Steps

        Step 1:
        - Ask for a file name that has the columns:
        First Name, Last Name, Title, Company, Email
        - Create a spreadsheet called friendly-company-names.csv with only the header:
        First Name, Last Name, Title, Company, Friendly Company Name, Email

        Step 2:
        For every row:
        - Using the Company name, you are going to come up with a friendly company name and place it in the Friendly Company Name column. I want your to come up with your best guess as to what someone might call the company in a casual conversation. You must remove special characters from names (e.g., ™, ®, ©, etc.).
          Let me give you some examples:
            Alea Advertising = Alea
            Kai Communications & Branding = Kai
            Depirrow/Garrone Advertising = DG
            Alpha Co. Marketing & Media = Alpha
            The Lubrizol = Lubrizol
            EmpowerFi™ = EmpowerFi
            Midwest Promotional Models = MPM (this one I would say this way because it isn't using generic terms so abbreviation might make sense)
        - Now append those values to the friendly-company-names.csv including all of the value from all of the columns. Do not include the column headers or any extra text before or after the rows.
      copy_label: Copy
      copied_label: Copied!

  - type: section
    class: py-6
    content:
      class: col-lg-10 mx-auto text-lg-start
      align: start
      title: Why This Workflow Works
      body: |
        - **Brand Consistency** — Create standardized friendly company names across all communication channels
        - **Improved Readability** — Simplify formal company names for better clarity in reports and communications
        - **Personalized Engagement** — Use conversational company names for more relatable client interactions
        - **Enhanced Memorability** — Convert complex company names into simpler forms that are easier to recall
        - **Automated Processing** — Transform entire contact lists in seconds, not hours of manual editing

        **Pro Tip:** Run this workflow on your CRM export before starting an email campaign to personalize messages with friendly company references that connect better with recipients.

  - type: cta
    class: py-6 bg-primary bg-opacity-10
    content:
      align: start
      class: col-lg-6 text-lg-start
      title: Humanize Your Business Communication
      body: Transform formal company names into conversational alternatives that connect better with your audience and simplify your communication materials.
      buttons:
        - text: Try It Free
          url: "https://app.chatterkb.com/auth/signup"
          class: btn-primary btn-lg
        - text: Book 15-Min Call
          url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
          class: btn-outline-secondary btn-lg
          icon: bi-calendar-event
---
