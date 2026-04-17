Analog Optical Signal Classifier (Astronomical)
High-precision signal chain for real-time celestial event categorization.
Core Specs

    Precision Hardware: Built with OP177 op-amps for ultra-low offset.
    Dynamic Range: Logarithmic compression to prevent saturation from high-intensity bursts.
    Temporal Filters: Parallel Differentiator (
    ) and Integrator (
    ) paths.

The Signal Chain

    Input: Dual TIA + Differential Amp for Common-Mode Rejection (CMRR) of light pollution.
    Logic: Dual Schmitt Triggers convert analog features into discrete pulses.
    Output: Summing Amp generates a 4-level classification voltage:
        4V: Fast (Meteors, Flares)
        2V: Sustained (Transits, Variable Stars)
        6V: Complex (Meteors with persistent trains)
    Count: 555 Timer stage for event frequency analysis.

Repository Contents

    Schematics: LTspice .asc files.
    Data: Waveform plots for TIAs, Log-Amp, and Final Summing stage.
    Report: Full mathematical derivations and flowcharts.

Jennita Rachel A | IIT Guwahati
