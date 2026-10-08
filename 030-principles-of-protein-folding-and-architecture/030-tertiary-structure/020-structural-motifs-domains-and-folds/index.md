---
layout: default
title: 'Structural motifs, domains, and folds'
---

# Structural motifs, domains, and folds

Understanding tertiary structure requires understanding domains, the fundamental building blocks that bridge the gap between individual secondary structures and complete proteins. At first glance, the folding process might seem capable of generating an almost infinite variety of shapes. However, protein structures are not random. Instead, evolution has repeatedly converged on a limited (albeit large) set of recurring architectural solutions that appear across diverse proteins and organisms.

Simple combinations of a few secondary structure elements with a specific geometric arrangement have been found to occur frequently in protein structures.

## **Motifs (supersecondary structure)**

The smallest of these recurring units is called a structural motif, or a supersecondary structure. These are short, recognisable combinations of secondary structure elements that appear repeatedly in unrelated proteins. Some of these motifs can be associated with a particular function, such as DNA binding; others have no specific independent biological function but are part of larger structural and functional assemblies.

Motifs often provide a stable local arrangement that can be reused as a building block within larger domains. Examples:

* **β-hairpin:** where two β-strands are connected by a short turn.
* **Helix-turn-helix:** where two α-helices are linked by a flexible loop.
* **Greek Key:** a specific topology of four antiparallel β-strands.












##### Helix-Turn-Helix (HTH) (PDB: [1LMB](https://www.ebi.ac.uk/pdbe/entry/pdb/1lmb)).

DNA-binding motif found in many transcription factors.

## **Domains: modular functional units**

When these motifs assemble into a compact region, they form a domain. A protein domain is a compact, globular unit that contains its own hydrophobic core and can fold independently of the rest of the protein. Many proteins are built modularly from two or more domains fused together, with each domain performing a distinct biochemical task. Domains may be linked together by a small linker or large disordered regions.

Domain architecture varies widely. Single-domain proteins, such as ubiquitin and lysozyme, are compact, globular structures in which the entire protein folds as a single unit. Multi-domain proteins are more common, especially in eukaryotes.

Domains are modular and can be mixed and matched during evolution to create proteins with novel functions. This process, known as domain shuffling, involves duplicating and recombining domain-encoding gene segments.

Most domains consist of a continuous stretch of amino acid sequence: residues 1-100 might comprise domain 1, while residues 101-250 form domain 2. However, some domains are discontinuous. In these cases, the sequence of one domain is interrupted by the insertion of another domain, which is then resumed. In three-dimensional space, these interrupted segments come together to form a coherent structural unit.












![](https://www.ebi.ac.uk/training/online/courses/foundations-protein-structure/wp-content/uploads/sites/311/2026/02/domains.png)

##### Tyrosine-protein kinase c-SRC (PDB ID: [2SRC](https://www.wwpdb.org/pdb?id=pdb_00002src))

![](https://www.ebi.ac.uk/training/online/courses/foundations-protein-structure/wp-content/uploads/sites/311/2026/02/domains._immunopng.png)

##### Fibronectin (PDB ID: [1FNF](https://www.wwpdb.org/pdb?id=pdb_00001fnf))

Domain architecture in multi-domain proteins.

A critical principle is that protein structure is significantly more conserved than protein sequence over evolutionary time. Protein evolution selects sequences which maintain the structure of a domain required to support its function. As a result, many protein domains form closely related structures.

Identifying domain boundaries, determining where one domain ends and another begins, can be approached from both sequence and structure. In amino acid sequences, domains are often separated by low-complexity linker regions that are enriched in glycine, proline, and charged residues. These linkers provide flexibility, allowing domains to move semi-independently. In three-dimensional structures, domain boundaries are usually evident as gaps or clefts between distinct regions, each with its own buried hydrophobic core.

Another helpful description of proteins is the high-level organisation of their domains, known as a protein **Fold**.

It is useful to group domain folds into three broad classes, based on the predominant secondary structure elements contained within them:

* All-α domains: These domains have a core built exclusively of α-helices. Many of these folds are small and form simple bundles where helices run in an up-and-down fashion.












##### All-α fold example: crystal structure of TehA (PDB ID: [3m71](https://www.ebi.ac.uk/pdbe/entry/pdb/3m71)).

Cartoon representation, illustrating an all-α domain architecture.

* All-β domains: Characterised by a core composed of β-sheets, often with two sheets packed against each other. Recurring motifs, such as the Greek key motif, are frequently identified in this class.












##### All-β fold example: immunoglobulin domain (PDB ID: [1A3L](https://www.ebi.ac.uk/pdbe/entry/pdb/1a3l))

The structure is composed predominantly of antiparallel β-strands arranged into two β-sheets packed face-to-face, forming a compact β-sandwich.

* α/β domains: Formed from a combination of β-α-β motifs, these domains predominantly feature a parallel β-sheet surrounded by amphipathic α-helices. Their secondary structures are typically arranged in layers or barrels.












##### α/β fold example: 3-oxoacyl-[acyl carrier protein] reductase (PDB ID:[2A4K](https://www.ebi.ac.uk/pdbe/entry/pdb/2a4k)).

The structure contains a central parallel β-sheet (shown as arrows) flanked by surrounding α-helices (shown as coiled ribbons), forming a layered arrangement typical of α/β folds.

Domain structure is often tightly coupled to protein function through the constrained evolution of functional motifs. However, some ancient proteins have maintained stable global structure while evolving highly divergent functional roles mediated by local structural diversity.












##### Aldo reductase (PDB ID: [1ADS](https://www.wwpdb.org/pdb?id=pdb_00001ads))

##### Phosphotriesterase (PDB ID: [1DPM](https://www.wwpdb.org/pdb?id=pdb_00001dpm))

The characteristic (β–α)\₈ architecture consists of eight parallel β-strands forming a central barrel, each followed by an α-helix on the exterior. Although the overall fold is highly conserved, TIM barrels support a wide range of distinct enzymatic functions, illustrating how a common structural framework can be adapted for diverse catalytic activities.