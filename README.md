# PON Licence

**Version 1.0**

A licence for developers who want their code freely usable by individuals — and fully under their own control the moment it reaches an organization or the public.

Created by Ponvasanth.

---

## What PON Licence Does

Anyone can view, personally modify, and even commercially use this software as an individual — completely free, no questions asked. The moment code, original or modified, is meant to reach the public or an organization, permission from the original developer is required. The developer can grant that for free, for a fee, or with custom conditions, case by case.

## Quick Summary

| Action | Allowed? |
|---|---|
| View the code (if made public) | ✅ Always free |
| Modify it for personal use | ✅ Always free |
| Use your modified version commercially, as one individual | ✅ Always free |
| Share your modified version privately (friends, family) | ✅ Always free |
| Publish the original or a modified version publicly | 🔒 Needs permission |
| Use it inside a company, team, or organization | 🔒 Needs permission |
| Share a modified version with anyone in an organization | 🔒 Needs permission |
| Relicense a modified version under a different licence | 🔒 Needs permission |

Full terms, including definitions of every term above, are in [`LICENSE.md`](./LICENSE.md).

## Why Not Just Use MIT, Apache, or GPL?

Permissive licences don't distinguish between one person tinkering with the code and a company deploying it commercially at scale — both get identical free rein. Copyleft licences force openness downstream but give the developer no ongoing say once their conditions are technically met.

PON Licence takes a different position: personal and private use is always free, but public distribution and organizational use stay a conversation with the original developer — one they can permit, charge for, or attach conditions to, indefinitely.

It also does something no mainstream licence does: it defines what happens to the code if the developer dies (Section 8) — succession to a named person, or automatic release under Apache 2.0 if there's no one left to ask.

## Is PON Licence OSI-Approved?

No, and it can't be. The Open Source Definition requires that redistribution and use not be restricted — PON Licence deliberately restricts both public redistribution and organizational use by default. That's an intentional trade-off, not an oversight. Source-visible, but not "open source" in the OSI sense.

## Repository Contents

- [`LICENSE.md`](./LICENSE.md) — the full licence: plain English summary + legal text. **This is the template — leave its `[Year]` / `[Full Name]` brackets exactly as they are.** Every project that adopts PON Licence fills those in for itself.
- [`LICENSE-META.md`](./LICENSE-META.md) — governing law and version choice, filled in per project.
- [`SUCCESSOR.md`](./SUCCESSOR.md) — successor declaration and death verification log, per project.
- [`PERMISSIONS.md`](./PERMISSIONS.md) — running log of every permission grant issued, per project.

## Using PON Licence In Your Own Project

1. Copy all four files into your project root.
2. Fill in `LICENSE-META.md`, and optionally `SUCCESSOR.md`, with your own details. Leave `LICENSE.md` untouched.
3. Add this to your source files or project README:

```
SPDX-License-Identifier: LicenseRef-PON-Licence-1.0
Copyright (c) [Year] [Full Name]
Full text and permission records: https://github.com/ponvasanth/pon-licence
```

## Reusing The Licence Text Itself

The text of `LICENSE.md` is not restricted by its own terms. Anyone may copy, adapt, and reuse the PON Licence text to license their own software, without asking permission — otherwise no one but the original author could ever legally use it.

## Versioning

This repository holds PON Licence v1.0. A project may adopt v1.0 only, or "v1.0 or any later version" — that choice belongs to whoever applies the licence, recorded in their own `LICENSE-META.md`. Future versions, if any, will be added here with a changelog.

## FAQ

**Can I use PON-licensed code in a personal project without telling the developer?**
Yes — personal use, individual commercial use, and private sharing never require contact.

**What counts as "an organization"?**
Any company, partnership, nonprofit, government body, or structured group of two or more people acting collectively. Full definition in `LICENSE.md` Section 1.

**What if the developer never responds to my permission request?**
The restricted use stays off-limits until they respond, or until Section 8 (succession/death) applies.

**What happens if the developer disappears or passes away?**
If a successor was named and can be reached, they take over (`SUCCESSOR.md`). Otherwise, once death is properly documented, the code automatically releases under Apache 2.0 (Section 8).

**Does using PON-licensed code give me any patent rights?**
No. Patent rights are explicitly separate from this licence (Section 5). If the code touches a developer's patent, that's a separate matter entirely.
