---
layout: default
title: 'The central dogma: from information to action'
---

# The central dogma: from information to action

The “central dogma” of molecular biology describes the directional flow of information within a cell:

DNA
→
RNA
→
Protein

* DNA serves as the long-term storage of genetic information, encoding the instructions required to build proteins; it contains the “blueprints”.
* RNA acts as a transient messenger. During transcription, a specific protein-coding gene sequence is copied into messenger RNA (mRNA). This molecule is less stable than DNA, allowing the cell to quickly upregulate or downregulate the production of specific proteins in response to environmental changes.
* Proteins are the final functional product. During translation, the cellular machinery (i.e. the ribosome) reads the mRNA sequence to assemble a polypeptide chain made of amino acids.

The polypeptide chain does not remain linear for long. Depending on the chemical properties of the amino acids in the chain and their interaction with one another, the chain folds into a specific three-dimensional shape (described in more detail below). The amino acid sequence determines how the chain folds. The folded structure then enables biological function.

In summary: DNA encodes RNA. RNA specifies protein sequence. Sequence determines structure. Structure enables function.

Why study proteins? Proteins underpin every aspect of biological activity.

![](https://www.ebi.ac.uk/training/online/courses/foundations-protein-structure/wp-content/uploads/sites/311/2026/02/image-17-1024x683.png)

This diagram represents the pathways of genetic information transfer, beginning with DNAreplication, the process by which a DNA molecule is copied to maintain the genetic blueprint. While most information flows through transcription to create RNA, unique cases like retroviruses can “flip the script” by using reverse transcription to turn RNA back into DNA. The messenger RNA is then translated into amino acids to direct the assembly of a specific Protein Structure, which then takes on its specific protein function within the cell.

## **The genetic code: Redundancy and robustness**

The ribosome reads mRNA in groups of three nucleotides called **codons**. With four possible bases (A, U, C, G), there are 43 = 64 possible codon combinations, yet only 20 standard amino acids. Because there are more codons (64) than amino acids (20), most amino acids are encoded by more than one codon. This feature is called degeneracy. For example, Glycine is encoded by the GGU, GGC, GGA and GGG codons. This redundancy provides critical biological robustness against mutations:

* If a DNA change results in a different codon that still specifies the same amino acid (e.g., GGT → GGC), the protein’s primary structure remains unchanged. These are often called **“silent” mutations**, though they can occasionally influence translation speed.
* If the change results in a different amino acid (a “missense” mutation), it can alter the protein’s physicochemical properties. Replacing a small, neutral amino acid with a large, charged one can disrupt the protein’s internal packing, potentially leading to misfolding or loss of function.
* However, consider a DNA mutation where a cytosine in an arginine codon (CGA) changes to a thymine (C → T). This alters the codon to TGA (STOP), resulting in premature termination that produces a truncated, likely nonfunctional protein. Such **nonsense mutations** typically have severe consequences.

![](https://www.ebi.ac.uk/training/online/courses/foundations-protein-structure/wp-content/uploads/sites/311/2026/02/codon-deg-1.png)

The standard RNA genetic code table. This grid illustrates the universal mapping of 64 mRNA triplet codons to the 20 standard amino acids used in protein biosynthesis. The table is organised by the position of the nucleotides within the triplet: the first letter (left axis), second letter (top axis), and third letter (right axis). The start codon (AUG), which codes for Methionine (Met), is highlighted in red, signifying the initiation site of translation. The three stop codons (UAA, UAG, UGA) are shown in bold; these signal the termination of the polypeptide chain.

This matters for structural biology because many sequence changes are structurally tolerated (no large fold change) yet can still alter stability, binding, or regulation. Seeing where a specific amino acid sits in the 3D structure makes it easier to understand how a mutation might change stability or function.

While the genetic code is universal, different organisms exhibit **codon usage bias**. Although several codons might code for the same amino acid, a specific organism (e.g. *E. coli* versus a human cell) may “prefer” one over the others. This preference often matches the availability of transfer RNAs (tRNAs), the molecules that carry amino acids to the ribosome ([Yi Liu, Qian Yang, Fangzhou Zhao, 2021](https://doi.org/10.1146/annurev-biochem-071320-112701)). Codon optimisation can dramatically improve protein expression yields.