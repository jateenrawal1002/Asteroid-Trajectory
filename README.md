**Asteroid-Trajectory Simulation**
This Python project simulates a high-energy spacecraft mission from Planet A (Earth-like) to Planet C
(Neptune-like). It utilizes a combination of Hohmann transfers and gravity assists at intermediate planets to optimize travel time and fuel consumption.

**Mission Overview**
The mission is divided into four distinct phases:
Departure: High-energy escape from Planet A's Low Orbit (LEO).
Phase 1: Transfer to Planet B using an optimized high-velocity trajectory.
Phase 2: A deceleration gravity assist at Planet B (Jupiter-like) to redirect the craft toward the outer system.
Phase 3: An acceleration gravity assist at Planet D (Saturn-like) to boost the craft toward the final destination.
Final Phase: Orbital insertion into an elliptical orbit around Planet C.

**Technical Physics & Math**
The simulation utilizes several core orbital mechanics principles:
Vis-viva Equation: To calculate velocities at specific points in elliptical and hyperbolic orbits.
Hohmann Transfer: For efficient orbital maneuvering between planetary radii.
Hyperbolic Excess Velocity ($v_{\infty}$): To determine the energy required to escape or enter a planetary sphere of influence.
Gravity Assist Deflection: Calculating flyby distances ($r_p$) and deflection angles required to achieve specific velocity changes ($\Delta v$).
Tsiolkovsky Rocket Equation: To determine the fuel mass required for the final orbital insertion based on engine $I_{sp}$.
