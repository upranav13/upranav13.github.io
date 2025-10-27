---
title: "Camouflage experiment: testing the adaptive value of patterns"
layout: single
permalink: /research/camouflage/
author_profile: true
classes: wide
---

## Simulating predation with a computer game

To test whether the stripes and spots seen in some squirrels provide camouflage advantages, I designed a computer simulation experiment inspired by classical predator–prey studies. Using Adobe Illustrator, I created three squirrel morphs — plain, striped, and spotted — simplified to standard shapes to control for size and brightness differences. These morphs were then placed against backgrounds of varying visual complexity (simple vs. complex) to test how quickly they could be detected.
 
<img src="/assets/images/research/morphs.png" alt="Squirrel morphs" style="max-width:100%; border-radius:8px; margin:12px 0;">

**Figure 1.** Squirrel morphs used in the experiment — (a) plain, (b) spotted, (c) striped — designed from real squirrel patterns but standardized for shape and colour. 
---

## Designing realistic backgrounds

The backgrounds were digitally constructed using geometric shapes to mimic natural environments of different structural complexity. Complexity levels were quantified using diversity indices and edge-detection analyses in ImageJ, ensuring that “complex” backgrounds contained significantly more visual elements than “simple” ones.
 
<img src="/assets/images/research/backgrounds.png" alt="Example backgrounds" style="max-width:100%; border-radius:8px; margin:12px 0;">

**Figure 2.** Example backgrounds used in the experiment: (a,b) complex environments with high visual diversity; (c,d) simple environments with low visual diversity. 

---

## The interactive experiment

The game was built using Scratch and displayed on touchscreen tablets during IISER Tirupati’s Science Day. Participants acted as “predators,” trying to find and tap hidden squirrel morphs on-screen. Each morph appeared in both simple and complex environments, and the game recorded  
(1) how long it took to find each squirrel and  
(2) how many were found within 15 seconds.
 
<img src="/assets/images/research/game-screens.png" alt="Game screens" style="max-width:100%; border-radius:8px; margin:12px 0;">

**Figure 3.** Screens from the game showing (a) instructions and reference morphs, (b) active search screen, and (c–d) post-game results showing average search times and detection rates. 

---

## Results: patterns improve camouflage in complex environments

Data from 49 players showed clear patterns:

- Striped and spotted squirrels took significantly longer to find on complex backgrounds, indicating a camouflage advantage through disruptive colouration.  
- Plain squirrels were equally detectable across environments.  
- The percentage of patterned squirrels “caught” was much lower in complex habitats, reinforcing that visual patterns can reduce detection probability.

<!-- SIDE-BY-SIDE FIGURES 4 & 5 -->
<div style="display:grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 20px;
            align-items:start;
            margin: 1rem 0;">

  <div style="text-align:center;">
    <img src="/assets/images/research/search-time.png"
         alt="Mean search time for squirrel morphs"
         style="width:100%; height:260px; object-fit:contain; background:#fafafa; border-radius:8px;">
    <p style="font-size:0.9rem; color:#555; margin-top:6px;">
      <strong>Figure 4.</strong> Mean search time for different squirrel morphs across background types. Patterned morphs took longer to detect in complex habitats.
    </p>
  </div>

  <div style="text-align:center;">
    <img src="/assets/images/research/catch-rate.png"
         alt="Percentage of squirrels caught"
         style="width:100%; height:260px; object-fit:contain; background:#fafafa; border-radius:8px;">
    <p style="font-size:0.9rem; color:#555; margin-top:6px;">
      <strong>Figure 5.</strong> Percentage of squirrels “caught” in simple vs. complex backgrounds. Patterned morphs were found less often in complex settings.
    </p>
  </div>

</div>

---

## Summary

This experiment provided experimental evidence that dorsal patterns can act as camouflage in visually complex environments. While the field-based meta-analysis found weak statistical correlations between pattern and habitat complexity, this simulation confirmed that such patterns do provide functional advantages under controlled conditions. The results illustrate how natural selection via predation pressure can shape coat-pattern diversity in squirrels and other mammals.
