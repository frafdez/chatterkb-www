---
layout: marketing-page
title: MCP Server Library
description: Extend the capabilities of ChatterKB using Model Context Protocol to connect to external tools and services. Here are some of the servers we find useful.
header_image: "/assets/images/marketing/mcp-hero.png"
---

<div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
  {% assign mcp_servers = site.mcp_servers | sort: 'order' %}
  {% for server in mcp_servers %}
    <div class="col">
      <a href="{{ server.url }}" class="text-decoration-none">
        <div class="card h-100 shadow-sm border-0">
          <div class="card-body">
            <h5 class="card-title fw-semibold mb-2 d-flex align-items-center gap-2">
              <i class="bi bi-pc-display fs-6" style="color:#3b82f6;"></i> 
              {{ server.hero.title | default: server.title }}
            </h5>
            {% if server.description %}
              <p class="card-text small text-muted">{{ server.description }}</p>
            {% endif %}
          </div>
        </div>
      </a>
    </div>
  {% endfor %}
</div> 