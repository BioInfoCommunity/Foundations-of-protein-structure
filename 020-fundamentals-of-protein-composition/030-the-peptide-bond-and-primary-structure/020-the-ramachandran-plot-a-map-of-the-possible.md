---
layout: default
title: 'The Ramachandran plot: A map of the possible'
---

# The Ramachandran plot: A map of the possible

Not all combinations of φ and ψ are allowed, due to clashes between backbone and side-chain atoms (i.e. steric clashes). The permitted combinations can be visualised using a Ramachandran plot, which maps the φ and ψ for amino acid residues and is a key tool for understanding and validating protein structures ([Ramachandran, G. N., et al., 1963](https://doi.org/10.1016/S0022-2836(63)80023-6)). This plot reveals that residues typically cluster into distinct “islands” corresponding to common secondary structures, such as α-helices and β-sheets.

It is important to note that these ‘allowed’ regions vary significantly for distinct amino acid types. Remember that glycine is the most flexible residue; because it lacks a bulky side chain (containing only a single hydrogen atom), it faces fewer steric clashes and can adopt angles strictly forbidden for other residues. In contrast, proline is the most restricted. Its side chain forms a cyclic ring that covalently bonds back to the backbone nitrogen, physically locking the φ angle and confining the residue to a very narrow conformational space.

The Ramachandran plot is also a standard structure-validation tool: residues far outside the allowed regions can indicate local modelling problems, strained geometry, or (rarely) genuinely unusual conformations that warrant closer inspection.

![](https://www.ebi.ac.uk/training/online/courses/foundations-protein-structure/wp-content/uploads/sites/311/2026/02/image-26-1024x883.png)

Ramachandran Plot. This plot visualises the energetically allowed conformational space for amino acid residues defined by their backbone dihedral angles, φ (phi, x-axis) and ψ (psi, y-axis). The coloured regions indicate angular combinations that avoid steric collisions between backbone and side-chain atoms. Darker regions represent the most energetically favoured conformations. Lighter regions represent allowed (but less energetically optimal) conformations. White space represents disallowed regions where steric hindrance (clashes between atoms) prevents the protein chain from adopting those angles. The four panels correspond to different residue classes: general residues, glycine, proline, and pre-proline (residues before and after the proline), each exhibiting distinct conformational preferences due to differences in side-chain geometry and steric constraints.