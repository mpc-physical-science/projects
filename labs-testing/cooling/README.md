# Cooling

## Summary

An attempt to find a reasonable set of parameters for demonstrating Newton's Law of Cooling in a desktop experiment

## Procedure

These experiments conducted with:

* Data acquisition with Pasco GLX and Capstone
* Pasco Fast Response Temp Probes <https://www.pasco.com/file_downloads/Downloads_Manuals/PASPORT-Fast-Response-Temperature-Probe-Manual-PS-2135.pdf>

Three vessels were tested:

* a black film canister (m = 5.1g)
* a styrofoam cup (m = 4.3 g)
* a glass 400mL beaker (141.9g)

The containers each had a lid with a feedthrough for the thermometer (not included in the above masses). Containers were filled with warm water (mass m_w), weighed, and covered. The temperature was recorded at 1 second intervals for several minutes with a thermometer in the water (T) and another reference thermometer sitting on a folded paper towel on the table.

## Results

The styrofoam cup and and glass beaker exhibited long time constants ( ~ 10^4 s) and were not pursued after the first round of tests.

The film canister time constant was approximately 10^3 seconds. Several trials were conducted with varying initial temperature and mass of water m_w

The Temperature vs Time curves were fit with a model:

> T(t) = A * exp( - B * t ) +y_0

The results of the fits are in the table below. It should be noted that the relevant fit parameters varied considerably while varying the selection window of the data input to the fit.

| T# | m_w (g) | A (deg C) | B (s^-1) | y_0 (deg C) | T_env (deg C)| T (s) |
|----|---------|-----------|----------|-------------|--------------|-------|
| 1  |   22.6  | 19.5      | 1.22^10-3|   26.1      |   22.9       | 1092  |
| 2  |   26.0  | 20.9      | 8.50^10-5|   27.1      |   23.6       | 495   |
| 3  |   16.4  | 15.7      | 8.83^10-4|   24.4      |   23.4       | 667   |

The additional variables ΔT = T - T_env and ln(ΔT) were computed. Graphing ln(ΔT) resulted in reasonably straight lines.


## Resources

<https://en.wikipedia.org/wiki/Newton%27s_law_of_cooling>