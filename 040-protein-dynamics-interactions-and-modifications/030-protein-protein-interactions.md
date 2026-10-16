---
layout: default
title: 'Protein-Protein interactions'
---

# Protein-Protein interactions

When proteins form a complex, the resulting interface is not a random patch of the protein’s surface. These areas are evolutionarily selected to ensure high specificity, meaning a protein can distinguish its correct partner from thousands of other cellular components.

The bonds that stabilise an interface are the same as those that stabilise the interior of a protein: hydrophobic interactions, hydrogen bonds, and salt bridges (electrostatic attractions between oppositely charged side chains).

The hydrophobic effect plays a dominant role here. The regions of a protein destined to be buried in an interface are generally less polar than the rest of the protein’s exposed surface.  When these nonpolar regions come together, they exclude water molecules, providing a major thermodynamic driving force for association. The released water molecules gain entropy, stabilising the complex.

Interestingly, the atomic packing at an interface is almost as dense as the interior of a protein. However, interfaces often trap “structural” water molecules. These are not merely bystanders; they can act as “molecular mortar,” filling gaps in the interface and extending the hydrogen-bonding network to bridge distances between the two proteins.

In some cases, subunits are only partially folded on their own. It is only upon meeting their partner that they assume their final stable tertiary structure. In these instances, the interface is essential not only for function but also for the structural integrity of the proteins themselves.

