---
layout: single
title: "Capabilities"
permalink: /demo/
author_profile: false
toc: true
toc_label: "Features"
toc_icon: "layer-group"
---

Saikei Civil provides production-ready infrastructure design capabilities built on IFC 4.3 and Blender.

---

## Horizontal Alignments

Design road centerlines using industry-standard PI (Point of Intersection) methodology.

![Horizontal Alignment - All Elements](/assets/images/Screenshots/HZ-Align-All.png)

| Feature | Description |
|---------|-------------|
| **PI-Based Design** | Define alignments through control points with automatic tangent generation |
| **Curve Geometry** | Circular curves with configurable radii |
| **Station Equations** | Full stationing support with equation handling |
| **Real-Time Preview** | Immediate visualization as parameters change |

---

## Vertical Profiles

Create vertical alignments with grade-compliant vertical curves.

![Vertical Alignment - Profile Viewer](/assets/images/Screenshots/VT-Align-Profile-Viewer.png)

| Feature | Description |
|---------|-------------|
| **PVI-Based Design** | Vertical curves defined through Points of Vertical Intersection |
| **Parabolic Curves** | AASHTO-compliant symmetric and asymmetric curves |
| **Grade Calculations** | Automatic grade percentage computation |
| **Terrain Tracing** | Sample elevations directly from terrain mesh |

---

## Cross-Section Templates

Define roadway typical sections with parametric components.

![Cross-Section Viewer](/assets/images/Screenshots/XS-Viewer.png)

| Feature | Description |
|---------|-------------|
| **AASHTO Templates** | Pre-configured lane and shoulder widths |
| **Parametric Lanes** | Adjustable travel lanes with crown slopes |
| **Shoulders** | Inside and outside shoulders with independent slopes |
| **Side Slopes** | Cut and fill slope definitions |

---

## Corridor Modeling

Generate 3D roadway corridors by combining alignments, profiles, and cross-sections.

![Corridor 3D View](/assets/images/Screenshots/CORR-3D-View.png)

| Feature | Description |
|---------|-------------|
| **3D Mesh Generation** | Complete corridor surfaces from design data |
| **Station Range Selection** | Define corridor extents by station |
| **Profile View Overlay** | Simultaneous plan and profile visualization |
| **Terrain Integration** | Corridors follow existing ground |

---

## Georeferencing

Accurate real-world positioning through coordinate reference systems.

| Feature | Description |
|---------|-------------|
| **CRS Integration** | PyProj-powered coordinate system support |
| **EPSG Codes** | Standard coordinate reference system identifiers |
| **Sub-Millimeter Precision** | Validated accuracy for survey-grade positioning |
| **Coordinate Transforms** | Project-to-global and global-to-project conversions |

---

## Native IFC 4.3 Export

Direct authoring to the international infrastructure BIM standard.

![IFC Export](/assets/images/Screenshots/VT-Align-IFC.png)

| Feature | Description |
|---------|-------------|
| **IfcAlignment** | Full horizontal and vertical alignment export |
| **IfcAlignmentHorizontal** | Tangent and curve segment definitions |
| **IfcAlignmentVertical** | Grade and parabolic curve segments |
| **Georeferenced Output** | IFC files include coordinate reference system data |

---

## Demonstration Project

### Lucky Peak Dam Access Road — Boise, Idaho

A demonstration project showcasing Saikei Civil's alignment and cross-section capabilities for rural road infrastructure.

![Corridor Generation](/assets/images/Screenshots/CORR-Generation.png)

**Scope:**
- 2.3 km horizontal alignment with compound curves
- Vertical profile with 4% maximum grade
- Rural road cross-section (24' travel way, 4' shoulders)
- IFC 4.3 export with Idaho State Plane coordinates

---

<div class="text-center" markdown="1">

## Get Started

Download Saikei Civil and explore these capabilities in your own projects.

[Download Latest Release](https://github.com/saikeicivil/SaikeiCivil/releases/latest){: .btn .btn--primary .btn--large}
[View Source Code](https://github.com/saikeicivil/SaikeiCivil){: .btn .btn--inverse .btn--large}

</div>
