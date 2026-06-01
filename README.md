# Hydraulic Circuit Designer

An interactive, offline simulator for learning and exploring hydraulic system
design. It runs as a single, self-contained HTML file in any modern browser —
just double-click it. (An internet connection is only needed the first time you
open it, so it can load its display libraries.)

It is built for **anyone learning to reason about hydraulic systems** — from a
curious beginner, to vocational and maintenance technicians, to practicing
engineers — and it scales with the user through selectable learning levels.

## Where it applies

The same fluid-power fundamentals run across many fields, and the tool speaks to
all of them: mobile and off-highway equipment, industrial power units and
presses, construction and material-handling machinery, manufacturing automation,
and agricultural machinery. Wherever a cylinder or motor moves a load, the
physics is the same.

## What it does

The tool is **problem-first**: you start from a real task and it sizes the
system, then lets you explore how the design behaves.

- **Design mode** — enter the task (load, mount angle, target speed, max
  pressure) and the tool sizes the cylinder bore, pump, and a standard-frame
  electric motor, explaining *why* each component was chosen.
- **Analyze mode** — enter a pump, or pick a power source, and see the resulting
  speeds, pressures, and behavior.
- **Power-source presets** — representative relief-pressure and flow values for
  common power units (industrial packs, mobile systems, tractor remotes) for the
  case where the user already has a machine in hand.
- **Animated schematic** — an ISO-style circuit that tilts the cylinder to the
  mount angle, shows extend/retract speeds and pressures, live force vectors at
  the load, and safety alerts (cavitation, stall, over-velocity, overheat).
- **Design Coach** — a transparent, rule-based review of the current design
  (not an AI chatbot): it flags issues and asks the questions an instructor
  would, with no risk of hallucinated numbers.
- **Guide & Physics tabs** — walk through the design process, the assumptions
  behind each value, and the underlying equations.

Units are Imperial (psi, lbf, in, GPM).

## How to use

1. Download `hydraulic-designer.html`.
2. Double-click it to open in your browser.
3. Start on the **Guide** tab, then enter your task.

## Status

Active development. This is an educational tool; component selections are
teaching approximations and should be verified against manufacturer data and the
relevant standards before any real-world build.

## Author

Ali Bulent Koc

## License

To be added.
