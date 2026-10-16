---
layout: default
title: 'β-sheet'
---

# β-sheet

The second major structural element found in globular proteins is the β-sheet. Unlike α-helices, which form from a single continuous stretch of sequence, β-sheets are built from multiple extended strands that lie alongside each other, connected by inter-strand hydrogen bonds. These strands can be quite far apart in the amino acid sequence but come together in three-dimensional space to form a sheet-like structure.

Each individual β-strand adopts an extended conformation quite different from the tightly coiled α-helix. The backbone is stretched out, with approximate dihedral angles φ ≈ -120° and ψ ≈ +120°. When two or more of these extended strands align side-by-side, hydrogen bonds form between the carbonyl oxygen of one strand and the amide hydrogen of the neighbouring strand, creating a pleated sheet structure.

β-sheets can be arranged in two different orientations.  These strands can run in the same direction (parallel) or in opposite directions (antiparallel), with the latter forming stronger, more linear hydrogen bonds. This structure can be thought of as a thread that is woven up and down through the fabric, offering strong interactions found at the core of many proteins. Side chains appear on the top or bottom of the structure in an alternating fashion, which can provide charge or hydrophobicity on one or both faces.

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
          <h5>Architecture of an antiparallel beta-sheet. </h5>
          <p style="text-align:center; margin-left:20px; margin-right:20px;  font-size: 16px; color: #54585a; margin-block-start: 0.5em !important; margin-block-end: 2em !important;">
          This model illustrates an antiparallel beta-sheet, where adjacent polypeptide strands run in opposite directions.
          The structure is stabilised by inter-strand hydrogen bonds (dashed blue lines) that form between the carbonyl oxygens and amide hydrogens of the backbone; in this antiparallel orientation, these bonds are nearly linear, providing maximum stability. 
          </p>
        </div>
  <!-- Repeat the structure for the other instances -->
  <div class="item">
    <div id="app2" class="app"></div>
    <div id="text">
      <h5>Parallel beta-sheet architecture.</h5>
      <p style="text-align:center; margin-left:20px; margin-right:20px;  font-size: 16px; color: #54585a; margin-block-start: 0.5em !important; margin-block-end: 2em !important;">
        This model depicts a parallel beta-sheet, a secondary structure motif where all polypeptide strands run in the same N-to-C terminal direction.
        In this parallel arrangement, the hydrogen bonds are skewed or angled rather than linear.
      </p>
    </div>
