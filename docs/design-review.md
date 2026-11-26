# IMAX95 design review checklist

Status: proposed design; not a validated board.

- Processor: confirm exact ordering code, package and pinout against manufacturer documentation.
- Memory: verify LPDDR4X device organization, channel/rank mapping, voltage domains, termination and controller support.
- Power: confirm rail requirements, transient current, sequencer configuration, power-good and reset timing.
- Clock/reset: verify oscillator requirements, boot straps and reset behavior.
- Interfaces: review PCIe, USB, Ethernet, MIPI CSI/DSI and display bridge lane assignment and voltage requirements.
- PCB: derive stackup, impedance, length constraints and return paths; review BGA escape and manufacturing tolerances.
- Mechanical: confirm enclosure, mounting holes, connector positions and thermal solution.
- Manufacturing: check footprints, BOM lifecycle, assembly drawings and test access.

## Bring-up gates

1. Inspect unpowered assembly and verify resistance to ground.
2. Apply current-limited power; observe rails and sequencing.
3. Verify clocks, reset, boot configuration and serial diagnostics.
4. Validate memory before enabling peripherals.
5. Exercise interfaces individually, document failures and retest after changes.

No fixed voltage, timing or routing limit is asserted without the relevant device documentation.
