---
layout: default
title: 'Protein-ligand interactions'
---

# Protein-ligand interactions

## **Active sites**

Enzyme active sites are typically pockets or clefts where substrates bind and chemical reactions occur. These sites are not mere passive binding cavities but highly evolved microenvironments optimized for catalysis. Deep burial within the protein interior allows active sites to exclude water when necessary, create unusual electrostatic environments, and precisely position catalytic groups. The active site brings together amino acid side chains that may be distant in the primary sequence but converge in three-dimensional space to form the catalytic apparatus.

## **Catalytic motifs**

Specific catalytic arrangements are highly effective and widely reused in natural enzymes. For example, canonical catalytic triads are composed of an acid (e.g., Asp or Glu), a base (e.g., His), and a nucleophile (e.g., Ser, Cys, or Thr), which coordinate to facilitate hydrolysis and transfer reactions.

Amino acid side chains are typically poor nucleophiles on their own and require activation through precise geometric arrangement within the triad. For instance, the acidic residue forms a hydrogen bond with the base, polarising it, which then abstracts a proton and activates the nucleophile. This catalytic motif often combines with additional structural features, such as a well-defined oxyanion hole, to stabilise catalytic intermediates and lower the activation energy of the reaction.

### **Substrate specificity and active site geometry**

The geometry of the active site determines not only the catalytic mechanism but also the enzyme’s substrate specificity. The substrate must be positioned precisely to facilitate catalysis.

An elegant demonstration of this principle comes from **inert mutants**, enzymes engineered by substituting a catalytic residue. The synthetic mutant loses catalytic ability but retains specificity for binding the target substrate. This strategy is commonly used to study the binding mode of an enzyme and its substrate without the complication of turnover.

Many enzymes undergo substantial conformational changes upon substrate binding. For example, phosphoglycerate kinase undergoes a dramatic domain closure that brings catalytic residues into proper alignment only after substrate binds, ensuring that catalysis occurs only when substrate is present.

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
          margin-top: 0px; /* Adjust margin as needed */
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
        <h5>Structure of HIV-1 protease in complex with a non-peptide inhibitor</h5>
        <p style="text-align: center; margin-top: 0px; margin-left:20px; margin-right:20px; font-size: 16px; color: #000000; margin-block-end: 1.5em !important;">(PDB: <a href="https://www.ebi.ac.uk/pdbe/entry/pdb/1aid" target="_blank" rel="noreferrer noopener">1AID</a>)<br></p>
      </div>
      </div>
  <!-- Repeat the structure for the other instances -->
  <div class="item">
    <div id="app2" class="app"></div>
    <div id="text">
        <h5>Structure of HIV-1 protease in complex with an inhibitor</h5>
        <!-- Add text for the second instance -->
        <p style="text-align: center; margin-top: 0px; margin-left:20px; margin-right:20px; font-size: 16px; color: #000000; margin-block-end: 1.5em !important;">(PDB: <a href="https://www.ebi.ac.uk/pdbe/entry/pdb/1hsg" target="_blank" rel="noreferrer noopener">1HSG</a>)</p>
    </div>