</div>
</div>
    <script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <script type="text/javascript">
        const  state1= {
  "timestamp": 1770287123559,
  "version": "5.6.0",
  "current": "7jSmnS5Cs-6YfkFnlQXOwg",
  "playback": {
    "isPlaying": false,
    "nextSnapshotDelayInMs": 1500
  },
  "entries": [
    {
      "timestamp": 1770287123557,
      "snapshot": {
        "id": "7jSmnS5Cs-6YfkFnlQXOwg",
        "data": {
          "tree": {
            "transforms": [
              {
                "parent": "-=root=-",
                "transformer": "build-in.root",
                "params": {},
                "ref": "-=root=-",
                "version": "3FQjurjMu8oBf2K7ryL9LA"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.download",
                "params": {
                  "url": {
                    "kind": "url",
                    "id": "8QWPVUqazrMxa5Q9srZngA",
                    "url": "https://www.ebi.ac.uk/pdbe/entry-files/download/4gcr.bcif"
                  },
                  "label": "PDBe: 4gcr (updated cif)",
                  "isBinary": true
                },
                "state": {
                  "isGhost": true
                },
                "ref": "EnG8ffHHBIJpA3UiCL9nlw",
                "version": "BFCjGLYXjq6xmibKqYd3zw"
              },
              {
                "parent": "EnG8ffHHBIJpA3UiCL9nlw",
                "transformer": "ms-plugin.parse-cif",
                "params": {},
                "state": {
                  "isGhost": true
                },
                "ref": "P_Qwi2I0ptSIxkrjq-xghw",
                "version": "GNIHl6RNTQkevvzp6voI9Q"
              },
              {
                "parent": "P_Qwi2I0ptSIxkrjq-xghw",
                "transformer": "ms-plugin.trajectory-from-mmcif",
                "params": {
                  "loadAllBlocks": false,
                  "blockHeader": "4GCR",
                  "blockIndex": 0
                },
                "ref": "kDSHxVQp32BMUCZICxiImw",
                "version": "x9CU_F1tTM0WBNZ36Y0UYw"
              },
              {
                "parent": "kDSHxVQp32BMUCZICxiImw",
                "transformer": "ms-plugin.model-from-trajectory",
                "params": {
                  "modelIndex": 0
                },
                "ref": "qIGNs2cTq76FyDNDHaSR2Q",
                "version": "TWkF8WEibXH3t1ckBvTI8Q"
              },
              {
                "parent": "qIGNs2cTq76FyDNDHaSR2Q",
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
                "ref": "Iieb37cBnjQ-9KtMuxNR1w",
                "version": "DNeBijJBQp_SzpDSrRyq6g"
              },
              {
                "parent": "Iieb37cBnjQ-9KtMuxNR1w",
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
                "ref": "6lCVBWWiKsqLco8UPdfqEw",
                "version": "SR380niAKyTV8WqoU0DmcQ"
              },
              {
                "parent": "6lCVBWWiKsqLco8UPdfqEw",
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
                "ref": "0u_Gys6Yftt1NCScudkMDA",
                "version": "Zgk1b7yKb8_Xv1nE5JBCsQ"
              },
              {
                "parent": "0u_Gys6Yftt1NCScudkMDA",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "bundle",
                    "params": {
                      "hash": 724931145,
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
                            59,
                            103,
                            182,
                            343,
                            400
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
                "ref": "wsBREgmVPeBgn78N-kr8rQ",
                "version": "SQ76kKtH6Wer9NJz_XclBg"
              },
              {
                "parent": "wsBREgmVPeBgn78N-kr8rQ",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "cartoon",
                    "params": {
                      "alpha": 0.66,
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
                "ref": "k8qPUcp64WKVWaqrnIixJQ",
                "version": "MeOgxQVBo77myNBZ8NpN6Q"
              },
              {
                "parent": "wsBREgmVPeBgn78N-kr8rQ",
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
                "ref": "le-vTySJ0-7CSI9oD4KTPg",
                "version": "4_gIPqkQT5EBd489r_t03Q"
              },
              {
                "parent": "wsBREgmVPeBgn78N-kr8rQ",
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
                "ref": "UPMi7U-WkACQLCtHFhESeg",
                "version": "XM7GkVZOiCfD_shoiQgKew"
              },
              {
                "parent": "Iieb37cBnjQ-9KtMuxNR1w",
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
                "ref": "o8ZHsbActpbfzziKPNp2ow",
                "version": "DX1mrBvMQfVt9aYAtWtkDg"
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
                "ref": "pE3b9LR6PelPUxFnfxEJnA",
                "version": "IFzkBGGgf8ZdX9ANzkh0jw"
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
              -3.3776668915389108,
              -7.76145931156978,
              64.72848859191488
            ],
            "up": [
              -0.9308928275668455,
              0.35439339079789545,
              0.08856561490416894
            ],
            "target": [
              2.485066715809494,
              13.626331579873042,
              40.767552138470144
            ],
            "radius": 14.90978969004062,
            "radiusMax": 66.15227048653666,
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
              "radius": 77,
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
              "maxDistance": 149.0978969004062,
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
            var data64 = btoa(JSON.stringify(state1));
            viewer.loadSnapshotFromUrl(`data:text/plain;base64,${data64}`, 'molj');
        });
    </script>
<!-- SECOND STRUCTURE --->
<script type="text/javascript" src="https://molstar.org/viewer/molstar.js"></script>
    <script type="text/javascript">
        const state2 = {
  "timestamp": 1770286891401,
  "version": "5.6.0",
  "current": "iWWzdGWWh77kAdeuWQfHGg",
  "playback": {
    "isPlaying": false,
    "nextSnapshotDelayInMs": 1500
  },
  "entries": [
    {
      "timestamp": 1770286891399,
      "snapshot": {
        "id": "iWWzdGWWh77kAdeuWQfHGg",
        "data": {
          "tree": {
            "transforms": [
              {
                "parent": "-=root=-",
                "transformer": "build-in.root",
                "params": {},
                "ref": "-=root=-",
                "version": "LrZ_VNDDDcpj8T4kx2KkNA"
              },
              {
                "parent": "-=root=-",
                "transformer": "ms-plugin.download",
                "params": {
                  "url": {
                    "kind": "url",
                    "id": "IgSf1NWbNlGWvVtwjaohhQ",
                    "url": "https://www.ebi.ac.uk/pdbe/entry-files/download/2pec.bcif"
                  },
                  "label": "PDBe: 2PEC (updated cif)",
                  "isBinary": true
                },
                "state": {
                  "isGhost": true
                },
                "ref": "92oa7fUddKQsUEBGE4ssRw",
                "version": "PSkEZbsxEpBfNJVXmaE6hg"
              },
              {
                "parent": "92oa7fUddKQsUEBGE4ssRw",
                "transformer": "ms-plugin.parse-cif",
                "params": {},
                "state": {
                  "isGhost": true
                },
                "ref": "2btL-5nPMpAMLQWgl3e0mA",
                "version": "-yXVk3FjLYPafHfadZ8v8w"
              },
              {
                "parent": "2btL-5nPMpAMLQWgl3e0mA",
                "transformer": "ms-plugin.trajectory-from-mmcif",
                "params": {},
                "ref": "vtWIMksP-xIHUy5Rk8b-oQ",
                "version": "n5zAo9weCcLRlj8Hw7oHUQ"
              },
              {
                "parent": "vtWIMksP-xIHUy5Rk8b-oQ",
                "transformer": "ms-plugin.model-from-trajectory",
                "params": {
                  "modelIndex": 0
                },
                "ref": "YoaKBOOBybw37WftEEDrcA",
                "version": "Rh5O1o8xHBWZE_7HAuY9bQ"
              },
              {
                "parent": "YoaKBOOBybw37WftEEDrcA",
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
                "ref": "QX3S42Lb7JYGzNgZ2zfsZw",
                "version": "OJNPNL4xXrlbGV8xPPj-SQ"
              },
              {
                "parent": "QX3S42Lb7JYGzNgZ2zfsZw",
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
                "ref": "_i5SDz0pfPl_sVfALzbjUg",
                "version": "QqF5zO1lqV4t6mR9XwmVhQ"
              },
              {
                "parent": "_i5SDz0pfPl_sVfALzbjUg",
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
                "ref": "ZzzucfoStTFcpUiClYbkTA",
                "version": "h2SmFsU6GeIXNR7jlo8lZw"
              },
              {
                "parent": "ZzzucfoStTFcpUiClYbkTA",
                "transformer": "ms-plugin.structure-component",
                "params": {
                  "type": {
                    "name": "bundle",
                    "params": {
                      "hash": 1360835015,
                      "elements": [
                        {
                          "groupedUnits": [
                            [
                              0
                            ]
                          ],
                          "set": [],
                          "ranges": [
                            1278,
                            1331,
                            1473,
                            1538,
                            1665,
                            1718,
                            1842,
                            1892,
                            2055,
                            2107
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
                "ref": "FgHClZEN3YLtHQwp0kx8RA",
                "version": "ZekgpkfAVb4_OIlQaonJbg"
              },
              {
                "parent": "FgHClZEN3YLtHQwp0kx8RA",
                "transformer": "ms-plugin.structure-representation-3d",
                "params": {
                  "type": {
                    "name": "cartoon",
                    "params": {
                      "alpha": 0.75,
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
                    "name": "chain-id",
                    "params": {
                      "asymId": "auth",
                      "palette": {
                        "name": "colors",
                        "params": {
                          "list": {
                            "kind": "set",
                            "colors": [
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
                "ref": "48owuOiDEE_5L1vS4yRnWw",
                "version": "BZw66Uy8rJe7R6HNMRHaSA"
              },
              {
                "parent": "FgHClZEN3YLtHQwp0kx8RA",
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
                "ref": "QzzfEuaNwZr2PQ0XIIMV7Q",
                "version": "C-580rWxZvpfIZrp_H00ZA"
              },
              {
                "parent": "FgHClZEN3YLtHQwp0kx8RA",
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
                "ref": "-HsZS5g3toNAodIfgpPukA",
                "version": "MdINkdgTY42L811YFgM4ZQ"
              },
              {
                "parent": "QX3S42Lb7JYGzNgZ2zfsZw",
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
                "ref": "MncCehCyhVKyNrlF8ah3Gw",
                "version": "LA8HQNAgnYkZwsEqe9SxBQ"
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
                "ref": "PdirydKxdbppuUOcwdwkYA",
                "version": "6thB0zUH6UJqtYR-zmAPDQ"
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
              26.58613768554958,
              -6.097234641579824,
              2.3728457158246616
            ],
            "up": [
              -0.8589134049733967,
              -0.22237432802750468,
              0.4613213857945463
            ],
            "target": [
              10.42891873562935,
              29.542668034602933,
              -10.529769939730189
            ],
            "radius": 35.587143268400744,
            "radiusMax": 75.71732610298031,
            "fog": 21,
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
                "intensity": 21
              }
            },
            "cameraClipping": {
              "far": true,
              "radius": 53,
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
              "maxDistance": 187.358803546744,
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
        molstar.Viewer.create('app2', {
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