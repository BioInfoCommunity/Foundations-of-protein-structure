---
layout: default
title: 'Protein dynamics and flexibility'
---

# Protein dynamics and flexibility

Static structures, while invaluable, present a fundamentally incomplete picture of proteins. Proteins are not rigid statues but dynamic entities in constant motion. This motion spans multiple timescales and is not random noise but rather functionally important, enabling proteins to sample different conformations, bind partners, and catalyze reactions.

## **Protein motion**

Protein flexibility is a natural consequence of the weak forces that hold tertiary structure together. Because the energies of these interactions are comparable to the kinetic energy available at physiological temperatures, proteins are inherently dynamic on multiple timescales.

On very short timescales (picoseconds to nanoseconds), side chains and even backbone atoms undergo rapid fluctuations, small wiggles and oscillations around their average positions.

On longer timescales (microseconds to seconds), many proteins undergo concerted, large-scale rearrangements, often involving entire domains moving relative to one another. These transitions between stable (or semi-stable) conformational states must cross higher energy barriers and therefore occur more slowly. This larger-scale flexibility underlies most biological “switches” and molecular motors and is typically triggered by the binding of another molecule.

## **Functional consequences of flexibility**

Perhaps the most common ligand-induced change is the “lid-like” movement of a loop to cover a binding site. Many enzymes have an active site cleft with a flexible loop poised above it. When the lid is open, substrate can enter. Once a substrate is bound, the loop closes over it, a rigid-body rotation on two flexible hinges. This closure serves multiple functions:

* Prevents premature product release
* Isolates the chemical reaction from the surrounding water (crucial for many catalytic mechanisms)
* Stabilises the bound substrate through additional contacts

