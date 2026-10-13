# Roadmap

Artifex is at the planning stage. The repository uses the MIT licence; there is no installable
release.

## 1. Define the portable workflow

Specify the project configuration, instruction source, provider-adapter boundary and handoff format.
Select the first supported platform and provider against current official documentation.

Acceptance: a reviewed design, synthetic example project and explicit checks for the complete
initialisation-to-handoff workflow.

## 2. Generalise one complete slice

Select the minimum reusable components needed for the first workflow. Remove organisation-specific
assumptions, preserve required third-party notices and implement the agreed configuration
boundaries.

Acceptance: the workflow passes in a clean temporary environment with no private configuration,
credentials or network services required by default.

## 3. Establish public verification

Add CI for the implemented contracts, exercise supported environments and review the distributable
files and Git history for unintended disclosure. Document installation, removal and failure recovery
against the tested behaviour.

Acceptance: a fresh user can follow the README and reproduce the checks. CI passes on the proposed
release commit, and its licence and disclosure reviews are recorded.

## 4. Publish an installable alpha

Publish a versioned release with its supported scope and limitations. Expand providers and workflows
through separate tested slices.

Acceptance: the released artefact is reproducible from its tag and the documented installation and
removal procedures pass in an isolated environment.
