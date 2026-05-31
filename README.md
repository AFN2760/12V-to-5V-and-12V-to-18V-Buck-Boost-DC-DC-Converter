# Design and Hardware Implementation of a 12V to 5V and 12V to 18V Buck-Boost DC-DC Converter

A power electronics project detailing the full analytical design, closed-loop simulation, and physical hardware deployment of an inverting buck-boost converter capable of both stepping down and stepping up an unregulated 12V DC rail.

## Engineering Specifications
- **Input Voltage:** Stable 12V DC nominal line.
- **Buck Output Channel:** Fixed 5V DC regulation path.
- **Boost Output Channel:** Fixed 18V DC amplification path.
- **Topologies Analyzed:** Classical switching structures using high-frequency switches, filtering inductors, low-ESR capacitors, and power diodes.

## Core Applications & Safety
- Sizing calculation criteria optimized for variable voltage integration paths like solar photovoltaic MPPT chargers or multi-cell lithium battery management circuits.
- Features active ripple minimization constraints designed to keep switching noise within tolerable bands.

## References
- *Power Electronics Devices, Circuits and Applications* (4th Edition) by Muhammad H. Rashid.
- *Power Electronics* by Daniel W. Hart.
- Texas Instruments / Analog Devices App Notes: *The Design of the Inverting Buck/Boost Converter Topology*.

## Project Authors (Section A1, Group 02)
- **Rejoun Rahi Rad** (2106003)
- **Md. Yeasir Alif** (2106011)
- **Abrar Fahim** (2106005)
- **Al Muktadir Khan** (2106012)

**Course:** Power Electronics Laboratory (EEE 316), Bangladesh University of Engineering and Technology (BUET).
