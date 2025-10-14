---
layout: pages/base
title: "Email Security Verification Workflow"
description: "Automate email security record verification using ChatterKB."
header_icon: bi-bar-chart-steps
order: 55
workflow_introduction: |
  This workflow guides you through verifying email security records for a domain using Google's DNS toolbox. Follow each step to ensure your domain's email security is properly configured.

workflow_steps: |
  Email Security Verification Workflow

  Overview:
  This workflow guides you through verifying email security records for a domain using Google's DNS toolbox. Follow each step to ensure your domain's email security is properly configured.

  Workflow Steps:

  Step 1: Identify Domain
  Ask: "Which domain would you like to check for email security records? (e.g., example.com)"

  Step 2: Check MX Records
  Navigate to: https://toolbox.googleapps.com/apps/dig/#MX/{{domain}}
  - Look for properly configured mail servers
  - Note priorities and TTL values
  - Verify they point to a valid email provider

  Step 3: Verify SPF Record
  Navigate to: https://toolbox.googleapps.com/apps/dig/#TXT/{{domain}}
  - Look for a TXT record beginning with "v=spf1"
  - Confirm it includes all authorized email senders
  - Check if it ends with ~all (softfail) or -all (hardfail)

  Step 4: Check DMARC Record
  Navigate to: https://toolbox.googleapps.com/apps/dig/#TXT/_dmarc.{{domain}}
  - Look for a TXT record beginning with "v=DMARC1"
  - Verify policy setting (p=none, p=quarantine, or p=reject)
  - Check reporting configuration if present

  Step 5: Verify DKIM Records
  Navigate to: https://toolbox.googleapps.com/apps/dig/#TXT/selector._domainkey.{{domain}}
  - Check for DKIM records using common selectors (default, mail, k1)
  - If no records are found, examine email headers from the domain to identify the actual selector
  - Look for TXT records containing "v=DKIM1"
  - Verify the record contains a valid public key

  Step 6: Analyze Results
  Evaluate each record against best practices:
  - MX: Properly configured mail servers
  - SPF: Authorized senders with appropriate policy
  - DMARC: Policy that matches your security needs
  - DKIM: Valid signing keys for email authentication

  Step 7: Identify Security Gaps
  Note any missing or misconfigured records:
  - Missing DKIM is a common issue
  - Weak SPF policy (~all instead of -all)
  - Missing or permissive DMARC policy

  Step 8: Recommend Improvements
  Based on findings, recommend specific actions to improve email security, such as:
  - Implementing missing records
  - Strengthening policies
  - Adding reporting for monitoring

cta:
  title: "Start Securing Your Email"
  description: "Try this workflow in ChatterKB and verify your domain's email security."
  image: "/assets/images/marketing/product-screenshot.png"
  primary_button:
    text: "Try It Free"
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: "Book 15-Min Call"
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"
---

### Why This Workflow Works

- **Complete Coverage** — Checks all four essential email security records: MX, SPF, DMARC, and DKIM
- **Step-by-Step Verification** — Guides users through checking each record in a logical sequence
- **Gap Analysis** — Helps identify missing or misconfigured security elements
- **Actionable Recommendations** — Provides specific guidance on how to strengthen email security
- **Easy Implementation** — Uses Google's free toolbox with no specialized knowledge required

---

Need something more advanced? Duplicate this template and add integration with email security scoring tools, or expand verification to include BIMI records and other advanced email authentication mechanisms.