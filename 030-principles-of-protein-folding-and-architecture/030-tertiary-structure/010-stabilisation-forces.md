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
{: .figure-caption}

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

{% raw %}
<div class="molstar-viewer">
    <link rel="stylesheet" type="text/css" href="https://molstar.org/viewer/molstar.css" />
    <style>
      .container {
          display: flex;
          justify-content: space-around; /* Adjust as needed */
          flex-wrap: wrap; /* Allow items to wrap to the next line */
      }
      .item {
          flex: 1;
          margin: 5px; /* Adjust margin as needed */
          text-align: center; /* Center text within each item */
          display: flex;
          flex-direction: column;
          align-items: center; /* Center content horizontally */
      }
      .item .app {
          height: 500px;
          width: 500px;
          position: relative;
      }
      .item .text {
          text-align: center; /* Center the text */
          margin-top: 5px; /* Adjust margin as needed */
      }
      .item h5 {
          text-align: center;
          margin-block-start: 0.5em !important;;
          margin-block-end: 0.5em !important;;
      }
      .msp-plugin small {
        display: initial !important;
        color: inherit !important;
    }
  </style>
  <div class="container">
    <div class="item">
        <div id="app" class="app"></div>
        <div id="text">
          <h5>Disulphide bridge stabilisation in the Bovine Pancreatic Trypsin Inhibitor (PDB: <a href="https://www.ebi.ac.uk/pdbe/entry/pdb/1bpi" target="_blank" rel="noreferrer noopener">1BPI</a>).</h5>
        </div>
      </div>
    </div>
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <script type="text/javascript">
        const state ={
  "timestamp": 1770295823311,
  "version": "5.6.0",
  "current": "WBBcOirbsxRcf6mALIbVow",
  "playback": {
    "isPlaying": false,
    "nextSnapshotDelayInMs": 1500
  },
  "entries": [
    {
      "timestamp": 1770295823310,
      "snapshot": {
        "id": "WBBcOirbsxRcf6mALIbVow",
        "data": {
          "tree": {
            "transforms": [
              {
                "parent": "-=root=-",
                "transformer": "build-in.root",
                "params": {},
                "ref": "-=root=-",
                "version": "UYGCYwHqq_AwaLy8vy3PQw"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.download",
                "params": {
                  "url": {
                    "kind": "url",
                    "id": "teb5iGTIrhZWRRPx_fMTHg",
                    "url": "https://www.ebi.ac.uk/pdbe/entry-files/download/1bpi.bcif"
                  },
                  "label": "PDBe: 1bpi (updated cif)",
                  "isBinary": true
                },
                "state": {
                  "isGhost": true
                },
                "ref": "Lw03eXoP9RLI08rXf6g4Ug",
                "version": "7zOYO5YXbXdl78ud5O7ZLw"
              },
              {
                "parent": "Lw03eXoP9RLI08rXf6g4Ug",
                "transformer": "ms-plugin.parse-cif",
                "params": {},
                "state": {
                  "isGhost": true
                },
                "ref": "-ccIiZ7Ek1ARHE-gVvXGwg",
                "version": "DFIXv2NgS16xPt849PLinA"
              },
              {
                "parent": "-ccIiZ7Ek1ARHE-gVvXGwg",
                "transformer": "ms-plugin.trajectory-from-mmcif",
                "params": {},
                "ref": "pSWNTQOoZri55GUF94jUYg",
                "version": "fA8RigLoXNR6ds19xGMthQ"
              },
              {
                "parent": "pSWNTQOoZri55GUF94jUYg",
                "transformer": "ms-plugin.model-from-trajectory",
                "params": {
                  "modelIndex": 0
                },
                "ref": "gfmDFA5WBOSIy3Kh9doXhg",
                "version": "Cukapj2au4Cqjjf0yj2kcQ"
              },
              {
                "parent": "gfmDFA5WBOSIy3Kh9doXhg",
                "transformer": "ms-plugin.custom-model-properties",
                "params": {
                  "autoAttach": [
                    "sifts_sequence_mapping"
                  ],
                  "properties": {
                    "asym_id_offset": {
                      "value": {
                        "auth": 0,
                        "label": 0
                      }
                    },
                    "index": {
                      "value": 0
                    },
                    "max_index": {
                      "value": 0
                    },
                    "sifts_sequence_mapping": {},
                    "pdbe_structure_quality_report": {
                      "serverUrl": "https://www.ebi.ac.uk/pdbe/api/validation/residuewise_outlier_summary/entry/"
                    },
                    "rcsb_validation_report": {
                      "source": {
                        "name": "server",
                        "params": {
                          "baseUrl": "https://files.rcsb.org/validation/view"
                        }
                      }
                    },
                    "mvs-is-mvs-model": {
                      "isMvs": false
                    },
                    "mvs-annotations": {
                      "annotations": []
                    }
                  }
                },
                "ref": "AokOYTTh1Dn72_AQfvoPaQ",
                "version": "UEeTBfce0552GPm_ogBb4w"
              },
              {
                "parent": "AokOYTTh1Dn72_AQfvoPaQ",
                "transformer": "ms-plugin.structure-from-model",
                "params": {
                  "type": {
                    "name": "assembly",
                    "params": {
                      "id": "1",
                      "dynamicBonds": false
                    }
                  }
                },
                "ref": "xGULBZQ_nIGiRa075NKK-w",
                "version": "cQ8zbowmdsy9z_qy8IA3Kw"
              },
              {
                "parent": "xGULBZQ_nIGiRa075NKK-w",
                "transformer": "ms-plugin.custom-structure-properties",
                "params": {
                  "autoAttach": [],
                  "properties": {
                    "index": {
                      "value": 0
                    },
                    "max_index": {
                      "value": 0
                    },
                    "molstar_accessible_surface_area": {
                      "numberOfSpherePoints": 92,
                      "probeSize": 1.4,
                      "nonPolymer": false,
                      "traceOnly": false
                    },
                    "molstar_computed_interactions": {
                      "providers": {
                        "ionic": {
                          "name": "off",
                          "params": {}
                        },
                        "pi-stacking": {
                          "name": "on",
                          "params": {
                            "distanceMax": 5.5,
                            "offsetMax": 2,
                            "angleDevMax": 30
                          }
                        },
                        "cation-pi": {
                          "name": "on",
                          "params": {
                            "distanceMax": 6,
                            "offsetMax": 2
                          }
                        },
                        "halogen-bonds": {
                          "name": "on",
                          "params": {
                            "distanceMax": 4,
                            "angleMax": 30
                          }
                        },
                        "hydrogen-bonds": {
                          "name": "on",
                          "params": {
                            "distanceMax": 3.5,
                            "backbone": true,
                            "accAngleDevMax": 45,
                            "ignoreHydrogens": false,
                            "donAngleDevMax": 45,
                            "accOutOfPlaneAngleMax": 90,
                            "donOutOfPlaneAngleMax": 45,
                            "water": false,
                            "sulfurDistanceMax": 4.1
                          }
                        },
                        "weak-hydrogen-bonds": {
                          "name": "off",
                          "params": {}
                        },
                        "hydrophobic": {
                          "name": "off",
                          "params": {}
                        },
                        "metal-coordination": {
                          "name": "on",
                          "params": {
                            "distanceMax": 3
                          }
                        }
                      },
                      "contacts": {
                        "lineOfSightDistFactor": 1
                      }
                    },
                    "molstar_computed_secondary_structure": {
                      "type": {
                        "name": "auto",
                        "params": {}
                      }
                    },
                    "molstar_computed_valence_model": {
                      "assignCharge": "auto",
                      "assignH": "auto"
                    },
                    "molstar_struct_symmetry": {
                      "serverType": "rcsb",
                      "serverUrl": "https://data.rcsb.org/graphql",
                      "symmetryIndex": 0
                    },
                    "anvil_computed_membrane_orientation": {
                      "numberOfSpherePoints": 175,
                      "stepSize": 1,
                      "minThickness": 20,
                      "maxThickness": 40,
                      "asaCutoff": 40,
                      "adjust": 14,
                      "tmdetDefinition": false
                    },
                    "mvs-custom-tooltips": {
                      "tooltips": []
                    },
                    "mvs-annotation-tooltips": {
                      "tooltips": []
                    }
                  }
                },
                "ref": "fvC-QIXnt1tJlgS7-UVREw",
                "version": "eM04HIOlxoUgOoQVRpJMhg"
              },
              {
                "parent": "fvC-QIXnt1tJlgS7-UVREw",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "static",
                    "params": "polymer"
                  },
                  "nullIfEmpty": true,
                  "label": ""
                },
                "tags": [
                  "structure-component-static-polymer"
                ],
                "ref": "7GyvSpRjXYZL64f7xKaX_g",
                "version": "dGLcNbMXW1iRjE1b9c8HLQ"
              },
              {
                "parent": "7GyvSpRjXYZL64f7xKaX_g",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "cartoon",
                    "params": {
                      "alpha": 1,
                      "quality": "auto",
                      "material": {
                        "metalness": 0,
                        "roughness": 1,
                        "bumpiness": 0
                      },
                      "clip": {
                        "variant": "pixel",
                        "objects": []
                      },
                      "emissive": 0,
                      "density": 0.1,
                      "instanceGranularity": false,
                      "lod": [
                        0,
                        0,
                        0
                      ],
                      "cellSize": 200,
                      "batchSize": 2000,
                      "doubleSided": false,
                      "flipSided": false,
                      "flatShaded": false,
                      "ignoreLight": true,
                      "celShaded": false,
                      "xrayShaded": false,
                      "transparentBackfaces": "off",
                      "bumpFrequency": 2,
                      "bumpAmplitude": 1,
                      "interior": {
                        "color": 5000268,
                        "colorStrength": 1,
                        "substance": {
                          "metalness": 0,
                          "roughness": 1,
                          "bumpiness": 0
                        },
                        "substanceStrength": 1
                      },
                      "unitKinds": [
                        "atomic",
                        "spheres"
                      ],
                      "includeParent": false,
                      "sizeFactor": 0.2,
                      "aspectRatio": 5,
                      "arrowFactor": 1.5,
                      "tubularHelices": false,
                      "roundCap": false,
                      "helixProfile": "elliptical",
                      "nucleicProfile": "square",
                      "detail": 0,
                      "linearSegments": 8,
                      "radialSegments": 16,
                      "thicknessFactor": 1,
                      "sizeAspectRatio": 1,
                      "solidInterior": true,
                      "colorMode": "default",
                      "tryUseImpostor": true,
                      "clipPrimitive": false,
                      "approximate": false,
                      "alphaThickness": 0,
                      "lodLevels": [],
                      "visuals": [
                        "polymer-trace"
                      ]
                    }
                  },
                  "colorTheme": {
                    "name": "chain-id",
                    "params": {
                      "asymId": "auth",
                      "palette": {
                        "name": "colors",
                        "params": {
                          "list": {
                            "kind": "set",
                            "colors": [
                              1810039,
                              14245634,
                              7696563,
                              15149450,
                              6727198,
                              15117058,
                              10909213,
                              6710886
                            ]
                          }
                        }
                      }
                    }
                  },
                  "sizeTheme": {
                    "name": "uniform",
                    "params": {
                      "value": 1
                    }
                  }
                },
                "tags": [
                  "polymer"
                ],
                "ref": "-hUa36ER8-LFFy0Chh0eNA",
                "version": "RfNdI0SU3weoEWO1huoE0A"
              },
              {
                "parent": "fvC-QIXnt1tJlgS7-UVREw",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "static",
                    "params": "water"
                  },
                  "nullIfEmpty": true,
                  "label": ""
                },
                "state": {
                  "isHidden": true
                },
                "tags": [
                  "structure-component-static-water"
                ],
                "ref": "SVP3mspRHIy0s_ZBstk14A",
                "version": "7ztD83BC4hGrxsP-jEEM-A"
              },
              {
                "parent": "SVP3mspRHIy0s_ZBstk14A",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "ball-and-stick",
                    "params": {
                      "alpha": 0.6,
                      "quality": "auto",
                      "material": {
                        "metalness": 0,
                        "roughness": 1,
                        "bumpiness": 0
                      },
                      "clip": {
                        "variant": "pixel",
                        "objects": []
                      },
                      "emissive": 0,
                      "density": 0.1,
                      "instanceGranularity": false,
                      "lod": [
                        0,
                        0,
                        0
                      ],
                      "cellSize": 200,
                      "batchSize": 2000,
                      "doubleSided": false,
                      "flipSided": false,
                      "flatShaded": false,
                      "ignoreLight": true,
                      "celShaded": false,
                      "xrayShaded": false,
                      "transparentBackfaces": "off",
                      "bumpFrequency": 0,
                      "bumpAmplitude": 1,
                      "interior": {
                        "color": 5000268,
                        "colorStrength": 1,
                        "substance": {
                          "metalness": 0,
                          "roughness": 1,
                          "bumpiness": 0
                        },
                        "substanceStrength": 1
                      },
                      "unitKinds": [
                        "atomic"
                      ],
                      "includeParent": false,
                      "sizeFactor": 0.15,
                      "solidInterior": true,
                      "clipPrimitive": false,
                      "approximate": false,
                      "alphaThickness": 0,
                      "lodLevels": [],
                      "detail": 0,
                      "ignoreHydrogens": false,
                      "ignoreHydrogensVariant": "all",
                      "traceOnly": false,
                      "tryUseImpostor": true,
                      "stride": 1,
                      "sizeAspectRatio": 0.6666666666666666,
                      "colorMode": "default",
                      "linkScale": 0.45,
                      "linkSpacing": 1,
                      "linkCap": false,
                      "aromaticScale": 0.3,
                      "aromaticSpacing": 1.5,
                      "aromaticDashCount": 2,
                      "dashCount": 4,
                      "dashScale": 0.8,
                      "dashCap": true,
                      "stubCap": true,
                      "radialSegments": 16,
                      "includeTypes": [
                        "covalent",
                        "metal-coordination",
                        "hydrogen-bond",
                        "disulfide",
                        "aromatic",
                        "computed"
                      ],
                      "excludeTypes": [],
                      "aromaticBonds": true,
                      "multipleBonds": "symmetric",
                      "adjustCylinderLength": false,
                      "visuals": [
                        "element-sphere",
                        "intra-bond",
                        "inter-bond"
                      ]
                    }
                  },
                  "colorTheme": {
                    "name": "element-symbol",
                    "params": {
                      "carbonColor": {
                        "name": "element-symbol",
                        "params": {}
                      },
                      "saturation": 0,
                      "lightness": 0.2,
                      "colors": {
                        "name": "default",
                        "params": {}
                      }
                    }
                  },
                  "sizeTheme": {
                    "name": "physical",
                    "params": {
                      "scale": 1
                    }
                  }
                },
                "state": {
                  "isHidden": true
                },
                "tags": [
                  "water"
                ],
                "ref": "UIdo8m4a-AGrD3ev3LbByg",
                "version": "8oy6c0XvL1pNT3cPVesQ3A"
              },
              {
                "parent": "fvC-QIXnt1tJlgS7-UVREw",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "static",
                    "params": "ion"
                  },
                  "nullIfEmpty": true,
                  "label": ""
                },
                "state": {
                  "isHidden": true
                },
                "tags": [
                  "structure-component-static-ion"
                ],
                "ref": "R0-WxjtEGTh6DGX3dg1Q8w",
                "version": "mYHGbOSK3bykJeis2g47kg"
              },
              {
                "parent": "R0-WxjtEGTh6DGX3dg1Q8w",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "ball-and-stick",
                    "params": {
                      "alpha": 1,
                      "quality": "auto",
                      "material": {
                        "metalness": 0,
                        "roughness": 1,
                        "bumpiness": 0
                      },
                      "clip": {
                        "variant": "pixel",
                        "objects": []
                      },
                      "emissive": 0,
                      "density": 0.1,
                      "instanceGranularity": false,
                      "lod": [
                        0,
                        0,
                        0
                      ],
                      "cellSize": 200,
                      "batchSize": 2000,
                      "doubleSided": false,
                      "flipSided": false,
                      "flatShaded": false,
                      "ignoreLight": true,
                      "celShaded": false,
                      "xrayShaded": false,
                      "transparentBackfaces": "off",
                      "bumpFrequency": 0,
                      "bumpAmplitude": 1,
                      "interior": {
                        "color": 5000268,
                        "colorStrength": 1,
                        "substance": {
                          "metalness": 0,
                          "roughness": 1,
                          "bumpiness": 0
                        },
                        "substanceStrength": 1
                      },
                      "unitKinds": [
                        "atomic"
                      ],
                      "includeParent": false,
                      "sizeFactor": 0.15,
                      "solidInterior": true,
                      "clipPrimitive": false,
                      "approximate": false,
                      "alphaThickness": 0,
                      "lodLevels": [],
                      "detail": 0,
                      "ignoreHydrogens": false,
                      "ignoreHydrogensVariant": "all",
                      "traceOnly": false,
                      "tryUseImpostor": true,
                      "stride": 1,
                      "sizeAspectRatio": 0.6666666666666666,
                      "colorMode": "default",
                      "linkScale": 0.45,
                      "linkSpacing": 1,
                      "linkCap": false,
                      "aromaticScale": 0.3,
                      "aromaticSpacing": 1.5,
                      "aromaticDashCount": 2,
                      "dashCount": 4,
                      "dashScale": 0.8,
                      "dashCap": true,
                      "stubCap": true,
                      "radialSegments": 16,
                      "includeTypes": [
                        "covalent",
                        "metal-coordination",
                        "hydrogen-bond",
                        "disulfide",
                        "aromatic",
                        "computed"
                      ],
                      "excludeTypes": [],
                      "aromaticBonds": true,
                      "multipleBonds": "symmetric",
                      "adjustCylinderLength": false,
                      "visuals": [
                        "element-sphere",
                        "intra-bond",
                        "inter-bond"
                      ]
                    }
                  },
                  "colorTheme": {
                    "name": "element-symbol",
                    "params": {
                      "carbonColor": {
                        "name": "element-symbol",
                        "params": {}
                      },
                      "saturation": 0,
                      "lightness": 0.2,
                      "colors": {
                        "name": "default",
                        "params": {}
                      }
                    }
                  },
                  "sizeTheme": {
                    "name": "physical",
                    "params": {
                      "scale": 1
                    }
                  }
                },
                "state": {
                  "isHidden": true
                },
                "tags": [
                  "ion"
                ],
                "ref": "b4IiK8sjZ01r8aGc_mcygQ",
                "version": "ky4vrh-04Deo3plT_fOHzQ"
              },
              {
                "parent": "fvC-QIXnt1tJlgS7-UVREw",
                "transformer": "ms-plugin.structure-selection-from-bundle",
                "params": {
                  "bundle": {
                    "hash": 1060573557,
                    "elements": [
                      {
                        "groupedUnits": [
                          [
                            0
                          ]
                        ],
                        "set": [],
                        "ranges": [
                          37,
                          42
                        ]
                      }
                    ]
                  },
                  "label": "[Focus] Target"
                },
                "tags": [
                  "structure-focus-target-sel"
                ],
                "ref": "QS7fOsi0VCSFDVYvwr9lSQ",
                "version": "FEisSAvgBZJrvTKANEaedw"
              },
              {
                "parent": "QS7fOsi0VCSFDVYvwr9lSQ",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "ball-and-stick",
                    "params": {
                      "alpha": 1,
                      "quality": "auto",
                      "material": {
                        "metalness": 0,
                        "roughness": 1,
                        "bumpiness": 0
                      },
                      "clip": {
                        "variant": "pixel",
                        "objects": []
                      },
                      "emissive": 0,
                      "density": 0.1,
                      "instanceGranularity": false,
                      "lod": [
                        0,
                        0,
                        0
                      ],
                      "cellSize": 200,
                      "batchSize": 2000,
                      "doubleSided": false,
                      "flipSided": false,
                      "flatShaded": false,
                      "ignoreLight": true,
                      "celShaded": false,
                      "xrayShaded": true,
                      "transparentBackfaces": "off",
                      "bumpFrequency": 0,
                      "bumpAmplitude": 1,
                      "interior": {
                        "color": 5000268,
                        "colorStrength": 1,
                        "substance": {
                          "metalness": 0,
                          "roughness": 1,
                          "bumpiness": 0
                        },
                        "substanceStrength": 1
                      },
                      "unitKinds": [
                        "atomic"
                      ],
                      "includeParent": false,
                      "sizeFactor": 0.22,
                      "solidInterior": true,
                      "clipPrimitive": false,
                      "approximate": false,
                      "alphaThickness": 0,
                      "lodLevels": [],
                      "detail": 0,
                      "ignoreHydrogens": false,
                      "ignoreHydrogensVariant": "all",
                      "traceOnly": false,
                      "tryUseImpostor": true,
                      "stride": 1,
                      "sizeAspectRatio": 0.73,
                      "colorMode": "default",
                      "linkScale": 0.45,
                      "linkSpacing": 1,
                      "linkCap": false,
                      "aromaticScale": 0.3,
                      "aromaticSpacing": 1.5,
                      "aromaticDashCount": 2,
                      "dashCount": 4,
                      "dashScale": 0.8,
                      "dashCap": true,
                      "stubCap": true,
                      "radialSegments": 16,
                      "includeTypes": [
                        "covalent",
                        "metal-coordination",
                        "hydrogen-bond",
                        "disulfide",
                        "aromatic",
                        "computed"
                      ],
                      "excludeTypes": [
                        "hydrogen-bond",
                        "metal-coordination"
                      ],
                      "aromaticBonds": false,
                      "multipleBonds": "off",
                      "adjustCylinderLength": true,
                      "visuals": [
                        "element-sphere",
                        "intra-bond",
                        "inter-bond"
                      ]
                    }
                  },
                  "colorTheme": {
                    "name": "element-symbol",
                    "params": {
                      "carbonColor": {
                        "name": "chain-id",
                        "params": {
                          "asymId": "auth",
                          "palette": {
                            "name": "colors",
                            "params": {
                              "list": {
                                "kind": "set",
                                "colors": [
                                  1810039,
                                  14245634,
                                  7696563,
                                  15149450,
                                  6727198,
                                  15117058,
                                  10909213,
                                  6710886,
                                  14948892,
                                  3636920,
                                  5091146,
                                  9981603,
                                  16744192,
                                  16777011,
                                  10901032,
                                  16220607,
                                  10066329,
                                  6734501,
                                  16551266,
                                  9281739,
                                  15174339,
                                  10934356,
                                  16767279,
                                  15058068,
                                  11776947
                                ]
                              }
                            }
                          }
                        }
                      },
                      "saturation": 0,
                      "lightness": 0.2,
                      "colors": {
                        "name": "default",
                        "params": {}
                      }
                    }
                  },
                  "sizeTheme": {
                    "name": "physical",
                    "params": {
                      "scale": 1
                    }
                  }
                },
                "tags": [
                  "structure-focus-target-repr"
                ],
                "ref": "fPoaB44Bya0Qa1oUNBlacA",
                "version": "BR4c1xYF62ZAPYcmR94aiQ"
              },
              {
                "parent": "fvC-QIXnt1tJlgS7-UVREw",
                "transformer": "ms-plugin.structure-selection-from-expression",
                "params": {
                  "expression": {
                    "head": {
                      "name": "structure-query.modifier.include-surroundings"
                    },
                    "args": {
                      "0": {
                        "head": {
                          "name": "internal.generator.bundle"
                        },
                        "args": {
                          "elements": {
                            "head": {
                              "name": "core.type.list"
                            },
                            "args": [
                              {
                                "head": {
                                  "name": "internal.generator.bundle-element"
                                },
                                "args": {
                                  "groupedUnits": {
                                    "head": {
                                      "name": "core.type.list"
                                    },
                                    "args": [
                                      {
                                        "head": {
                                          "name": "core.type.list"
                                        },
                                        "args": [
                                          0
                                        ]
                                      }
                                    ]
                                  },
                                  "ranges": {
                                    "head": {
                                      "name": "core.type.list"
                                    },
                                    "args": [
                                      37,
                                      42
                                    ]
                                  },
                                  "set": {
                                    "head": {
                                      "name": "core.type.list"
                                    },
                                    "args": []
                                  }
                                }
                              }
                            ]
                          }
                        }
                      },
                      "radius": 5,
                      "as-whole-residues": true
                    }
                  },
                  "label": "[Focus] Surroundings (5 Å)"
                },
                "tags": [
                  "structure-focus-surr-sel"
                ],
                "ref": "v6yCSMvKgveLyR29Vv4Pfg",
                "version": "yEvYGcze7uI3ViCrVKxJNw"
              },
              {
                "parent": "v6yCSMvKgveLyR29Vv4Pfg",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "ball-and-stick",
                    "params": {
                      "alpha": 1,
                      "quality": "auto",
                      "material": {
                        "metalness": 0,
                        "roughness": 1,
                        "bumpiness": 0
                      },
                      "clip": {
                        "variant": "pixel",
                        "objects": []
                      },
                      "emissive": 0,
                      "density": 0.1,
                      "instanceGranularity": false,
                      "lod": [
                        0,
                        0,
                        0
                      ],
                      "cellSize": 200,
                      "batchSize": 2000,
                      "doubleSided": false,
                      "flipSided": false,
                      "flatShaded": false,
                      "ignoreLight": true,
                      "celShaded": false,
                      "xrayShaded": false,
                      "transparentBackfaces": "off",
                      "bumpFrequency": 0,
                      "bumpAmplitude": 1,
                      "interior": {
                        "color": 5000268,
                        "colorStrength": 1,
                        "substance": {
                          "metalness": 0,
                          "roughness": 1,
                          "bumpiness": 0
                        },
                        "substanceStrength": 1
                      },
                      "unitKinds": [
                        "atomic"
                      ],
                      "includeParent": false,
                      "sizeFactor": 0.16,
                      "solidInterior": true,
                      "clipPrimitive": false,
                      "approximate": false,
                      "alphaThickness": 0,
                      "lodLevels": [],
                      "detail": 0,
                      "ignoreHydrogens": false,
                      "ignoreHydrogensVariant": "all",
                      "traceOnly": false,
                      "tryUseImpostor": true,
                      "stride": 1,
                      "sizeAspectRatio": 0.6666666666666666,
                      "colorMode": "default",
                      "linkScale": 0.45,
                      "linkSpacing": 1,
                      "linkCap": false,
                      "aromaticScale": 0.3,
                      "aromaticSpacing": 1.5,
                      "aromaticDashCount": 2,
                      "dashCount": 4,
                      "dashScale": 0.8,
                      "dashCap": true,
                      "stubCap": true,
                      "radialSegments": 16,
                      "includeTypes": [
                        "covalent",
                        "metal-coordination",
                        "hydrogen-bond",
                        "disulfide",
                        "aromatic",
                        "computed"
                      ],
                      "excludeTypes": [
                        "hydrogen-bond",
                        "metal-coordination"
                      ],
                      "aromaticBonds": true,
                      "multipleBonds": "symmetric",
                      "adjustCylinderLength": false,
                      "visuals": [
                        "element-sphere",
                        "intra-bond",
                        "inter-bond"
                      ]
                    }
                  },
                  "colorTheme": {
                    "name": "element-symbol",
                    "params": {
                      "carbonColor": {
                        "name": "chain-id",
                        "params": {
                          "asymId": "auth",
                          "palette": {
                            "name": "colors",
                            "params": {
                              "list": {
                                "kind": "set",
                                "colors": [
                                  1810039,
                                  14245634,
                                  7696563,
                                  15149450,
                                  6727198,
                                  15117058,
                                  10909213,
                                  6710886,
                                  14948892,
                                  3636920,
                                  5091146,
                                  9981603,
                                  16744192,
                                  16777011,
                                  10901032,
                                  16220607,
                                  10066329,
                                  6734501,
                                  16551266,
                                  9281739,
                                  15174339,
                                  10934356,
                                  16767279,
                                  15058068,
                                  11776947
                                ]
                              }
                            }
                          }
                        }
                      },
                      "saturation": 0,
                      "lightness": 0.2,
                      "colors": {
                        "name": "default",
                        "params": {}
                      }
                    }
                  },
                  "sizeTheme": {
                    "name": "physical",
                    "params": {
                      "scale": 1
                    }
                  }
                },
                "tags": [
                  "structure-focus-surr-repr"
                ],
                "ref": "L2ol2bSI7he2NSLEldhJ9Q",
                "version": "eCln1CkzgfGFbpOga1xNIA"
              },
              {
                "parent": "v6yCSMvKgveLyR29Vv4Pfg",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "interactions",
                    "params": {
                      "alpha": 1,
                      "quality": "auto",
                      "material": {
                        "metalness": 0,
                        "roughness": 1,
                        "bumpiness": 0
                      },
                      "clip": {
                        "variant": "pixel",
                        "objects": []
                      },
                      "emissive": 0,
                      "density": 0.2,
                      "instanceGranularity": false,
                      "lod": [
                        0,
                        0,
                        0
                      ],
                      "cellSize": 200,
                      "batchSize": 2000,
                      "doubleSided": false,
                      "flipSided": false,
                      "flatShaded": false,
                      "ignoreLight": true,
                      "celShaded": false,
                      "xrayShaded": false,
                      "transparentBackfaces": "off",
                      "bumpFrequency": 0,
                      "bumpAmplitude": 1,
                      "interior": {
                        "color": 5000268,
                        "colorStrength": 1,
                        "substance": {
                          "metalness": 0,
                          "roughness": 1,
                          "bumpiness": 0
                        },
                        "substanceStrength": 1
                      },
                      "unitKinds": [
                        "atomic"
                      ],
                      "includeParent": false,
                      "linkScale": 0.45,
                      "linkSpacing": 1,
                      "linkCap": false,
                      "aromaticScale": 0.3,
                      "aromaticSpacing": 1.5,
                      "aromaticDashCount": 2,
                      "dashCount": 6,
                      "dashScale": 0.4,
                      "dashCap": true,
                      "stubCap": true,
                      "radialSegments": 16,
                      "colorMode": "default",
                      "sizeFactor": 0.2,
                      "ignoreHydrogens": false,
                      "ignoreHydrogensVariant": "all",
                      "parentDisplay": "stub",
                      "visuals": [
                        "intra-unit",
                        "inter-unit"
                      ]
                    }
                  },
                  "colorTheme": {
                    "name": "interaction-type",
                    "params": {}
                  },
                  "sizeTheme": {
                    "name": "uniform",
                    "params": {
                      "value": 1
                    }
                  }
                },
                "tags": [
                  "structure-focus-surr-nci-repr"
                ],
                "ref": "aedGByOVrscRPbDEHVDBJw",
                "version": "2oMmjD-4ATTig42I63tw6w"
              },
              {
                "parent": "fvC-QIXnt1tJlgS7-UVREw",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "bundle",
                    "params": {
                      "hash": 1060573557,
                      "elements": [
                        {
                          "groupedUnits": [
                            [
                              0
                            ]
                          ],
                          "set": [],
                          "ranges": [
                            37,
                            42,
                            440,
                            445
                          ]
                        }
                      ]
                    }
                  },
                  "nullIfEmpty": true,
                  "label": "Custom Selection"
                },
                "tags": [
                  "structure-component-seaOTeFkDNACWUWZFOUdGQ"
                ],
                "ref": "GfiumPx-FW77ok-QC9fH3g",
                "version": "4plb0zkH_mn5OBWiERzv1Q"
              },
              {
                "parent": "GfiumPx-FW77ok-QC9fH3g",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "label",
                    "params": {
                      "alpha": 1,
                      "quality": "auto",
                      "material": {
                        "metalness": 0,
                        "roughness": 1,
                        "bumpiness": 0
                      },
                      "clip": {
                        "variant": "pixel",
                        "objects": []
                      },
                      "emissive": 0,
                      "density": 0.2,
                      "instanceGranularity": false,
                      "lod": [
                        0,
                        0,
                        0
                      ],
                      "cellSize": 200,
                      "batchSize": 2000,
                      "fontFamily": "sans-serif",
                      "fontQuality": 3,
                      "fontStyle": "normal",
                      "fontVariant": "normal",
                      "fontWeight": "normal",
                      "sizeFactor": 1,
                      "borderWidth": 0.15,
                      "borderColor": 8421504,
                      "offsetX": 0.2,
                      "offsetY": 0.8,
                      "offsetZ": 0,
                      "background": false,
                      "backgroundMargin": 0,
                      "backgroundColor": 0,
                      "backgroundOpacity": 0.5,
                      "tether": false,
                      "tetherLength": 1,
                      "tetherBaseWidth": 0.3,
                      "attachment": "middle-center",
                      "unitKinds": [
                        "atomic",
                        "spheres"
                      ],
                      "includeParent": false,
                      "level": "residue",
                      "ignoreHydrogens": false,
                      "ignoreHydrogensVariant": "all",
                      "chainScale": 10,
                      "residueScale": 1,
                      "elementScale": 0.5,
                      "visuals": [
                        "label-text"
                      ]
                    }
                  },
                  "colorTheme": {
                    "name": "uniform",
                    "params": {
                      "value": 13421772,
                      "saturation": 0.7,
                      "lightness": 0
                    }
                  },
                  "sizeTheme": {
                    "name": "physical",
                    "params": {
                      "scale": 1
                    }
                  }
                },
                "ref": "lvuRNLGsYpy5yTtpkifI6Q",
                "version": "rVc93at9FdGS3KvXgpj9fg"
              },
              {
                "parent": "AokOYTTh1Dn72_AQfvoPaQ",
                "transformer": "ms-plugin.model-unitcell-3d",
                "params": {
                  "alpha": 1,
                  "quality": "auto",
                  "material": {
                    "metalness": 0,
                    "roughness": 1,
                    "bumpiness": 0
                  },
                  "clip": {
                    "variant": "pixel",
                    "objects": []
                  },
                  "emissive": 0,
                  "density": 0.2,
                  "instanceGranularity": false,
                  "lod": [
                    0,
                    0,
                    0
                  ],
                  "cellSize": 200,
                  "batchSize": 2000,
                  "doubleSided": false,
                  "flipSided": false,
                  "flatShaded": false,
                  "ignoreLight": false,
                  "celShaded": false,
                  "xrayShaded": false,
                  "transparentBackfaces": "off",
                  "bumpFrequency": 0,
                  "bumpAmplitude": 1,
                  "interior": {
                    "color": 5000268,
                    "colorStrength": 1,
                    "substance": {
                      "metalness": 0,
                      "roughness": 1,
                      "bumpiness": 0
                    },
                    "substanceStrength": 1
                  },
                  "cellColor": 16753920,
                  "cellScale": 2,
                  "ref": "model",
                  "attachment": "corner"
                },
                "state": {
                  "isHidden": true
                },
                "ref": "gz9JCwQlLgFDPgiCt9XQDA",
                "version": "HvARAK06hB18fAy1v28ohw"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.create-group",
                "params": {
                  "label": "Measurements",
                  "description": ""
                },
                "tags": [
                  "measurement-group"
                ],
                "ref": "H6ab1oHGpqTgcG6RoaMPNg",
                "version": "KumLhXcWyUD7_m3mEwBUwA"
              }
            ]
          }
        },
        "animation": {
          "state": {
            "params": {
              "current": "built-in.animate-model-index"
            },
            "animationState": "stopped"
          },
          "current": {
            "paramValues": {
              "mode": {
                "name": "loop",
                "params": {
                  "direction": "forward"
                }
              },
              "duration": {
                "name": "fixed",
                "params": {
                  "durationInS": 5
                }
              }
            },
            "state": {}
          }
        },
        "camera": {
          "current": {
            "mode": "perspective",
            "fov": 0.7853981633974483,
            "position": [
              34.29412157603216,
              21.389707591846765,
              17.19422105961359
            ],
            "up": [
              -0.9735159767297609,
              -0.10628074143150272,
              0.20241306047946345
            ],
            "target": [
              30.071386575422988,
              12.013266224308248,
              -8.03851400709506
            ],
            "radius": 8.77087623226511,
            "radiusMax": 43.85438116132555,
            "fog": 45,
            "clipFar": true,
            "minNear": 20,
            "minFar": 0
          },
          "transitionStyle": "animate",
          "transitionDurationInMs": 250
        },
        "canvas3dContext": {
          "props": {
            "resolutionMode": "auto",
            "pixelScale": 1,
            "pickScale": 0.25,
            "transparency": "wboit"
          }
        },
        "canvas3d": {
          "props": {
            "camera": {
              "mode": "perspective",
              "helper": {
                "axes": {
                  "name": "on",
                  "params": {
                    "alpha": 0.51,
                    "colorX": 16711680,
                    "colorY": 32768,
                    "colorZ": 255,
                    "scale": 0.33,
                    "location": "bottom-left",
                    "locationOffsetX": 0,
                    "locationOffsetY": 0,
                    "originColor": 8421504,
                    "radiusScale": 0.075,
                    "showPlanes": true,
                    "planeColorXY": 8421504,
                    "planeColorXZ": 8421504,
                    "planeColorYZ": 8421504,
                    "showLabels": false,
                    "labelX": "X",
                    "labelY": "Y",
                    "labelZ": "Z",
                    "labelColorX": 8421504,
                    "labelColorY": 8421504,
                    "labelColorZ": 8421504,
                    "labelOpacity": 1,
                    "labelScale": 0.25
                  }
                }
              },
              "stereo": {
                "name": "off",
                "params": {}
              },
              "fov": 45,
              "manualReset": false
            },
            "cameraFog": {
              "name": "on",
              "params": {
                "intensity": 45
              }
            },
            "cameraClipping": {
              "far": true,
              "radius": 80,
              "minNear": 20
            },
            "cameraResetDurationMs": 250,
            "sceneRadiusFactor": 1,
            "transparentBackground": false,
            "checkeredTransparentBackground": true,
            "dpoitIterations": 2,
            "pickPadding": 3,
            "userInteractionReleaseMs": 250,
            "viewport": {
              "name": "canvas",
              "params": {}
            },
            "postprocessing": {
              "enabled": true,
              "occlusion": {
                "name": "on",
                "params": {
                  "samples": 32,
                  "multiScale": {
                    "name": "off",
                    "params": {}
                  },
                  "radius": 5,
                  "bias": 0.8,
                  "blurKernelSize": 15,
                  "blurDepthBias": 0.5,
                  "resolutionScale": 1,
                  "color": 0,
                  "transparentThreshold": 0.4
                }
              },
              "shadow": {
                "name": "off",
                "params": {}
              },
              "outline": {
                "name": "on",
                "params": {
                  "scale": 1,
                  "color": 0,
                  "threshold": 0.33,
                  "includeTransparent": true
                }
              },
              "dof": {
                "name": "off",
                "params": {}
              },
              "antialiasing": {
                "name": "smaa",
                "params": {
                  "edgeThreshold": 0.1,
                  "maxSearchSteps": 16
                }
              },
              "sharpening": {
                "name": "off",
                "params": {}
              },
              "background": {
                "variant": {
                  "name": "off",
                  "params": {}
                }
              },
              "bloom": {
                "name": "on",
                "params": {
                  "strength": 1,
                  "radius": 0,
                  "threshold": 0,
                  "mode": "emissive"
                }
              }
            },
            "marking": {
              "enabled": true,
              "highlightEdgeColor": 13119595,
              "selectEdgeColor": 51712,
              "edgeScale": 1,
              "highlightEdgeStrength": 1,
              "selectEdgeStrength": 1,
              "ghostEdgeStrength": 0.3,
              "innerEdgeFactor": 1.5
            },
            "multiSample": {
              "mode": "temporal",
              "sampleLevel": 2,
              "reduceFlicker": true,
              "reuseOcclusion": true
            },
            "illumination": {
              "enabled": false,
              "maxIterations": 5,
              "denoise": true,
              "denoiseThreshold": [
                0.15,
                1
              ],
              "ignoreOutline": true,
              "rendersPerFrame": [
                1,
                16
              ],
              "targetFps": 30,
              "steps": 32,
              "firstStepSize": 0.01,
              "refineSteps": 4,
              "rayDistance": 256,
              "thicknessMode": "auto",
              "minThickness": 0.5,
              "thicknessFactor": 1,
              "thickness": 4,
              "bounces": 4,
              "glow": true,
              "shadowEnable": false,
              "shadowSoftness": 0.1,
              "shadowThickness": 0.5
            },
            "hiZ": {
              "enabled": false,
              "maxFrameLag": 10,
              "minLevel": 3
            },
            "renderer": {
              "backgroundColor": 16579577,
              "pickingAlphaThreshold": 0.5,
              "colorMarker": true,
              "highlightColor": 16737945,
              "selectColor": 3407641,
              "dimColor": 16777215,
              "highlightStrength": 0.3,
              "selectStrength": 0.3,
              "dimStrength": 0,
              "markerPriority": 1,
              "xrayEdgeFalloff": 1,
              "celSteps": 5,
              "exposure": 1,
              "light": [
                {
                  "inclination": 150,
                  "azimuth": 320,
                  "color": 16777215,
                  "intensity": 0.6
                }
              ],
              "ambientColor": 16777215,
              "ambientIntensity": 0.4
            },
            "trackball": {
              "rotateSpeed": 5,
              "zoomSpeed": 7,
              "panSpeed": 1,
              "moveSpeed": 0.75,
              "boostMoveFactor": 5,
              "flyMode": false,
              "animate": {
                "name": "off",
                "params": {}
              },
              "staticMoving": true,
              "dynamicDampingFactor": 0.2,
              "minDistance": 5,
              "maxDistance": 222.27464159456358,
              "gestureScaleFactor": 1,
              "maxWheelDelta": 0.02,
              "autoAdjustMinMaxDistance": {
                "name": "on",
                "params": {
                  "minDistanceFactor": 0,
                  "minDistancePadding": 5,
                  "maxDistanceFactor": 10,
                  "maxDistanceMin": 20
                }
              }
            },
            "interaction": {
              "maxFps": 30,
              "preferAtomPixelPadding": 3,
              "convertCoordsToRay": false
            },
            "debug": {
              "sceneBoundingSpheres": false,
              "visibleSceneBoundingSpheres": false,
              "objectBoundingSpheres": false,
              "instanceBoundingSpheres": false
            },
            "handle": {
              "handle": {
                "name": "off",
                "params": {}
              }
            },
            "pointer": {
              "alpha": 1,
              "quality": "auto",
              "material": {
                "metalness": 0,
                "roughness": 1,
                "bumpiness": 0
              },
              "clip": {
                "variant": "pixel",
                "objects": []
              },
              "emissive": 0,
              "density": 0.2,
              "instanceGranularity": false,
              "lod": [
                0,
                0,
                0
              ],
              "cellSize": 200,
              "batchSize": 2000,
              "doubleSided": false,
              "flipSided": false,
              "flatShaded": false,
              "ignoreLight": true,
              "celShaded": false,
              "xrayShaded": false,
              "transparentBackfaces": "off",
              "bumpFrequency": 0,
              "bumpAmplitude": 1,
              "interior": {
                "color": 5000268,
                "colorStrength": 1,
                "substance": {
                  "metalness": 0,
                  "roughness": 1,
                  "bumpiness": 0
                },
                "substanceStrength": 1
              },
              "enabled": "off",
              "color": 8421504,
              "hitColor": 16761035
            },
            "xr": {
              "minTargetDistance": 0.4,
              "disablePostprocessing": true,
              "resolutionScale": 1,
              "sceneRadiusInMeters": 0.25
            }
          }
        },
        "interactivity": {
          "props": {
            "granularity": "residue"
          }
        },
        "structureFocus": {
          "current": {
            "label": "CYS 5 | A",
            "ref": "fvC-QIXnt1tJlgS7-UVREw",
            "bundle": {
              "hash": 1060573557,
              "elements": [
                {
                  "groupedUnits": [
                    [
                      0
                    ]
                  ],
                  "set": [],
                  "ranges": [
                    37,
                    42
                  ]
                }
              ]
            }
          }
        },
        "structureComponentManager": {
          "options": {
            "hydrogens": "all",
            "visualQuality": "auto",
            "ignoreLight": true,
            "materialStyle": {
              "metalness": 0,
              "roughness": 1,
              "bumpiness": 0
            },
            "clipObjects": {
              "variant": "pixel",
              "objects": []
            },
            "interactions": {
              "providers": {
                "ionic": {
                  "name": "off",
                  "params": {}
                },
                "pi-stacking": {
                  "name": "on",
                  "params": {
                    "distanceMax": 5.5,
                    "offsetMax": 2,
                    "angleDevMax": 30
                  }
                },
                "cation-pi": {
                  "name": "on",
                  "params": {
                    "distanceMax": 6,
                    "offsetMax": 2
                  }
                },
                "halogen-bonds": {
                  "name": "on",
                  "params": {
                    "distanceMax": 4,
                    "angleMax": 30
                  }
                },
                "hydrogen-bonds": {
                  "name": "on",
                  "params": {
                    "distanceMax": 3.5,
                    "backbone": true,
                    "accAngleDevMax": 45,
                    "ignoreHydrogens": false,
                    "donAngleDevMax": 45,
                    "accOutOfPlaneAngleMax": 90,
                    "donOutOfPlaneAngleMax": 45,
                    "water": false,
                    "sulfurDistanceMax": 4.1
                  }
                },
                "weak-hydrogen-bonds": {
                  "name": "off",
                  "params": {}
                },
                "hydrophobic": {
                  "name": "off",
                  "params": {}
                },
                "metal-coordination": {
                  "name": "on",
                  "params": {
                    "distanceMax": 3
                  }
                }
              },
              "contacts": {
                "lineOfSightDistFactor": 1
              }
            },
            "interior": {
              "color": 5000268,
              "colorStrength": 1,
              "substance": {
                "metalness": 0,
                "roughness": 1,
                "bumpiness": 0
              },
              "substanceStrength": 1
            }
          }
        },
        "durationInMs": 1500
      }
    }
  ]
};
        molstar.Viewer.create('app', {
          layoutShowControls: false,
          layoutIsExpanded: false,
          viewportShowControls: false,
          viewportShowExpand: false,
          viewportShowSettings: false,
          viewportShowSelectionMode: false,
          viewportShowToggleFullscreen: false,
          viewportShowAnimation: false,
        }).then(viewer => {
            var data64 = btoa(JSON.stringify(state));
            viewer.loadSnapshotFromUrl(`data:text/plain;base64,${data64}`, 'molj');
        });
    </script>
