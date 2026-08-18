# OpenPLC Practice — plcIOsim Problems

Working through the practice problems from [plcIOsim](https://plciosim.com/problems), a browser-based PLC I/O simulator for ladder logic and industrial automation training. Each problem is solved in **OpenPLC**, twice: once in Ladder Logic (LD) and once in Structured Text (ST).

## Goals

- Build fluency in the two most common IEC 61131-3 languages
- Practice translating the same control logic between graphical and text-based representations
- Apply consistent I/O naming using ISA-5.1 instrument tag conventions (e.g. `HS-101`, `LSH-201`, `XV-301`)

## Repository Structure

Each problem gets its own numbered folder containing both implementations:

```
01_simpleLamp/
├── ladder/          # Ladder Logic (LD) solution
└── structuredtext/  # Structured Text (ST) solution
02_.../
├── ladder/
└── structuredtext/
...
```

Each problem folder also includes a short README with a link to the original problem and a brief description of the control requirements.

## Tools

- [OpenPLC](https://autonomylogic.com/) — open-source PLC runtime and editor
- [plcIOsim](https://plciosim.com/) — simulated I/O scenes for testing the logic

## Approach

1. Read the problem and define the I/O list with ISA-5.1 tag names
2. Solve in Ladder Logic first
3. Re-implement the same logic in Structured Text
4. Verify both against the simulated I/O scene