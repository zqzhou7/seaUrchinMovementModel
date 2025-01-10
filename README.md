# Sea Urchin Movement Model
This repository contains R scripts for simulating the foraging movement of sea urchins. The simulation is based on the Lévy walk theory, which describes random movements composed of clusters of short steps interspersed with occasional longer steps. This pattern is observed in various organisms’ search behaviors and is modeled here to represent sea urchin foraging.

## Overview

The Lévy walk theory suggests that organisms search for food using short steps in a localized area and, after depleting that area, transition to another potential food source using longer steps. This model incorporates this behavior by simulating:
- Four food sources, represented as dashed circles. These circles indicate the range within which chemical cues from the food source can be detected by the sea urchin.
- When a sea urchin enters the range of a food source (within one of the circles), it detects the chemical cues and moves directly to the food source.

The model visually tracks the movement and behavior of the sea urchin in a simulated environment.

## Features
1. Simulates Lévy walk-based movement behavior.
2. Includes chemical cue detection for food sources.
3. Tracks interactions between the sea urchin’s movement and food source locations.

## Limitations
1. Simulation Duration:
2. Simplified Assumptions:
- The model is highly idealized and does not account for environmental complexity.
- In real-world scenarios, sea urchin foraging behavior may not strictly follow a Lévy walk pattern.
- Other abiotic factors (e.g., water currents, temperature gradients) that influence foraging behavior are not included in the model.

## References
Learn more about Lévy walks on [Wikipedia](https://en.wikipedia.org/wiki/L%C3%A9vy_flight).
