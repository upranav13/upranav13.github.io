---
title: "Transcriptomic effects of 6Pgdh polymorphism"
layout: single
permalink: /research/transcriptomics/
author_profile: true
classes: wide
---

## Linking genotype, gene expression, and sexual selection

Building on the field and laboratory studies, we explored the molecular mechanisms connecting **6Pgdh polymorphism** to reproductive success in *Rhizoglyphus robini*.  
Although the S and F alleles of 6Pgdh differ by a single amino acid substitution, they have strong effects on male reproductive performance. To uncover how this genetic variation shapes physiology, we compared genome-wide gene expression profiles of males homozygous for each allele.

---

## Research objectives

- Test whether **6Pgdh genotype** is associated with global differences in gene expression.  
- Identify genes and functional pathways overexpressed in **S- and F-line males**.  
- Examine whether expression divergence is linked to **genomic position** or specific metabolic routes, such as the pentose phosphate pathway and its derivatives.

---

## Methods in brief

Males from three independent genetic backgrounds were reared to obtain **S- and F-homozygous lines**, which were then sampled in triplicate for RNA extraction. RNA-seq libraries were prepared using the NEBNext® Ultra™ II Directional RNA kit and sequenced (150 bp paired-end reads) on an MGISEQ-2000 platform.  

Reads were trimmed with **Trimmomatic**, mapped to the *R. robini* genome using **STAR**, and analyzed for differential expression with **DESeq2**, accounting for both genotype and background.  
**Gene ontology enrichment** (using the *goseq* R package) identified overrepresented molecular and biological categories, and **pathway searches** linked differentially expressed genes to known KEGG pathways from *Drosophila melanogaster*.

---

## Key results

<div style="display:grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 24px;
            align-items:start;
            margin: 1rem 0;">

  <div style="text-align:center;">
    <img src="/assets/images/research/Picture1.png"
         alt="PCA of RNA-seq samples by genotype and background"
         style="width:100%; height:260px; object-fit:contain; background:#fafafa; border-radius:8px;">
    <p style="font-size:0.9rem; color:inherit; margin-top:6px;">
      <strong>Figure 1.</strong> Principal component analyses (A, B) showing clustering of S- and F-line samples across three genetic backgrounds.
    </p>
  </div>

  <div style="text-align:center;">
    <img src="/assets/images/research/Picture2.png"
         alt="Hierarchical clustering of transcriptomic samples"
         style="width:100%; height:260px; object-fit:contain; background:#fafafa; border-radius:8px;">
    <p style="font-size:0.9rem; color:inherit; margin-top:6px;">
      <strong>Figure 2.</strong> Hierarchical clustering of gene expression profiles confirming consistent differentiation between genotypes within backgrounds.
    </p>
  </div>

  <div style="text-align:center;">
    <img src="/assets/images/research/Picture3.png"
         alt="Genome-wide distribution of differentially expressed genes"
         style="width:100%; height:260px; object-fit:contain; background:#fafafa; border-radius:8px;">
    <p style="font-size:0.9rem; color:inherit; margin-top:6px;">
      <strong>Figure 3.</strong> Genome-wide distribution of genes overexpressed in S (blue) and F (red) lines across linkage groups. The 6Pgdh and <em>rhrob01g23970</em> loci, both on linkage group 5, are shown with violet and green dots.
    </p>
  </div>

  <div style="text-align:center;">
    <img src="/assets/images/research/Picture4.png"
         alt="Proportion of overexpressed genes per linkage group"
         style="width:100%; height:260px; object-fit:contain; background:#fafafa; border-radius:8px;">
    <p style="font-size:0.9rem; color:inherit; margin-top:6px;">
      <strong>Figure 4.</strong> Proportion of genes overexpressed in S (teal) and F (coral) lines across eight linkage groups, showing the highest concentration on linkage group 5.
    </p>
  </div>

</div>

---

## Interpretation

Across genetic backgrounds, **over 3,400 genes** showed differential expression between genotypes.  
S-line males exhibited higher expression of genes involved in **protein folding, binding, and proteolysis**, while F-line males showed enrichment for **ATP binding and phosphorylation** categories.  
Although enzymes of the pentose phosphate pathway itself did not differ, several genes from related carbohydrate and amino acid metabolism pathways were affected, highlighting **indirect regulatory connections**.

The linked gene **rhrob01g23970**, located about 5 Mb from 6Pgdh on linkage group 5, was previously identified as **male-limited in expression** and overexpressed in more sexually selected male morphs. Its position and co-variation suggest it may complement 6Pgdh in shaping gene expression and fitness differences.

---

## Conclusion

This study demonstrates that a single metabolic polymorphism, together with a closely linked variant, can drive **genome-wide expression divergence** across thousands of genes.  
By integrating field data, experimental evolution, and transcriptomics, we reveal how selection acting on reproductive success can cascade into **broad physiological and metabolic differentiation** in *R. robini*.