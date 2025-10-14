---
layout: pages/base
title: Workflow Library
description: Real-world automated workflow templates you can clone and adapt.
header_image: "/assets/images/marketing/workflow-diagram.png"
---

<div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
  {% assign workflows = site.workflow_library | sort: 'order' %}
  {% for wf in workflows %}
    <div class="col">
      <a href="{{ wf.url }}" class="text-decoration-none">
        <div class="card h-100 shadow-sm border-0">
          <div class="card-body">
            <h5 class="card-title fw-semibold mb-2 d-flex align-items-center gap-2"><i class="bi bi-bar-chart-steps fs-6" style="color:#3b82f6;"></i> {{ wf.title }}</h5>
            {% if wf.description %}
              <p class="card-text small text-muted">{{ wf.description }}</p>
            {% endif %}
          </div>
        </div>
      </a>
    </div>
  {% endfor %}
</div> 