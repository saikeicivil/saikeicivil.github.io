---
layout: single
title: "Development Roadmap"
permalink: /roadmap/
author_profile: false
toc: true
toc_label: "Development"
toc_icon: "road"
---

Saikei Civil is under active development with a capability-driven approach. Features are built to production quality before moving forward.

---

## Current Capabilities

Core infrastructure design tools ready for use today.

| Capability | Status | Description |
|------------|--------|-------------|
| **Horizontal Alignments** | Complete | PI-based design, tangent/curve generation, IFC export |
| **Vertical Profiles** | Complete | PVI-based profiles, parabolic curves, grade calculations |
| **Cross-Sections** | Complete | AASHTO templates, lane/shoulder/slope definitions |
| **Georeferencing** | Complete | CRS integration, PyProj support, sub-millimeter precision |
| **Native IFC 4.3 Export** | Complete | IfcAlignment, georeferenced output |
| **Terrain Integration** | Complete | Mesh sampling, elevation extraction |

**Metrics:**
- 30,000+ lines of production code
- 107+ tests passing (100% pass rate)
- IFC 4.3 compliance validated

---

## In Development

### Corridor Modeling

3D corridor generation combining horizontal alignments, vertical profiles, and cross-sections into complete roadway models.

| Feature | Status |
|---------|--------|
| Corridor mesh generation | Active |
| 3D visualization | Active |
| Profile view overlay | Complete |
| Station range selection | Complete |

---

## Planned

### Site Modeling

| Capability | Description |
|------------|-------------|
| **Earthwork** | Cut/fill calculations, mass haul diagrams |
| **Drainage** | Pipe networks, inlet/outlet structures |
| **Utilities** | Underground utilities, conflict detection |
| **Grading** | Surface grading, parking lots, pads |

### Interoperability

| Capability | Description |
|------------|-------------|
| **LandXML Import** | Industry-standard alignment exchange |
| **Civil 3D Import** | Autodesk Civil 3D file support |
| **OpenRoads Import** | Bentley OpenRoads file support |

---

## Ecosystem

Saikei Civil is developed in collaboration with the open-source BIM community.

| Connection | Description |
|------------|-------------|
| **OSArch Community** | Active participation in open-source architecture/engineering |
| **Bonsai Collaboration** | Coordination with the native IFC building design tool |
| **buildingSMART Engagement** | IFC 4.3 standards compliance and testing |
| **IFC MasterClass** | Professional development through BIM Corner |

---

## Version History

| Version | Highlights |
|---------|------------|
| v0.6.0 | Rebrand to Saikei Civil, cross-section foundations |
| v0.5.0 | Vertical alignment system |
| v0.4.0 | Georeferencing with PyProj |
| v0.3.0 | Horizontal alignment improvements |
| v0.2.0 | Initial IFC 4.3 support |
| v0.1.0 | Project inception |

---

<div class="text-center" markdown="1">

Interested in contributing?

[Get Involved](/contribute/){: .btn .btn--primary .btn--large}
[View on GitHub](https://github.com/saikeicivil/SaikeiCivil){: .btn .btn--inverse .btn--large}

</div>
