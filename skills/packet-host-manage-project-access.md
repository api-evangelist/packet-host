---
name: Manage a project and its SSH access
description: Create a project, register SSH keys, and invite members in Equinix Metal (formerly Packet).
api: openapi/packet-host-metal-openapi-original.yml
operations: [createProject, findProjectById, createProjectSSHKey, findProjectSSHKeys, createProjectInvitation, deleteProject]
---

# Manage a project and its SSH access (Packet / Equinix Metal)

> Note: Equinix Metal was sunset on 2026-06-30. These steps document the
> historical flow.

## Authentication
Send `X-Auth-Token: <API_KEY>` on every request. Base URL:
`https://api.equinix.com/metal/v1`.

## Steps
1. **Create a project** — `createProject` (`POST /projects`) with a `name`
   (and optional `organization_id`).
2. **Confirm it** — `findProjectById` (`GET /projects/{id}`).
3. **Register an SSH key** — `createProjectSSHKey`
   (`POST /projects/{id}/ssh-keys`) with `label` and `key`; list with
   `findProjectSSHKeys` (`GET /projects/{id}/ssh-keys`).
4. **Invite a member** — `createProjectInvitation`
   (`POST /projects/{project_id}/invitations`) with the invitee `invitee`
   email and `roles`.
5. **Clean up** — `deleteProject` (`DELETE /projects/{id}`).

## Conventions
- Auth model: User vs Project API keys (see
  `authentication/packet-host-authentication.yml`).
- Errors: JSON `error` / `errors` envelope; `422` for validation failures.
- Pagination: `page` / `per_page` (see
  `conventions/packet-host-conventions.yml`).
