---
title: Two-sided aluminum coaster production
order: 1
category: CNC / CAM
summary: Overhauled an early-stage CAM program into a repeatable, two-sided production workflow the department still runs.
hero: /assets/img/projects/cnc-coaster/hero.jpg
hero_alt: Finished two-sided aluminum coaster held in hand
card_image: /assets/img/projects/cnc-coaster/batch-six.jpg
result: 5.5 → 2.75 hrs
result_note: Total time per part, including setup, prep and machining. Cycle time alone went from 42 to 37 min.
facts:
  - label: Role
    value: CNC/CAM Technician, Wesleyan College of Design and Engineering Studies
  - label: Tools
    value: Fusion CAM, Tormach PCNC 1100
  - label: When
    value: April 2026 – present
  - label: Status
    value: In departmental use
---

## Goal

Cut the total time per part, improve surface finish, and make two-sided production repeatable.

## Baseline

I used a part from the original program as a baseline. The pocket floors had a poor finish, and a lip on the edge of the chamfer kept it from being smooth.

<div class="gallery gallery-tall gallery-3">
{% include figure.html src="/assets/img/projects/cnc-coaster/baseline-chamfer-lip.jpg" caption="Baseline: a lip on the edge of the chamfer." alt="Close-up of the original coaster's chamfered edge, showing a lip" %}
{% include figure.html src="/assets/img/projects/cnc-coaster/baseline-floor.jpg" caption="Baseline: poor floor finish in the pockets." alt="Original coaster's logo face with visible tool marks on the pocket floors" %}
{% include figure.html src="/assets/img/projects/cnc-coaster/baseline-back.jpg" caption="Baseline: back face." alt="Back face of the original coaster with engraved logo" %}
</div>

## What I did

- Rebuilt the CAM toolpaths for both faces and removed redundant tool changes.
- Designed end reference notches that give the second operation a reliable, repeatable locating feature.
- Reworked workholding around those notches, which eliminated a bandsaw operation between milling steps, along with several other non-CNC processing steps.

## CAM

### Chamfer and engraving: 9:20 → 6:06

In the original program, the top-face chamfer and engraving took 9:20 of machining time. The rebuilt operations cover the same features in 6:06, and the full program uses fewer tool changes.

<div class="gallery gallery-cad gallery-wide">
{% include figure.html src="/assets/img/projects/cnc-coaster/cam-time-old.png" caption="Original program: chamfer and engraving, 9:20." alt="Fusion CAM showing the original program's three chamfer and engraving operations with a total machining time of 9 minutes 20 seconds" %}
{% include figure.html src="/assets/img/projects/cnc-coaster/cam-time-new.png" caption="Rebuilt program: chamfer, CODES and year engraving, 6:06." alt="Fusion CAM showing the rebuilt program's chamfer and engraving operations with a total machining time of 6 minutes 6 seconds" %}
</div>

### Floor finish

The baseline's poor floor finish was fixed with a roughing pass followed by custom finishing passes on the pocket floors.

<div class="gallery gallery-cad gallery-3">
{% include figure.html src="/assets/img/projects/cnc-coaster/cam-roughing.png" caption="Roughing pass on the pocket floor." alt="2D pocket roughing toolpath on the coaster's logo face" %}
{% include figure.html src="/assets/img/projects/cnc-coaster/cam-floor-scallop.png" caption="Custom floor finish: scallop pass." alt="Scallop finishing toolpath on a pocket floor" %}
{% include figure.html src="/assets/img/projects/cnc-coaster/cam-floor-inner.png" caption="Custom floor finish: inner pocket contour." alt="Contour finishing toolpath around the inner pocket" %}
</div>

### Toolpaths

<div class="gallery gallery-cad gallery-2">
{% include figure.html src="/assets/img/projects/cnc-coaster/cam-side-1.png" caption="Side 1 CAM: rebuilt toolpaths for the logo face, with fewer tool changes." alt="Fusion CAM toolpaths for side 1, the logo face of the hexagonal coaster" %}
{% include figure.html src="/assets/img/projects/cnc-coaster/cam-side-2.png" caption="Side 2 CAM: corner pockets and back-face engraving." alt="Fusion CAM toolpaths for side 2" %}
</div>

## Machining

Stock is first cut into 5 × 5 squares on the bandsaw. That step stayed; the bandsaw step I removed came later, between milling operations.

<div class="gallery gallery-tall gallery-3">
{% include figure.html src="/assets/img/projects/cnc-coaster/stock-cut.jpg" caption="Cutting stock into 5 × 5 squares on the bandsaw." alt="Aluminum plate being cut into square blanks on a bandsaw" %}
{% include figure.html src="/assets/img/projects/cnc-coaster/end-notches.jpg" caption="Machining the end reference notches." alt="End mill with coolant machining notches into the end of the aluminum stock" %}
{% include figure.html src="/assets/img/projects/cnc-coaster/side-1-in-vise.jpg" caption="Side 1 machined into the plate stock, held in the vise." alt="Side 1 machined into aluminum plate stock, held in the mill vise" %}
</div>

### Flycut clearance

The flycutter ran very close to the rotary axis. I set up the toolpath so the flycutter cleared it while still leaving the flycut finish I wanted.

<div class="gallery gallery-tall gallery-2">
{% include figure.html src="/assets/img/projects/cnc-coaster/flycut-clearance-1.jpg" caption="Flycutter passing close to the rotary axis." alt="Flycutter on the mill spindle positioned just past the rotary axis" %}
{% include figure.html src="/assets/img/projects/cnc-coaster/flycut-clearance-2.jpg" caption="Clearance between the flycutter and the rotary axis." alt="Second view of the flycutter clearing the rotary axis" %}
</div>

## Result

Time per part was cut in half, from 5.5 to 2.75 hours, with better surface finish across all features. The department still uses the workflow.

<div class="gallery">
{% include figure.html src="/assets/img/projects/cnc-coaster/first-front.jpg" caption="My first coaster from the new program, logo face." alt="First coaster from the new program, logo face, held in hand" %}
{% include figure.html src="/assets/img/projects/cnc-coaster/first-back.jpg" caption="First coaster, back face." alt="First coaster from the new program, back face with engraved logo" %}
{% include figure.html src="/assets/img/projects/cnc-coaster/batch-six.jpg" caption="A small production batch." alt="Six finished coasters laid out on a table" %}
{% include figure.html src="/assets/img/projects/cnc-coaster/batch-front.jpg" caption="Batch parts, logo face." alt="Several finished coasters showing the logo face" %}
</div>

## Next

I designed soft jaws to further improve production. They're being made next.

{% include figure.html src="/assets/img/projects/cnc-coaster/soft-jaws.png" caption="Soft jaw design." alt="CAD model of a soft jaw with a locating ledge and two mounting holes" %}
