---
layout: default
title: 'Stabilisation forces'
---

# Stabilisation forces

Once the protein has collapsed into its globular shape, what keeps it in that shape? The native state is maintained by a cooperative network of thousands of weak interactions (non-covalent) and a smaller number of strong ones (covalent). No single force dominates in isolation — rather, the folded state emerges from their collective, cumulative contribution. These interactions fall into two broad categories: non-covalent forces, which are individually weak and reversible, and covalent bonds, which serve as permanent structural anchors ([Pace et al., 2014](https://doi.org/10.1016/j.febslet.2014.05.006)).

As the chain folds, hydrophobic residues tend to become buried away from water, forming a tightly packed hydrophobic core. This is the primary driving force behind tertiary structure formation and is explored in detail in the “How proteins fold” section. The structural consequence is clear: the interior of virtually every soluble protein is built from nonpolar residues shielded from the aqueous environment. This burial is not just about avoiding water; it also brings these residues into close contact with one another, where a second class of interaction becomes important.

## **Van der Waals interactions**

Even atoms that carry no charge interact weakly with one another through van der Waals forces. These arise from transient, fluctuating asymmetries in the electron cloud surrounding any atom: at any given instant, the cloud is not perfectly symmetrical, creating a fleeting dipole that induces a complementary dipole in a neighbouring atom. The result is a weak, short-range attraction. Van der Waals interactions have a critical distance dependence; attraction builds as atoms approach, but turns sharply repulsive if they come too close and their electron clouds begin to overlap. This gives each atom an effective “size” and means that atoms in the folded protein settle at an optimal packing distance.

The hydrophobic core is where van der Waals interactions make their greatest contribution. The methyl and methylene groups of hydrophobic side chains such as leucine and valine are particularly polarisable, making them effective van der Waals partners. While each individual contact contributes only a fraction of a kcal/mol, the interior of a folded protein contains thousands of such contacts, making their collective contribution substantial. Van der Waals interactions diminish rapidly as the interacting species get farther apart, so only atoms that are already close together (about 3.5 Å apart or less) have a chance to participate in such interactions. This is why even conservative mutations that alter side-chain size; for example, replacing a leucine with a valine; can measurably destabilise a tightly packed core: the geometric complementarity is disrupted, and van der Waals contacts are lost.

A given van der Waals interaction is extremely weak, but in proteins, they sum up to a substantial energetic contribution.

![](https://www.ebi.ac.uk/training/online/courses/foundations-protein-structure/wp-content/uploads/sites/311/2026/02/image-28-1024x857.png)

Summary of the main forces that stabilise protein structures: Hydrogen bonds organise the backbone into regular secondary structures such as α-helices and β-sheets. Covalent disulphide bonds form between cysteine residues, creating sulphur bridges that reinforce structural stability. In addition, hydrophobic interactions drive nonpolar side chains to cluster within the protein core, reducing exposure to water and promoting proper folding. Together, these interactions maintain the protein’s three-dimensional conformation.

## **Non-covalent interactions**

These forces are individually weak, transient, and reversible.  This reversibility is not a flaw; it is a feature. It allows proteins to “breathe,” undergo conformational changes, and interact dynamically with partners and ligands.

* **Hydrogen Bonds (H-bonds)**: As introduced in the secondary structure section, backbone hydrogen bonds define the geometry of helices and sheets. At the tertiary level, an additional network of hydrogen bonds forms between polar side chains and between side chains and water molecules at the protein surface. These bonds don’t just contribute energetically, they impose specificity, constraining exactly which conformations and binding interfaces are accessible. When analysing a structure, tracking H-bond networks between side chains often reveals which residues are critical for stability or function.
* **Ionic interactions (salt bridges)**: Strong electrostatic attractions can form between oppositely charged side chains, such as the positively charged amine of Lysine (NH3+) and the negatively charged carboxylate of Glutamate (COO-). When two oppositely charged residues are in close proximity (~ within 4 Å), they form a salt bridge. These “salt bridges” can act as latches on the protein surface, but their strength depends heavily on the local environment (pH and salt concentration).

## **Aromatic interactions**

Aromatic residues (Phenylalanine, Tyrosine, Tryptophan) possess ring systems rich in delocalised **π**-electrons (clouds of circulating electrons above and below the ring). These electron clouds can interact with one another and with charged groups in two main ways:

* **π-π stacking:** Two aromatic rings stack parallel or perpendicular (T-shaped) to one another, stabilising the hydrophobic core.
* **Cation-** **π interactions:** A positively charged residue (like Arginine) can sit flat against the electron-rich face of an aromatic ring. This is a surprisingly strong interaction.

## **Covalent Interactions**

While non-covalent forces shape the fold, some proteins are reinforced by covalent bonds that act as permanent anchors.

**Disulphide Bonds.** In harsh environments (such as the extracellular space), where weak forces might fail, proteins are often reinforced by covalent “staples”. Pairs of Cysteine residues can undergo oxidation to form a sulphur-sulphur bond (S-S). This linkage locks distant parts of the chain together, preventing the protein from unfolding even under thermal stress. Disulphide bonds are only broken at high temperatures, acidic pH or in the presence of reductants.












##### Disulphide bridge stabilisation in the Bovine Pancreatic Trypsin Inhibitor (PDB: [1BPI](https://www.ebi.ac.uk/pdbe/entry/pdb/1bpi)).

**Metal coordination.** A common interaction in proteins is the coordination of a metal ion to protein side chains; the coordinate covalent bonds between the protein and the metal ion form a type of internal metal chelate. A given protein can have more than one stabilising metal ion binding site. The metal ions that most commonly form such chelates are Calcium (Ca²⁺), Iron (Fe²⁺/³⁺) and Zinc (Zn2+). Sometimes when these metal ions are removed by chelating agents (e.g. EDTA), the protein remains folded, although less stable, under physiological conditions. In other cases, removal of the metal ions from the protein leads to denaturation.












##### Subtilisin Carlsberg (PDB: [1SCA](https://www.ebi.ac.uk/pdbe/entry/pdb/1sca)).This calcium ion acts as a stabilisation factor, not involved in catalysis. Removal of this significantly destabilises the protein.

**Cofactor binding.** Some proteins are additionally stabilised by the covalent or tight non-covalent binding of organic or organometallic cofactors at or near the active site. These cofactors can make important contributions to both fold stability and function.