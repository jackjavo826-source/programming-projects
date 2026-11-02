# Programming Projects

Independent programming work focused on clear implementations, debugging, and reproducible behavior.

**Status: documentation stage.** This repository establishes the scope and quality criteria for future source releases. It currently contains no executable project or course submission.

## Project categories

| Category | Focus | Evidence to publish |
| --- | --- | --- |
| C fundamentals | Pointers, arrays, strings, and dynamic memory | Ownership assumptions, edge cases, and checked example runs |
| Data structures | Representation, invariants, and operations | Behavioral tests and documented time/space tradeoffs |
| Algorithms | Correctness and complexity | Inputs, expected outputs, analysis, and reproducible measurements |
| Utilities | Small tools that solve a concrete problem | Build/run steps, sample inputs, and failure behavior |

## Development expectations

Prefer small programs with explicit inputs, readable interfaces, and useful diagnostics. Separate reusable logic from demonstration code when it improves clarity.

For C projects, check allocation failures, array bounds, input validity, and resource cleanup. Use compiler warnings and appropriate runtime analysis tools; report their actual results rather than implying that compilation proves correctness.

## Reproducibility record

Every release should identify:

- Compiler/toolchain and operating system
- Exact build and run commands
- Representative inputs and expected outputs
- Edge cases and error handling
- Tests performed and their observed results
- Known limitations and the tested commit

Performance claims should state input sizes, measurement method, machine context, and whether the claim is analytical or empirical.

## Coursework boundary

Publish independent examples or work explicitly permitted for public sharing. Restricted assignments, answer keys, instructor materials, private test cases, and other students' work do not belong here.

See the [portfolio documentation standards](https://github.com/jackjavo826-source/jackjavo826-source/blob/main/PORTFOLIO_STANDARDS.md).
