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

Saikei Civil is native-IFC authoring for horizontal infrastructure — roads, alignments, corridors, and earthwork — extending into civil what [Bonsai](https://bonsaibim.org) already does for vertical construction (buildings).

The work is contributed into Bonsai, a Blender extension, and authors **IFC 4.3** directly rather than exporting to it. That means infrastructure designs are interoperable from initial creation.

---

## The Developer

<div style="display: flex; gap: 2rem; align-items: flex-start; flex-wrap: wrap;">
<div style="flex: 1; min-width: 280px;" markdown="1">

Saikei Civil is the name I give to my own contributions extending native-IFC authoring to civil infrastructure. It is not a standalone work owned by me or by any firm, and no party holds exclusive rights in it. The work is contributed upstream into Bonsai and IfcOpenShell and lives under those projects' licenses.

I'm Michael Yoder, PE — licensed in Idaho, with 16+ years of civil engineering experience and a B.S. in Civil Engineering from Purdue University (2010). A husband and father of four, and an avid rockhound who believes the best tools are built by people who use them.

</div>
<div style="flex: 1; min-width: 280px;" markdown="1">

| Experience | Focus |
|------------|-------|
| **Federal Agencies** | Federal water infrastructure |
| **National Consultancies** | Transportation consulting |
| **Regional Firms** | Roadway design, water projects, construction inspection |

</div>
</div>

That breadth — from construction inspection to federal infrastructure — is what shapes the work into something practical for engineers who do the job.

[Connect on LinkedIn](https://linkedin.com/company/saikeicivil){: .btn .btn--inverse .btn--small}

---

## The Name

**Saikei** (栽景) is the Japanese art of creating miniature planted landscapes—tray landscapes depicting natural scenery. The name complements Bonsai's focus on individual trees.

Together, Bonsai and Saikei represent a complete approach to open-source BIM:
- **Bonsai** — Buildings (vertical construction)
- **Saikei** — Infrastructure (horizontal construction)

The word combines:
- 栽 (*sai*) — to plant, to cultivate
- 景 (*kei*) — scenery, landscape

---

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

Traditional BIM workflows treat IFC as an export format—a deliverable created at the end of the design process. This works, but information can be lost in translation.

**Saikei Civil takes a different approach:**

By authoring directly in IFC 4.3, designs maintain full fidelity from first sketch to final deliverable. The IFC file isn't a conversion—it's the source.

This complements existing tools rather than replacing them, with IFC serving as the common language for collaboration.

---

## Technology Stack

| Component | Technology |
|-----------|------------|
| **Platform** | [Blender](https://blender.org) 4.5+ |
| **IFC Engine** | [IfcOpenShell](https://ifcopenshell.org) |
| **Coordinate Systems** | [PyProj](https://pyproj4.github.io/pyproj/) |
| **Language** | Python 3.13+ |
| **License** | The upstream projects' licenses (Bonsai, IfcOpenShell) |

---

## Part of the OSArch Ecosystem

Saikei Civil is part of the [OSArch](https://osarch.org) (Open Source Architecture) community, alongside:

- **Bonsai** — Native IFC for buildings
- **IfcOpenShell** — The open-source IFC toolkit

These projects share a vision of an open, interoperable built environment.

## Interoperability First

This work is meant to sit within the broader AEC ecosystem, not against it. The IFC 4.3 files it produces open in any compliant viewer or authoring tool — commercial or open-source.

The goal isn't to replace existing workflows, but to provide an open-source option that speaks the same language as the rest of the industry.

---

<div class="text-center" markdown="1">

[Capabilities](/demo/){: .btn .btn--primary .btn--large}
[Get Involved](/contribute/){: .btn .btn--inverse .btn--large}

</div>
