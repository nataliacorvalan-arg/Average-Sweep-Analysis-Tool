# Average-Sweep-Analysis-Tool – Quick Start Guide (Version 1.0.0)

This Python script performs automated sweep extraction, frequency-domain Gaussian lowpass filtering, and computation of the mean waveform across all sweeps contained in one or multiple ABF files within a selected directory.

System Requirements:
• Windows operating system
• No Python installation required

How to Run:

1. Place the executable in a folder containing .abf files.
2. Double-click the executable.
3. Enter:
   - Gaussian cutoff frequency (Hz)
   - Channel number to analyze
4. Output files will be generated in the same directory.

Output Files:
• average_sweep.txt
• individual_sweeps_raw.txt
• individual_sweeps_filtered.txt
• comparative_average_sweep.png

Notes
• The working directory must contain at least one .abf file.
• The program processes all sweeps across all ABF files in the folder.
• The program assumes consistent sampling rate and sweep length across files.

For citation and technical details, see the Technical Documentation .txt file.

Author: Natalia Andrea Corvalán
CONICET - Córdoba, Argentina
