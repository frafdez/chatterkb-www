---
layout: page
title: ChatterKB Knowledge Base CSS
image: /docs/images/image1.webp
description: A comprehensive guide to ChatterKB's CSS classes and theming system
---

<style>
.code-block-container {
    position: relative;
}

.copy-button {
    position: absolute;
    top: 5px;
    right: 5px;
    padding: 4px 8px;
    background-color: var(--bs-secondary-bg);
    border: 1px solid var(--bs-border-color);
    border-radius: 4px;
    cursor: pointer;
    font-size: 14px;
    transition: all 0.2s ease;
    display: flex;
    align-items: center;
    justify-content: center;
}

.copy-button:hover {
    background-color: var(--bs-secondary-bg-subtle);
}

.copy-button.copied {
    background-color: var(--bs-success-bg-subtle);
    border-color: var(--bs-success);
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
    document.querySelectorAll('pre').forEach(function(pre) {
        const container = document.createElement('div');
        container.className = 'code-block-container';
        pre.parentNode.insertBefore(container, pre);
        container.appendChild(pre);

        const copyButton = document.createElement('button');
        copyButton.className = 'copy-button';
        copyButton.innerHTML = '<i class="bi bi-copy"></i>';
        container.appendChild(copyButton);

        copyButton.addEventListener('click', async function() {
            const code = pre.querySelector('code')?.textContent || pre.textContent;
            try {
                await navigator.clipboard.writeText(code);
                copyButton.innerHTML = '<i class="bi bi-check2-square"></i>';
                copyButton.classList.add('copied');
                setTimeout(() => {
                    copyButton.innerHTML = '<i class="bi bi-copy"></i>';
                    copyButton.classList.remove('copied');
                }, 2000);
            } catch (err) {
                console.error('Failed to copy:', err);
                copyButton.innerHTML = '<i class="bi bi-clipboard-x"></i>';
            }
        });
    });
});
</script>

<style>
.image-list img {
    height: 300px;
}
</style>

### Skin your knowledge base
You can skin your knowledge base by providing your own CSS. This is a great way to make your knowledge base reflect your brand.

<div class="row image-list my-5">
    <div class="col-lg-4 col-md-12 d-flex justify-content-center mb-4">
      <img src="/docs/images/image2.webp" class="d-block" alt="...">
    </div>
    <div class="col-lg-4 col-md-4 d-flex justify-content-center d-none d-lg-flex mb-4">
      <img src="/docs/images/image1.webp" class="d-block" alt="...">
    </div>
    <div class="col-lg-4 col-md-4 d-flex justify-content-center d-none d-lg-flex mb-4">
      <img src="/docs/images/image3.webp" class="d-block" alt="...">
    </div>
    <div class="col-lg-6 col-md-46 d-flex justify-content-center d-none d-lg-flex mb-4">
      <img src="/docs/images/image4.webp" class="d-block" alt="...">
    </div>
    <div class="col-lg-6 col-md-4 d-flex justify-content-center d-none d-lg-flex mb-4">
      <img src="/docs/images/image5.webp" class="d-block" alt="...">
    </div>
</div>


### How to Use
Create the CSS file for your theme and copy the code into the knowledge base settings. You can access the settings by clicking on the gear icon for the knowledge base and then clicking on the gear icon menu and selecting "Edit". You'll find a section called "Css" in the advanced settings area. Here are some example CSS files you can use as a starting point.


<a href="/docs/files/ckb-example-simple.css" class="btn btn-outline-primary mb-2">Download Example 2 CSS (Simple)</a>
<a href="/docs/files/ckb-example.css" class="btn btn-outline-primary mb-2">Download Example 1 CSS (Advanced)</a>

### Core Layout Components

#### Body & Container
```css
.chatterkb-body {
    background-color: #ffffff;
    background-image: url("PLACEHOLDER_BACKGROUND_IMAGE_URL");
}

.chatterkb-offcanvas {
    background-color: #ffffff;
    color: #333333;
}
```

