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

## Why Open Source?

Open source tools empower every community to build sustainable infrastructure, foster innovation through shared knowledge, and accelerate solutions to the  most pressing infrastructure needs. 

- **Small and mid-size firms** competing for infrastructure projects
- **Students** learning infrastructure design workflows
- **Engineers in developing regions** with limited software budgets
- **Researchers** requiring transparent, modifiable tools

Saikei Civil provides these capabilities while advancing open standards adoption.

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
| **Language** | Python 3.11+ |
| **License** | GPL v3 |

## The Developer

**Saikei Civil** is developed by **Michael Yoder, PE** at **Desert Springs Civil Engineering PLLC** in Nampa, Idaho.

Michael is a licensed Professional Engineer focused on making civil engineering tools accessible through open standards and open-source software.

## Part of the OSArch Ecosystem

Saikei Civil is part of the [OSArch](https://osarch.org) (Open Source Architecture) community, alongside:

- **Bonsai** — Native IFC for buildings
- **IfcOpenShell** — The open-source IFC toolkit
- **BlenderBIM** ecosystem tools

These projects share a vision of an open, interoperable built environment.

---

<div class="text-center" markdown="1">

[View the Roadmap](/roadmap/){: .btn .btn--primary .btn--large}
[Get Involved](/contribute/){: .btn .btn--inverse .btn--large}

</div>
