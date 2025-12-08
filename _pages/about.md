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

Saikei Civil is the world's first open-source **native IFC authoring tool** for horizontal infrastructure. While tools like [Bonsai](https://bonsaibim.org) excel at vertical construction (buildings), Saikei shapes the world around them — roads, alignments, corridors, and earthwork.

Built as a Blender extension, Saikei Civil creates **IFC 4.3** files as its native format — not as an export target. This "native IFC" philosophy means your infrastructure designs are truly interoperable from the start.

> *"While Bonsai crafts the buildings, Saikei shapes the world around them."*

## The Name

**Saikei** (栽景) is the Japanese art of creating miniature planted landscapes — tray landscapes that depict natural scenery. It's the perfect complement to Bonsai's focus on individual trees.

Together, Bonsai and Saikei represent a complete vision for open-source BIM:
- **Bonsai** → Buildings (vertical construction)
- **Saikei** → Infrastructure (horizontal construction)

The word combines:
- 栽 (*sai*) — to plant, to cultivate
- 景 (*kei*) — scenery, landscape

Our tagline, *"Cultivating Open Infrastructure,"* reflects this meaning.

## Why Open Source?

Professional civil engineering software costs **$5,000–$10,000 annually**, putting it out of reach for:

- 🏢 **Small firms** trying to compete with larger companies
- 🎓 **Students** learning infrastructure design
- 🌍 **Engineers in developing countries** who can't access expensive tools
- 🔬 **Researchers** who need transparent, modifiable software

Saikei Civil aims to **democratize these tools** while advancing open standards.

### The Native IFC Advantage

Traditional BIM workflows look like this:

```
.dwg → .rvt → .ifc (export)
```

Data is lost at every conversion. The IFC file is an afterthought.

**Saikei Civil flips this:**

```
.ifc = Source of Truth
```

By building on **IFC 4.3** — the international standard for infrastructure BIM — we create tools that work *with* any compliant software, not against it.

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

Michael is a licensed Professional Engineer with a passion for making civil engineering tools accessible to everyone. He believes that open standards and open-source software are the future of infrastructure design.

## Part of the OSArch Ecosystem

Saikei Civil is proud to be part of the [OSArch](https://osarch.org) (Open Source Architecture) community, alongside:

- **Bonsai** — Native IFC for buildings
- **IfcOpenShell** — The open-source IFC toolkit
- **BlenderBIM** ecosystem tools

We share the vision of a truly open, interoperable built environment.

---

<div class="text-center" markdown="1">

[View the Roadmap](/roadmap/){: .btn .btn--primary .btn--large}
[Get Involved](/contribute/){: .btn .btn--inverse .btn--large}

</div>