</div>
</div>
<div class="container">
  <div class="item">
    <div id="app3" class="app"></div>
    <div id="text">
      <h5>Structure of HIV-1 protease in complex with an analog of CA-p2 substrate</h5>
      <p style="text-align: center; margin-top: 0px; margin-left:20px; margin-right:20px; font-size: 16px; color: #000000; margin-block-end: 1.5em !important;">(PDB: <a href="https://www.ebi.ac.uk/pdbe/entry/pdb/1a8k" target="_blank" rel="noreferrer noopener">1A8K</a>)</p>
    </div>
    </div>
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <script type="text/javascript">
        const  state1= {
  "timestamp": 1772108261214,
  "version": "5.6.0",
  "current": "aseflUt6B2VMwmdzMA71qg",
  "playback": {
    "isPlaying": false,
    "nextSnapshotDelayInMs": 1500
  },
  "entries": [
    {
      "timestamp": 1772108261213,
      "snapshot": {
        "id": "aseflUt6B2VMwmdzMA71qg",
        "data": {
          "tree": {
            "transforms": [
              {
                "parent": "-=root=-",
                "transformer": "build-in.root",
                "params": {},
                "ref": "-=root=-",
                "version": "Lu1_X5wPcDeG-9Xof4peeQ"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.download",
                "params": {
                  "url": {
                    "kind": "url",
                    "id": "2Vjt71fkuJpr69gQJlvTzQ",
                    "url": "https://www.ebi.ac.uk/pdbe/entry-files/download/1aid.bcif"
                  },
                  "label": "PDBe: 1aid (updated cif)",
                  "isBinary": true
                },
                "state": {
                  "isGhost": true
                },
                "ref": "4NrGloJ3AFy75IJndycKdA",
                "version": "ssSImN7kqQDSjq7jdnHuAQ"
              },
              {
                "parent": "4NrGloJ3AFy75IJndycKdA",
                "transformer": "ms-plugin.parse-cif",
                "params": {},
                "state": {
                  "isGhost": true
                },
                "ref": "pESUjLJ5-EehlrYenh2B-w",
                "version": "UI2nploTxlUbiW2JInj8zQ"
              },
              {
                "parent": "pESUjLJ5-EehlrYenh2B-w",
                "transformer": "ms-plugin.trajectory-from-mmcif",
                "params": {},
                "ref": "8lfh6An4uFQAPyWY2hcXSg",
                "version": "HcVMmOR-FzRXM-LtS1zD2w"
              },
              {
                "parent": "8lfh6An4uFQAPyWY2hcXSg",
                "transformer": "ms-plugin.model-from-trajectory",
                "params": {
                  "modelIndex": 0
                },
                "ref": "VMuTS360NZLvHGJhOE2UhQ",
                "version": "5JDQ1T4RbDGUvF27bIkNEQ"
              },
              {
                "parent": "VMuTS360NZLvHGJhOE2UhQ",
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
                "ref": "yrMyrqlAbhx3SWJwmHePcQ",
                "version": "jc8knKNHCSfY7-IXyKkgcw"
              },
              {
                "parent": "yrMyrqlAbhx3SWJwmHePcQ",
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
                "ref": "CQVTfk1Tv48zF9JZOMUX0w",
                "version": "PinhqVEFnk67vYed3d_-ug"
              },
              {
                "parent": "CQVTfk1Tv48zF9JZOMUX0w",
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
                "ref": "htAAEYKA3_7Cjsp2V9dWCg",
                "version": "6Ha9vTjK3YOBSYFco1VEKA"
              },
              {
                "parent": "htAAEYKA3_7Cjsp2V9dWCg",
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
                "ref": "BlnYitz5XTi0mWteXQI0ZA",
                "version": "jorkEU-_0bgc2FlU2M3fTg"
              },
              {
                "parent": "BlnYitz5XTi0mWteXQI0ZA",
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
                "ref": "IkITs1shAzQgb3xt8H707Q",
                "version": "DREGTs3GjG070pTX6MPNCA"
              },
              {
                "parent": "IkITs1shAzQgb3xt8H707Q",
                "transformer": "ms-plugin.overpaint-structure-representation-3d-from-bundle",
                "params": {
                  "layers": [
                    {
                      "bundle": {
                        "hash": 839640378,
                        "elements": [
                          {
                            "groupedUnits": [
                              [
                                0
                              ]
                            ],
                            "set": [],
                            "ranges": [
                              0,
                              757
                            ]
                          }
                        ]
                      },
                      "color": 8921685,
                      "clear": false
                    },
                    {
                      "bundle": {
                        "hash": 839640378,
                        "elements": [
                          {
                            "groupedUnits": [
                              [
                                1
                              ]
                            ],
                            "set": [],
                            "ranges": [
                              0,
                              757
                            ]
                          }
                        ]
                      },
                      "color": 14535799,
                      "clear": false
                    }
                  ]
                },
                "tags": [
                  "overpaint-controls"
                ],
                "ref": "CSTfRyNLQ71Z0Abynx1SQg",
                "version": "hcvNWrGdZAYNZUzhhtHEyA"
              },
              {
                "parent": "htAAEYKA3_7Cjsp2V9dWCg",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "static",
                    "params": "ligand"
                  },
                  "nullIfEmpty": true,
                  "label": ""
                },
                "tags": [
                  "structure-component-static-ligand"
                ],
                "ref": "8vAQjDdyfHE0Dyx72gSrvA",
                "version": "sLAGBalJxkz2GzubhVdSYg"
              },
              {
                "parent": "8vAQjDdyfHE0Dyx72gSrvA",
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
                  "ligand"
                ],
                "ref": "0u47Cwpkt0FVEwt1Z2fpSQ",
                "version": "V6dZjfXjaXH6r8H5diO4BA"
              },
              {
                "parent": "0u47Cwpkt0FVEwt1Z2fpSQ",
                "transformer": "ms-plugin.overpaint-structure-representation-3d-from-bundle",
                "params": {
                  "layers": []
                },
                "tags": [
                  "overpaint-controls"
                ],
                "ref": "3kBZLpjNZuRPAcmnYUnCGw",
                "version": "eXOhWBqbGFWc8a3E_RYquA"
              },
              {
                "parent": "htAAEYKA3_7Cjsp2V9dWCg",
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
                "ref": "GS_m-xtmImWhL7YwbzAxYg",
                "version": "uUPPT1ZCuUXm1Oj3Pe7J_A"
              },
              {
                "parent": "GS_m-xtmImWhL7YwbzAxYg",
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
                "ref": "A9usM-U42tL8ggwgVFGE8g",
                "version": "A4Wc361DDKJExZD5-BofxA"
              },
              {
                "parent": "A9usM-U42tL8ggwgVFGE8g",
                "transformer": "ms-plugin.overpaint-structure-representation-3d-from-bundle",
                "params": {
                  "layers": []
                },
                "tags": [
                  "overpaint-controls"
                ],
                "ref": "sBHitJxd54d9FkenBCnDlQ",
                "version": "xmDkRT52nLlMOn2SlX91TQ"
              },
              {
                "parent": "htAAEYKA3_7Cjsp2V9dWCg",
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
                "ref": "9-O2TXOPpAP9C-KnXHanIg",
                "version": "E7JvLcvvlsVM8I6P3fdMMw"
              },
              {
                "parent": "9-O2TXOPpAP9C-KnXHanIg",
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
                "ref": "2oKAhsYU_JbyBPQqWlDksw",
                "version": "IKs_0bm-NA9d1njY1DkJbg"
              },
              {
                "parent": "2oKAhsYU_JbyBPQqWlDksw",
                "transformer": "ms-plugin.overpaint-structure-representation-3d-from-bundle",
                "params": {
                  "layers": []
                },
                "tags": [
                  "overpaint-controls"
                ],
                "ref": "fui0RcLEBeZPTE3wYpAafQ",
                "version": "OinqPVae3wKyVkJawqP-8g"
              },
              {
                "parent": "yrMyrqlAbhx3SWJwmHePcQ",
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
                "ref": "Bp0IC8B1DhADQV1vAZ_nNQ",
                "version": "Biyqwpo_s-gRbukT0oquoQ"
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
                "ref": "TgrhrpUCVFjbsH9CN0XfIA",
                "version": "lWEzBdLYQoZ_QhYhWJVPwA"
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
              1.6431646241286586,
              113.10211839846696,
              -19.00135499097299
            ],
            "up": [
              -0.7103844135202373,
              -0.7017893875253142,
              -0.0533445459660416
            ],
            "target": [
              68.89144897419199,
              43.526364585367304,
              0.7830971537198075
            ],
            "radius": 32.08286336976754,
            "radiusMax": 72.91559856765349,
            "fog": 53,
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
                "intensity": 53
              }
            },
            "cameraClipping": {
              "far": true,
              "radius": 56,
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
                "name": "on",
                "params": {
                  "steps": 1,
                  "maxDistance": 3,
                  "tolerance": 1
                }
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
              "maxDistance": 320.0331014499145,
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
            "granularity": "chain"
          }
        },
        "structureFocus": {},
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
            viewportShowTrajectoryControls:false,
        }).then(viewer => {
            var data64 = btoa(JSON.stringify(state1));
            viewer.loadSnapshotFromUrl(`data:text/plain;base64,${data64}`, 'molj');
        });
    </script>
