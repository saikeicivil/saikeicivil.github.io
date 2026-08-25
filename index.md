---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#2d5a27"
  overlay_filter: "0.6"
  overlay_image: /assets/images/hero-bg.svg
excerpt: >
  Native-IFC authoring for roads, alignments, and corridors — contributed upstream into Bonsai and IfcOpenShell.

intro:
  - excerpt: '**Native IFC 4.3** · **Built on Blender and IfcOpenShell** · **Contributed upstream**'

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

## What the work covers

Infrastructure modelling capability for horizontal civil engineering, authored natively in IFC.

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

## What Saikei Civil is

Saikei Civil (栽景) is the name I give to my own contributions extending native-IFC authoring to civil infrastructure. It is not a standalone product, and no party holds exclusive rights in it. The work is contributed upstream into [Bonsai](https://bonsaibim.org) and [IfcOpenShell](https://ifcopenshell.org), and lives under those projects' licenses.

Built natively on IFC 4.3, designs travel between applications and remain accessible throughout the asset lifecycle.

### Upstream

<ul style="list-style:none;padding:0;font-size:0.95rem;">
  <li><a href="https://github.com/IfcOpenShell/IfcOpenShell/pull/9304">#9304 — horizontal alignment authoring foundation for Bonsai, plus alignment API fixes</a> · opened August 15, 2026</li>
  <li><a href="https://github.com/IfcOpenShell/IfcOpenShell/pull/9305">#9305 — Windows build artifact collection for underscore-prefixed plugin DLLs</a> · opened August 15, 2026</li>
</ul>

This is my **Google Summer of Code 2026** project.

[About the Project](/about/){: .btn .btn--primary .btn--large}
[Capabilities](/demo/){: .btn .btn--inverse .btn--large}

---

*Michael Yoder, PE · Meridian, Idaho*

</div>
