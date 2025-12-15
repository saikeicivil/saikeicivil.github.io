---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#2d5a27"
  overlay_filter: "0.6"
  overlay_image: /assets/images/hero-bg.svg
  actions:
    - label: "View on GitHub"
      url: "https://github.com/saikeicivil/SaikeiCivil"
    - label: "Download"
      url: "https://github.com/saikeicivil/SaikeiCivil/releases/latest"
excerpt: >
  Open-source native IFC infrastructure design software for roads, alignments, and civil engineering projects. Built on Blender and IFC 4.3 for true interoperability.

intro:
  - excerpt: '**30,000+ lines of code** · **107+ tests passing** · **Native IFC 4.3** · **Phase 1 Complete**'

feature_row:
  - image_path: /assets/images/feature-crosssection.svg
    alt: "Cross-Sections"
    title: "Cross-Sections"
    excerpt: "AASHTO-compliant templates with parametric lane widths, shoulders, and side slopes."
  - image_path: /assets/images/feature-ifc.svg
    alt: "Native IFC"
    title: "Native IFC 4.3"
    excerpt: "True native IFC authoring. Infrastructure designs are IFC from creation, not converted after the fact."
  - image_path: /assets/images/feature-blender.svg
    alt: "Blender Powered"
    title: "Blender Powered"
    excerpt: "Built on Blender's 3D platform. Free, open-source, and production-capable."
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

---

<div class="text-center" markdown="1">

## Complete Infrastructure Design Suite

Professional infrastructure modeling capabilities for horizontal civil engineering projects.

</div>

<style>
.feature-grid {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  gap: 2rem;
  max-width: 900px;
  margin: 0 auto;
  padding: 1rem;
}
.feature-grid .feature-box {
  text-align: left;
}
.feature-grid .feature-box h4 {
  margin-bottom: 0.5rem;
  font-size: 1.1rem;
}
.feature-grid .feature-box ul {
  margin: 0;
  padding-left: 1.2rem;
}
@media (max-width: 600px) {
  .feature-grid {
    grid-template-columns: 1fr;
  }
}
</style>

<div class="feature-grid">
  <div class="feature-box">
    <h4>Alignment Tools</h4>
    <ul>
      <li>Horizontal and vertical alignment creation</li>
      <li>Curve and spiral calculations</li>
      <li>Station equations and references</li>
    </ul>
  </div>
  <div class="feature-box">
    <h4>Cross-Sections</h4>
    <ul>
      <li>AASHTO-compliant templates</li>
      <li>Parametric lanes, shoulders, slopes</li>
      <li>Superelevation calculations</li>
    </ul>
  </div>
  <div class="feature-box">
    <h4>Native IFC 4.3</h4>
    <ul>
      <li>Direct IFC authoring (not conversion)</li>
      <li>Full IfcAlignment support</li>
      <li>Interoperability with major BIM platforms</li>
    </ul>
  </div>
  <div class="feature-box">
    <h4>Corridor Modeling</h4>
    <ul>
      <li>3D corridor generation</li>
      <li>Terrain integration</li>
      <li>Profile view overlay</li>
    </ul>
  </div>
</div>

---

<div class="text-center" markdown="1">

## About Saikei Civil

Saikei Civil (栽景) enables infrastructure design teams to work with open standards from day one. Built natively on IFC 4.3, designs travel between applications and remain accessible throughout the asset lifecycle.

**30,000+ lines of production-tested code** serving firms of all sizes, academic institutions, and practitioners worldwide.

[About the Project](/about/){: .btn .btn--primary .btn--large}
[Development Roadmap](/roadmap/){: .btn .btn--inverse .btn--large}
[Support the Project](/support/){: .btn .btn--inverse .btn--large}

---

*Developed by [Desert Springs Civil Engineering PLLC](https://linkedin.com/company/saikeicivil) · Meridian, Idaho*

</div>
