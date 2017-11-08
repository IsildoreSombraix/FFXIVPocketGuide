---
layout: guide_post
title:  "The Thousand Maws of Toto-Rak"
date:   2017-04-09 18:00:14 -0300
description: "Read our Guide on the dungeon Xelphatol where you'll face off against Nuzal Hueloc, Dotoli Ciloc, and Tozol Huatotl."
image:
    - url: "/assets/img/dungeons/thousand_maws.jpg"
    - urlSmall: "/assets/img/dungeons/small/thousand_maws.jpg"
patchNumber: 2.0
patchName: "A Realm Reborn"
difficulty: "Normal"
plvl: 24
ilvl: 0
# Order is a direct combination of plvl+ilvl (e.g. 23+000 = 23000, 70+310 = 70310).
order: 24000
instanceType: "dungeon"
mtqvid: "YouTube URL"
#
# Paired Attack Tags: Marker
# AoE Attack Tags: Cone AoE, Circular AoE, Puddle AoE, Donut AoE, Column AoE, Area AoE, Point Blank AoE, Raid Wide AoE, Proximity AoE
# Other Attack Tags: Knockback, Cleave, Buff, Debuff, Tankbuster, Stack, Spread, Tether, Stun
# Unique Attack Tags: Mechanic, Animation, Spawn, Ultimate, Active Time Maneuver
#
mechanics:
  - title: ""
    steps:
      - step: 01
        notes:
          - note: ""
bosses:
  - title: ""
    # Boss ID is required for sidebar menu linking purposes (e.g. boss01, boss02, boss03, etc.).
    id: "boss01"
    # Use "reg", "combo", "vari" to tab attack snippets in.
    attacks:
      - title: "Attack Name"
        phases:
          - phase: 01
        roles:
          - role: ""
        dutyActions:
          - action: ""
        tags:
          - tag: ""
        notes:
          - note: ""
    sequence:
      - phase: 01
        attacks:
          - attack: ""
            # Include dutyActions: true only if the attack requires the use of a Duty Action.
            dutyActions: true
        alerts:
          - alert: ""
        mechanics:
          - title: ""
            notes:
              - note: ""
---