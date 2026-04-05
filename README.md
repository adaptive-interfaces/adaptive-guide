# adaptive-guide

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Markdown Lint](https://github.com/adaptive-interfaces/adaptive-guide/actions/workflows/md-lint.yml/badge.svg?branch=main)](https://github.com/adaptive-interfaces/adaptive-guide/actions/workflows/md-lint.yml)
[![Check Links](https://github.com/adaptive-interfaces/adaptive-guide/actions/workflows/links.yml/badge.svg?branch=main)](https://github.com/adaptive-interfaces/adaptive-guide/actions/workflows/links.yml)
[![Dependabot](https://img.shields.io/badge/Dependabot-enabled-brightgreen.svg)](https://github.com/adaptive-interfaces/adaptive-guide/security)

> How to Structure Agent Context for Team-Conforming Output

[Adaptive Interfaces](https://github.com/adaptive-interfaces).

Engineering discipline guide for designing agent context for team-conforming output.

This repository contains the core guide for
writing priors, structuring agent context, and
evaluating agent output in engineering environments.

## Guide

The [GUIDE.md](GUIDE.md) explains:

- why agent output is often correct but not team-aligned
- how to write actionable priors
- the three-prior framework:
  - ACS (behavior)
  - ATD (tools)
  - AO (team conventions)
- how to evaluate agent output

This is not a tutorial.
It is a discipline for configuring agents to operate correctly within real systems.

## Actions

Use this repository as follows:

1. Read the guide
   - GUIDE.md

2. Load foundational behavior
   - adaptive-conformance-specification

3. Capture team context
   - adaptive-onboarding

4. Map tool capabilities (if applicable)
   - adaptive-tool-discovery

5. Run a real task and evaluate output
   - Update priors where output does not match team conventions.

6. Iterate until output would pass code review without style or structure corrections.

## Developer

```shell
npm install -g markdownlint-cli
npm update -g markdownlint-cli
markdownlint "**/*.md"
```

## Annotations

[ANNOTATIONS.md](./ANNOTATIONS.md)

## Manifest

[MANIFEST.toml](./MANIFEST.toml)

- kind: guide
- role: defines how to write and evaluate priors
- provides: GUIDE.md, CITATION.cff, LICENSE, README.md, MANIFEST.toml
- depends (optional): ACS, ATD, AO, sensor-testing example

The guide defines the discipline.
Other repositories implement the skills.

## Citation

[CITATION.cff](./CITATION.cff)

## License

[MIT](./LICENSE)
