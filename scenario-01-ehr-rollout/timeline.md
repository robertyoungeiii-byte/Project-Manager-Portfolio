# Rollout Timeline — EHR System Rollout

> **Note:** This is a fictional case study created to demonstrate technical 
> project management skills. It is not based on a real employer, client, 
> or project.

## Phase Overview

| Phase | Timeframe | Key Activities |
|-------|-----------|-----------------|
| Planning & Vendor Kickoff | Month 1–2 | Charter approval, vendor contract finalized, pilot site selected, project team assembled |
| Pilot Site Build | Month 3–4 | System configuration, data migration testing, staff training design, workflow mapping |
| Pilot Go-Live & Stabilization | Month 5 | Pilot site cutover, hypercare support, issue resolution, workflow refinement |
| Phased Rollout | Month 6–8 | Sites 2–6 configured and launched in staggered waves (roughly 1 site every 2–3 weeks) |
| Final Go-Live & Closeout | Month 9 | Final site live, legacy system decommissioned, post-implementation review, project closeout |

## Detailed Gantt View (Mermaid)

```mermaid
gantt
    title EHR System Rollout — 9 Month Timeline
    dateFormat  YYYY-MM-DD
    section Planning
    Charter & Vendor Kickoff     :a1, 2025-01-01, 30d
    Pilot Site Selection         :a2, after a1, 15d
    section Pilot
    System Configuration         :b1, after a2, 30d
    Data Migration Testing       :b2, after a2, 30d
    Staff Training (Pilot)       :b3, after b1, 15d
    Pilot Go-Live                :milestone, after b3, 0d
    Hypercare & Stabilization    :b4, after b3, 30d
    section Phased Rollout
    Site 2 Go-Live                :c1, after b4, 20d
    Site 3 Go-Live                :c2, after c1, 20d
    Site 4 Go-Live                :c3, after c2, 20d
    Site 5 Go-Live                :c4, after c3, 20d
    Site 6 Go-Live                :c5, after c4, 20d
    section Closeout
    Legacy System Decommission    :d1, after c5, 15d
    Post-Implementation Review    :d2, after d1, 15d