#### Navigation & Header
```css
.chatterkb-nav-link {
    color: #178D00 !important;
}

.chatterkb-logo-text:before {
    content: "Starter ";
    font-family: "Helvetica Neue", Arial, sans-serif;
    color: #178D00;
}

.chatterkb-logo-text:after {
    content: "Syrup";
    font-family: "Helvetica Neue", Arial, sans-serif;
    font-weight: bold;
    color: #178D00;
}

.chatterkb-sm-logo {
    width: 100%;
    height: auto;
    border-radius: 50%;
    object-fit: cover;
    display: block;
    content: url("PLACEHOLDER_SM_LOGO_URL");
}

.chatterkb-lg-logo {
    height: 100px;
    width: 100px;
    border-radius: 50%;
    object-fit: cover;
    display: block;
    content: url("PLACEHOLDER_LG_LOGO_URL");
}
```

### Knowledge Base Components

#### Knowledge Base Card
```css
.chatterkb-knowledge-base-card {
    background-color: #000000E6;
    background-image: url("PLACEHOLDER_SVG_URL");
    color: white;
}

.chatterkb-knowledge-base-image {
    margin-top: 40px;
    margin-bottom: 40px !important;
}

.chatterkb-knowledge-base-name {
    /* Styles for knowledge base name */
}

.chatterkb-knowledge-base-description {
    /* Styles for knowledge base description */
}
```

#### Action Buttons
```css
.chatterkb-knowledge-base-subscribe-button {
    background-color: #178D0033;
    border-color: #178D00;
    color: #178D00;
}

.chatterkb-knowledge-base-subscribe-button:hover {
    background-color: #178D00;
    color: white;
}

.chatterkb-knowledge-base-sign-up-button {
    background-color: #178D00;
    color: white;
}

.chatterkb-knowledge-base-sign-up-button:hover {
    background-color: #178D00;
    color: white;
}

.chatterkb-new-chat-btn {
    --bs-btn-bg: #178D00 !important;
    --bs-btn-hover-bg: #218838 !important;
    color: white;
}
```

### Conversation Components

#### Conversation List
```css
.chatterkb-conversations-list-group {
    --bs-list-group-bg: #f1f1f1 !important;
    --bs-list-group-action-hover-bg: #e9ecef !important;
    border: none;
}

.chatterkb-conversations-list-item {
    --bs-highlight-bg: #178D0033 !important;
}

.chatterkb-conversations-list-item.active {
    background-color: #178D0033;
    color: #178D00;
    border: none;
}

.chatterkb-conversation-name {
    color: #333333 !important;
}
```

#### Response Elements
```css
.chatterkb-response-button {
    color: #178D00 !important;
}

.chatterkb-response-button:hover {
    color: #ffffff !important;
    background-color: #178D0033 !important;
}
```

### Theme Variations

#### Light Theme
```css
.chatterkb-body[data-bs-theme="light"] .chatterkb-input-container {
    background-color: #000000;
    background-image: url("PLACEHOLDER_LIGHT_INPUT_CONTAINER_BACKGROUND_IMAGE_URL");
    border-top: 1px solid #e0e0e0;
}

.chatterkb-body[data-bs-theme="light"] .chatterkb-footer {
    background-color: #151515;
    background-image: url("PLACEHOLDER_LIGHT_FOOTER_BACKGROUND_IMAGE_URL");
    color: gray !important;
}

.chatterkb-body[data-bs-theme="light"] .chatterkb-send-button {
    color: #178D00;
}
```

#### Dark Theme
```css
.chatterkb-body[data-bs-theme="dark"] .chatterkb-input-container {
    background-color: #333333;
    background-image: url("PLACEHOLDER_DARK_INPUT_CONTAINER_BACKGROUND_IMAGE_URL");
    border-top: 1px solid #444444;
}

.chatterkb-body[data-bs-theme="dark"] .chatterkb-footer {
    background-color: #222222;
    background-image: url("PLACEHOLDER_DARK_FOOTER_BACKGROUND_IMAGE_URL");
    color: #cccccc !important;
}

.chatterkb-body[data-bs-theme="dark"] .chatterkb-send-button {
    color: #00FF00;
}
```

---

Any questions? [Contact us](mailto:hello@chatterkb.com)