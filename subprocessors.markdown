layout: pages/standard
title: Subprocessors
permalink: /subprocessors/
---

# Subprocessors

_Last updated: 2025-01-15_

This page lists the third-party subprocessors used by ChatterKB to provide and support the service, in accordance with the EU General Data Protection Regulation (GDPR).

A **subprocessor** is a third party engaged by ChatterKB to process personal data on behalf of our customers. ChatterKB remains responsible for ensuring that subprocessors provide appropriate data protection safeguards.

## Infrastructure and Cloud Services

| Subprocessor | Purpose | Data Location | Safeguards |
|-------------|---------|---------------|------------|
| Google Cloud Platform | Application hosting, databases, networking | United States | SCCs, encryption in transit and at rest |
| Amazon Web Services (S3) | Object storage for customer documents and RAG files | United States | SCCs, encryption in transit and at rest |
| Amazon Web Services (Cognito) | Authentication and identity management | United States | SCCs, encryption in transit and at rest |

## AI and Model Services

| Subprocessor | Purpose | Data Location | Safeguards |
|-------------|---------|---------------|------------|
| Amazon Web Services (Bedrock) | Large language model inference | United States | SCCs, transient processing, no model training |
| OpenAI | Large language model inference (GPT models) | United States | SCCs, transient processing, no model training |
| Google Cloud Platform (Vertex AI) | Large language model inference (Gemini models) | United States | SCCs, transient processing, no model training |
| Perplexity AI | Large language model inference and search augmentation | United States | SCCs, transient processing, no model training |
| xAI (Grok) | Large language model inference | United States | SCCs, transient processing, no model training |

ChatterKB routes AI inference requests dynamically based on customer configuration, model availability, and performance characteristics. Only the minimum data required to generate a response is transmitted to model providers, and such data is processed transiently and not retained beyond the scope of the request.

## Subprocessor Updates

ChatterKB may update this list from time to time as subprocessors are added or replaced. Customers will be notified of material changes in accordance with the Data Processing Agreement.

## Contact

For questions regarding subprocessors or data protection practices, please contact:

**Email:** privacy@chatterkb.com
