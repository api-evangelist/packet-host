---
name: Provision a bare-metal device
description: Create and manage a bare-metal server in an Equinix Metal (formerly Packet) project.
api: openapi/packet-host-metal-openapi-original.yml
operations: [findProjects, findPlans, findMetros, findOperatingSystems, createDevice, findDeviceById, deleteDevice]
---

# Provision a bare-metal device (Packet / Equinix Metal)

> Note: Equinix Metal was sunset on 2026-06-30 and no longer permits new
> resource creation via the API. These steps document the historical flow.

## Authentication
All requests send the header `X-Auth-Token: <API_KEY>` (a User or Project API
key). Base URL: `https://api.equinix.com/metal/v1`.

## Steps
1. **Pick a project** — `findProjects` (`GET /projects`) and choose the project
   id you will deploy into.
2. **Choose a plan** — `findPlans` (`GET /plans`) to select a server plan
   (e.g. `c3.small.x86`).
3. **Choose a location** — `findMetros` (`GET /locations/metros`) for a metro
   code.
4. **Choose an OS** — `findOperatingSystems` (`GET /operating-systems`) for an
   `operating_system` slug.
5. **Create the device** — `createDevice`
   (`POST /projects/{id}/devices`) with `plan`, `metro`, `operating_system`,
   and `hostname` in the body.
6. **Poll status** — `findDeviceById` (`GET /devices/{id}`) until `state`
   becomes `active`.
7. **Tear down** — `deleteDevice` (`DELETE /devices/{id}`) when finished.

## Conventions
- Pagination: `page` / `per_page`; use `include` / `exclude` for sparse fields
  (see `conventions/packet-host-conventions.yml`).
- Errors: JSON envelope with `error` / `errors` (see
  `errors/packet-host-problem-types.yml`); handle `429` with backoff.
- No idempotency-key mechanism — do not blindly retry `createDevice`.
