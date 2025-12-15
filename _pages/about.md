---
layout: single
title: "About Saikei Civil"
permalink: /about/
author_profile: false
toc: true
toc_label: "On This Page"
toc_icon: "leaf"
---

## What is Saikei Civil?

Saikei Civil is an open-source **native IFC authoring tool** for horizontal infrastructure. While tools like [Bonsai](https://bonsaibim.org) address vertical construction (buildings), Saikei handles roads, alignments, corridors, and earthwork.

Built as a Blender extension, Saikei Civil creates **IFC 4.3** files as its native format—not as an export target. This native IFC approach means infrastructure designs are interoperable from initial creation.

## The Name

**Saikei** (栽景) is the Japanese art of creating miniature planted landscapes—tray landscapes depicting natural scenery. The name complements Bonsai's focus on individual trees.

Together, Bonsai and Saikei represent a complete approach to open-source BIM:
- **Bonsai** — Buildings (vertical construction)
- **Saikei** — Infrastructure (horizontal construction)

The word combines:
- 栽 (*sai*) — to plant, to cultivate
- 景 (*kei*) — scenery, landscape

## Why Open Standards?

Infrastructure projects involve dozens of stakeholders using different software across decades-long asset lifecycles. Open standards solve this coordination problem.

**IFC 4.3** is the buildingSMART standard for infrastructure data exchange. By building natively on IFC, Saikei Civil creates designs that:

- Travel between applications without data loss
- Remain accessible regardless of vendor changes
- Support the full project lifecycle from design through operations

### Who Benefits

- **Large firms and agencies** coordinating complex project teams across multiple software platforms
- **Small and mid-size firms** delivering to clients with varying BIM requirements
- **Students and educators** learning infrastructure design with industry-standard formats
- **Researchers** requiring transparent, modifiable tools for analysis

### The Native IFC Approach

Traditional BIM workflows follow this pattern:

```
.dwg → .ifc (export)
```
```
.rvt → .ifc (export)
```
```
.dgn → .ifc (export)
```

Data degrades at each conversion. The IFC file becomes an afterthought.

**Saikei Civil works differently:**

```
.ifc = Source of Truth
```

By building on **IFC 4.3**—the international standard for infrastructure BIM—the software creates files that work with any compliant application.

## Technology Stack

| Component | Technology |
|-----------|------------|
| **Platform** | [Blender](https://blender.org) 4.5+ |
| **IFC Engine** | [IfcOpenShell](https://ifcopenshell.org) |
| **Coordinate Systems** | [PyProj](https://pyproj4.github.io/pyproj/) |
| **Language** | Python 3.13+ |
| **License** | GPL v3 |

## The Developer

**Saikei Civil** is developed by **Michael Yoder, PE** through **Desert Springs Civil Engineering PLLC** in Meridian, Idaho.

Michael is a licensed Professional Engineer (Idaho, Indiana) with over 14 years of civil engineering experience. He holds a B.S. in Civil Engineering from Purdue University (2010) and has worked across multiple sectors of the industry:

| Experience | Focus |
|------------|-------|
| **Bureau of Reclamation** | Federal water infrastructure projects |
| **HDR** | Transportation and infrastructure consulting |
| **Regional Firms** | Roadway design, water projects, construction inspection |

This breadth of experience—from construction inspection to federal infrastructure—informs Saikei Civil's design as a practical tool for working engineers.

## Part of the OSArch Ecosystem

Saikei Civil is part of the [OSArch](https://osarch.org) (Open Source Architecture) community, alongside:

- **Bonsai** — Native IFC for buildings
- **IfcOpenShell** — The open-source IFC toolkit

These projects share a vision of an open, interoperable built environment.

---

<div class="text-center" markdown="1">

[View the Roadmap](/roadmap/){: .btn .btn--primary .btn--large}
[Get Involved](/contribute/){: .btn .btn--inverse .btn--large}

</div>
