---
layout: post
title: "Granite Vibe: Holiday Vibe Coding"
date: 2025-12-30
---

Over the Christmas holidays I vibe coded a little LiDAR ray tracer. It was a
steady climb of water level and depth estimation, better water rendering, and
depthmap caching to keep iterations fast. Lighting got love too (global
illumination, shadow tweaks, and filtering), and I kept refining the UI until
it supported nicer interaction and lat/lon readouts.

The data comes from the USGS 3D Elevation Program (3DEP) LiDAR acquisition
project for Yosemite. Huge thanks to the USGS for making it available:
[USGS Yosemite 2019 LAZ](https://rockyweb.usgs.gov/vdelivery/Datasets/Staged/Elevation/LPC/Projects/CA_YosemiteNP_2019_D19/CA_YosemiteNP_2019/LAZ/)

See the results here: [Granite Vibe](https://tpyl.github.io/granitevibe/)
