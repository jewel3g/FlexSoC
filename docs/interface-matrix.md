# IMAX95 proposed interface matrix

| Function | Candidate interface | Verification required |
|---|---|---|
| RAM | LPDDR4X | Topology, rank and channel mapping, timing |
| Boot | Serial NOR / boot media | Boot ROM support, voltage, ordering code |
| Storage | PCIe NVMe | Lane mapping, clocks, reset, power |
| Network | Ethernet | MAC/PHY mode, reference clock, magnetics |
| USB | USB-C | Role, power delivery requirements, ESD, routing |
| Wireless | M.2 expansion | Key, interface mapping, supply, antennas |
| Display | MIPI DSI / bridge options | Bandwidth, panel pinout, AUX/HPD, backlight |
| Camera | MIPI CSI-2 | Lane mapping, clocks, sensor control |
| Audio | Codec / amplifier | Digital interface, analog supplies, output load |
| Debug | Serial console / debug interface | Voltage and access |
 
All entries are design candidates. Confirm actual processor capability, multiplexing and board implementation before fabrication.
