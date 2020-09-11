---
category: SONATA
url_path: null
title: 'About'
type: null

layout: null
---
# SONATA

SONATA: A Toolkit to Generate Social Navigation Datasets and HRI

## Introduction

The toolkit is used to generate the dataset by simulating the scenarios for robot's navigation in a social setting. We show an usecase of this data collected from the toolkit by converting into graphs and feeding it into the GNNs to predicts the robot's path in a given scene. The data collected from the toolkit comprises of the following for a given entity:
* Co-ordinates
* Velocity with respect to the robot
* Type of interaction betweeen the two entities
* Orientation
* Size

The data is stored in the form of JSON files, with the following structure:
```
"timestamp": 1598462029.7540903,
        "walls": [
            {
                "x1": 5.64804220199585,
                "x2": 4.9704155921936035,
                "y1": 4.951876163482666,
                "y2": -1.009736180305481
            },
            {
                "x1": 4.970417499542236,
                "x2": -0.991195559501648,
                "y1": -1.0097349882125854,
                "y2": -0.3321133852005005
            },
            {
                "x1": -0.991193413734436,
                "x2": -0.3135751187801361,
                "y1": -0.332114040851593,
                "y2": 5.629499435424805
            },
            {
                "x1": -0.3135727047920227,
                "x2": 5.648040294647217,
                "y1": 5.629498481750488,
                "y2": 4.951875686645508
            }
        ]
    },
    {
        "command": [
            -0.06999999843537807,
            0,
            0.25999999046325684
        ],
        "goal": [
            {
                "x": 0.9240278005599976,
                "y": 3.107682704925537
            }
        ],
        "interaction": [
            {
                "dst": 2,
                "relation": "human_laptop_interaction",
                "src": 1
            }
        ],
        "objects": [
            {
                "a": 0.11155806481838226,
                "id": 2,
                "size_x": 0.8999996185302734,
                "size_y": 0.800000011920929,
                "va": 0.0016205161809921265,
                "vx": 0.006066322326660156,
                "vy": -0.005913734436035156,
                "x": 3.3170711994171143,
                "y": 3.743642807006836
            }
        ],
        "people": [
            {
                "a": -1.458441972732544,
                "id": 1,
                "va": 0.0016202926635742188,
                "vx": -1.5497207641601562e-05,
                "vy": -0.005223274230957031,
                "x": 2.8968095779418945,
                "y": -0.007299661636352539
            }
        ]
```
