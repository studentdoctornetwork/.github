# Repository Instructions

<!-- sdn-deployment-policy:v1 -->
## Shared deployment policy

Before deployment work, read [the shared SDN deployment policy](../sdn-harness/docs/sdn-deployment-policy.md).
Schools Database and other Git-managed applications must deploy with hosted
`git pull --ff-only`, after serving-path, source-drift, and reviewed release-SHA
checks. Do not copy or extract application source over a hosted checkout or use
file sync as a fallback. This supersedes conflicting older deployment notes.
Preserve XenForo Admin CP archive installation and native template workflows.
If the linked harness is absent, locate the approved sibling `sdn-harness`
checkout before proceeding. This rule does not authorize production access.
<!-- /sdn-deployment-policy -->

This repository controls the public Student Doctor Network GitHub organization
profile.

Before working here, read the shared SDN harness:

- `/Users/leeburnett/Developer/github.com/studentdoctornetwork/AGENTS.md`
- `/Users/leeburnett/Developer/github.com/studentdoctornetwork/docs/harness/README.md`

## Organization Identity

- The current legal organization name is `Student Doctor Network`, effective
  September 8, 2026. Use `The Student Doctor Network` as the public-facing brand
  name and `SDN` as the short name.
- Coastal Research Group, founded in 1983, is the originating organization from
  whose mission SDN grew.
- Do not describe HPSA as the current parent, publisher, operator, owner, or
  service provider. Preserve the former name only in dated history, exact legal
  records, legacy URLs, or technical identifiers that cannot yet be migrated
  safely.

## Publishing Boundary

- Treat `profile/README.md` as the GitHub organization profile and `README.md`
  as its repository-level mirror. Keep their public identity copy aligned.
- Keep public claims concise and verifiable. Link current products and support
  paths to `studentdoctor.net`.
- Do not mutate GitHub organization settings or other external profiles unless
  the operator explicitly approves that external change.

## Shared SDN guidance

Read `../sdn-harness/AGENTS.md` for shared product, Design 5, writing,
safety, and agent coordination rules. STARS owns taxonomy and search contracts.

<!-- sdn-1password-policy:v1 -->
## Shared 1Password access policy

Before credential-dependent work, read the [shared SDN policy](../sdn-harness/docs/1password-agent-access.md)
and use the [bounded diagnostic](../1password-manager/scripts/diagnose-1password.py).
Existing task and environment authorization boundaries remain in force.
<!-- /sdn-1password-policy -->
