# Repo intent — azurelocal-vmware-migration

**End-to-end runbooks and tooling for migrating VMware vSphere workloads to Azure Local — assessment, conversion, cutover, post-migration validation.**

## What this repo is

End-to-end runbooks and tooling for migrating VMware vSphere workloads to Azure Local — assessment, conversion, cutover, post-migration validation. Per its own README: **under active development** — scripts, templates,
and automation are not guaranteed to work yet; expect breaking changes.

## Shape

- `src/`, `scripts/`, `config/`, `tests/`, `docs/` — standard AzureLocal toolkit
  layout (matches the sibling repos in this org)
- Full documentation published separately at
  `https://azurelocal.github.io/azurelocal-vmware-migration/`

## How it relates to other repos

- Part of the AzureLocal org's toolkit family — see `azurelocal.github.io` for the
  full solution catalog and `azurelocal-toolkit` for the shared automation patterns
  (Terraform+PowerShell, Terraform+Ansible, Ansible-only) these tools are built on

## Status

Active, early — README explicitly warns not to trust this yet in production.
