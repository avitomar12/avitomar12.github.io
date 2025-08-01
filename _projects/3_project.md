---
layout: page
title: Grocery Price Comparison Web App
description: Full-stack application for real-time grocery price comparison across supermarkets.
img: assets/img/1.png
importance: 1
category: work
related_publications: false
---

Designed and developed a grocery price comparison platform using **Python FastAPI**, enabling users to retrieve real-time pricing data across 5 major supermarkets.

- Integrated search feature powered by **Sentence Transformer model** deployed on AWS Lambda.
- Backend hosted on AWS EC2 with API Gateway ensuring low-latency responses.
- Automated deployment using CI/CD pipelines with GitHub Actions.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.png" title="Search Feature" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.png" title="API Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.png" title="Deployment Pipeline" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: Search interface; Middle: API architecture; Right: CI/CD pipeline overview.
</div>