These mobile loops act as functional gates, controlling access to active sites and coordinating the catalytic cycle.

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
          <h5>Conformational flexibility in Adenylate Kinase (PDB ID: <a href="https://www.ebi.ac.uk/pdbe/entry/pdb/1ank" target="_blank" rel="noreferrer noopener">1ANK</a> and <a href="https://www.ebi.ac.uk/pdbe/entry/pdb/2ak3" target="_blank" rel="noreferrer noopener">2AK3</a>).</h5>
          <p>This superposition illustrates the dynamic nature of protein structures, transitioning from an &#8220;open&#8221; apo-state (light purple, PDB: 2AK3) to a &#8220;closed&#8221; ligand-bound state (grey, PDB: 1ANK).
            The transition demonstrates a large-scale, concerted rearrangement where flexible &#8220;hinge&#8221; regions allow entire domains to rotate, effectively creating a &#8220;lid-like&#8221; movement that covers the active site cleft.</p>
        </div>
      </div>
    </div>
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <script type="text/javascript">
        const state2 ={
  "timestamp": 1770306421966,
  "version": "5.6.0",
  "current": "dJ40OSXIIWUC-bjwWcJwpA",
  "playback": {
    "isPlaying": false,
    "nextSnapshotDelayInMs": 1500
  },
  "entries": [
    {
      "timestamp": 1770306421963,
      "snapshot": {
        "id": "dJ40OSXIIWUC-bjwWcJwpA",
        "data": {
          "tree": {
            "transforms": [
              {
                "parent": "-=root=-",
                "transformer": "build-in.root",
                "params": {},
                "ref": "-=root=-",
                "version": "zADsVk1wUP3r4LMvlNhFIA"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.download",
                "params": {
                  "url": {
                    "kind": "url",
                    "id": "4s8gfeWHcrqKZoSGSNKOGQ",
                    "url": "https://www.ebi.ac.uk/pdbe/entry-files/download/1ank.bcif"
                  },
                  "label": "PDBe: 1ank (updated cif)",
                  "isBinary": true
                },
                "state": {
                  "isGhost": true
                },
                "ref": "KhkZXH5KS3oJ_R273xH2Lw",
                "version": "jwZ2e-qY1HYapw20pu24kA"
              },
              {
                "parent": "KhkZXH5KS3oJ_R273xH2Lw",
                "transformer": "ms-plugin.parse-cif",
                "params": {},
                "state": {
                  "isGhost": true
                },
                "ref": "DtecRuaU1ma6Nocv_arjZA",
                "version": "O1aKNIj0tQ_zyGaaRruqRA"
              },
              {
                "parent": "DtecRuaU1ma6Nocv_arjZA",
                "transformer": "ms-plugin.trajectory-from-mmcif",
                "params": {},
                "ref": "GybNulos_KBh7sLNpsg1UA",
                "version": "Dw7dll1SHWYwnaohmP78kQ"
              },
              {
                "parent": "GybNulos_KBh7sLNpsg1UA",
                "transformer": "ms-plugin.model-from-trajectory",
                "params": {
                  "modelIndex": 0
                },
                "ref": "6i1ZmkI8D8_nX0DkKI1F0A",
                "version": "MAiypbMJVUFMUY0ey3ysqg"
              },
              {
                "parent": "6i1ZmkI8D8_nX0DkKI1F0A",
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
                "state": {
                  "isCollapsed": true
                },
                "ref": "GYbHtB689EnvLIg8yyG0qg",
                "version": "n19OPlUOYW0y86DNVgzQtg"
              },
              {
                "parent": "GYbHtB689EnvLIg8yyG0qg",
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
                "ref": "mfbQKN84kSNak6WUPijf-g",
                "version": "1yyJl4OTTkoid6BYrqUvvw"
              },
              {
                "parent": "mfbQKN84kSNak6WUPijf-g",
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
                "ref": "ljZ88tV4f8n23l6Zllj3bQ",
                "version": "YeAZDmHKXxfSP3ItooLRMw"
              },
              {
                "parent": "ljZ88tV4f8n23l6Zllj3bQ",
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
                "ref": "9pgDYyKsojyaIROfMz5_eQ",
                "version": "L1eACROMWwoy9QA5lgxjBw"
              },
              {
                "parent": "9pgDYyKsojyaIROfMz5_eQ",
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
                "ref": "_tedDcj2cD0x2oQlvD_bTQ",
                "version": "32wubuhq2PBeqsB0F92WHQ"
              },
              {
                "parent": "_tedDcj2cD0x2oQlvD_bTQ",
                "transformer": "ms-plugin.overpaint-structure-representation-3d-from-bundle",
                "params": {
                  "layers": [
                    {
                      "bundle": {
                        "hash": 1140261575,
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
                              2033
                            ]
                          }
                        ]
                      },
                      "color": 12700374,
                      "clear": false
                    }
                  ]
                },
                "tags": [
                  "overpaint-controls"
                ],
                "ref": "LRy9Z9LHitYIImEawxeSXg",
                "version": "iuMesNMrC9O81pHALRUm7w"
              },
              {
                "parent": "ljZ88tV4f8n23l6Zllj3bQ",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "static",
                    "params": "ligand"
                  },
                  "nullIfEmpty": true,
                  "label": ""
                },
                "state": {
                  "isHidden": true
                },
                "tags": [
                  "structure-component-static-ligand"
                ],
                "ref": "YZ4mfEOMaRX7vG7rmUXLSQ",
                "version": "gbVCXjuKOPHSI2EighWr0g"
              },
              {
                "parent": "YZ4mfEOMaRX7vG7rmUXLSQ",
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
                "state": {
                  "isHidden": true
                },
                "tags": [
                  "ligand"
                ],
                "ref": "f8cTuAcCeVsBy_hly8JzJQ",
                "version": "m6cSwBsji8LuT2zKh6e_Jw"
              },
              {
                "parent": "f8cTuAcCeVsBy_hly8JzJQ",
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
                "ref": "xRWqdniTN7Bubf6HxazEGQ",
                "version": "ThT20ptCf4HCTW2Hxmn00g"
              },
              {
                "parent": "ljZ88tV4f8n23l6Zllj3bQ",
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
                "ref": "6aJ-0VI_mLfA-57CFH6fcw",
                "version": "9kWlrzPouQbUkbgZftx5pw"
              },
              {
                "parent": "6aJ-0VI_mLfA-57CFH6fcw",
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
                "ref": "6nWz0pZ2nIiGDnEvl4Pa_Q",
                "version": "LAFIdTsxL6ZLiganjD98GA"
              },
              {
                "parent": "6nWz0pZ2nIiGDnEvl4Pa_Q",
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
                "ref": "u1-EZhV_zddr_KUvSMKfOA",
                "version": "Y0bFdy1y20rEh0L7zKUgug"
              },
              {
                "parent": "GYbHtB689EnvLIg8yyG0qg",
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
                "ref": "mk_YDrcLRoT7mQqioFaBeQ",
                "version": "8E8pLipFMjsPHdINJFe58Q"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.download",
                "params": {
                  "url": {
                    "kind": "url",
                    "id": "MIeaFMUA8pmSzGZ6s1C45Q",
                    "url": "https://www.ebi.ac.uk/pdbe/entry-files/download/2ak3.bcif"
                  },
                  "label": "PDBe: 2ak3 (updated cif)",
                  "isBinary": true
                },
                "state": {
                  "isGhost": true
                },
                "ref": "FZH7tK2P40xVDG2Gedj4gg",
                "version": "-hoqgD4pyQ9uCswMMpixUg"
              },
              {
                "parent": "FZH7tK2P40xVDG2Gedj4gg",
                "transformer": "ms-plugin.parse-cif",
                "params": {},
                "state": {
                  "isGhost": true
                },
                "ref": "JT3HTOvnXmclyWd9Dn66nQ",
                "version": "D1fxK87hXgfiLmH3hPB9uw"
              },
              {
                "parent": "JT3HTOvnXmclyWd9Dn66nQ",
                "transformer": "ms-plugin.trajectory-from-mmcif",
                "params": {},
                "state": {
                  "isCollapsed": true
                },
                "ref": "RcPS0dwKrMJsdOqaCVp_zA",
                "version": "tEyN73Zw0nZqd5bDGFl8jQ"
              },
              {
                "parent": "RcPS0dwKrMJsdOqaCVp_zA",
                "transformer": "ms-plugin.model-from-trajectory",
                "params": {
                  "modelIndex": 0
                },
                "ref": "nCTxoBHSyQHp2kMHeWq_Rw",
                "version": "HYpjyDqUjf6db3WGKvdBBA"
              },
              {
                "parent": "nCTxoBHSyQHp2kMHeWq_Rw",
                "transformer": "ms-plugin.custom-model-properties",
                "params": {
                  "autoAttach": [
                    "sifts_sequence_mapping"
                  ],
                  "properties": {
                    "asym_id_offset": {
                      "value": {
                        "auth": 2,
                        "label": 8
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
                "ref": "GyFqu1SX53p41pmOTlj1kg",
                "version": "nAfU-8YXCCwNaQ-aYEcNcQ"
              },
              {
                "parent": "GyFqu1SX53p41pmOTlj1kg",
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
                "ref": "az53-83cZM_ZloxrW5mPjA",
                "version": "fWX7xwLgVOog1D6DwKv5zw"
              },
              {
                "parent": "az53-83cZM_ZloxrW5mPjA",
                "transformer": "ms-plugin.transform-structure-conformation",
                "params": {
                  "transform": {
                    "name": "matrix",
                    "params": {
                      "data": [
                        0.6574963021634055,
                        -0.7501741180220591,
                        -0.0702664554421375,
                        0,
                        -0.048774506803241024,
                        -0.13544002114903897,
                        0.9895842293326123,
                        0,
                        -0.7518774033023448,
                        -0.6472207444972273,
                        -0.12564066999131462,
                        0,
                        49.91358252429038,
                        46.388169737658465,
                        -1.984255163271527,
                        1
                      ],
                      "transpose": false
                    }
                  }
                },
                "tags": [
                  "SuperpositionTransform"
                ],
                "ref": "YraIp9T7dFRXElATNUrnUQ",
                "version": "LkX39g_HR6BjMPok96gO5w"
              },
              {
                "parent": "YraIp9T7dFRXElATNUrnUQ",
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
                "ref": "lplzOpXSccaIYoTvSPNIjA",
                "version": "NIDuHp2s0NhKGQ1Kn8l9fA"
              },
              {
                "parent": "lplzOpXSccaIYoTvSPNIjA",
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
                "ref": "Ab_GLlu8moRnytzNZN6RlQ",
                "version": "Wx5ruiZj8YCvckioBZnDzA"
              },
              {
                "parent": "Ab_GLlu8moRnytzNZN6RlQ",
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
                "ref": "3nN-LBwpeYgkEowqlZzTwQ",
                "version": "yJabNEhUJXBNaIq2IjCOCQ"
              },
              {
                "parent": "lplzOpXSccaIYoTvSPNIjA",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "static",
                    "params": "ligand"
                  },
                  "nullIfEmpty": true,
                  "label": ""
                },
                "state": {
                  "isHidden": true
                },
                "tags": [
                  "structure-component-static-ligand"
                ],
                "ref": "Sokk5WG4tGGNY4dto2tyMA",
                "version": "lLe8hWtmMcCg8LUscj65Lg"
              },
              {
                "parent": "Sokk5WG4tGGNY4dto2tyMA",
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
                "state": {
                  "isHidden": true
                },
                "tags": [
                  "ligand"
                ],
                "ref": "BHo8VfQLlpQwWXUpxzhKHw",
                "version": "Lmd7tmGKKcg2W1nHjT2DcA"
              },
              {
                "parent": "lplzOpXSccaIYoTvSPNIjA",
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
                "ref": "5h4HFOip_QRKsU7BT9hy3A",
                "version": "yySLfbWtF-yjf9UEG9-VHQ"
              },
              {
                "parent": "5h4HFOip_QRKsU7BT9hy3A",
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
                "ref": "WMyAt_PeydDAIc92vpmZ9A",
                "version": "8_65I4QGKpkCIHIOdZBP2A"
              },
              {
                "parent": "lplzOpXSccaIYoTvSPNIjA",
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
                "ref": "ZUjXqauXpqzR8vpADnPWew",
                "version": "dvnq2mYJdP0fOSz8KEcHYA"
              },
              {
                "parent": "ZUjXqauXpqzR8vpADnPWew",
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
                "ref": "sgLioKp6vKgw_vP3NN2Bxg",
                "version": "lymOP59LLdEHC1gchUWedQ"
              },
              {
                "parent": "GyFqu1SX53p41pmOTlj1kg",
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
                "ref": "e3ApKW-kBMqai64NthW3Pg",
                "version": "80f9ZqGNQu_4nKkh6Xx8Jg"
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
                "ref": "vvCrYCwbuZ5me-un1bVllQ",
                "version": "tj7Yzc37r1HN0rIw2loE4A"
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
              -5.859506469720162,
              -70.33878455878026,
              -44.45909391383492
            ],
            "up": [
              -0.6475737829401106,
              0.5486601031079391,
              -0.5287913453396798
            ],
            "target": [
              6.211717709636878,
              6.108301511840504,
              20.07762386724431
            ],
            "radius": 41.79161153350996,
            "radiusMax": 112.9503014419188,
            "fog": 51,
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
                "intensity": 51
              }
            },
            "cameraClipping": {
              "far": true,
              "radius": 63,
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
              "maxDistance": 386.1653072938131,
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
        }).then(viewer => {
            var data64 = btoa(JSON.stringify(state2));
            viewer.loadSnapshotFromUrl(`data:text/plain;base64,${data64}`, 'molj');
        });
    </script>
</div>
{% endraw %}