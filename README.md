# Packet Host

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Packet Host, Inc. (packet.com / api.packet.net) was a New York-based bare-metal cloud provider, backed by Battery Ventures, that let developers provision dedicated single-tenant servers on demand through a REST API, CLI, and Terraform. Equinix acquired Packet in 2020 and rebranded the service Equinix Metal, moving the API to api.equinix.com/metal/v1. Equinix Metal was fully retired: End-of-Sale was announced 2024-11-07 and the service was sunset 2026-06-30. This profile captures the Metal API surface (220 operations across 40 tags) and the Packet-to-Equinix-Metal lineage.

**Areas:** Company · Bare Metal · Cloud Infrastructure · Infrastructure-as-a-Service · Servers · Compute · Provisioning · Equinix Metal · Retired

## Packet Host on APIs.io

Everything profiled for Packet Host is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/packet-host/](https://apis.io/providers/packet-host/)** — or go straight to one of the APIs or properties below.

### APIs (40)

- [Packet Host Authentication API](https://apis.io/apis/packet-host/packet-host-authentication-api/) — Nearly all of the endpoints in the API require authentication. Authentication is performed by providing an authentication token (interchangeably referred to…
- [Packet Host Batches API](https://apis.io/apis/packet-host/packet-host-batches-api/) — Manage device batches. See project endpoints to list batches for a particular project. Check out the product docs to learn more about [Batch…
- [Packet Host BGP API](https://apis.io/apis/packet-host/packet-host-bgp-api/) — Manage BGP configs and sessions. See device endpoints to create and list BGP sessions for a particular device. Check out the product docs to learn more…
- [Packet Host Capacity API](https://apis.io/apis/packet-host/packet-host-capacity-api/) — Capacity Management. Check out the product docs to learn more about [Capacity](https://metal.equinix.com/developers/docs/locations/capacity/).
- [Packet Host Console Log Details API](https://apis.io/apis/packet-host/packet-host-console-log-details-api/) — Console Log Details. Notice: This is a test feature currently under active development, and only available to certain users. Please contact Customer Success…
- [Packet Host Devices API](https://apis.io/apis/packet-host/packet-host-devices-api/) — Device Management. Check out the product docs to learn more about [Server Devices](https://metal.equinix.com/developers/docs/servers/).
- [Packet Host Emails API](https://apis.io/apis/packet-host/packet-host-emails-api/) — Email Management
- [Packet Host Events API](https://apis.io/apis/packet-host/packet-host-events-api/) — Event Management
- [Packet Host Facilities API](https://apis.io/apis/packet-host/packet-host-facilities-api/) — Facility Management. Check out the product docs to learn more about [Facilities](https://metal.equinix.com/developers/docs/locations/).
- [Packet Host Firmware Sets API](https://apis.io/apis/packet-host/packet-host-firmware-sets-api/) — Firmware Sets Management. Notice: Firmware Sets are a test feature currently under active development, and only available to certain users. Please contact…
- [Packet Host HardwareReservations API](https://apis.io/apis/packet-host/packet-host-hardwarereservations-api/) — Hardware Reservation Management. Check out the product docs to learn more about [Reserved Hardware](https://metal.equinix.com/developers/docs/deploy/reserved/).
- [Packet Host Incidents API](https://apis.io/apis/packet-host/packet-host-incidents-api/) — Incident Management
- [Packet Host Interconnections API](https://apis.io/apis/packet-host/packet-host-interconnections-api/) — Network Interconnections. See Instructions to create Network Interconnections at Check out the product docs to learn more about [Equinix…
- [Packet Host Invitations API](https://apis.io/apis/packet-host/packet-host-invitations-api/) — Manage invitations. See project endpoints to create a new invitation. Check out the product docs to learn more about…
- [Packet Host Invoices API](https://apis.io/apis/packet-host/packet-host-invoices-api/) — The Invoices API from Packet Host — 2 operation(s) for invoices.
- [Packet Host Licenses API](https://apis.io/apis/packet-host/packet-host-licenses-api/) — Manage licenses. See project endpoints to list and create licenses for a particular project.
- [Packet Host Memberships API](https://apis.io/apis/packet-host/packet-host-memberships-api/) — Membership Management (Project). Check out the product docs to learn more about [Membership](https://metal.equinix.com/developers/docs/accounts/).
- [Packet Host MetalGateways API](https://apis.io/apis/packet-host/packet-host-metalgateways-api/) — Metal Gateway Management.Check out the product docs to learn more about [Metal Gateways](https://metal.equinix.com/developers/docs/networking/metal-gateway/).
- [Packet Host Metros API](https://apis.io/apis/packet-host/packet-host-metros-api/) — Metro Management. Check out the product docs to learn more about [Metros](https://metal.equinix.com/developers/docs/locations/metros/).
- [Packet Host OperatingSystems API](https://apis.io/apis/packet-host/packet-host-operatingsystems-api/) — Operating System Management. Check out the product docs to learn more about [Operating Systems…
- [Packet Host Organizations API](https://apis.io/apis/packet-host/packet-host-organizations-api/) — Organizations Management. Check out the product docs to learn more about [Organizations](https://metal.equinix.com/developers/docs/accounts/).
- [Packet Host PasswordResetTokens API](https://apis.io/apis/packet-host/packet-host-passwordresettokens-api/) — Password Reset Token Management
- [Packet Host Plans API](https://apis.io/apis/packet-host/packet-host-plans-api/) — Plan Management (Device). Check out the product docs to learn more about [Device Plans](https://metal.equinix.com/developers/docs/servers/).
- [Packet Host Ports API](https://apis.io/apis/packet-host/packet-host-ports-api/) — Port ManagementCheck out the product docs to learn more about [Port configurations](https://metal.equinix.com/developers/docs/layer2-networking/overview/).
- [Packet Host Projects API](https://apis.io/apis/packet-host/packet-host-projects-api/) — Project Management. Check out the product docs to learn more about [Projects](https://metal.equinix.com/developers/docs/accounts/projects/).
- [Packet Host SelfServiceReservations API](https://apis.io/apis/packet-host/packet-host-selfservicereservations-api/) — Self Service Reservations
- [Packet Host SpotMarket API](https://apis.io/apis/packet-host/packet-host-spotmarket-api/) — Spot Market Pricing and Requests Management. Check out the product docs to learn more about [Spot Market…
- [Packet Host SupportRequest API](https://apis.io/apis/packet-host/packet-host-supportrequest-api/) — Support request
- [Packet Host TransferRequests API](https://apis.io/apis/packet-host/packet-host-transferrequests-api/) — Project Transfer Requests Management
- [Packet Host Usages API](https://apis.io/apis/packet-host/packet-host-usages-api/) — Usage Management
- [Packet Host Users API](https://apis.io/apis/packet-host/packet-host-users-api/) — User Management
- [Packet Host UserVerificationTokens API](https://apis.io/apis/packet-host/packet-host-userverificationtokens-api/) — User Verification Token Management
- [Packet Host VLANs API](https://apis.io/apis/packet-host/packet-host-vlans-api/) — Manage virtual networks (VLANs). See project endpoints to list and create virtual networks. Check out the product docs to learn more about…
- [Packet Host VRFs API](https://apis.io/apis/packet-host/packet-host-vrfs-api/) — VRF Management. A VRF is a project-scoped virtual router resource that defines a collection of customer-managed IP blocks that can be used in BGP peering on…
- [Packet Host OT Ps API](https://apis.io/apis/packet-host/packet-host-otps-api/) — OTP Management. Check out the product docs to learn more about [OTP](https://metal.equinix.com/developers/docs/accounts/two-factor-authentication/).
- [Packet Host IP Addresses API](https://apis.io/apis/packet-host/packet-host-ip-addresses-api/) — Manage IP addresses. See device and project endpoints to list and create IP assignments for a particular project or device. Check out the product docs to…
- [Packet Host Payment Methods API](https://apis.io/apis/packet-host/packet-host-payment-methods-api/) — Payment Method Management
- [Packet Host SSH Keys API](https://apis.io/apis/packet-host/packet-host-ssh-keys-api/) — Manage SSH keys. See project endpoints to list and create project-level SSH keys.
- [Packet Host Two Factor Auth API](https://apis.io/apis/packet-host/packet-host-two-factor-auth-api/) — Two Factor Authentication Management. Check out the product docs to learn more about 2FA.
- [Packet Host User Data API](https://apis.io/apis/packet-host/packet-host-user-data-api/) — Userdata Management

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [packet-host-metal](https://apis.io/servers/packet-host/packet-host-metal/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Packet Host Agentic Access](https://apis.io/agentic-access/packet-host/packet-host-agentic-access/)

#### Collections (40)

Postman and Open Collection request collections.

- [Metal Authentication API](https://apis.io/collections/packet-host/open-packet-host-authentication-api/)
- [Metal Authentication Batches API](https://apis.io/collections/packet-host/open-packet-host-batches-api/)
- [Metal Authentication BGP API](https://apis.io/collections/packet-host/open-packet-host-bgp-api/)
- [Metal Authentication Capacity API](https://apis.io/collections/packet-host/open-packet-host-capacity-api/)
- [Metal Authentication Console Log Details API](https://apis.io/collections/packet-host/open-packet-host-console-log-details-api/)
- [Metal Authentication Devices API](https://apis.io/collections/packet-host/open-packet-host-devices-api/)
- [Metal Authentication Emails API](https://apis.io/collections/packet-host/open-packet-host-emails-api/)
- [Metal Authentication Events API](https://apis.io/collections/packet-host/open-packet-host-events-api/)
- [Metal Authentication Facilities API](https://apis.io/collections/packet-host/open-packet-host-facilities-api/)
- [Metal Authentication Firmware Sets API](https://apis.io/collections/packet-host/open-packet-host-firmware-sets-api/)
- [Metal Authentication HardwareReservations API](https://apis.io/collections/packet-host/open-packet-host-hardwarereservations-api/)
- [Metal Authentication Incidents API](https://apis.io/collections/packet-host/open-packet-host-incidents-api/)
- [Metal Authentication Interconnections API](https://apis.io/collections/packet-host/open-packet-host-interconnections-api/)
- [Metal Authentication Invitations API](https://apis.io/collections/packet-host/open-packet-host-invitations-api/)
- [Metal Authentication Invoices API](https://apis.io/collections/packet-host/open-packet-host-invoices-api/)
- [Metal Authentication IPAddresses API](https://apis.io/collections/packet-host/open-packet-host-ipaddresses-api/)
- [Metal Authentication Licenses API](https://apis.io/collections/packet-host/open-packet-host-licenses-api/)
- [Metal Authentication Memberships API](https://apis.io/collections/packet-host/open-packet-host-memberships-api/)
- [Metal Authentication MetalGateways API](https://apis.io/collections/packet-host/open-packet-host-metalgateways-api/)
- [Metal Authentication Metros API](https://apis.io/collections/packet-host/open-packet-host-metros-api/)
- [Metal Authentication OperatingSystems API](https://apis.io/collections/packet-host/open-packet-host-operatingsystems-api/)
- [Metal Authentication Organizations API](https://apis.io/collections/packet-host/open-packet-host-organizations-api/)
- [Metal Authentication OTPs API](https://apis.io/collections/packet-host/open-packet-host-otps-api/)
- [Metal Authentication PasswordResetTokens API](https://apis.io/collections/packet-host/open-packet-host-passwordresettokens-api/)
- [Metal Authentication PaymentMethods API](https://apis.io/collections/packet-host/open-packet-host-paymentmethods-api/)
- …and 15 more published on APIs.io

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Packet Host Metal Overlay](https://apis.io/overlays/packet-host/packet-host-metal-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Packet Host Authentication](https://apis.io/security/packet-host/packet-host-authentication/)
- [Packet Host Domain Security](https://apis.io/security/packet-host/packet-host-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Documentation](https://docs.equinix.com/metal/)
- [API reference](https://docs.equinix.com/api-catalog/metalv1/)
- [Terms of service](https://www.equinix.com/company/legal/terms)
- [Privacy policy](https://www.equinix.com/privacy)
- [GitHub](https://github.com/equinix)
- [Status](https://status.equinix.com/)

## API Evangelist rating

**Unrated** — no public website could be reached for this company, so there was almost nothing to measure and nothing a reader could check.

This is not a score of zero. No rating is published for this company. If that is wrong because something public exists that we missed, say so on this repository or email [info@apievangelist.com](mailto:info@apievangelist.com) and it will be re-run — free, and no justification needed.

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Packet Host: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/packet-host/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
