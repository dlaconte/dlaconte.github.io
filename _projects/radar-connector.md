---
title: Injection-molded wireless power connector
order: 2
category: Injection molding
summary: Designed and injection molded a polypropylene bracket that gives my radar detector a magnetic power connection to its mount, iterating on 3D-printed mold inserts.
hero: /assets/img/projects/radar-connector/final-brackets.jpg
hero_alt: Two finished black molded brackets with magnetic pogo-pin connectors set into them
card_image: /assets/img/projects/radar-connector/final-brackets.jpg
facts:
  - label: Role
    value: Solo project for a class (design, molds, molding)
  - label: Process
    value: 120 psi benchtop injection molder
  - label: Material
    value: Polypropylene
  - label: Mold inserts
    value: PETG (FDM) for early iterations, then SLA resin once the geometry was settled
---

## Goal

Replace the cable taped to my radar detector's mount with a clean power connection: a bracket that holds a magnetic pogo-pin connector, so the detector connects to power when it's set on the mount.

<div class="gallery gallery-tall">
{% include figure.html src="/assets/img/projects/radar-connector/before-taped-cable.jpg" caption="Before: the power cable plugged into the detector and taped along the mount." alt="Radar detector on its suction mount with a braided power cable taped to it" %}
{% include figure.html src="/assets/img/projects/radar-connector/fit-check-print.jpg" caption="Fit check with 3D-printed bracket prototypes before molding." alt="Yellow 3D-printed bracket prototypes fitted to the radar detector and mount" %}
</div>

## Design

I modeled the bracket and the connector in Fusion. The connector pocket is sized to the magnetic pogo-pin connector: a 14.50 × 4.00 mm slot with Ø3.00 mm magnet holes and Ø1.50 mm pin holes.

<div class="gallery gallery-cad gallery-3">
{% include figure.html src="/assets/img/projects/radar-connector/cad-bracket.png" caption="Bracket model, with the connector slot and mounting hole." alt="CAD model of the bracket with an oval connector slot and a mounting hole in one tab" %}
{% include figure.html src="/assets/img/projects/radar-connector/cad-connector.png" caption="Model of the magnetic pogo-pin connector, used to size its pocket." alt="CAD model of the pogo-pin connector with two magnet faces and two pin holes" %}
{% include figure.html src="/assets/img/projects/radar-connector/cad-connector-sketch.png" caption="Connector pocket sketch: 14.50 × 4.00 mm slot, Ø3.00 magnet and Ø1.50 pin holes." alt="Dimensioned sketch of the connector pocket" %}
</div>

## Mold setup

An aluminum mold frame holds a pair of interchangeable insert halves, so each new design only needs new inserts. The inserts were sized to the frame's pockets, and the frame's pins keep the halves aligned. Parts were shot in polypropylene on a 120 psi benchtop molder.

<div class="gallery gallery-tall">
{% include figure.html src="/assets/img/projects/radar-connector/benchtop-molder.jpg" caption="120 psi benchtop injection molder with the mold clamped in its vise." alt="Benchtop injection molder with a heated barrel over an aluminum mold held in a vise" %}
{% include figure.html src="/assets/img/projects/radar-connector/mold-open.jpg" caption="Mold open, showing both insert halves, the gate and the runner." alt="Two aluminum mold frame halves holding black printed inserts, with gate and runner visible" %}
{% include figure.html src="/assets/img/projects/radar-connector/mold-pocket-calipers.jpg" caption="Measuring the frame pocket (50.85 mm) to size the inserts." alt="Digital calipers measuring the pocket of the aluminum mold frame at 50.85 mm" %}
{% include figure.html src="/assets/img/projects/radar-connector/polypropylene.jpg" caption="Polypropylene pellets: 420–430 °F setpoint, 80–120 °F mold temperature." alt="Jar of violet polypropylene pellets labeled with temperature setpoints" %}
</div>

