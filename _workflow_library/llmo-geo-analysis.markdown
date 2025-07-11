---
layout: marketing-page
title: "LLMO/GEO Analysis"
description: "Compare how different AI models rank and analyze topics across 16 leading language models simultaneously."
header_icon: bi-bar-chart-steps
cta:
  title: "Run Multi-Model Analysis"
  description: "See how different AI models interpret the same prompt with ChatterKB's advanced workflow automation."
  image: "/assets/images/marketing/product-screenshot.png"
  primary_button:
    text: "Try It Free"
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: "Book 15-Min Call"
    url: "https://calendar.google.com/calendar/u/0/appointments/schedules/AcZssZ0oYQ10osj27ugUfwOrSoV893uJ-kWPhIKNBhII5bTlwc3j6HdkEunH29TciGeOttFjfxqEn92O"
---

This workflow is a bit more involved than the others, but it's still easy to follow and showcases the incredible control you have over complex, multi-step processes. You'll run the same prompt across 16 different AI models and automatically compile the results into a comprehensive analysis table.

**Important:** Before running this workflow, make sure to enable the LLMO/GEO tool in your knowledge base settings.

---

```markdown

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
c. Specifically Mention in Step: Add the statistics table (without the header) from the LLMO results as new rows in the 'llmo_results_{{unique_id_for_run}}.md' table. 
- Ensure that you add one column, at the end of the row, that include the model name. Each row **must** contain values (even if blank) for Rank, Name, Mention Count, Associated Keywords, Related Links (where applicable), and Model (**IMPORTANT** do **not** include headers). 
- Example content format: 
| 1 | Skechers | 1 | Memory Foam Insoles, comfort for all-day wear | | Claude Sonnet 4 |
- Use kb_write_file to append to the end of the file. IMPORTANT: You must use the default model for the steps. The model mentioned here is only for the llmo tool call.
- **IMPORTANT** Mention this in the step: YOU **MUST** replace {{unique_id_for_run}} with the value found in memory for "unique_id_for_run".

Step 21
Display that you have finished the process.

```

---

### Why This Workflow Works

- **Comprehensive Model Coverage** — Tests your prompt against 16 different AI models to reveal biases and variations in responses
- **Automated Data Collection** — Eliminates the manual work of running the same prompt across multiple models
- **Structured Output** — Automatically formats results into a comparative table for easy analysis
- **Unique Session Tracking** — Each analysis gets its own unique identifier to prevent data mixing
- **Detailed Logging** — Saves individual model responses for deeper investigation
- **Scalable Analysis** — Perfect for market research, competitive analysis, or AI model evaluation

---

**Pro Tip:** This workflow is perfect for understanding how different AI models interpret the same business question, helping you choose the right model for specific tasks or identify consensus vs. outlier responses. 