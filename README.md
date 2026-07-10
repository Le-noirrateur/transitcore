# TransitCore

> A modern railway transportation framework for Minecraft NeoForge.

TransitCore is an open-source framework designed to provide a complete railway transportation engine for Minecraft.

Unlike traditional railway mods, TransitCore separates the simulation engine from its content. The core framework focuses on providing the technology while vehicles, infrastructure, signaling systems and other assets are distributed through independent addons.

The objective of the project is to provide a realistic and extensible platform capable of simulating:

- Heavy Rail
- High-Speed Rail
- Metro Systems
- Tramways
- Light Rail
- Fictional Railway Networks

---

# Project Goals

TransitCore combines ideas inspired by several well-known railway projects while introducing a completely modern architecture.

## Track System

- Node-based track placement.
- Smooth curves and slopes.
- Fully editable tracks after placement.
- Switches and crossings.
- Multiple track types.
- Configurable or automatically calculated speed limits.

## Rolling Stock

- Realistic driving mechanics.
- Manual and automatic train operation.
- Route system.
- NPC drivers.
- Multiple-unit support.
- Accurate dimensions.
- Proper collision boxes.
- Animated doors.
- Lighting.
- Sounds.
- Pantographs.
- Cab controls.

## Signaling

TransitCore provides a complete signaling framework.

The objective is not only to display railway signals, but also to simulate an entire railway operation environment.

Planned systems include:

- Signal blocks
- Interlocking
- Route locking
- Occupancy detection
- Dispatch panels
- Signal boxes
- Country-specific signaling through addons

## Catenary

- Fully 3D catenary system.
- Automatic wire generation.
- Curves.
- Slopes.
- Multiple support types.
- Country-specific catenary addons.

---

# Addon System

TransitCore has been designed from the beginning as an addon-based framework.

The core mod only contains the engine.

Everything else can be added through independent addons:

- Vehicles
- Signals
- Tracks
- Stations
- Decorations
- Sounds
- Animations
- Railway infrastructure

---

# Repository Structure

This repository only contains the TransitCore engine.

Example addon repositories may be published separately.

```
TransitCore
│
├── Core
├── API
├── Track Engine
├── Rolling Stock Engine
├── Signaling
├── Catenary
├── Networking
└── Rendering
```

---

# Branches

The repository uses multiple branches.

## main

The **main** branch is **not used for development**.

It only contains stable information about the project, documentation and released versions.

Development never happens directly on this branch.

## Neoforge

Primary development branch.

All current development happens here.

## Fabric

Reserved for future Fabric support.

## Forge

Reserved for future Forge support.

---

# Issues

Issues are used exclusively for:

- Bugs
- Crashes
- Mod incompatibilities

Feature requests may be opened only when they follow the project vision.

Before opening a report:

- Search existing issues.
- Read the issue guidelines.
- Provide every required information.

Reports without logs or reproduction steps may be closed without investigation.

---

# Labels

TransitCore uses labels to organize reports.

General labels:

- Bug
- Crash
- Fixed
- Incompatibility
- On going
- On hold
- Wontfix
- Off-topic
- Not-applicable

Version labels:

- MC 1.21.x
- MC 26.x
- ...

Loader labels:

- NeoForge
- Forge
- Fabric

Labels are assigned by the development team.

---

# Contributing

Contributions are welcome.

Please read CONTRIBUTING.md before submitting pull requests.

---

# License

TransitCore is licensed under the GNU LGPL v3.