<!-- SECOND STRUCTURE --->
<script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <script type="text/javascript">
        const state2 = {
  "timestamp": 1772112888087,
  "version": "5.6.0",
  "current": "LWjDAWwS44Dp8CdAi1c8cQ",
  "playback": {
    "isPlaying": false,
    "nextSnapshotDelayInMs": 1500
  },
  "entries": [
    {
      "timestamp": 1772112888086,
      "snapshot": {
        "id": "LWjDAWwS44Dp8CdAi1c8cQ",
        "data": {
          "tree": {
            "transforms": [
              {
                "parent": "-=root=-",
                "transformer": "build-in.root",
                "params": {},
                "ref": "-=root=-",
                "version": "Lu1_X5wPcDeG-9Xof4peeQ"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.download",
                "params": {
                  "url": {
                    "kind": "url",
                    "id": "bAXpa4CZGhTHpuSqGCUgWg",
                    "url": "https://www.ebi.ac.uk/pdbe/entry-files/download/1hsg.bcif"
                  },
                  "label": "PDBe: 1hsg (updated cif)",
                  "isBinary": true
                },
                "state": {
                  "isGhost": true
                },
                "ref": "esnD972qfJTH5u1TTfBHXA",
                "version": "JFiYihHIH0RVM1y_2eDuvQ"
              },
              {
                "parent": "esnD972qfJTH5u1TTfBHXA",
                "transformer": "ms-plugin.parse-cif",
                "params": {},
                "state": {
                  "isGhost": true
                },
                "ref": "ON4J55F_48mTkFWFD5QW-g",
                "version": "ZEtGfMCtGlYko7wncWtwqw"
              },
              {
                "parent": "ON4J55F_48mTkFWFD5QW-g",
                "transformer": "ms-plugin.trajectory-from-mmcif",
                "params": {},
                "ref": "RtJKhPWHC5kwcxKLl06IEA",
                "version": "csjMDGHu3J025tnnPR9Xug"
              },
              {
                "parent": "RtJKhPWHC5kwcxKLl06IEA",
                "transformer": "ms-plugin.model-from-trajectory",
                "params": {
                  "modelIndex": 0
                },
                "ref": "i1nj9rKqF1RflEDatmTj1g",
                "version": "yYa4KoJLS_0BugPR2vO8Lg"
              },
              {
                "parent": "i1nj9rKqF1RflEDatmTj1g",
                "transformer": "ms-plugin.custom-model-properties",
                "params": {
                  "autoAttach": [
                    "sifts_sequence_mapping"
                  ],
                  "properties": {
                    "asym_id_offset": {
                      "value": {
                        "auth": 2,
                        "label": 6
                      }
                    },
                    "index": {
                      "value": 1
                    },
                    "max_index": {
                      "value": 1
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
                "ref": "urpU7hQRPzNM-kX34O4jvg",
                "version": "gL3PFq-SAtDLNCq2LfohcA"
              },
              {
                "parent": "urpU7hQRPzNM-kX34O4jvg",
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
                "ref": "g3KQnlVZx6kp4DJQPt4-dg",
                "version": "SR0RKgvfc0iBy_P8oBxITA"
              },
              {
                "parent": "g3KQnlVZx6kp4DJQPt4-dg",
                "transformer": "ms-plugin.transform-structure-conformation",
                "params": {
                  "transform": {
                    "name": "matrix",
                    "params": {
                      "data": [
                        -0.1832175210776672,
                        0.9820017383901565,
                        -0.045872530074504425,
                        0,
                        0.8390918388902513,
                        0.13190047913903236,
                        -0.5277569668098536,
                        0,
                        -0.5122075644936359,
                        -0.13518548704380606,
                        -0.8481561544611225,
                        0,
                        51.97290275091289,
                        25.08609768681354,
                        18.328631349853396,
                        1
                      ],
                      "transpose": false
                    }
                  }
                },
                "tags": [
                  "SuperpositionTransform"
                ],
                "ref": "cADsTEXlWk1UsY503iYprg",
                "version": "4ppxuJ5EgmYhxeCBLzA7vw"
              },
              {
                "parent": "cADsTEXlWk1UsY503iYprg",
                "transformer": "ms-plugin.custom-structure-properties",
                "params": {
                  "autoAttach": [],
                  "properties": {
                    "index": {
                      "value": 1
                    },
                    "max_index": {
                      "value": 1
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
                "ref": "8SvUPXBNmxnIK968DZ7s0Q",
                "version": "EQCIHBjoLZjCjWCeavv-iQ"
              },
              {
                "parent": "8SvUPXBNmxnIK968DZ7s0Q",
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
                "ref": "07obKkF8lZqglo8hYDGSOg",
                "version": "v-jLhq77X4XiOiOXDykiqA"
              },
              {
                "parent": "07obKkF8lZqglo8hYDGSOg",
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
                "ref": "93_R7LMEoTT8s9aEM7Feeg",
                "version": "T5ZLzywQhE8DjKYvL5mshQ"
              },
              {
                "parent": "93_R7LMEoTT8s9aEM7Feeg",
                "transformer": "ms-plugin.overpaint-structure-representation-3d-from-bundle",
                "params": {
                  "layers": [
                    {
                      "bundle": {
                        "hash": 702140133,
                        "elements": [
                          {
                            "groupedUnits": [
                              [
                                1
                              ]
                            ],
                            "set": [],
                            "ranges": [
                              0,
                              756
                            ]
                          }
                        ]
                      },
                      "color": 14535799,
                      "clear": false
                    },
                    {
                      "bundle": {
                        "hash": 702140133,
                        "elements": [
                          {
                            "groupedUnits": [
                              [
                                0
                              ]
                            ],
                            "set": [],
                            "ranges": [
                              0,
                              756
                            ]
                          }
                        ]
                      },
                      "color": 8921685,
                      "clear": false
                    }
                  ]
                },
                "tags": [
                  "overpaint-controls"
                ],
                "ref": "cuQ8MpNGbRFy2bDp-4LOIA",
                "version": "DNJxsBEbRpwMN3rs0q2nRA"
              },
              {
                "parent": "8SvUPXBNmxnIK968DZ7s0Q",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "static",
                    "params": "ligand"
                  },
                  "nullIfEmpty": true,
                  "label": ""
                },
                "tags": [
                  "structure-component-static-ligand"
                ],
                "ref": "kaiyAnayMdw1-uwvPQbwRA",
                "version": "AFwTOhGITBLIHrA4wo8PeA"
              },
              {
                "parent": "kaiyAnayMdw1-uwvPQbwRA",
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
                  "ligand"
                ],
                "ref": "CWHptiRttY3Efl40QIE-kg",
                "version": "5_G77BgnV5FY7I7qCquP0w"
              },
              {
                "parent": "CWHptiRttY3Efl40QIE-kg",
                "transformer": "ms-plugin.overpaint-structure-representation-3d-from-bundle",
                "params": {
                  "layers": []
                },
                "tags": [
                  "overpaint-controls"
                ],
                "ref": "VkzoOmom35DFqyj18CtUdw",
                "version": "lmZnzkDEBeI-yLkP7nLfZA"
              },
              {
                "parent": "8SvUPXBNmxnIK968DZ7s0Q",
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
                "ref": "bBOGAbOdft0ovtLz4nsa1g",
                "version": "D5knz8sgajI0hXFH-9wOjA"
              },
              {
                "parent": "bBOGAbOdft0ovtLz4nsa1g",
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
                "ref": "oqDmbyluHkxi3X5AQylCFw",
                "version": "EP5f842ktApvCeUaeTQ3eQ"
              },
              {
                "parent": "oqDmbyluHkxi3X5AQylCFw",
                "transformer": "ms-plugin.overpaint-structure-representation-3d-from-bundle",
                "params": {
                  "layers": []
                },
                "state": {
                  "isHidden": true
                },
                "tags": [
                  "overpaint-controls"
                ],
                "ref": "38lOFZMuk1XUNetPB3MKmg",
                "version": "hQCIVeMFfRStEJ6KaxU7pg"
              },
              {
                "parent": "urpU7hQRPzNM-kX34O4jvg",
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
                "ref": "JDFMK9TWnoN8U4i5iDShKA",
                "version": "OunCuj8zvi_cMKUGoTrpgg"
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
              9.350035837738695,
              127.22702344831023,
              -19.149894198790328
            ],
            "up": [
              -0.8131784065637262,
              -0.5806904195893738,
              -0.039236662645246737
            ],
            "target": [
              67.90272751524854,
              43.829073223711376,
              1.6114584638112126
            ],
            "radius": 38.83504041655345,
            "radiusMax": 67.50166435838602,
            "fog": 53,
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
                "intensity": 53
              }
            },
            "cameraClipping": {
              "far": true,
              "radius": 42,
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
                "name": "on",
                "params": {
                  "steps": 1,
                  "maxDistance": 3,
                  "tolerance": 1
                }
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
              "maxDistance": 388.3504041655345,
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
            "granularity": "chain"
          }
        },
        "structureFocus": {},
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
        molstar.Viewer.create('app2', {
            layoutShowControls: false,
            layoutIsExpanded: false,
            viewportShowControls: false,
            viewportShowExpand: false,
            viewportShowSettings: false,
            viewportShowSelectionMode: false,
            viewportShowToggleFullscreen: false,
            viewportShowAnimation: false,
            viewportShowTrajectoryControls:false,
          }).then(viewer => {
            var data64 = btoa(JSON.stringify(state2));
            viewer.loadSnapshotFromUrl(`data:text/plain;base64,${data64}`, 'molj');
        });
    </script>
<!---THIRD STRUCTURE-->
<script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <script type="text/javascript">
        const  state3= {
  "timestamp": 1772112993927,
  "version": "5.6.0",
  "current": "Jip7YM5TxSPKlNDxS7ZG5Q",
  "playback": {
    "isPlaying": false,
    "nextSnapshotDelayInMs": 1500
  },
  "entries": [
    {
      "timestamp": 1772112993926,
      "snapshot": {
        "id": "Jip7YM5TxSPKlNDxS7ZG5Q",
        "data": {
          "tree": {
            "transforms": [
              {
                "parent": "-=root=-",
                "transformer": "build-in.root",
                "params": {},
                "ref": "-=root=-",
                "version": "Lu1_X5wPcDeG-9Xof4peeQ"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.download",
                "params": {
                  "url": {
                    "kind": "url",
                    "id": "MW1scPsvn80gojAtXAo_4g",
                    "url": "https://www.ebi.ac.uk/pdbe/entry-files/download/1a8k.bcif"
                  },
                  "label": "PDBe: 1a8k (updated cif)",
                  "isBinary": true
                },
                "state": {
                  "isGhost": true
                },
                "ref": "S4gffD6fNWFPeNECd2IUoQ",
                "version": "veTlUUpNEL2xZJKgmH2VKg"
              },
              {
                "parent": "S4gffD6fNWFPeNECd2IUoQ",
                "transformer": "ms-plugin.parse-cif",
                "params": {},
                "state": {
                  "isGhost": true
                },
                "ref": "nnn6wndzSwbM8uvfVCLQ6Q",
                "version": "Bmpqgf1KA6pw2_USOu9XMQ"
              },
              {
                "parent": "nnn6wndzSwbM8uvfVCLQ6Q",
                "transformer": "ms-plugin.trajectory-from-mmcif",
                "params": {},
                "ref": "aCt7ZqJEJS7WyV2YM7RQXA",
                "version": "UNGSE6KF92oFHC-SlVWRVg"
              },
              {
                "parent": "aCt7ZqJEJS7WyV2YM7RQXA",
                "transformer": "ms-plugin.model-from-trajectory",
                "params": {
                  "modelIndex": 0
                },
                "ref": "5qFASaxyw9mkxDhBZ5qfxA",
                "version": "gHY3lS6-wAkgRYK1pkPyeQ"
              },
              {
                "parent": "5qFASaxyw9mkxDhBZ5qfxA",
                "transformer": "ms-plugin.custom-model-properties",
                "params": {
                  "autoAttach": [
                    "sifts_sequence_mapping"
                  ],
                  "properties": {
                    "asym_id_offset": {
                      "value": {
                        "auth": 4,
                        "label": 11
                      }
                    },
                    "index": {
                      "value": 2
                    },
                    "max_index": {
                      "value": 2
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
                "ref": "8xlthqweJ_F4qX7ldPX3kw",
                "version": "G1lGS9DGfT6dajV6W4r4Qw"
              },
              {
                "parent": "8xlthqweJ_F4qX7ldPX3kw",
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
                "ref": "V9lPks6Fg4dtYhQivkq61w",
                "version": "f9LOawNyCUFdj4b07cwPEA"
              },
              {
                "parent": "V9lPks6Fg4dtYhQivkq61w",
                "transformer": "ms-plugin.transform-structure-conformation",
                "params": {
                  "transform": {
                    "name": "matrix",
                    "params": {
                      "data": [
                        0.9884862968475272,
                        -0.13586888796019211,
                        -0.06659485975921325,
                        0,
                        0.0673418936673269,
                        0.0009037470656444863,
                        0.99772981669275,
                        0,
                        -0.135499971408326,
                        -0.9907265341103282,
                        0.010042881987288393,
                        0,
                        11.598661658665009,
                        80.13020893204376,
                        -14.020646388235953,
                        1
                      ],
                      "transpose": false
                    }
                  }
                },
                "tags": [
                  "SuperpositionTransform"
                ],
                "ref": "lf1lPoycL07yjLmPIPcxxA",
                "version": "IVTE6eOrRLLI96NjkxMhLQ"
              },
              {
                "parent": "lf1lPoycL07yjLmPIPcxxA",
                "transformer": "ms-plugin.custom-structure-properties",
                "params": {
                  "autoAttach": [],
                  "properties": {
                    "index": {
                      "value": 2
                    },
                    "max_index": {
                      "value": 2
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
                "ref": "bRhCAEPafXN5aIX0HU7JcQ",
                "version": "ynRouajOoH6tgfTK6FJj4w"
              },
              {
                "parent": "bRhCAEPafXN5aIX0HU7JcQ",
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
                "ref": "-YmfG298dihUbJ585xw80g",
                "version": "PuMNlzsZOxSk7FoxBhl4oA"
              },
              {
                "parent": "-YmfG298dihUbJ585xw80g",
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
                "ref": "sIRnkxvbEQksSOmRrMkpIw",
                "version": "g0fL0XogaJqMKeZoGX25PQ"
              },
              {
                "parent": "sIRnkxvbEQksSOmRrMkpIw",
                "transformer": "ms-plugin.overpaint-structure-representation-3d-from-bundle",
                "params": {
                  "layers": [
                    {
                      "bundle": {
                        "hash": 1117989593,
                        "elements": [
                          {
                            "groupedUnits": [
                              [
                                0
                              ]
                            ],
                            "set": [],
                            "ranges": [
                              0,
                              921
                            ]
                          }
                        ]
                      },
                      "color": 8921685,
                      "clear": false
                    },
                    {
                      "bundle": {
                        "hash": 1117989593,
                        "elements": [
                          {
                            "groupedUnits": [
                              [
                                1
                              ]
                            ],
                            "set": [],
                            "ranges": [
                              0,
                              921
                            ]
                          }
                        ]
                      },
                      "color": 14535799,
                      "clear": false
                    }
                  ]
                },
                "tags": [
                  "overpaint-controls"
                ],
                "ref": "d0jciSTvBjEVTenMu0a-5g",
                "version": "e4ltaWnQgz75SvAL4bI8Eg"
              },
              {
                "parent": "bRhCAEPafXN5aIX0HU7JcQ",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "static",
                    "params": "ligand"
                  },
                  "nullIfEmpty": true,
                  "label": ""
                },
                "tags": [
                  "structure-component-static-ligand"
                ],
                "ref": "UC67nUWk9Kl-WvZZpMrQMg",
                "version": "9GaMK62nszWv3YzssSueKQ"
              },
              {
                "parent": "UC67nUWk9Kl-WvZZpMrQMg",
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
                  "ligand"
                ],
                "ref": "Bobe4bSHNrgeKxRYuXU7XA",
                "version": "cRZiU8N7j35UzGm7uQ8neQ"
              },
              {
                "parent": "Bobe4bSHNrgeKxRYuXU7XA",
                "transformer": "ms-plugin.overpaint-structure-representation-3d-from-bundle",
                "params": {
                  "layers": []
                },
                "tags": [
                  "overpaint-controls"
                ],
                "ref": "b0wExigDT3AxNwfTc3tfyA",
                "version": "jq8TlCh0JiHvqVYhHPZ19Q"
              },
              {
                "parent": "bRhCAEPafXN5aIX0HU7JcQ",
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
                "ref": "92HAPRT8ENAvbtqMVoUvBA",
                "version": "FO3vwC9hWIo34KWUU3KYzQ"
              },
              {
                "parent": "92HAPRT8ENAvbtqMVoUvBA",
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
                "ref": "55IHfDUGHSpWxqBVoGnQGg",
                "version": "vLgBBnCdtr7s3VU0D3m7LA"
              },
              {
                "parent": "55IHfDUGHSpWxqBVoGnQGg",
                "transformer": "ms-plugin.overpaint-structure-representation-3d-from-bundle",
                "params": {
                  "layers": []
                },
                "tags": [
                  "overpaint-controls"
                ],
                "ref": "IR7Kq0XgByfzDXCqRRrGjw",
                "version": "TRyEVarIHoPJYJ1EJar4lw"
              },
              {
                "parent": "8xlthqweJ_F4qX7ldPX3kw",
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
                "ref": "TjAzx-0YDN3F-qv6tCft3A",
                "version": "xGDE0_Tpx7typl30Rs7HJQ"
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
                "ref": "iuTiW0Zf6HjL1AuCezvXGg",
                "version": "S0Qmv-Bbu53deb1gPZ-LPA"
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
              3.0793337438634865,
              126.94420064875591,
              -9.988351768964485
            ],
            "up": [
              -0.7926401111081472,
              -0.6096177771301794,
              -0.009371236270379732
            ],
            "target": [
              67.69752134048866,
              42.76446854806356,
              0.5218694654405924
            ],
            "radius": 33.515063026182986,
            "radiusMax": 65.93060342826445,
            "fog": 53,
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
                "intensity": 53
              }
            },
            "cameraClipping": {
              "far": true,
              "radius": 49,
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
                "name": "on",
                "params": {
                  "steps": 1,
                  "maxDistance": 3,
                  "tolerance": 1
                }
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
              "maxDistance": 335.15063026182986,
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
            "granularity": "chain"
          }
        },
        "structureFocus": {},
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
        molstar.Viewer.create('app3', {
            layoutShowControls: false,
            layoutIsExpanded: false,
            viewportShowControls: false,
            viewportShowExpand: false,
            viewportShowSettings: false,
            viewportShowSelectionMode: false,
            viewportShowToggleFullscreen: false,
            viewportShowAnimation: false,
            viewportShowTrajectoryControls:false,
        }).then(viewer => {
            var data64 = btoa(JSON.stringify(state3));
            viewer.loadSnapshotFromUrl(`data:text/plain;base64,${data64}`, 'molj');
        });
    </script>
</div>