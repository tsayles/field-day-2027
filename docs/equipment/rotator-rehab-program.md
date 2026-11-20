# Off-Season Rotator Rehabilitation Program

**Purpose:** Restore reliable, repairable rotator systems before Field Day 2027.
This is the program and verification plan for [issue #6](https://github.com/tsayles/field-day-2027/issues/6).
See the [December 1, 2026 M&K Board approval deck](rotator-rehab-board-approval-2026-12-01.odp).
Record component findings, repairs, and completed test results under
[issue #39](https://github.com/tsayles/field-day-2027/issues/39); use the early
trailer workday in [issue #23](https://github.com/tsayles/field-day-2027/issues/23)
for any work that requires site equipment.

## Known starting point

At Field Day 2026, all three rotators reportedly failed; the 20-meter antenna
had to be turned by hand. The after-action review also noted fragile cable
connectors and inconsistent controller-side terminations (ring terminals,
spade terminals, and bare wire at screws). Rotator models, cable pinouts,
failure causes, and electrical ratings have not yet been recorded here. Treat
these as inspection items, not assumptions.

## Work sequence

1. **Inventory and make safe.** Assign each rotator a unique ID and record its
   antenna/station, manufacturer, model, serial number, controller, manual, and
   cable assemblies. Disconnect power before inspecting or changing
   terminations. Follow each manufacturer's service instructions; do not work
   aloft as part of this bench program.
2. **Inspect each interface end to end.** Trace and label every conductor from
   controller to rotator. Record connector type, pin/terminal assignment,
   wire gauge, cable length, strain relief, and any adapter or splice. Check
   plugs, sockets, terminal blocks, crimps, insulation, corrosion, moisture
   protection, and cable jacket for looseness, damage, or evidence of heating.
3. **Test and repair.** Use the manufacturer's procedure to check controller
   output, cable continuity and shorts, motor operation, direction, position
   indication, and limit/stop behavior. Log the symptom and evidence before
   repair; link each repair to the affected component and repeat the failed
   test afterward. Do not energize a cable with an unknown pinout.
4. **Standardize repair interfaces and prepare spares.** Apply the decision
   below after recording the actual ratings and pinouts. Label both ends of
   every finished cable and adapter.
5. **Run the complete functional checkout.** Test each assembled system,
   including its controller, production-length cable, rotator, and intended
   antenna load where practical. Record the results and release decision below
   before packing for transport.

## Inspection checklist

Complete one checklist for each rotator ID in the issue #39 execution record.

- [ ] System, controller, manual, cable, and antenna assignment identified.
- [ ] Cable route and every connector, splice, and adapter documented.
- [ ] Pinout verified against the manual or measured safely and recorded at
      both ends; no conductor identity inferred from color alone.
- [ ] Connector contacts and terminals checked for looseness, corrosion,
      contamination, bent pins, heat damage, and inadequate sealing.
- [ ] Cable checked for cuts, crushed sections, abrasion, brittle insulation,
      poor crimps, and inadequate strain relief.
- [ ] Continuity and conductor-to-conductor / conductor-to-shield isolation
      checked with equipment disconnected, as appropriate to the system.
- [ ] Controller, motor, indication, direction, and stops assessed per the
      manufacturer's procedure.
- [ ] Defects, measurements, photos, repairs, parts, and retest outcomes
      recorded and linked to this rotator ID.

## Connector and termination decision

**Standardize the field-repair cable interface, not the equipment's OEM
terminals.** Retain each rotator and controller's manufacturer-specified
termination. For replacement or repair cable assemblies, use one common,
keyed, locking, weather-resistant connector family across the systems only
after verifying that an available configuration meets each system's measured
conductor count, wire size, voltage, and continuous / motor-start current.
Use labeled, system-specific adapter tails where pin assignments or OEM
interfaces differ; document the pin map at both ends. Do not directly mate
different systems merely because their plugs fit.

This is a repairability-first standard: a damaged field cable can be swapped
without re-terminating fragile wires at the controller, and keyed locking
connections resist accidental separation and mis-mating. A generic connector
part number is intentionally not selected before inspection because the
rotator models, pinouts, and current requirements are not yet known. The
equipment lead must record the selected family and part numbers here or in the
issue #39 record after confirming ratings and fit. If one family cannot safely
serve all systems, document the exception rather than undersizing or forcing
compatibility.

For screw-clamp OEM terminals, use correctly sized, properly crimped ferrules
only where permitted by the terminal manufacturer. Use the specified lug or
terminal on other connection types; do not leave bare, unsupported strands.
Provide cable strain relief and protective caps. Apply contact lubricant only
when compatible with the connector manufacturer's instructions.

## Spare connector and cable kit

Prepare, label, and bench-test before packing:

- [ ] One complete, tested spare cable assembly per rotator system, sized and
      long enough for the planned deployment route.
- [ ] At least one mating connector pair per system, with contacts and approved
      backshells/strain relief; include extra contacts if field-replaceable.
- [ ] Any system-specific adapter tails, each labeled with rotator ID,
      controller end, and pinout.
- [ ] Correct terminals, seals, boots, caps, and compatible crimp tooling for
      the selected connector and OEM terminations.
- [ ] Printed pinout and cable-length labels, plus the system inventory and
      test records.

Keep spares protected from moisture and dirt. Do not count untested or
unidentified cable assemblies as ready spares.

## Pre-transport functional verification

Run the following on each final configuration and record date, operator,
equipment IDs, cable/antenna load, observations, and pass/fail in issue #39.
Use the manufacturer's operating limits and procedures; stop on abnormal
noise, heating, binding, erratic indication, or unexpected movement.

- [ ] Inspect and secure the assembled connectors, strain relief, and cable
      route; confirm the correct labeled controller, cable, and rotator are
      paired.
- [ ] Confirm pinout and cable continuity/isolation before connecting power.
- [ ] Power up and check controller indications and normal operation.
- [ ] Command clockwise and counterclockwise movement; verify actual antenna
      movement agrees with controller indication and direction labels.
- [ ] Sweep the usable range and verify smooth movement and manufacturer
      limit/stop behavior without forcing a hard stop.
- [ ] Test with the production cable length and intended antenna load where
      practicable; note any load or setup differences from deployment.
- [ ] Power down, inspect connectors and cable again, and confirm the system
      remains ready after reassembly.
- [ ] Repeat applicable checks with each spare cable and adapter.
- [ ] Mark the system **PASS / REPAIR REQUIRED / NOT TESTED**. Pack only systems
      marked PASS for operational use; separately label and isolate any
      failed or untested equipment.

### Results record

Duplicate this row per system in issue #39; attach readings, photographs, and
repair details there rather than overwriting prior results.

| Rotator ID / station | Controller + model | Cable / connector set | Inspection & repair record | Full-system test (date / operator) | Result / transport disposition |
|---|---|---|---|---|---|
| TBD | TBD | TBD | Pending | Pending | Not tested |

## Ownership and readiness

Tom Sayles (KE4HET) leads the inventory, connector selection, donated parts,
work coordination, and records. Recruit a second person to independently
check pin maps and final pairing. Parts and labor are donated; no club funds
are requested. If donated resources do not cover the planned scope, return to
the Board before incurring any cost. Close the program only when each deployed
system and spare has a recorded result and all failed or untested equipment is
clearly excluded from the ready-to-deploy inventory.
