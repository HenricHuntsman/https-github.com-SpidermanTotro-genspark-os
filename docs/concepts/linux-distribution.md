# Genspark OS Concept

A preserved project idea for an AI-oriented Linux distribution.

**Stage: planning only.** This default branch contains a README, not an operating system implementation. No kernel/userspace assembly, bootloader configuration, ISO, installer, package repository or boot-test evidence is present here.

## What remains

Define requirements and choose a base distribution; create a reproducible image build; boot it in a VM; test installation, updates, rollback and supported hardware; preserve applicable licences. These are proposed milestones, not implemented features.

For an existing application workspace, see [AgentFoundry Workspace](https://github.com/HenricHuntsman/AgentFoundry-instantly). It is a separate application project, not evidence this OS concept has been built.

The historical repository slug remains unchanged. Updated 18 October 2026.

## Acceptance milestones

| Milestone | Evidence required | Current result |
| --- | --- | --- |
| Requirements | Chosen base, supported architecture and intended applications | Open |
| Image build | Versioned build inputs, successful log and image checksum | Absent |
| First boot | VM boot log and usable desktop/input | Unverified |
| Installation | Disposable-disk install and reboot | Unverified |
| Updates/recovery | Successful update and recovery exercise | Unverified |

AgentFoundry is a possible application to evaluate after its own Linux installation tests. Vitruvian is a separate upstream-derived OS fork, not an implemented Genspark backend. Reusing either needs an explicit architecture decision and licence review. No application source was copied or merged by this organisation pass.
