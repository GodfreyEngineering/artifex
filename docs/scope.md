# Project scope

Artifex is intended to help people run repeatable software engineering workflows with coding
assistants. Its public implementation will be heavily generalised from Godfrey Engineering's
internal toolbox.

## Intended capabilities

- Project instructions with a provider-neutral source and explicit adapters where assistants use
  different formats.
- Reusable workflows for planning, implementation, review, verification and handoff.
- Project configuration that declares the checks and approval boundaries a team chooses to use.
- Clear, inspectable results from checks, including failed and unavailable checks.

These capabilities are planned. The repository currently contains documentation and identity assets.

## Generalisation requirements

Every included component must work from a fresh clone in a temporary workspace without access to the
originating organisation's machines, accounts or private repositories. Paths, organisation names,
provider choices and optional integrations must be explicit configuration where they affect
behaviour.

Select components individually. Review their dependencies, retained notices and licence
compatibility before inclusion. Use synthetic examples and test fixtures. Keep the public Git
history independent of the internal repository.

Credentials, private operational records, customer material, internal prompts containing
confidential context and organisation-specific infrastructure do not belong in this repository.
Optional external services must have documented configuration and must remain inactive until the
user enables them.

## First implementation boundary

The first implementation should provide one complete workflow: initialise a project with shared
instructions, use a supported assistant adapter, run declared project checks and write a portable
handoff. Choose its interfaces and toolchain in a reviewed design proposal before implementation.

Installer behaviour, supported providers and platforms, update policy and any background processes
remain open design decisions. Do not claim support for them until they have been tested.
