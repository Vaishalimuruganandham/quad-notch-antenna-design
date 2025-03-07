# Design and Implementation of Quad Notch UWB Antenna

## Overview
This project focuses on designing a **Quad Notch Ultra-Wideband (UWB) Antenna** with selective frequency rejection to minimize interference in wireless communication. The antenna is designed using a combination of geometric structures and simulated in **HFSS (High-Frequency Structure Simulator)** to evaluate its performance.

## Objectives
- Develop a **UWB antenna** that operates within the **3.1 GHz to 10.6 GHz** range.
- Introduce **four notch bands** to reject specific frequencies and minimize interference.
- Simulate and optimize the design using **HFSS**.
- Analyze radiation patterns, gain, and impedance characteristics.

## Key Features
- **Ultra-Wideband (UWB) Coverage**: Efficient radiation over a broad frequency range.
- **Notch Filtering**: Uses **U-shaped slits, mushroom structures, rectangular slots, and split-ring resonators** to create frequency stop bands at:
  - **3.7 – 4.2 GHz** (C-band)
  - **5.15 – 5.35 GHz** (WLAN1 band)
  - **5.725 – 5.825 GHz** (WLAN2 band)
  - **8.025 – 8.4 GHz** (X-band)
- **Compact Size**: 41.5 x 32 mm dimensions with a **partially tapered ground plane**.
- **Applications**: Medical imaging, military radar systems, and commercial UWB applications.

## Project Structure
```
|-- docs/               # Documentation and reports
|-- simulations/        # HFSS simulation files
|-- designs/            # Antenna structure and CAD models
|-- results/            # Plots and analysis of performance
|-- README.md           # Project documentation
```

## Tools & Technologies
- **Ansys HFSS** – Electromagnetic simulation
- **MATLAB/Python** – Data analysis and visualization
- **Microstrip Patch Antenna Design** – CPW-fed UWB antenna modeling

## Simulation & Testing
1. **Antenna Design:**
   - Created a **coplanar waveguide-fed UWB antenna**.
   - Integrated four notch structures to selectively filter out unwanted frequencies.
2. **Simulation in HFSS:**
   - **VSWR, S-parameters, and radiation patterns** analyzed.
   - Verified the notch band effectiveness.
3. **Fabrication & Testing:**
   - Prototyped and measured performance.
   - Compared **simulated vs. measured** results.

## Results
- The antenna achieved a **VSWR ≤ 2** across the operating range.
- The four notch bands effectively suppressed interference frequencies.
- The measured and simulated results closely aligned.

## Future Enhancements
- Improve notch bandwidth selectivity.
- Explore reconfigurable notches using **varactor diodes**.
- Develop a real-world prototype for commercial applications.

## Contributors
- **Vaishali M**  
- **Sheereen Nisma M**  
- **Gowtham Kumar Y**  

## License
This project is open-source under the **MIT License**.

