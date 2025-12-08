---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#2d5a27"
  overlay_filter: "0.6"
  overlay_image: /assets/images/hero-bg.svg
  actions:
    - label: "<i class='fab fa-github'></i> View on GitHub"
      url: "https://github.com/saikeicivil/SaikeiCivil"
    - label: "<i class='fas fa-download'></i> Download v0.6.0"
      url: "https://github.com/saikeicivil/SaikeiCivil/releases"
excerpt: >
  **栽景** — Open-source civil engineering BIM software creating native IFC 4.3 files for roads, alignments, and infrastructure design.<br />
  <small>*"While Bonsai crafts the buildings, Saikei shapes the world around them."*</small>

intro:
  - excerpt: '**25,000+ lines of code** · **107+ tests passing** · **Native IFC 4.3** · **Sprint 5 of 16**'

feature_row:
  - image_path: /assets/images/feature-alignment.svg
    alt: "Horizontal Alignments"
    title: "🛤️ Horizontal Alignments"
    excerpt: "PI-based design with automatic tangent and curve generation following professional civil engineering workflows."
  - image_path: /assets/images/feature-vertical.svg
    alt: "Vertical Profiles"
    title: "📈 Vertical Profiles"
    excerpt: "PVI-based profiles with parabolic vertical curves, matching Civil 3D and OpenRoads methodologies."
  - image_path: /assets/images/feature-georef.svg
    alt: "Georeferencing"
    title: "🌍 Georeferencing"
    excerpt: "Survey-grade accuracy with 6,000+ coordinate reference systems via PyProj integration."

feature_row2:
  - image_path: /assets/images/feature-crosssection.svg
    alt: "Cross-Sections"
    title: "📐 Cross-Sections"
    excerpt: "AASHTO-compliant templates with parametric lane widths, shoulders, and side slopes."
  - image_path: /assets/images/feature-ifc.svg
    alt: "Native IFC"
    title: "📄 Native IFC 4.3"
    excerpt: "True native IFC authoring — your infrastructure designs are IFC from the start, not converted to it."
  - image_path: /assets/images/feature-blender.svg
    alt: "Blender Powered"
    title: "🎨 Blender Powered"
    excerpt: "Built on Blender's world-class 3D platform. Free, open source, and incredibly capable."

feature_row3:
  - image_path: /assets/images/feature-blender.svg
    alt: "Saikei Civil in action"
    title: "See It In Action"
    excerpt: "Saikei Civil integrates directly into Blender, providing professional civil engineering tools in an open-source environment. Design alignments, create profiles, and generate IFC-compliant infrastructure models."
    url: "https://github.com/saikeicivil/SaikeiCivil"
    btn_label: "Learn More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" %}

---

## Development Roadmap
{: .text-center}

<div class="roadmap-container" markdown="0">
  <div class="roadmap-item complete">
    <div class="roadmap-marker">✓</div>
    <div class="roadmap-content">
      <h4>Phase 1: Foundation</h4>
      <p>Alignments, Georeferencing, Vertical Profiles</p>
      <span class="roadmap-status">Complete</span>
    </div>
  </div>
  
  <div class="roadmap-item current">
    <div class="roadmap-marker">●</div>
    <div class="roadmap-content">
      <h4>Phase 2: Cross-Sections & Corridors</h4>
      <p>Assembly templates, corridor generation, 3D modeling</p>
      <span class="roadmap-status">In Progress — Sprint 5</span>
    </div>
  </div>
  
  <div class="roadmap-item">
    <div class="roadmap-marker">○</div>
    <div class="roadmap-content">
      <h4>Phase 3: Advanced Modeling</h4>
      <p>Earthwork, drainage, utilities, grading</p>
      <span class="roadmap-status">Planned</span>
    </div>
  </div>
  
  <div class="roadmap-item">
    <div class="roadmap-marker">○</div>
    <div class="roadmap-content">
      <h4>Phase 4: Enterprise & Ecosystem</h4>
      <p>Collaboration, import/export, extensions</p>
      <span class="roadmap-status">Planned</span>
    </div>
  </div>
</div>

---

## Why Open Source?
{: .text-center}

Professional civil engineering software costs **$5,000–$10,000 annually**, putting it out of reach for small firms, students, and engineers in developing countries. Saikei Civil aims to **democratize these tools** while advancing open standards.

By building on **IFC 4.3** — the international standard for infrastructure BIM — we're creating tools that work *with* any compliant software, not against it.

<div class="text-center" markdown="0">
  <a href="https://github.com/saikeicivil/SaikeiCivil" class="btn btn--primary btn--large"><i class="fab fa-github"></i> Explore the Code</a>
  <a href="https://linkedin.com/company/saikeicivil" class="btn btn--inverse btn--large"><i class="fab fa-linkedin"></i> Follow Updates</a>
</div>

---

## Get Involved
{: .text-center}

Saikei Civil welcomes contributors of all kinds:

| Role | How You Can Help |
|------|------------------|
| **Civil Engineers** | Validate workflows, suggest features, test designs |
| **Developers** | Contribute code, tests, or documentation |
| **Designers** | Help with UI/UX and visual design |
| **Testers** | Try it out and report issues |
| **Advocates** | Share the project, write tutorials, spread the word |

---

## About
{: .text-center}

**Saikei Civil** is developed by **Michael Yoder, PE** at **Desert Springs Civil Engineering PLLC** in Nampa, Idaho.

The name "Saikei" (栽景) refers to the Japanese art of creating miniature planted landscapes — the perfect complement to Bonsai's focus on individual trees. Together, they represent a complete vision for open-source BIM.

*Saikei Civil is part of the [OSArch](https://osarch.org) open-source architecture community and built on [IfcOpenShell](https://ifcopenshell.org).*
