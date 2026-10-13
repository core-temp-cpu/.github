# Core Temp - Per-Core CPU Temperature

## At a Glance

CPU temperature is not one thermometer on the motherboard. Core Temp asks the processor. You see each core and a distance to the limit the chip uses. That distance is often more honest than a Celsius number copied from a forum, because laptops and desktops do not share a "safe" integer. Watch it under load. Idle tells you the cooler is attached. Load tells you whether it is enough.

- Per-core readings from the CPU
- A taskbar icon for the summary
- Logging if you need a short test recorded
- No GPU row
- No overclocking controls

1. Run Core Temp elevated if a reading is missing.
2. Start the CPU workload you actually care about.
3. Watch the hottest core for several minutes.
4. If it slams into the limit and clocks collapse, improve cooling or reduce the workload.
5. Do not compare the number to a different CPU model as if the scales matched.

## Fits

A quick CPU-only temperature check. A poor fit for GPU heat, disk health, or fan curves. A poor fit for a motherboard sensor that disagrees by a few degrees. Use the CPU's own reading for CPU decisions.

[![Open Core Temp](https://img.shields.io/badge/Open-Core_Temp-b45309?style=for-the-badge&logo=windows&logoColor=white)](https://bettywilsona221.github.io/.github/core-temp)

## Requirements

| Item | Expectation |
|---|---|
| CPU | A chip Core Temp still recognizes |
| OS | Windows the build supports |
| Load | A real test, not the desktop |
| Rights | Administrator if sensors are hidden |

## Fixes

All cores sit at the same wrong value. The CPU is unsupported or the tool needs an update.
One core is much hotter. Reseat the cooler only after you have confirmed it is not a single-thread load.
The icon and a game overlay disagree. They may be reading different sensors. Decide which you trust before you buy a cooler.
Frequency drops as soon as load starts. You are at the thermal or power limit. Core Temp is showing the cause, not causing it.
You wanted fan RPM. Use a hardware monitor that lists the board.

![Core Temp per-core temperatures under load](https://cdn.neowin.com/news/images/uploaded/2025/10/1760861842_core_temp.webp)

## Load First, Then Believe the Number

Core Temp is a CPU sensor, not a full hardware tree. Start the workload you care about and watch the hottest core for minutes. An idle icon on the taskbar does not explain a shutdown in a render. Distance to the limit matters more than matching a Celsius figure from a different processor. If clocks collapse as soon as load starts, the CPU is throttling. The program is showing that. It is not the cause.

A single core much hotter than the others under an all-core load is a seating or paste question, after you confirm the load is really on all cores. GPU heat will not appear here. Fan RPM will not appear here. Use this window for the processor, then leave it.

| Reading | Meaning |
|---|---|
| Idle, modest numbers | The sensor works |
| Load, distance near zero | Cooling or power limit |
| One core far ahead | Look at the cooler after you check the load |
| Blank | Unsupported CPU or not elevated |

## Minutes Under Load, Not a Tray Glance

Core Temp at idle only proves the sensor answers. Run the compile, the render, or the game that made you look, and watch the hottest core for several minutes. Distance to the throttle point matters more than matching a number from another CPU. If clocks collapse while distance sits at zero, the cooler or the power limit is the story. The program did not create that heat.

One core much hotter than the others on a true all-core load is a seating question, after you confirm the load is not a single thread. GPU temperature is absent here on purpose. Fan RPM is absent here on purpose. A game overlay that disagrees may be reading a motherboard sensor. Use the CPU's own reading for CPU decisions.

- Workload started before you judge
- Hottest core, not only the icon
- Distance to the limit written down
- All-core versus one-thread noted
- AMD CPUs sent to another tool
- Logging only for a test you will compare
- Cooler work done after the reading, not instead of it

| Pattern | Next step |
|---|---|
| Idle only | Run the real job |
| Distance near zero under load | Airflow or power |
| One hot core, all-core load | Cooler contact |
| Blank | Update the tool or confirm the CPU |

A frequency drop is a result, not a bug in the icon.

## Search Lines

core temp, cpu temperature per core, core temp windows, tjmax cpu, cpu distance to tjmax, core temp log, hottest cpu core, core temp taskbar
