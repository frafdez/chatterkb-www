# Marketing Solutions Template

## Overview

The `marketing-solutions` layout is a new variant that sits between the homepage (`marketing-home`) and the models page (`marketing-page`). It's designed for creating targeted solution pages for different industries and organizations.

## Key Differences

### vs. Homepage (`marketing-home`)
- **More focused**: Removes ROI section and trusted logos for a tighter experience
- **Industry-specific**: Content is tailored to specific audience pain points
- **Streamlined**: Fewer sections mean faster loading and clearer messaging

### vs. Models Page (`marketing-page`)
- **More visual**: Includes hero, problems, solution workflow, and features sections
- **More engaging**: Uses the full marketing template components instead of basic content
- **Better conversion**: Includes proper CTA section instead of simple CTA

## Layout Structure

The `marketing-solutions` layout includes these sections in order:
1. **Hero** - Industry-specific headline and value proposition
2. **Problems** - 3 key challenges specific to the target audience
3. **Solution** - 3-step workflow showing how ChatterKB solves their problems
4. **Features** - 4 key features relevant to the industry
5. **CTA** - Call-to-action with industry-specific messaging

## Default Images

The template uses the same images as the homepage by default:
- **Hero**: `/assets/images/marketing/hero-image.webp`
- **Solution workflow**: `/assets/images/marketing/workflow-diagram.webp`
- **Solution steps**: `workflow-step1.webp`, `workflow-step2.webp`, `workflow-step3.webp`
- **Features**: `feature-pin.webp`, `feature-docs.webp`, `feature-sop.webp`, `feature-team.webp`
- **CTA**: `/assets/images/marketing/product-screenshot.png`

You can override any of these by specifying different image paths in your page's front matter.

## Usage

Create a new markdown file with the `marketing-solutions` layout:

```yaml
---
layout: marketing-solutions
title: "Your Page Title"
description: "SEO description"

hero:
  title: "Main Headline"
  split_title:
    main: "First Part"
    highlight: "Highlighted Part"
  description: "Subheadline description"
  image: "/assets/images/marketing/hero-image.webp"  # Uses homepage image by default
  primary_button:
    text: "Primary CTA"
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: "Secondary CTA"
    url: "calendar-link"

problems:
  section_title: "Section Title"
  items:
    - title: "Problem 1"
      description: "Description of the problem"
    # ... 2 more problems

solution:
  title: "Solution Title"
  description: "Solution description"
  image: "/assets/images/marketing/workflow-diagram.webp"  # Uses homepage image by default
  steps:
    - title: "Step 1"
      description: "Step description"
      image: "/assets/images/marketing/workflow-step1.webp"  # Uses homepage image by default
      badges:
        - "Badge 1"
        - "Badge 2"
    # ... 2 more steps

features:
  tagline: "VERB • VERB • VERB"
  title: "Features Title"
  items:
    - icon: "bi-icon-name"
      title: "Feature Title"
      description: "Feature description"
      image: "/assets/images/marketing/feature-pin.webp"  # Uses homepage image by default
    # ... 3 more features

cta:
  title: "CTA Title"
  description: "CTA description"
  image: "/assets/images/marketing/product-screenshot.png"  # Uses homepage image by default
  primary_button:
    text: "Primary CTA"
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: "Secondary CTA"
    url: "calendar-link"
---
```

## Examples

- `ngo.markdown` - NGO/nonprofit organizations
- `credit-unions.markdown` - Credit unions and community banks

## Best Practices

1. **Industry-specific language**: Use terminology and pain points specific to your target audience
2. **Relevant examples**: Choose badges, features, and images that resonate with the industry
3. **Appropriate CTAs**: Adjust button text to match the audience's decision-making process
4. **Focused problems**: Address 3 specific challenges rather than generic business problems
5. **Clear value prop**: Make the benefit obvious in the hero section
6. **Image customization**: Start with default homepage images, then replace with industry-specific ones as needed

## File Naming

Use the pattern: `<industry>.markdown` (inside the `solutions/` folder)

Examples:
- `healthcare.markdown`
- `education.markdown`
- `manufacturing.markdown`
- `consulting.markdown` 