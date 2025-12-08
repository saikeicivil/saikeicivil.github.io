---
layout: single
title: "Development Roadmap"
permalink: /roadmap/
author_profile: false
toc: true
toc_label: "Phases"
toc_icon: "road"
---

Saikei Civil follows a structured 16-sprint development roadmap divided into four phases. We're currently in **Phase 2**.

---

## Phase 1: Foundation ✅
{: .phase-complete}

**Sprints 1–4 — COMPLETE**

The foundation phase established core infrastructure capabilities with production-ready code.

### Completed Features

| Sprint | Focus | Deliverables |
|--------|-------|--------------|
| Sprint 1 | Horizontal Alignments | PI-based design, tangent/curve generation, IFC export |
| Sprint 2 | Georeferencing | CRS integration, PyProj support, coordinate transforms |
| Sprint 3 | Vertical Profiles | PVI-based profiles, parabolic curves, grade calculations |
| Sprint 4 | Cross-Sections | AASHTO templates, lane/shoulder/slope definitions |

### Key Metrics

- ✅ 8,000+ lines of production code
- ✅ 107+ tests passing (100% pass rate)
- ✅ Sub-millimeter georeferencing precision
- ✅ IFC 4.3 compliance validated

---

## Phase 2: Cross-Sections & Corridors 🚧
{: .phase-current}

**Sprints 5–8 — IN PROGRESS**

Building complete 3D infrastructure models by combining alignments, profiles, and cross-sections.

### Current Sprint: Sprint 5

**Focus:** Corridor Generation

| Task | Status |
|------|--------|
| `IfcSectionedSolidHorizontal` implementation | 🔄 In Progress |
| Corridor mesh generation | 📋 Planned |
| Blender visualization integration | 📋 Planned |
| Multi-region corridor support | 📋 Planned |

### Upcoming Sprints

| Sprint | Focus | Description |
|--------|-------|-------------|
| Sprint 6 | Corridor Refinement | Transitions, superelevation, widening |
| Sprint 7 | Surface Generation | Top/bottom surfaces, subgrade modeling |
| Sprint 8 | Corridor Visualization | Real-time preview, section cuts |

---

## Phase 3: Advanced Modeling
{: .phase-planned}

**Sprints 9–12 — PLANNED**

Expanding beyond corridors to complete site modeling capabilities.

### Planned Features

| Sprint | Focus | Description |
|--------|-------|-------------|
| Sprint 9 | Earthwork | Cut/fill calculations, mass haul diagrams |
| Sprint 10 | Drainage | Pipe networks, inlet/outlet structures |
| Sprint 11 | Utilities | Underground utilities, conflict detection |
| Sprint 12 | Grading | Surface grading, parking lots, pads |

---

## Phase 4: Enterprise & Ecosystem
{: .phase-planned}

**Sprints 13–16 — PLANNED**

Professional features for team collaboration and ecosystem integration.

### Planned Features

| Sprint | Focus | Description |
|--------|-------|-------------|
| Sprint 13 | Collaboration | Multi-user editing, version control |
| Sprint 14 | Import/Export | LandXML, Civil 3D, OpenRoads import |
| Sprint 15 | Extensions API | Plugin system for custom tools |
| Sprint 16 | Documentation | Comprehensive user guides, tutorials |

---

## Project Statistics

<div class="stats-grid" markdown="0">
  <div class="stat-box">
    <span class="stat-number">25K+</span>
    <span class="stat-label">Lines of Code</span>
  </div>
  <div class="stat-box">
    <span class="stat-number">107+</span>
    <span class="stat-label">Tests Passing</span>
  </div>
  <div class="stat-box">
    <span class="stat-number">5</span>
    <span class="stat-label">Sprints Complete</span>
  </div>
  <div class="stat-box">
    <span class="stat-number">16</span>
    <span class="stat-label">Total Sprints</span>
  </div>
</div>

---

## Version History

| Version | Date | Highlights |
|---------|------|------------|
| v0.6.0 | Dec 2024 | Rebrand to Saikei Civil, cross-section foundations |
| v0.5.0 | Nov 2024 | Vertical alignment system |
| v0.4.0 | Nov 2024 | Georeferencing with PyProj |
| v0.3.0 | Oct 2024 | Horizontal alignment improvements |
| v0.2.0 | Oct 2024 | Initial IFC 4.3 support |
| v0.1.0 | Sep 2024 | Project inception |

---

<div class="text-center" markdown="1">

Want to help accelerate the roadmap?

[Get Involved](/contribute/){: .btn .btn--primary .btn--large}
[View on GitHub](https://github.com/saikeicivil/SaikeiCivil){: .btn .btn--inverse .btn--large}

</div>
