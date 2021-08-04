---
widget: blank
active: false
headless: true
design:
# Choose how many columns the section has. Valid values: 1 or 2.
  columns: 1
weight: 20  # Order that this section will appear.

title: RDH Roadmap
subtitle: Draft version 0.9 (4-Aug-2021)
---

**DRAFT** Research Data Handling roadmap for The University of the West Indies, Cave Hill campus.

The Research Data Handling (RDH) Roadmap is a living document. Version 1, covering the period 2020-2022, has been approved by the Cave Hill campus Research Data Handling committee _(meeting metadata...)_. <mark>You can read more about the RDH committee here</mark>.

Version 1 of the RoadMap includes objectives falling under **seven** main categories:

1. **Plan and Design:**
   Support and services for planning activities that are typically performed before research data is collected or created.
2. **Collect and Capture:**
   The facilities to collect and store active data (data that is actively being used in current research activities), and to provide access to that storage through a number of channels. 
3. **Process and Analyse:** 
   Facilities to prepare data for analysis, and for analysing and interpreting the data resources.
4. **Store and Preserve:**
   Tools and services to aid in the description, deposit, and ongoing management of completed research data outputs.
5. **Share, Publish and Discover:** 
   Support and services for best-practices sharing of research data
6. **Training and Support:** 
   General Research Data Handling training, support and consultancy services 
7. **RDH Operations:** 
   Planning and organisational activities for RDH implementation team
### RDH implementation timeline
Version 1 of our roadmap covers the period from Sep 2020 when our RDH project began until Aug 2022. This first period covers phases 0 and 1 of the implementation process. 
- **Phase 0** _(Sep 2020 - Aug 2021)_ is largely a planning phase, with some pilot activity and early deliverables.
- **Phase 1** _(Sep 2021 - Aug 2022)_ involves initial rollout of primary services.
Phase 1 will include an assessment of progress, with the addition of further phases.

{{% staticref "uploads/RDH-roadmap-v1.pdf" "newtab" %}}Download this document{{% /staticref %}} for full details of RoadMap phases 0 and 1. Use the document in conjunction with these Gantt charts.

### RDH RoadMap Gantt charts (Phase 0)

<!-- PLAN and DESIGN phase 0 -->
```mermaid
gantt
  title 1. PLAN and DESIGN (Sep 2020 to Aug 2021)
  dateFormat  YYYY-M
  axisFormat  %b
  todayMarker stroke-width:5px,stroke:#fb2d50,opacity:0.25

  %% section 1 - PLAN AND DESIGN (PHASE 0)
  section (1.0)
  Plan RoadMap                 : done , a1-0, 2020-09, 12w
  section (1.1)
  Assess DMP Online            : a1-1, 2021-1, 12w
  section (1.2)
  Customise DMP Online         : a1-2, after a1-1, 16w
  section (1.5)
  Guidance documents...           : a1-5, 2021-4 , 2021-9
  ```


```mermaid
gantt
       dateFormat  YYYY-MM-DD
       title Adding GANTT diagram functionality to mermaid

       section A section
       Completed task            :done,    des1, 2014-01-06,2014-01-08
       Active task               :active,  des2, 2014-01-09, 3d
       Future task               :         des3, after des2, 5d
       Future task2              :         des4, after des3, 5d

       section Critical tasks
       Completed task in the critical line :crit, done, 2014-01-06,24h
       Implement parser and jison          :crit, done, after des1, 2d
       Create tests for parser             :crit, active, 3d
       Future task in critical line        :crit, 5d
       Create tests for renderer           :2d
       Add to mermaid                      :1d

       section Documentation
       Describe gantt syntax               :active, a1, after des1, 3d
       Add gantt diagram to demo page      :after a1  , 20h
       Add another diagram to demo page    :doc1, after a1  , 48h

       section Last section
       Describe gantt syntax               :after doc1, 3d
       Add gantt diagram to demo page      :20h
       Add another diagram to demo page    :48h
```