This highlights an important point: complementarity is not always pre-existing. In a phenomenon called induced fit, one or both binding partners may be relatively unstructured or flexible when alone. Upon binding, they undergo conformational changes to achieve the complementary state required for high-affinity interaction. This emphasises that protein structures are dynamic entities rather than rigid blocks, a theme we’ll explore further below.

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
          <h5> Human Transthyretin (prealbumin) complex with Flufenamic acid (PDB: <a href="https://www.ebi.ac.uk/pdbe/entry/pdb/1bm7" target="_blank" rel="noreferrer noopener">1BM7</a>).</h5>
        </div>
      </div>
    </div>
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <script type="text/javascript">
        const state ={
  "timestamp": 1772032601380,
  "version": "5.6.0",
  "current": "9hPAK3kOZzdXpIek1T1lrQ",
  "playback": {
    "isPlaying": false,
    "nextSnapshotDelayInMs": 1500
  },
  "entries": [
    {
      "timestamp": 1772032601378,
      "snapshot": {
        "id": "9hPAK3kOZzdXpIek1T1lrQ",
        "data": {
          "tree": {
            "transforms": [
              {
                "parent": "-=root=-",
                "transformer": "build-in.root",
                "params": {},
                "ref": "-=root=-",
                "version": "bKb976yFhI42331hETlVew"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.download",
                "params": {
                  "url": {
                    "kind": "url",
                    "id": "LVn7R8JE5LklhN6fTSDLuQ",
                    "url": "https://www.ebi.ac.uk/pdbe/entry-files/download/1bm7.bcif"
                  },
                  "label": "PDBe: 1bm7 (updated cif)",
                  "isBinary": true
                },
                "state": {
                  "isGhost": true
                },
                "ref": "TmlWFQRVlXYLGOIkm4QCyQ",
                "version": "qXD-9IQtGzTXozHr8K_uGg"
              },
              {
                "parent": "TmlWFQRVlXYLGOIkm4QCyQ",
                "transformer": "ms-plugin.parse-cif",
                "params": {},
                "state": {
                  "isGhost": true
                },
                "ref": "V1e4241o8ofA4iMNxBeRTQ",
                "version": "qFHSvqXkD2L3xuCMcpZCXQ"
              },
              {
                "parent": "V1e4241o8ofA4iMNxBeRTQ",
                "transformer": "ms-plugin.trajectory-from-mmcif",
                "params": {},
                "ref": "XDgYQj29n-xTvfMTzxUTdA",
                "version": "iWaK1g21ClOEYz3GnBZEhg"
              },
              {
                "parent": "XDgYQj29n-xTvfMTzxUTdA",
                "transformer": "ms-plugin.model-from-trajectory",
                "params": {
                  "modelIndex": 0
                },
                "ref": "l8CESTGrs4J-TeUZLH4SEA",
                "version": "-xpHRTrrqpsdazoWg84lDw"
              },
              {
                "parent": "l8CESTGrs4J-TeUZLH4SEA",
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
                "ref": "tpG8CUiDyNBR_Qf-zp2urw",
                "version": "6B9DE4JAu0IdlmogZxYV7A"
              },
              {
                "parent": "tpG8CUiDyNBR_Qf-zp2urw",
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
                "ref": "vIEKoAuiQTjhL-4mdKn7pg",
                "version": "Owu5Ti9Y_PkA4YeOP2lZ8A"
              },
              {
                "parent": "vIEKoAuiQTjhL-4mdKn7pg",
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
                "ref": "ppdO3qcXRoyP1T4xGShLaw",
                "version": "pJu-3Jr-eC4TMnl8pP6Q7A"
              },
              {
                "parent": "ppdO3qcXRoyP1T4xGShLaw",
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
                "ref": "HixGQ_VTTsS0nXyFAYiCag",
                "version": "KreyDVYker4PNfCcI0VsVA"
              },
              {
                "parent": "HixGQ_VTTsS0nXyFAYiCag",
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
                "ref": "bk1P4SE7Zh_3gyMjvzICLg",
                "version": "kgb7r2ZCd0n47FollMHK5Q"
              },
              {
                "parent": "ppdO3qcXRoyP1T4xGShLaw",
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
                "ref": "qQcMPRxRcxbn2i1RI4aAAQ",
                "version": "8wdnWUfYWgfilC3Kpae--A"
              },
              {
                "parent": "qQcMPRxRcxbn2i1RI4aAAQ",
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
                "ref": "vu8-FS0XJI0RudkStyAf-g",
                "version": "gFXSGnbdiGAxyU2p3lV-KA"
              },
              {
                "parent": "ppdO3qcXRoyP1T4xGShLaw",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "static",
                    "params": "water"
                  },
                  "nullIfEmpty": true,
                  "label": ""
                },
                "tags": [
                  "structure-component-static-water"
                ],
                "ref": "rkhtJtofyO9i3f4imW7imw",
                "version": "6-TMRRtbhxK5fU03rGGMIw"
              },
              {
                "parent": "rkhtJtofyO9i3f4imW7imw",
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
                "tags": [
                  "water"
                ],
                "ref": "GrQT4H7QRTnYJTRsneY6Hg",
                "version": "hZ3xYp9wb_5o7Iw4mZlFzw"
              },
              {
                "parent": "ppdO3qcXRoyP1T4xGShLaw",
                "transformer": "ms-plugin.structure-selection-from-bundle",
                "params": {
                  "bundle": {
                    "hash": 1482753666,
                    "elements": [
                      {
                        "groupedUnits": [
                          [
                            4
                          ]
                        ],
                        "set": [
                          34
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
                "ref": "6vSsx9_0bsKHvri6qu6pfg",
                "version": "z76CgqpmXEQPe0WzptAaKA"
              },
              {
                "parent": "6vSsx9_0bsKHvri6qu6pfg",
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
                "ref": "AojCX65WOVWUc4qrvMSzVg",
                "version": "fHEvVLEpGnGiGYOvOBiopA"
              },
              {
                "parent": "ppdO3qcXRoyP1T4xGShLaw",
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
                                          4
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
                                      34
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
                "ref": "rGQjKTvhfYyck6XVVKC2-A",
                "version": "h15XxMGmo8lOmioqXezB3w"
              },
              {
                "parent": "rGQjKTvhfYyck6XVVKC2-A",
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
                "ref": "sp2g9SAjmmQiBmiIXGbWbA",
                "version": "Gi-CnnZiJyuY0yjqh8HvwQ"
              },
              {
                "parent": "rGQjKTvhfYyck6XVVKC2-A",
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
                "ref": "r2p83jfWNASgChB7AZg3_Q",
                "version": "XTrXF_ZapDc-gAYanmtFxQ"
              },
              {
                "parent": "tpG8CUiDyNBR_Qf-zp2urw",
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
                "ref": "fQDIMjVbaWquaDkGcbNURg",
                "version": "3Kobc3GJDVje7bShl0OESQ"
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
                "ref": "VwhrOZsYPQg_8awbGnUazw",
                "version": "hcjSIlXHB4td1eT2Sk-LxQ"
              },
              {
                "parent": "VwhrOZsYPQg_8awbGnUazw",
                "transformer": "ms-plugin.structure-multi-selection-from-bundle",
                "params": {
                  "selections": [
                    {
                      "key": "a",
                      "ref": "ppdO3qcXRoyP1T4xGShLaw",
                      "groupId": "",
                      "bundle": {
                        "hash": 1482753666,
                        "elements": [
                          {
                            "groupedUnits": [
                              [
                                1
                              ]
                            ],
                            "set": [],
                            "ranges": [
                              593,
                              603
                            ]
                          }
                        ]
                      }
                    }
                  ],
                  "isTransitive": true,
                  "label": "Label"
                },
                "ref": "DcsLSCv8a1z2POf42Pr2Kw",
                "dependsOn": [
                  "ppdO3qcXRoyP1T4xGShLaw"
                ],
                "version": "ss0caLbdt_Eux3eHl3U_Kw"
              },
              {
                "parent": "DcsLSCv8a1z2POf42Pr2Kw",
                "transformer": "ms-plugin.structure-selections-label-3d",
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
                  "borderWidth": 0.2,
                  "borderColor": 8421504,
                  "offsetX": 0,
                  "offsetY": 0,
                  "offsetZ": 0,
                  "background": false,
                  "backgroundMargin": 0.2,
                  "backgroundColor": 8421504,
                  "backgroundOpacity": 1,
                  "tether": false,
                  "tetherLength": 1,
                  "tetherBaseWidth": 0.3,
                  "attachment": "middle-center",
                  "customText": "",
                  "textColor": 0,
                  "textSize": 0.3,
                  "scaleByRadius": true,
                  "visuals": [
                    "text"
                  ],
                  "snapshotKey": "",
                  "tooltip": ""
                },
                "ref": "nnvNGidWpWOukKn78rj4gA",
                "version": "pZ3EhEDJi0x4QZxjbNwfOQ"
              },
              {
                "parent": "VwhrOZsYPQg_8awbGnUazw",
                "transformer": "ms-plugin.structure-multi-selection-from-bundle",
                "params": {
                  "selections": [
                    {
                      "key": "a",
                      "ref": "ppdO3qcXRoyP1T4xGShLaw",
                      "groupId": "",
                      "bundle": {
                        "hash": 1482753666,
                        "elements": [
                          {
                            "groupedUnits": [
                              [
                                0
                              ]
                            ],
                            "set": [],
                            "ranges": [
                              672,
                              678
                            ]
                          }
                        ]
                      }
                    }
                  ],
                  "isTransitive": true,
                  "label": "Label"
                },
                "ref": "E9OFA_IgAQexQk6wAgJ7Qg",
                "dependsOn": [
                  "ppdO3qcXRoyP1T4xGShLaw"
                ],
                "version": "Sc5DIB_dbhOlBrsET5mTjQ"
              },
              {
                "parent": "E9OFA_IgAQexQk6wAgJ7Qg",
                "transformer": "ms-plugin.structure-selections-label-3d",
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
                  "borderWidth": 0.2,
                  "borderColor": 8421504,
                  "offsetX": 0,
                  "offsetY": 0,
                  "offsetZ": 0,
                  "background": false,
                  "backgroundMargin": 0.2,
                  "backgroundColor": 8421504,
                  "backgroundOpacity": 1,
                  "tether": false,
                  "tetherLength": 1,
                  "tetherBaseWidth": 0.3,
                  "attachment": "middle-center",
                  "customText": "",
                  "textColor": 0,
                  "textSize": 0.3,
                  "scaleByRadius": true,
                  "visuals": [
                    "text"
                  ],
                  "snapshotKey": "",
                  "tooltip": ""
                },
                "ref": "lRsKuQyPdHmE5Mz9zVYtDg",
                "version": "jCOwlvXCcxUHvQytE69pCw"
              },
              {
                "parent": "VwhrOZsYPQg_8awbGnUazw",
                "transformer": "ms-plugin.structure-multi-selection-from-bundle",
                "params": {
                  "selections": [
                    {
                      "key": "a",
                      "ref": "ppdO3qcXRoyP1T4xGShLaw",
                      "groupId": "",
                      "bundle": {
                        "hash": 1482753666,
                        "elements": [
                          {
                            "groupedUnits": [
                              [
                                1
                              ]
                            ],
                            "set": [],
                            "ranges": [
                              614,
                              622
                            ]
                          }
                        ]
                      }
                    }
                  ],
                  "isTransitive": true,
                  "label": "Label"
                },
                "ref": "nk_MFxDF_e4jw6YOX4IiMQ",
                "dependsOn": [
                  "ppdO3qcXRoyP1T4xGShLaw"
                ],
                "version": "UYYk37nJNqHkZH9q-g-QmQ"
              },
              {
                "parent": "nk_MFxDF_e4jw6YOX4IiMQ",
                "transformer": "ms-plugin.structure-selections-label-3d",
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
                  "borderWidth": 0.2,
                  "borderColor": 8421504,
                  "offsetX": 0,
                  "offsetY": 0,
                  "offsetZ": 0,
                  "background": false,
                  "backgroundMargin": 0.2,
                  "backgroundColor": 8421504,
                  "backgroundOpacity": 1,
                  "tether": false,
                  "tetherLength": 1,
                  "tetherBaseWidth": 0.3,
                  "attachment": "middle-center",
                  "customText": "",
                  "textColor": 0,
                  "textSize": 0.3,
                  "scaleByRadius": true,
                  "visuals": [
                    "text"
                  ],
                  "snapshotKey": "",
                  "tooltip": ""
                },
                "ref": "LGga2Bc-Jw9PJLW_Mwpivg",
                "version": "5s1sMYtK9X3GHeqrtZ7n9w"
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
              -12.64503763391241,
              34.28373748969134,
              2.9055125885044273
            ],
            "up": [
              -0.3207944320302796,
              -0.8132584205338742,
              0.4854911675909843
            ],
            "target": [
              10.585576950238517,
              29.700714473341932,
              10.578298419345076
            ],
            "radius": 8,
            "radiusMax": 59.299639254207726,
            "fog": 64,
            "clipFar": true,
            "minNear": 14.4,
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
                "intensity": 64
              }
            },
            "cameraClipping": {
              "far": true,
              "radius": 87,
              "minNear": 14.4
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
              "maxDistance": 387.9701468964364,
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
            "label": "O[idx 1877] | HOH 505 | F [auth B]",
            "ref": "ppdO3qcXRoyP1T4xGShLaw",
            "bundle": {
              "hash": 1482753666,
              "elements": [
                {
                  "groupedUnits": [
                    [
                      4
                    ]
                  ],
                  "set": [
                    34
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

## **Induced fit and conformational changes**

The classical “lock and key” model of protein-ligand binding, proposed by [Emil Fischer in 1894](https://chemistry-europe.onlinelibrary.wiley.com/doi/abs/10.1002/cber.18940270364), envisions rigid partners whose shapes are pre-formed to match perfectly. While conceptually useful, this model is fundamentally incomplete because it ignores protein flexibility. In reality, both proteins in a complex are dynamic, and binding often involves conformational changes in one or both partners ([Tripathi, A., & Bankaitis, V. A., 2017](https://pmc.ncbi.nlm.nih.gov/articles/PMC5764188/)).

The concept of induced fit recognises that binding can drive conformational changes. A protein may exist in a relatively open or disordered state when free in solution. Upon encountering its binding partner, favourable interactions begin to form, and the free energy gained from these interactions provides thermodynamic impetus for conformational changes that optimise the interface. The protein effectively moulds itself around the ligand, achieving better complementarity than existed in the initial encounter.

Many proteins undergo substantial domain movements upon binding. The driving force for this conformational change is the formation of new, favourable interactions (hydrogen bonds, van der Waals contacts, electrostatic attractions), which lowers the overall energy of the complex. Additionally, the displacement of ordered water molecules from hydrophobic pockets or surfaces increases the system’s entropy, providing additional thermodynamic impetus for complex formation.

This flexibility helps explain how many drugs that don’t obviously resemble the natural ligand can still bind tightly; both the drug and the binding site can adjust to accommodate differences in shape, provided enough favourable interactions can be made.