---
title: Small-part machining tutorial
order: 3
category: CNC / Training
summary: Reverse engineered a steel shelf bracket, machined it in aluminum, and made an instructional video on milling small parts for the lab's students.
hero: /assets/img/projects/shelf-bracket/cover.jpg
hero_alt: The original steel bracket, a black 3D-printed test version and two machined aluminum copies in a row, beside two tool holders with small end mills
facts:
  - label: Role
    value: Rapid Prototyping Lab Technician, Virginia Tech
  - label: When
    value: Summer 2026
  - label: Tools
    value: Fusion (CAD/CAM), Tormach PCNC 440, FDM 3D printing
  - label: Output
    value: Instructional video on milling small parts and brackets
---

## Goal

Make an instructional video on machining strategies for small parts and brackets, using a real part from the lab: an existing steel shelf bracket.

## Reverse engineering

I measured the existing steel bracket, modeled it in Fusion, and 3D printed test versions to check the model before machining.

<figure class="figure figure-wide">
  <a href="{{ '/assets/img/projects/shelf-bracket/parts-labeled.jpg' | relative_url }}"><img src="{{ '/assets/img/projects/shelf-bracket/parts-labeled.jpg' | relative_url }}" alt="Four brackets labeled: a black 3D-printed test, a partially machined aluminum part without its hook slot, the original steel bracket, and the finished machined bracket" loading="lazy"></a>
  <figcaption>From the original part to the finished copy.</figcaption>
</figure>

{% include figure.html src="/assets/img/projects/shelf-bracket/cad.png" caption="CAD model of the bracket." alt="CAD model of the small hook-shaped shelf bracket" %}

## CAM

Adaptive roughing, 2D contours and a trace operation, with 14:29 of total machining time.

{% include figure.html src="/assets/img/projects/shelf-bracket/cam.png" caption="Setup and operations in Fusion CAM." alt="Fusion CAM setup for the shelf bracket showing adaptive, contour and trace operations on the stock" %}

## Machining and workholding

The video covered workholding constraints and tooling choices for small parts. The stock is held mainly by screws and clamps. Painter's tape and superglue only hold the part as the final passes free it from the stock.

<div class="gallery gallery-tall">
{% include figure.html src="/assets/img/projects/shelf-bracket/tooling.jpg" caption="Tooling and finished parts." alt="Tool holders with small end mills beside finished brackets" %}
{% include figure.html src="/assets/img/projects/shelf-bracket/workholding-1.jpg" caption="Stock plate with screw holes, backed with painter's tape." alt="Aluminum stock plate with screw holes and painter's tape, with finished brackets nearby" %}
{% include figure.html src="/assets/img/projects/shelf-bracket/workholding-2.jpg" caption="Painter's tape and superglue, used to hold the part as it's freed." alt="Stock plate covered in painter's tape beside a tube of superglue" %}
{% include figure.html src="/assets/img/projects/shelf-bracket/machined-pocket.jpg" caption="Part held by the tape as it's freed from the stock." alt="Bracket machined into aluminum stock on the mill, with painter's tape around it and chips" %}
</div>

## Video

The final output was an instructional video for the lab's students.

{% include figure.html src="/assets/img/projects/shelf-bracket/video-still.jpg" caption="Still from the instructional video: stock clamped on the Tormach PCNC 440." alt="Aluminum stock clamped to the table of a Tormach PCNC 440 mill" %}