</div>
{% endraw %}

**Metal coordination.** A common interaction in proteins is the coordination of a metal ion to protein side chains; the coordinate covalent bonds between the protein and the metal ion form a type of internal metal chelate. A given protein can have more than one stabilising metal ion binding site. The metal ions that most commonly form such chelates are Calcium (Ca²⁺), Iron (Fe²⁺/³⁺) and Zinc (Zn2+). Sometimes when these metal ions are removed by chelating agents (e.g. EDTA), the protein remains folded, although less stable, under physiological conditions. In other cases, removal of the metal ions from the protein leads to denaturation.

{% raw %}
<div class="molstar-viewer">
    <link rel="stylesheet" type="text/css" href="https://molstar.org/viewer/molstar.css" />
    <style>
      .container {
          display: flex;
          justify-content: space-around; /* Adjust as needed */
          flex-wrap: wrap; /* Allow items to wrap to the next line */
      }
      .item {
          flex: 1;
          margin: 5px; /* Adjust margin as needed */
          text-align: center; /* Center text within each item */
          display: flex;
          flex-direction: column;
          align-items: center; /* Center content horizontally */
      }
      .item .app {
          height: 500px;
          width: 500px;
          position: relative;
      }
      .item .text {
          text-align: center; /* Center the text */
          margin-top: 5px; /* Adjust margin as needed */
      }
      .item h5 {
          text-align: center;
          margin-block-start: 0.5em !important;;
          margin-block-end: 0.5em !important;;
      }
      .msp-plugin small {
        display: initial !important;
        color: inherit !important;
    }
  </style>
  <div class="container">
    <div class="item">
        <div id="app1" class="app"></div>
        <div id="text">
          <h5>Subtilisin Carlsberg (PDB: <a href="https://www.ebi.ac.uk/pdbe/entry/pdb/1sca" target="_blank" rel="noreferrer noopener">1SCA</a>).This calcium ion acts as a stabilisation factor, not involved in catalysis. Removal of this significantly destabilises the protein.</h5>
        </div>
      </div>
    </div>
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <script type="text/javascript">
        const state2 ={
  "timestamp": 1770296366822,
  "version": "5.6.0",
  "current": "TgxjL2lkDZ2OBnWSuT0u2w",
  "playback": {
    "isPlaying": false,
    "nextSnapshotDelayInMs": 1500
  },
  "entries": [
    {
      "timestamp": 1770296366821,
      "snapshot": {
        "id": "TgxjL2lkDZ2OBnWSuT0u2w",
        "data": {
          "tree": {
            "transforms": [
              {
                "parent": "-=root=-",
                "transformer": "build-in.root",
                "params": {},
                "ref": "-=root=-",
                "version": "UYGCYwHqq_AwaLy8vy3PQw"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.download",
                "params": {
                  "url": {
                    "kind": "url",
                    "id": "U0p7o6EKR0XWhpJA_ox0Eg",
                    "url": "https://www.ebi.ac.uk/pdbe/entry-files/download/1sca.bcif"
                  },
                  "label": "PDBe: 1sca (updated cif)",
                  "isBinary": true
                },
                "state": {
                  "isGhost": true
                },
                "ref": "Yw3M72iKyAL2mDxCFytSHw",
                "version": "pEKfnkiOf4weV_L1rHG09w"
              },
              {
                "parent": "Yw3M72iKyAL2mDxCFytSHw",
                "transformer": "ms-plugin.parse-cif",
                "params": {},
                "state": {
                  "isGhost": true
                },
                "ref": "CTDKVV9Y22ucIJp9DnzxdQ",
                "version": "sRqG1K_MFL0Wk7IKIMQLMg"
              },
              {
                "parent": "CTDKVV9Y22ucIJp9DnzxdQ",
                "transformer": "ms-plugin.trajectory-from-mmcif",
                "params": {},
                "ref": "5E_WrcGa3Nv7zpJwF9hqzg",
                "version": "ab8rumjMoRPlPgPYkGRgyA"
              },
              {
                "parent": "5E_WrcGa3Nv7zpJwF9hqzg",
                "transformer": "ms-plugin.model-from-trajectory",
                "params": {
                  "modelIndex": 0
                },
                "ref": "6eJjg_cCpeDhI6w-n7oUPQ",
                "version": "MIbujdKwZyEGMi3BRrf7MA"
              },
              {
                "parent": "6eJjg_cCpeDhI6w-n7oUPQ",
                "transformer": "ms-plugin.custom-model-properties",
                "params": {
                  "autoAttach": [
                    "sifts_sequence_mapping"
                  ],
                  "properties": {
                    "asym_id_offset": {
                      "value": {
                        "auth": 0,
                        "label": 0
                      }
                    },
                    "index": {
                      "value": 0
                    },
                    "max_index": {
                      "value": 0
                    },
                    "sifts_sequence_mapping": {},
                    "pdbe_structure_quality_report": {
                      "serverUrl": "https://www.ebi.ac.uk/pdbe/api/validation/residuewise_outlier_summary/entry/"
                    },
                    "rcsb_validation_report": {
                      "source": {
                        "name": "server",
                        "params": {
                          "baseUrl": "https://files.rcsb.org/validation/view"
                        }
                      }
                    },
                    "mvs-is-mvs-model": {
                      "isMvs": false
                    },
                    "mvs-annotations": {
                      "annotations": []
                    }
                  }
                },
                "ref": "PwFKKarLLV-Y_h2n5DgpnQ",
                "version": "8khaChU659_fnE2hSyPjNw"
              },
              {
                "parent": "PwFKKarLLV-Y_h2n5DgpnQ",
                "transformer": "ms-plugin.structure-from-model",
                "params": {
                  "type": {
                    "name": "assembly",
                    "params": {
                      "id": "1",
                      "dynamicBonds": false
                    }
                  }
                },
                "ref": "lXf96j9KfK4Z5AKsUQvZ0A",
                "version": "mkjmz66UccKFC1zuJmV7NQ"
              },
              {
                "parent": "lXf96j9KfK4Z5AKsUQvZ0A",
                "transformer": "ms-plugin.custom-structure-properties",
                "params": {
                  "autoAttach": [],
                  "properties": {
                    "index": {
                      "value": 0
                    },
                    "max_index": {
                      "value": 0
                    },
                    "molstar_accessible_surface_area": {
                      "numberOfSpherePoints": 92,
                      "probeSize": 1.4,
                      "nonPolymer": false,
                      "traceOnly": false
                    },
                    "molstar_computed_interactions": {
                      "providers": {
                        "ionic": {
                          "name": "off",
                          "params": {}
                        },
                        "pi-stacking": {
                          "name": "on",
                          "params": {
                            "distanceMax": 5.5,
                            "offsetMax": 2,
                            "angleDevMax": 30
                          }
                        },
                        "cation-pi": {
                          "name": "on",
                          "params": {
                            "distanceMax": 6,
                            "offsetMax": 2
                          }
                        },
                        "halogen-bonds": {
                          "name": "on",
                          "params": {
                            "distanceMax": 4,
                            "angleMax": 30
                          }
                        },
                        "hydrogen-bonds": {
                          "name": "on",
                          "params": {
                            "distanceMax": 3.5,
                            "backbone": true,
                            "accAngleDevMax": 45,
                            "ignoreHydrogens": false,
                            "donAngleDevMax": 45,
                            "accOutOfPlaneAngleMax": 90,
                            "donOutOfPlaneAngleMax": 45,
                            "water": false,
                            "sulfurDistanceMax": 4.1
                          }
                        },
                        "weak-hydrogen-bonds": {
                          "name": "off",
                          "params": {}
                        },
                        "hydrophobic": {
                          "name": "off",
                          "params": {}
                        },
                        "metal-coordination": {
                          "name": "on",
                          "params": {
                            "distanceMax": 3
                          }
                        }
                      },
                      "contacts": {
                        "lineOfSightDistFactor": 1
                      }
                    },
                    "molstar_computed_secondary_structure": {
                      "type": {
                        "name": "auto",
                        "params": {}
                      }
                    },
                    "molstar_computed_valence_model": {
                      "assignCharge": "auto",
                      "assignH": "auto"
                    },
                    "molstar_struct_symmetry": {
                      "serverType": "rcsb",
                      "serverUrl": "https://data.rcsb.org/graphql",
                      "symmetryIndex": 0
                    },
                    "anvil_computed_membrane_orientation": {
                      "numberOfSpherePoints": 175,
                      "stepSize": 1,
                      "minThickness": 20,
                      "maxThickness": 40,
                      "asaCutoff": 40,
                      "adjust": 14,
                      "tmdetDefinition": false
                    },
                    "mvs-custom-tooltips": {
                      "tooltips": []
                    },
                    "mvs-annotation-tooltips": {
                      "tooltips": []
                    }
                  }
                },
                "ref": "79xGbeSME0Cgvpaz_a6xFg",
                "version": "qxIY0R2IxpHgWVHMXTiBbA"
              },
              {
                "parent": "79xGbeSME0Cgvpaz_a6xFg",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "static",
                    "params": "polymer"
                  },
                  "nullIfEmpty": true,
                  "label": ""
                },
                "tags": [
                  "structure-component-static-polymer"
                ],
                "ref": "DLVl77gpqsrXU2UnLzHJLg",
                "version": "LDuQEWTp4UNGOh-znFY3Pg"
              },
              {
                "parent": "DLVl77gpqsrXU2UnLzHJLg",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "cartoon",
                    "params": {
                      "alpha": 1,
                      "quality": "auto",
                      "material": {
                        "metalness": 0,
                        "roughness": 1,
                        "bumpiness": 0
                      },
                      "clip": {
                        "variant": "pixel",
                        "objects": []
                      },
                      "emissive": 0,
                      "density": 0.1,
                      "instanceGranularity": false,
                      "lod": [
                        0,
                        0,
                        0
                      ],
                      "cellSize": 200,
                      "batchSize": 2000,
                      "doubleSided": false,
                      "flipSided": false,
                      "flatShaded": false,
                      "ignoreLight": true,
                      "celShaded": false,
                      "xrayShaded": false,
                      "transparentBackfaces": "off",
                      "bumpFrequency": 2,
                      "bumpAmplitude": 1,
                      "interior": {
                        "color": 5000268,
                        "colorStrength": 1,
                        "substance": {
                          "metalness": 0,
                          "roughness": 1,
                          "bumpiness": 0
                        },
                        "substanceStrength": 1
                      },
                      "unitKinds": [
                        "atomic",
                        "spheres"
                      ],
                      "includeParent": false,
                      "sizeFactor": 0.2,
                      "aspectRatio": 5,
                      "arrowFactor": 1.5,
                      "tubularHelices": false,
                      "roundCap": false,
                      "helixProfile": "elliptical",
                      "nucleicProfile": "square",
                      "detail": 0,
                      "linearSegments": 8,
                      "radialSegments": 16,
                      "thicknessFactor": 1,
                      "sizeAspectRatio": 1,
                      "solidInterior": true,
                      "colorMode": "default",
                      "tryUseImpostor": true,
                      "clipPrimitive": false,
                      "approximate": false,
                      "alphaThickness": 0,
                      "lodLevels": [],
                      "visuals": [
                        "polymer-trace"
                      ]
                    }
                  },
                  "colorTheme": {
                    "name": "chain-id",
                    "params": {
                      "asymId": "auth",
                      "palette": {
                        "name": "colors",
                        "params": {
                          "list": {
                            "kind": "set",
                            "colors": [
                              1810039,
                              14245634,
                              7696563,
                              15149450,
                              6727198,
                              15117058,
                              10909213,
                              6710886,
                              14948892,
                              3636920,
                              5091146,
                              9981603,
                              16744192,
                              16777011,
                              10901032,
                              16220607,
                              10066329,
                              6734501,
                              16551266,
                              9281739,
                              15174339,
                              10934356,
                              16767279,
                              15058068,
                              11776947
                            ]
                          }
                        }
                      }
                    }
                  },
                  "sizeTheme": {
                    "name": "uniform",
                    "params": {
                      "value": 1
                    }
                  }
                },
                "tags": [
                  "polymer"
                ],
                "ref": "raCi7zsrnQ9BWGCAkNyDqw",
                "version": "0rNcvIfF9A_s0fELHy8T5w"
              },
              {
                "parent": "79xGbeSME0Cgvpaz_a6xFg",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "static",
                    "params": "ion"
                  },
                  "nullIfEmpty": true,
                  "label": ""
                },
                "tags": [
                  "structure-component-static-ion"
                ],
                "ref": "0q7bq3kONDOI_kh7zvDQhQ",
                "version": "4prnbp7AHMONxTaR09isNw"
              },
              {
                "parent": "0q7bq3kONDOI_kh7zvDQhQ",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "ball-and-stick",
                    "params": {
                      "alpha": 1,
                      "quality": "auto",
                      "material": {
                        "metalness": 0,
                        "roughness": 1,
                        "bumpiness": 0
                      },
                      "clip": {
                        "variant": "pixel",
                        "objects": []
                      },
                      "emissive": 0,
                      "density": 0.1,
                      "instanceGranularity": false,
                      "lod": [
                        0,
                        0,
                        0
                      ],
                      "cellSize": 200,
                      "batchSize": 2000,
                      "doubleSided": false,
                      "flipSided": false,
                      "flatShaded": false,
                      "ignoreLight": true,
                      "celShaded": false,
                      "xrayShaded": false,
                      "transparentBackfaces": "off",
                      "bumpFrequency": 0,
                      "bumpAmplitude": 1,
                      "interior": {
                        "color": 5000268,
                        "colorStrength": 1,
                        "substance": {
                          "metalness": 0,
                          "roughness": 1,
                          "bumpiness": 0
                        },
                        "substanceStrength": 1
                      },
                      "unitKinds": [
                        "atomic"
                      ],
                      "includeParent": false,
                      "sizeFactor": 0.15,
                      "solidInterior": true,
                      "clipPrimitive": false,
                      "approximate": false,
                      "alphaThickness": 0,
                      "lodLevels": [],
                      "detail": 0,
                      "ignoreHydrogens": false,
                      "ignoreHydrogensVariant": "all",
                      "traceOnly": false,
                      "tryUseImpostor": true,
                      "stride": 1,
                      "sizeAspectRatio": 0.6666666666666666,
                      "colorMode": "default",
                      "linkScale": 0.45,
                      "linkSpacing": 1,
                      "linkCap": false,
                      "aromaticScale": 0.3,
                      "aromaticSpacing": 1.5,
                      "aromaticDashCount": 2,
                      "dashCount": 4,
                      "dashScale": 0.8,
                      "dashCap": true,
                      "stubCap": true,
                      "radialSegments": 16,
                      "includeTypes": [
                        "covalent",
                        "metal-coordination",
                        "hydrogen-bond",
                        "disulfide",
                        "aromatic",
                        "computed"
                      ],
                      "excludeTypes": [],
                      "aromaticBonds": true,
                      "multipleBonds": "symmetric",
                      "adjustCylinderLength": false,
                      "visuals": [
                        "element-sphere",
                        "intra-bond",
                        "inter-bond"
                      ]
                    }
                  },
                  "colorTheme": {
                    "name": "element-symbol",
                    "params": {
                      "carbonColor": {
                        "name": "element-symbol",
                        "params": {}
                      },
                      "saturation": 0,
                      "lightness": 0.2,
                      "colors": {
                        "name": "default",
                        "params": {}
                      }
                    }
                  },
                  "sizeTheme": {
                    "name": "physical",
                    "params": {
                      "scale": 1
                    }
                  }
                },
                "tags": [
                  "ion"
                ],
                "ref": "2iIaHrENlI02iJnxYeZa3g",
                "version": "2kF8JgX25T62b3TZbM5mfw"
              },
              {
                "parent": "79xGbeSME0Cgvpaz_a6xFg",
                "transformer": "ms-plugin.structure-selection-from-bundle",
                "params": {
                  "bundle": {
                    "hash": 880277281,
                    "elements": [
                      {
                        "groupedUnits": [
                          [
                            1
                          ]
                        ],
                        "set": [
                          0
                        ],
                        "ranges": []
                      }
                    ]
                  },
                  "label": "[Focus] Target"
                },
                "tags": [
                  "structure-focus-target-sel"
                ],
                "ref": "ZQiRaBFyq1wnrpLnEm2jVQ",
                "version": "ii25DNMqWOh92XmpeHYlEQ"
              },
              {
                "parent": "ZQiRaBFyq1wnrpLnEm2jVQ",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "ball-and-stick",
                    "params": {
                      "alpha": 1,
                      "quality": "auto",
                      "material": {
                        "metalness": 0,
                        "roughness": 1,
                        "bumpiness": 0
                      },
                      "clip": {
                        "variant": "pixel",
                        "objects": []
                      },
                      "emissive": 0,
                      "density": 0.1,
                      "instanceGranularity": false,
                      "lod": [
                        0,
                        0,
                        0
                      ],
                      "cellSize": 200,
                      "batchSize": 2000,
                      "doubleSided": false,
                      "flipSided": false,
                      "flatShaded": false,
                      "ignoreLight": true,
                      "celShaded": false,
                      "xrayShaded": true,
                      "transparentBackfaces": "off",
                      "bumpFrequency": 0,
                      "bumpAmplitude": 1,
                      "interior": {
                        "color": 5000268,
                        "colorStrength": 1,
                        "substance": {
                          "metalness": 0,
                          "roughness": 1,
                          "bumpiness": 0
                        },
                        "substanceStrength": 1
                      },
                      "unitKinds": [
                        "atomic"
                      ],
                      "includeParent": false,
                      "sizeFactor": 0.22,
                      "solidInterior": true,
                      "clipPrimitive": false,
                      "approximate": false,
                      "alphaThickness": 0,
                      "lodLevels": [],
                      "detail": 0,
                      "ignoreHydrogens": false,
                      "ignoreHydrogensVariant": "all",
                      "traceOnly": false,
                      "tryUseImpostor": true,
                      "stride": 1,
                      "sizeAspectRatio": 0.73,
                      "colorMode": "default",
                      "linkScale": 0.45,
                      "linkSpacing": 1,
                      "linkCap": false,
                      "aromaticScale": 0.3,
                      "aromaticSpacing": 1.5,
                      "aromaticDashCount": 2,
                      "dashCount": 4,
                      "dashScale": 0.8,
                      "dashCap": true,
                      "stubCap": true,
                      "radialSegments": 16,
                      "includeTypes": [
                        "covalent",
                        "metal-coordination",
                        "hydrogen-bond",
                        "disulfide",
                        "aromatic",
                        "computed"
                      ],
                      "excludeTypes": [
                        "hydrogen-bond",
                        "metal-coordination"
                      ],
                      "aromaticBonds": false,
                      "multipleBonds": "off",
                      "adjustCylinderLength": true,
                      "visuals": [
                        "element-sphere",
                        "intra-bond",
                        "inter-bond"
                      ]
                    }
                  },
                  "colorTheme": {
                    "name": "element-symbol",
                    "params": {
                      "carbonColor": {
                        "name": "chain-id",
                        "params": {
                          "asymId": "auth",
                          "palette": {
                            "name": "colors",
                            "params": {
                              "list": {
                                "kind": "set",
                                "colors": [
                                  1810039,
                                  14245634,
                                  7696563,
                                  15149450,
                                  6727198,
                                  15117058,
                                  10909213,
                                  6710886,
                                  14948892,
                                  3636920,
                                  5091146,
                                  9981603,
                                  16744192,
                                  16777011,
                                  10901032,
                                  16220607,
                                  10066329,
                                  6734501,
                                  16551266,
                                  9281739,
                                  15174339,
                                  10934356,
                                  16767279,
                                  15058068,
                                  11776947
                                ]
                              }
                            }
                          }
                        }
                      },
                      "saturation": 0,
                      "lightness": 0.2,
                      "colors": {
                        "name": "default",
                        "params": {}
                      }
                    }
                  },
                  "sizeTheme": {
                    "name": "physical",
                    "params": {
                      "scale": 1
                    }
                  }
                },
                "tags": [
                  "structure-focus-target-repr"
                ],
                "ref": "_sv6diBWXh3OEaz8VLMPLA",
                "version": "yHQ6DrKtggOeT9IAXQEbjA"
              },
              {
                "parent": "79xGbeSME0Cgvpaz_a6xFg",
                "transformer": "ms-plugin.structure-selection-from-expression",
                "params": {
                  "expression": {
                    "head": {
                      "name": "structure-query.modifier.include-surroundings"
                    },
                    "args": {
                      "0": {
                        "head": {
                          "name": "internal.generator.bundle"
                        },
                        "args": {
                          "elements": {
                            "head": {
                              "name": "core.type.list"
                            },
                            "args": [
                              {
                                "head": {
                                  "name": "internal.generator.bundle-element"
                                },
                                "args": {
                                  "groupedUnits": {
                                    "head": {
                                      "name": "core.type.list"
                                    },
                                    "args": [
                                      {
                                        "head": {
                                          "name": "core.type.list"
                                        },
                                        "args": [
                                          1
                                        ]
                                      }
                                    ]
                                  },
                                  "ranges": {
                                    "head": {
                                      "name": "core.type.list"
                                    },
                                    "args": []
                                  },
                                  "set": {
                                    "head": {
                                      "name": "core.type.list"
                                    },
                                    "args": [
                                      0
                                    ]
                                  }
                                }
                              }
                            ]
                          }
                        }
                      },
                      "radius": 5,
                      "as-whole-residues": true
                    }
                  },
                  "label": "[Focus] Surroundings (5 Å)"
                },
                "tags": [
                  "structure-focus-surr-sel"
                ],
                "ref": "ByqiahzmEFIZBWQkKhCQaA",
                "version": "yyWy8HOqPyCC0kGdgCHjTA"
              },
              {
                "parent": "ByqiahzmEFIZBWQkKhCQaA",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "ball-and-stick",
                    "params": {
                      "alpha": 1,
                      "quality": "auto",
                      "material": {
                        "metalness": 0,
                        "roughness": 1,
                        "bumpiness": 0
                      },
                      "clip": {
                        "variant": "pixel",
                        "objects": []
                      },
                      "emissive": 0,
                      "density": 0.1,
                      "instanceGranularity": false,
                      "lod": [
                        0,
                        0,
                        0
                      ],
                      "cellSize": 200,
                      "batchSize": 2000,
                      "doubleSided": false,
                      "flipSided": false,
                      "flatShaded": false,
                      "ignoreLight": true,
                      "celShaded": false,
                      "xrayShaded": false,
                      "transparentBackfaces": "off",
                      "bumpFrequency": 0,
                      "bumpAmplitude": 1,
                      "interior": {
                        "color": 5000268,
                        "colorStrength": 1,
                        "substance": {
                          "metalness": 0,
                          "roughness": 1,
                          "bumpiness": 0
                        },
                        "substanceStrength": 1
                      },
                      "unitKinds": [
                        "atomic"
                      ],
                      "includeParent": false,
                      "sizeFactor": 0.16,
                      "solidInterior": true,
                      "clipPrimitive": false,
                      "approximate": false,
                      "alphaThickness": 0,
                      "lodLevels": [],
                      "detail": 0,
                      "ignoreHydrogens": false,
                      "ignoreHydrogensVariant": "all",
                      "traceOnly": false,
                      "tryUseImpostor": true,
                      "stride": 1,
                      "sizeAspectRatio": 0.6666666666666666,
                      "colorMode": "default",
                      "linkScale": 0.45,
                      "linkSpacing": 1,
                      "linkCap": false,
                      "aromaticScale": 0.3,
                      "aromaticSpacing": 1.5,
                      "aromaticDashCount": 2,
                      "dashCount": 4,
                      "dashScale": 0.8,
                      "dashCap": true,
                      "stubCap": true,
                      "radialSegments": 16,
                      "includeTypes": [
                        "covalent",
                        "metal-coordination",
                        "hydrogen-bond",
                        "disulfide",
                        "aromatic",
                        "computed"
                      ],
                      "excludeTypes": [
                        "hydrogen-bond",
                        "metal-coordination"
                      ],
                      "aromaticBonds": true,
                      "multipleBonds": "symmetric",
                      "adjustCylinderLength": false,
                      "visuals": [
                        "element-sphere",
                        "intra-bond",
                        "inter-bond"
                      ]
                    }
                  },
                  "colorTheme": {
                    "name": "element-symbol",
                    "params": {
                      "carbonColor": {
                        "name": "chain-id",
                        "params": {
                          "asymId": "auth",
                          "palette": {
                            "name": "colors",
                            "params": {
                              "list": {
                                "kind": "set",
                                "colors": [
                                  1810039,
                                  14245634,
                                  7696563,
                                  15149450,
                                  6727198,
                                  15117058,
                                  10909213,
                                  6710886,
                                  14948892,
                                  3636920,
                                  5091146,
                                  9981603,
                                  16744192,
                                  16777011,
                                  10901032,
                                  16220607,
                                  10066329,
                                  6734501,
                                  16551266,
                                  9281739,
                                  15174339,
                                  10934356,
                                  16767279,
                                  15058068,
                                  11776947
                                ]
                              }
                            }
                          }
                        }
                      },
                      "saturation": 0,
                      "lightness": 0.2,
                      "colors": {
                        "name": "default",
                        "params": {}
                      }
                    }
                  },
                  "sizeTheme": {
                    "name": "physical",
                    "params": {
                      "scale": 1
                    }
                  }
                },
                "tags": [
                  "structure-focus-surr-repr"
                ],
                "ref": "Tyd0GTh_CJilDUau3oYWDQ",
                "version": "y6BrxSBw5G-v-fInmkFVHg"
              },
              {
                "parent": "ByqiahzmEFIZBWQkKhCQaA",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "interactions",
                    "params": {
                      "alpha": 1,
                      "quality": "auto",
                      "material": {
                        "metalness": 0,
                        "roughness": 1,
                        "bumpiness": 0
                      },
                      "clip": {
                        "variant": "pixel",
                        "objects": []
                      },
                      "emissive": 0,
                      "density": 0.2,
                      "instanceGranularity": false,
                      "lod": [
                        0,
                        0,
                        0
                      ],
                      "cellSize": 200,
                      "batchSize": 2000,
                      "doubleSided": false,
                      "flipSided": false,
                      "flatShaded": false,
                      "ignoreLight": true,
                      "celShaded": false,
                      "xrayShaded": false,
                      "transparentBackfaces": "off",
                      "bumpFrequency": 0,
                      "bumpAmplitude": 1,
                      "interior": {
                        "color": 5000268,
                        "colorStrength": 1,
                        "substance": {
                          "metalness": 0,
                          "roughness": 1,
                          "bumpiness": 0
                        },
                        "substanceStrength": 1
                      },
                      "unitKinds": [
                        "atomic"
                      ],
                      "includeParent": false,
                      "linkScale": 0.45,
                      "linkSpacing": 1,
                      "linkCap": false,
                      "aromaticScale": 0.3,
                      "aromaticSpacing": 1.5,
                      "aromaticDashCount": 2,
                      "dashCount": 6,
                      "dashScale": 0.4,
                      "dashCap": true,
                      "stubCap": true,
                      "radialSegments": 16,
                      "colorMode": "default",
                      "sizeFactor": 0.2,
                      "ignoreHydrogens": false,
                      "ignoreHydrogensVariant": "all",
                      "parentDisplay": "stub",
                      "visuals": [
                        "intra-unit",
                        "inter-unit"
                      ]
                    }
                  },
                  "colorTheme": {
                    "name": "interaction-type",
                    "params": {}
                  },
                  "sizeTheme": {
                    "name": "uniform",
                    "params": {
                      "value": 1
                    }
                  }
                },
                "tags": [
                  "structure-focus-surr-nci-repr"
                ],
                "ref": "SENlLibkfN5TaoT0Fe51ew",
                "version": "bJkkHa10x4mQOe6tWmuInQ"
              },
              {
                "parent": "PwFKKarLLV-Y_h2n5DgpnQ",
                "transformer": "ms-plugin.model-unitcell-3d",
                "params": {
                  "alpha": 1,
                  "quality": "auto",
                  "material": {
                    "metalness": 0,
                    "roughness": 1,
                    "bumpiness": 0
                  },
                  "clip": {
                    "variant": "pixel",
                    "objects": []
                  },
                  "emissive": 0,
                  "density": 0.2,
                  "instanceGranularity": false,
                  "lod": [
                    0,
                    0,
                    0
                  ],
                  "cellSize": 200,
                  "batchSize": 2000,
                  "doubleSided": false,
                  "flipSided": false,
                  "flatShaded": false,
                  "ignoreLight": false,
                  "celShaded": false,
                  "xrayShaded": false,
                  "transparentBackfaces": "off",
                  "bumpFrequency": 0,
                  "bumpAmplitude": 1,
                  "interior": {
                    "color": 5000268,
                    "colorStrength": 1,
                    "substance": {
                      "metalness": 0,
                      "roughness": 1,
                      "bumpiness": 0
                    },
                    "substanceStrength": 1
                  },
                  "cellColor": 16753920,
                  "cellScale": 2,
                  "ref": "model",
                  "attachment": "corner"
                },
                "state": {
                  "isHidden": true
                },
                "ref": "HMKJxD9fBue-ttzjTAlR_A",
                "version": "_bMeeSmidkv2LHE1AfPr-A"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.create-group",
                "params": {
                  "label": "Measurements",
                  "description": ""
                },
                "tags": [
                  "measurement-group"
                ],
                "ref": "GbABNq7nzpslhJ3lr7Haiw",
                "version": "PqEhvNfP4VFkRKDTodRwMQ"
              }
            ]
          }
        },
        "animation": {
          "state": {
            "params": {
              "current": "built-in.animate-model-index"
            },
            "animationState": "stopped"
          },
          "current": {
            "paramValues": {
              "mode": {
                "name": "loop",
                "params": {
                  "direction": "forward"
                }
              },
              "duration": {
                "name": "fixed",
                "params": {
                  "durationInS": 5
                }
              }
            },
            "state": {}
          }
        },
        "camera": {
          "current": {
            "mode": "perspective",
            "fov": 0.7853981633974483,
            "position": [
              108.96605709239715,
              60.606968807637664,
              68.45467596245672
            ],
            "up": [
              -0.41286835448678966,
              0.0922601727919607,
              -0.906105833983922
            ],
            "target": [
              90.18799999999999,
              65.646,
              77.52399999999999
            ],
            "radius": 7.788536242118237,
            "radiusMax": 59.91181724706336,
            "fog": 51,
            "clipFar": true,
            "minNear": 12,
            "minFar": 0
          },
          "transitionStyle": "animate",
          "transitionDurationInMs": 250
        },
        "canvas3dContext": {
          "props": {
            "resolutionMode": "auto",
            "pixelScale": 1,
            "pickScale": 0.25,
            "transparency": "wboit"
          }
        },
        "canvas3d": {
          "props": {
            "camera": {
              "mode": "perspective",
              "helper": {
                "axes": {
                  "name": "on",
                  "params": {
                    "alpha": 0.51,
                    "colorX": 16711680,
                    "colorY": 32768,
                    "colorZ": 255,
                    "scale": 0.33,
                    "location": "bottom-left",
                    "locationOffsetX": 0,
                    "locationOffsetY": 0,
                    "originColor": 8421504,
                    "radiusScale": 0.075,
                    "showPlanes": true,
                    "planeColorXY": 8421504,
                    "planeColorXZ": 8421504,
                    "planeColorYZ": 8421504,
                    "showLabels": false,
                    "labelX": "X",
                    "labelY": "Y",
                    "labelZ": "Z",
                    "labelColorX": 8421504,
                    "labelColorY": 8421504,
                    "labelColorZ": 8421504,
                    "labelOpacity": 1,
                    "labelScale": 0.25
                  }
                }
              },
              "stereo": {
                "name": "off",
                "params": {}
              },
              "fov": 45,
              "manualReset": false
            },
            "cameraFog": {
              "name": "on",
              "params": {
                "intensity": 51
              }
            },
            "cameraClipping": {
              "far": true,
              "radius": 87,
              "minNear": 12
            },
            "cameraResetDurationMs": 250,
            "sceneRadiusFactor": 1,
            "transparentBackground": false,
            "checkeredTransparentBackground": true,
            "dpoitIterations": 2,
            "pickPadding": 3,
            "userInteractionReleaseMs": 250,
            "viewport": {
              "name": "canvas",
              "params": {}
            },
            "postprocessing": {
              "enabled": true,
              "occlusion": {
                "name": "on",
                "params": {
                  "samples": 32,
                  "multiScale": {
                    "name": "off",
                    "params": {}
                  },
                  "radius": 5,
                  "bias": 0.8,
                  "blurKernelSize": 15,
                  "blurDepthBias": 0.5,
                  "resolutionScale": 1,
                  "color": 0,
                  "transparentThreshold": 0.4
                }
              },
              "shadow": {
                "name": "off",
                "params": {}
              },
              "outline": {
                "name": "on",
                "params": {
                  "scale": 1,
                  "color": 0,
                  "threshold": 0.33,
                  "includeTransparent": true
                }
              },
              "dof": {
                "name": "off",
                "params": {}
              },
              "antialiasing": {
                "name": "smaa",
                "params": {
                  "edgeThreshold": 0.1,
                  "maxSearchSteps": 16
                }
              },
              "sharpening": {
                "name": "off",
                "params": {}
              },
              "background": {
                "variant": {
                  "name": "off",
                  "params": {}
                }
              },
              "bloom": {
                "name": "on",
                "params": {
                  "strength": 1,
                  "radius": 0,
                  "threshold": 0,
                  "mode": "emissive"
                }
              }
            },
            "marking": {
              "enabled": true,
              "highlightEdgeColor": 13119595,
              "selectEdgeColor": 51712,
              "edgeScale": 1,
              "highlightEdgeStrength": 1,
              "selectEdgeStrength": 1,
              "ghostEdgeStrength": 0.3,
              "innerEdgeFactor": 1.5
            },
            "multiSample": {
              "mode": "temporal",
              "sampleLevel": 2,
              "reduceFlicker": true,
              "reuseOcclusion": true
            },
            "illumination": {
              "enabled": false,
              "maxIterations": 5,
              "denoise": true,
              "denoiseThreshold": [
                0.15,
                1
              ],
              "ignoreOutline": true,
              "rendersPerFrame": [
                1,
                16
              ],
              "targetFps": 30,
              "steps": 32,
              "firstStepSize": 0.01,
              "refineSteps": 4,
              "rayDistance": 256,
              "thicknessMode": "auto",
              "minThickness": 0.5,
              "thicknessFactor": 1,
              "thickness": 4,
              "bounces": 4,
              "glow": true,
              "shadowEnable": false,
              "shadowSoftness": 0.1,
              "shadowThickness": 0.5
            },
            "hiZ": {
              "enabled": false,
              "maxFrameLag": 10,
              "minLevel": 3
            },
            "renderer": {
              "backgroundColor": 16579577,
              "pickingAlphaThreshold": 0.5,
              "colorMarker": true,
              "highlightColor": 16737945,
              "selectColor": 3407641,
              "dimColor": 16777215,
              "highlightStrength": 0.3,
              "selectStrength": 0.3,
              "dimStrength": 0,
              "markerPriority": 1,
              "xrayEdgeFalloff": 1,
              "celSteps": 5,
              "exposure": 1,
              "light": [
                {
                  "inclination": 150,
                  "azimuth": 320,
                  "color": 16777215,
                  "intensity": 0.6
                }
              ],
              "ambientColor": 16777215,
              "ambientIntensity": 0.4
            },
            "trackball": {
              "rotateSpeed": 5,
              "zoomSpeed": 7,
              "panSpeed": 1,
              "moveSpeed": 0.75,
              "boostMoveFactor": 5,
              "flyMode": false,
              "animate": {
                "name": "off",
                "params": {}
              },
              "staticMoving": true,
              "dynamicDampingFactor": 0.2,
              "minDistance": 5,
              "maxDistance": 286.2735227470269,
              "gestureScaleFactor": 1,
              "maxWheelDelta": 0.02,
              "autoAdjustMinMaxDistance": {
                "name": "on",
                "params": {
                  "minDistanceFactor": 0,
                  "minDistancePadding": 5,
                  "maxDistanceFactor": 10,
                  "maxDistanceMin": 20
                }
              }
            },
            "interaction": {
              "maxFps": 30,
              "preferAtomPixelPadding": 3,
              "convertCoordsToRay": false
            },
            "debug": {
              "sceneBoundingSpheres": false,
              "visibleSceneBoundingSpheres": false,
              "objectBoundingSpheres": false,
              "instanceBoundingSpheres": false
            },
            "handle": {
              "handle": {
                "name": "off",
                "params": {}
              }
            },
            "pointer": {
              "alpha": 1,
              "quality": "auto",
              "material": {
                "metalness": 0,
                "roughness": 1,
                "bumpiness": 0
              },
              "clip": {
                "variant": "pixel",
                "objects": []
              },
              "emissive": 0,
              "density": 0.2,
              "instanceGranularity": false,
              "lod": [
                0,
                0,
                0
              ],
              "cellSize": 200,
              "batchSize": 2000,
              "doubleSided": false,
              "flipSided": false,
              "flatShaded": false,
              "ignoreLight": true,
              "celShaded": false,
              "xrayShaded": false,
              "transparentBackfaces": "off",
              "bumpFrequency": 0,
              "bumpAmplitude": 1,
              "interior": {
                "color": 5000268,
                "colorStrength": 1,
                "substance": {
                  "metalness": 0,
                  "roughness": 1,
                  "bumpiness": 0
                },
                "substanceStrength": 1
              },
              "enabled": "off",
              "color": 8421504,
              "hitColor": 16761035
            },
            "xr": {
              "minTargetDistance": 0.4,
              "disablePostprocessing": true,
              "resolutionScale": 1,
              "sceneRadiusInMeters": 0.25
            }
          }
        },
        "interactivity": {
          "props": {
            "granularity": "element"
          }
        },
        "structureFocus": {
          "current": {
            "label": "CA 401 | B [auth A]",
            "ref": "79xGbeSME0Cgvpaz_a6xFg",
            "bundle": {
              "hash": 880277281,
              "elements": [
                {
                  "groupedUnits": [
                    [
                      1
                    ]
                  ],
                  "set": [
                    0
                  ],
                  "ranges": []
                }
              ]
            }
          }
        },
        "structureComponentManager": {
          "options": {
            "hydrogens": "all",
            "visualQuality": "auto",
            "ignoreLight": true,
            "materialStyle": {
              "metalness": 0,
              "roughness": 1,
              "bumpiness": 0
            },
            "clipObjects": {
              "variant": "pixel",
              "objects": []
            },
            "interactions": {
              "providers": {
                "ionic": {
                  "name": "off",
                  "params": {}
                },
                "pi-stacking": {
                  "name": "on",
                  "params": {
                    "distanceMax": 5.5,
                    "offsetMax": 2,
                    "angleDevMax": 30
                  }
                },
                "cation-pi": {
                  "name": "on",
                  "params": {
                    "distanceMax": 6,
                    "offsetMax": 2
                  }
                },
                "halogen-bonds": {
                  "name": "on",
                  "params": {
                    "distanceMax": 4,
                    "angleMax": 30
                  }
                },
                "hydrogen-bonds": {
                  "name": "on",
                  "params": {
                    "distanceMax": 3.5,
                    "backbone": true,
                    "accAngleDevMax": 45,
                    "ignoreHydrogens": false,
                    "donAngleDevMax": 45,
                    "accOutOfPlaneAngleMax": 90,
                    "donOutOfPlaneAngleMax": 45,
                    "water": false,
                    "sulfurDistanceMax": 4.1
                  }
                },
                "weak-hydrogen-bonds": {
                  "name": "off",
                  "params": {}
                },
                "hydrophobic": {
                  "name": "off",
                  "params": {}
                },
                "metal-coordination": {
                  "name": "on",
                  "params": {
                    "distanceMax": 3
                  }
                }
              },
              "contacts": {
                "lineOfSightDistFactor": 1
              }
            },
            "interior": {
              "color": 5000268,
              "colorStrength": 1,
              "substance": {
                "metalness": 0,
                "roughness": 1,
                "bumpiness": 0
              },
              "substanceStrength": 1
            }
          }
        },
        "durationInMs": 1500
      }
    }
  ]
};
        molstar.Viewer.create('app1', {
          layoutShowControls: false,
          layoutIsExpanded: false,
          viewportShowControls: false,
          viewportShowExpand: false,
          viewportShowSettings: false,
          viewportShowSelectionMode: false,
          viewportShowToggleFullscreen: false,
          viewportShowAnimation: false,
        }).then(viewer => {
            var data64 = btoa(JSON.stringify(state2));
            viewer.loadSnapshotFromUrl(`data:text/plain;base64,${data64}`, 'molj');
        });
    </script>
</div>
{% endraw %}

**Cofactor binding.** Some proteins are additionally stabilised by the covalent or tight non-covalent binding of organic or organometallic cofactors at or near the active site. These cofactors can make important contributions to both fold stability and function.