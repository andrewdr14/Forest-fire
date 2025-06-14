# Forest Fire Model Simulation

This project implements a **forest fire model** based on the Drossel-Schwabl cellular automaton, designed to investigate **self-organized criticality** in dynamic systems. The simulation evolves over multiple iterations, demonstrating how tree clusters form and fires propagate under specific probabilistic conditions.

## Features
- **Forest Evolution:** Trees grow and fires ignite based on adjustable probabilities.
- **Animation & Analysis Modes:** Choose to visualize the simulation or analyze statistical properties.
- **Cluster Size Distribution:** Implements a **power-law fit** to evaluate tree cluster formation dynamics.
- **Histogram & Curve Fitting:** Uses **Scipy's curve fitting** to analyze cluster distributions.

## User Input
- Tree growth probability
- Lightning strike probability
- Canvas size (50×50 or 200×200)
- Simulation mode (animation or analysis)
- Number of iterations

## Dependencies
Requires:
- `matplotlib`
- `numpy`
- `scipy`

## Insights
This project explores **self-organized criticality**, a concept where complex systems naturally evolve into critical states. The histogram fitting reveals a power-law behavior indicative of **scale-free distributions**, commonly observed in **natural phenomena** like earthquakes and brain activity.
