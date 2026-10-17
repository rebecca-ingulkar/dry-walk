# Dry Walk

## Overview

Dry Walk is a walking route planner designed to help people get from point A to point B while minimising their exposure to rain.

Unlike traditional route planners that primarily optimise for distance or travel time, Dry Walk aims to consider rainfall and available shelter along footpaths to find a more comfortable walking route.

## Problem Statement

Walking in the rain can be uncomfortable, even when the destination is relatively close. Traditional mapping tools do not necessarily account for how much shelter is available along a walking route.

Dry Walk aims to help users make more informed route choices based on expected rainfall and pedestrian shelter.

## MVP Scope

The initial minimum viable product (MVP) will focus on:

- Finding a walking route between two addresses.
- Using OpenStreetMap data to investigate pedestrian paths and shelter.
- Identifying legitimate pedestrian crossings.
- Considering available shelter along footpaths.
- Estimating rain exposure using current and forecast rainfall over the duration of the walk.

The initial goal is to investigate whether available mapping and geographic data can support this functionality.

## Initial Data Research

For our Wellington test route, OpenStreetMap provides detailed pedestrian infrastructure and building geometry, but we haven't found reliable explicit shelter information.

Research will focus on relevant map features, tagging conventions, data coverage, and limitations.

## Development Status

**Current phase:** Research and MVP planning.

- [x] Define the core problem and initial concept.
- [x] Establish the initial MVP requirements.
- [ ] Investigate OpenStreetMap data and shelter tagging.
- [ ] Determine the routing and rainfall data requirements.
- [ ] Select the initial technology stack.
- [ ] Build the first working route-planning prototype.

## Future Considerations

Potential future enhancements include:

- User preferences for shelter and route trade-offs.
- More detailed rain-exposure estimates.
- Support for additional locations and regions.

## Disclaimer

Dry Walk is an early-stage project. Route quality, shelter data availability, and rainfall estimates will need to be evaluated during development.