<div class="gallery gallery-cad gallery-2">
{% include figure.html src="/assets/img/projects/radar-connector/cad-mold-cavity.png" caption="Insert half with the bracket cavity and sprue." alt="CAD model of a mold insert half with the bracket cavity and a tapered sprue" %}
{% include figure.html src="/assets/img/projects/radar-connector/cad-mold-core.png" caption="Matching half, with the raised boss that forms the connector pocket." alt="CAD model of the opposite mold insert half with a raised oval boss" %}
</div>

## Iterating with FDM inserts

Early inserts were FDM printed in PETG, which made each change to the part cheap and fast to test. Early shots had flash and incomplete fills, and the part grew from a small clip to a short bracket and then to the full L-bracket with a mounting tab.

<div class="gallery gallery-tall">
{% include figure.html src="/assets/img/projects/radar-connector/early-shot-flash.jpg" caption="An early shot on a PETG insert, with heavy flash." alt="Orange polypropylene shot over a purple printed insert, with large flash around the part" %}
{% include figure.html src="/assets/img/projects/radar-connector/fdm-insert-shot.jpg" caption="A cleaner shot on an FDM insert, sprue and runner still attached." alt="Orange FDM insert in the mold frame with a black sprue and runner" %}
{% include figure.html src="/assets/img/projects/radar-connector/shot-on-insert.jpg" caption="L-bracket shot on a PETG insert." alt="Black molded L-bracket with sprue still attached, sitting on a blue printed insert" %}
{% include figure.html src="/assets/img/projects/radar-connector/parting-line-flash.jpg" caption="Flash squeezed out at the parting line." alt="Black bracket between its mold halves with white plastic squeezed out at the parting line" %}
{% include figure.html src="/assets/img/projects/radar-connector/white-clip.jpg" caption="An early small clip version of the part." alt="Small white molded clip with a round boss" %}
{% include figure.html src="/assets/img/projects/radar-connector/all-iterations.jpg" caption="Every iteration, from small clips to the full L-bracket." alt="All molded iterations laid out, from small clips to short brackets to full L-shaped brackets" %}
</div>

## Moving to resin inserts

Once the geometry was roughly settled, I printed the inserts in SLA resin. The resin inserts have smoother surfaces and finer detail than the FDM versions, which shows directly on the molded part.

<div class="gallery gallery-tall">
{% include figure.html src="/assets/img/projects/radar-connector/resin-cure.jpg" caption="Resin inserts in the cure station." alt="Two resin mold inserts curing in a Formlabs cure station" %}
{% include figure.html src="/assets/img/projects/radar-connector/resin-vs-fdm-clip.jpg" caption="Clip inserts: FDM (orange) vs. resin (gray)." alt="Orange FDM insert pair above a gray resin insert pair for the small clip" %}
{% include figure.html src="/assets/img/projects/radar-connector/all-mold-inserts.jpg" caption="Every insert pair: PETG at top, resin at bottom." alt="Mold insert pairs laid out, PETG prints in purple, pink and tan above clear, amber and gray resin" %}
</div>

{% include figure.html src="/assets/img/projects/radar-connector/resin-vs-fdm-bracket.jpg" caption="Bracket inserts: resin (gray) vs. FDM (blue). The resin halves hold sharper edges and a smooth finish." alt="Gray resin bracket insert pair beside a blue FDM pair of the same design" %}

## Result

Molded brackets with the magnetic pogo-pin connector set in, mounting the detector without the taped cable.

<div class="gallery">
{% include figure.html src="/assets/img/projects/radar-connector/molded-vs-printed.jpg" caption="Molded brackets with connectors installed, next to a printed bracket." alt="Black molded brackets with magnetic pogo-pin connectors beside a 3D-printed bracket and a white clip" %}
{% include figure.html src="/assets/img/projects/radar-connector/final-brackets.jpg" caption="Final parts: the full L-bracket and the short bracket." alt="Two finished black molded brackets with pogo-pin connectors" %}
</div>

