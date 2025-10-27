---
title: "Phylogenetic analyses of squirrel coat colour and pattern"
layout: single
permalink: /research/phylogenetics/
author_profile: true
classes: wide
---

To understand the evolutionary history of squirrel coat traits, I compiled a global database of 280+ squirrel species with information on colour, dorsal patterns, morphology, and habitat. I built species- and genus-level phylogenetic trees using mitochondrial and nuclear gene sequences (cytb, 12s, 16s, COXI, etc.) and applied comparative methods in IQ-TREE and R (phytools, fitDiscrete). Results showed that the ancestral squirrel was likely brown and plain-coated, but darker colours evolved repeatedly in wetter habitats, consistent with Gloger’s rule. Patterns had weaker environmental associations but showed strong phylogenetic signal, suggesting they may have been shaped by past selection.

## Building the squirrel tree of life

To study how colour and patterns evolved across squirrels, I first compiled a database of more than 280 species with information on dorsal coat colour, dorsal pattern, and habitat. Using both mitochondrial and nuclear genes (*cytb, 12s, 16s, COX1*), I built species-level and genus-level phylogenetic trees for over 200 squirrel species. These trees provide the evolutionary framework to test how traits evolved and whether they were shaped by climate.

<img src="/assets/images/research/phylo-tree.png" alt="Squirrel phylogenetic tree" style="max-width:100%; border-radius:6px; margin:12px 0;">

**Figure 1.** Phylogenetic tree of ~209 squirrel species.  
*The tree was reconstructed using concatenated mitochondrial and nuclear genes with partition-specific substitution models (IQ-TREE, ultrafast bootstrap).*
---

## Mapping traits onto the tree

By mapping coat traits onto the phylogeny and reconstructing ancestral states, I found that the earliest squirrels were most likely brown and plain-coated. Darker colours and patterned coats evolved independently multiple times across lineages, suggesting repeated adaptation to environmental pressures.

<div style="display:grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px; align-items:start;">

  <div style="text-align:center;">
    <img src="/assets/images/research/colour-mapped.png"
         alt="Colour-mapped tree"
         style="width:100%; height:auto; border-radius:8px;">
    <p style="font-size:0.9rem; color:#555; margin-top:6px;">
      <strong>Figure 2.</strong> Colour-mapped tree showing that brown is the ancestral state and that darker colours evolved multiple times in wetter habitats.
    </p>
  </div>

  <div style="text-align:center;">
    <img src="/assets/images/research/pattern-mapped.png"
         alt="Pattern-mapped tree"
         style="width:100%; height:auto; border-radius:8px;">
    <p style="font-size:0.9rem; color:#555; margin-top:6px;">
      <strong>Figure 3.</strong> Pattern-mapped tree showing that plain dorsum is ancestral, with independent origins of stripes and spots in different lineages.
    </p>
  </div>

</div>


---

## Climate rules and coat colour

Comparative analyses revealed that coat colour in squirrels follows **Gloger’s rule**: darker species are more common in humid, high-precipitation regions, while lighter species dominate dry and colder habitats. In contrast, dorsal patterns showed weaker direct links to climate, though experimental results (see [Camouflage Game](/research/camouflage/)) suggest they may still provide adaptive advantages in certain habitats.

<div style="display:grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 20px;
            align-items:start;
            margin: 1rem 0;">

  <div style="text-align:center;">
    <img src="/assets/images/research/colour-climate.png"
         alt="Boxplots coat colour vs climate"
         style="width:100%; height:260px; object-fit:contain; background:#fafafa; border-radius:8px;">
    <p style="font-size:0.9rem; color:#555; margin-top:6px;">
      <strong>Figure 4.</strong> Boxplots showing the relationship between coat colour and precipitation/evapotranspiration.
    </p>
  </div>

  <div style="text-align:center;">
    <img src="/assets/images/research/combined-colour-pattern.png"
         alt="Combined colour + pattern vs precipitation"
         style="width:100%; height:260px; object-fit:cover; border-radius:8px;">
    <p style="font-size:0.9rem; color:#555; margin-top:6px;">
      <strong>Figure 5.</strong> Combined colour + pattern variable plotted against precipitation, supporting the prediction of Gloger’s rule.
    </p>
  </div>

</div>

---

## Summary

Phylogenetic analyses showed that:

- Brown and plain coats were ancestral in squirrels.  
- Darker colours evolved repeatedly in wetter environments.  
- Patterns show strong phylogenetic signal but weaker climate correlations, suggesting they may have been shaped by past selection.

Together, these results highlight the interplay between evolutionary history and ecological adaptation in shaping the diversity of squirrel coat traits.

