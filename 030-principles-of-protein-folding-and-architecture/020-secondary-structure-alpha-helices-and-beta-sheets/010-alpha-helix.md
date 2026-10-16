---
layout: default
title: 'α-helix'
---

# α-helix

The α-helix is by far the most common secondary structure element in proteins.

An α-helix forms when the polypeptide backbone coils into a right-handed spiral. The defining feature is the hydrogen bonding pattern: the carbonyl oxygen of residue i forms a hydrogen bond with the amide hydrogen of residue i+4. This means that if you start at any amino acid in the helix, count four residues forward along the sequence, and you’ll find the backbone hydrogen bond partner. This pattern creates a tightly wound structure with 3.6 residues per complete turn.

The helical geometry places all side chains projecting outward from the central axis, much like the bristles on a bottle brush. This arrangement minimises steric clashes between bulky side chains while allowing the backbone to maintain its favourable hydrogen bonding. The rise per residue along the helical axis is only 1.5 Å, making α-helices remarkably compact structures. A 20-residue helix spans approximately 30 Å, exactly the thickness of a lipid bilayer membrane, which is why transmembrane proteins often use α-helices to span membranes.

![](https://www.ebi.ac.uk/training/online/courses/foundations-protein-structure/wp-content/uploads/sites/311/2026/02/image-10.png)

There are 3.6 residues per turn in an alpha helix, which corresponds to 5.4 Å (1.5 Å per residue).
{: .figure-caption}

​​Not all amino acids are equally compatible with helical structure. Alanine, glutamate, leucine, methionine, arginine, and lysine are particularly well-suited for helices due to their backbone angles and side chain properties. In contrast, proline is strongly helix-breaking: its unusual structure, where the side chain bonds back to the backbone nitrogen, prevents the nitrogen from donating a hydrogen bond. When proline appears in the middle of what would otherwise be a helix, it creates a kink or break. For this reason, proline often appears at helix termini or in loops between secondary structures rather than within helices. Glycine, being the most flexible amino acid, is also disfavoured in helices because it pays an entropic cost to adopt the restricted helical conformation.

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
          <h5>Structural features of the right-handed alpha-helix.</h5>
          <p style="text-align:center; margin-left:20px; margin-right:20px;  font-size: 16px; color: #54585a; margin-block-start: 0.5em !important; margin-block-end: 2em !important;">
            The ball-and-stick model depicts a representative alpha-helix, a ubiquitous motif of protein secondary structure stabilised by a regular network of hydrogen bonds (dashed blue lines).
            These bonds occur between the carbonyl oxygen of residue <i>i</i> and the amide nitrogen of residue <i>i+4</i>, resulting in a structure with 3.6 residues per turn and a pitch of 5.4 Å.
            The polypeptide backbone is highlighted by a semi-transparent pink ribbon, while the various amino acid side chains (R-groups) are shown projecting radially outward from the central axis to minimise steric clashing.
          </p>
        </div>
      </div>
    </div>
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <script type="text/javascript">
        const state ={
  "timestamp": 1770378281982,
  "version": "5.6.0",
  "current": "iaFxI99c3JYNualVB6Ogkg",
  "playback": {
    "isPlaying": false,
    "nextSnapshotDelayInMs": 1500
  },
  "entries": [
    {
      "timestamp": 1770378281981,
      "snapshot": {
        "id": "iaFxI99c3JYNualVB6Ogkg",
        "data": {
          "tree": {
            "transforms": [
              {
                "parent": "-=root=-",
                "transformer": "build-in.root",
                "params": {},
                "ref": "-=root=-",
                "version": "qi3AKV3xy76VZss4qVGBMw"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.download",
                "params": {
                  "url": {
                    "kind": "url",
                    "id": "oIKNYXVzq22HkCoNAqxz0g",
                    "url": "https://www.ebi.ac.uk/pdbe/entry-files/download/5lbm.bcif"
                  },
                  "label": "PDBe: 5lbm (updated cif)",
                  "isBinary": true
                },
                "state": {
                  "isGhost": true
                },
                "ref": "hRO2lE7xsa-Rf0hFCPdvFw",
                "version": "-1o3mIXz06GkbTw0mzyS-A"
              },
              {
                "parent": "hRO2lE7xsa-Rf0hFCPdvFw",
                "transformer": "ms-plugin.parse-cif",
                "params": {},
                "state": {
                  "isGhost": true
                },
                "ref": "fECsPzZaZja9PXZlpkFMqg",
                "version": "IAEOqdjT9K5ZyHb72KbdxA"
              },
              {
                "parent": "fECsPzZaZja9PXZlpkFMqg",
                "transformer": "ms-plugin.trajectory-from-mmcif",
                "params": {
                  "loadAllBlocks": false,
                  "blockHeader": "5LBM",
                  "blockIndex": 0
                },
                "ref": "XL45m5OB42dp_PdApYVc6g",
                "version": "-_Mb8ptlNGZEQ46Fcf6IKw"
              },
              {
                "parent": "XL45m5OB42dp_PdApYVc6g",
                "transformer": "ms-plugin.model-from-trajectory",
                "params": {
                  "modelIndex": 0
                },
                "ref": "eokPBQ6dvE4O7VtWG5VoAQ",
                "version": "YzunQ0LUJupgxiaRGEQtNg"
              },
              {
                "parent": "eokPBQ6dvE4O7VtWG5VoAQ",
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
                "ref": "mV01fDecNHnA9upDg4PV7Q",
                "version": "JFSo2SCXR-af8jArXPOFXw"
              },
              {
                "parent": "mV01fDecNHnA9upDg4PV7Q",
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
                "ref": "f1HvgLiVZLy6K8dYLnzsmg",
                "version": "CveuTAW87gjgppLRvGwaNg"
              },
              {
                "parent": "f1HvgLiVZLy6K8dYLnzsmg",
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
                "ref": "-SrtwA6nMDGpQ6zgo3-ZyQ",
                "version": "2P6bHe3zg1ug5nsHYr8z1g"
              },
              {
                "parent": "-SrtwA6nMDGpQ6zgo3-ZyQ",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "bundle",
                    "params": {
                      "hash": 12784414,
                      "elements": [
                        {
                          "groupedUnits": [
                            [
                              3
                            ]
                          ],
                          "set": [],
                          "ranges": [
                            270,
                            389
                          ]
                        }
                      ]
                    }
                  },
                  "nullIfEmpty": true,
                  "label": "Polymer"
                },
                "tags": [
                  "structure-component-static-polymer"
                ],
                "ref": "nc7Fgc3eF_lUeGPrvau9oQ",
                "version": "FTqUy8eq4k4DNaRd_bIQWw"
              },
              {
                "parent": "nc7Fgc3eF_lUeGPrvau9oQ",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "cartoon",
                    "params": {
                      "alpha": 0.44,
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
                      "ignoreLight": false,
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
                    "name": "uniform",
                    "params": {
                      "value": 1
                    }
                  }
                },
                "tags": [
                  "polymer"
                ],
                "ref": "m0Xs-Hlaa4GFe_O4IYOHbA",
                "version": "wIR1zDF3OZiJrPKa9IfHaA"
              },
              {
                "parent": "nc7Fgc3eF_lUeGPrvau9oQ",
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
                "ref": "yrUFbh4KMFGtaiHHEEUj7w",
                "version": "QnB3pDSKkRmLragwK87FdQ"
              },
              {
                "parent": "nc7Fgc3eF_lUeGPrvau9oQ",
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
                "ref": "B7IBc3Xq7zZwBgu_o8kDwA",
                "version": "vEz5z4dP-FDOxtwZ90RnJA"
              },
              {
                "parent": "-SrtwA6nMDGpQ6zgo3-ZyQ",
                "transformer": "ms-plugin.structure-selection-from-bundle",
                "params": {
                  "bundle": {
                    "hash": -1,
                    "elements": []
                  },
                  "label": "[Focus] Target"
                },
                "tags": [
                  "structure-focus-target-sel"
                ],
                "ref": "ZVmUfeIRG3iQVK8QXzhTmg",
                "version": "9dUjp31Xqpm32JfsiGDJhg"
              },
              {
                "parent": "ZVmUfeIRG3iQVK8QXzhTmg",
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
                      "ignoreLight": false,
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
                "ref": "bJ-avV87AfzFbtnTqp9pRw",
                "version": "ZywhJHqZyf0FkFMc2-Jwgw"
              },
              {
                "parent": "-SrtwA6nMDGpQ6zgo3-ZyQ",
                "transformer": "ms-plugin.structure-selection-from-expression",
                "params": {
                  "expression": {
                    "head": {
                      "name": "structure-query.generator.empty"
                    }
                  },
                  "label": "[Focus] Surroundings (5 Å)"
                },
                "tags": [
                  "structure-focus-surr-sel"
                ],
                "ref": "iOfE4yisRUG9MHZBHaF2pA",
                "version": "FJ_Ldr2JP4D19KrQ3Vr1cQ"
              },
              {
                "parent": "iOfE4yisRUG9MHZBHaF2pA",
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
                "ref": "9RNe8MzzlQxdtLpiTzFEcg",
                "version": "NjZ-MLqx_U4ZuIAUNg1Xew"
              },
              {
                "parent": "iOfE4yisRUG9MHZBHaF2pA",
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
                "ref": "1YDCDdIRvF1y0ppHD65ylw",
                "version": "wE7-a-Hk50Jc-Bxt2rWWTw"
              },
              {
                "parent": "mV01fDecNHnA9upDg4PV7Q",
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
                "ref": "BqdXT02T3CYm6s-2SpeL0Q",
                "version": "wF9XhHx233xPh8Qvgkbr9A"
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
                "ref": "cimhwu-StBBoMjuvstO76g",
                "version": "pnFL50suv8lVhFxBXGY9eQ"
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
              23.584706789494795,
              -55.196943716430496,
              6.987169390291923
            ],
            "up": [
              0.9170295235661525,
              0.39843117969901065,
              0.017591132756366194
            ],
            "target": [
              7.598641499934949,
              -18.53756781476673,
              10.025941787333846
            ],
            "radius": 17.84754582554949,
            "radiusMax": 80.93853467333616,
            "fog": 15,
            "clipFar": true,
            "minNear": 1,
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
                "intensity": 15
              }
            },
            "cameraClipping": {
              "far": true,
              "radius": 78,
              "minNear": 1
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
                  "threshold": 1,
                  "color": 0,
                  "includeTransparent": false
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
              "maxDistance": 178.47545825549489,
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
        "structureFocus": {},
        "structureComponentManager": {
          "options": {
            "hydrogens": "all",
            "visualQuality": "auto",
            "ignoreLight": false,
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

Alpha helices can be right-handed (clockwise spiral staircase) or left-handed (counterclockwise), but because all amino acids except glycine in proteins have the L-configuration, steric constraints favour the right-handed helix ([L. Pauling,R.B. Corey, & H.R. Branson, 1951](https://doi.org/10.1073/pnas.37.4.205)).

![](https://www.ebi.ac.uk/training/online/courses/foundations-protein-structure/wp-content/uploads/sites/311/2026/02/image-11.png)

For a right-handed helix (right), the ribbon curls in the direction of the right hand’s fingers when the thumb points along the axis of growth; conversely, a left-handed helix (left) follows the curl of the left hand. While both are geometrically possible, the right-handed alpha-helix is the standard conformation in functional proteins due to the reduced steric interference between side chains and the peptide backbone.
{: .figure-caption}