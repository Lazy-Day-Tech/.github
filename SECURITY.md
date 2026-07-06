# Security policy

## Reporting a vulnerability

Please don't open a public issue for a security problem, in any Lazy-Day-Tech repo. Two private routes:

- Where a repo shows a "Report a vulnerability" button under its Security tab, use it. It opens a private advisory only the maintainers can see.
- Otherwise, reach out to @gbasran or @goldentg on GitHub directly rather than posting anything public.

Tell us what you found, how to reproduce it, and what an attacker could do with it. A proof-of-concept helps but isn't required.

## What happens next

We'll acknowledge your report within two business days, usually sooner. Once we've confirmed what you found, we'll tell you the severity call and the fix timeline. Anything critical and actively exploitable gets dropped-everything treatment. We'll credit you when the fix ships, unless you'd rather we didn't.

## Scope

This policy covers the Lazy-Day-Tech repositories. They run as single-tenant internal services, so there's no bug-bounty program behind this, just a private channel to a small team that will act on what you send.

Out of scope: the third-party systems these talk to (Airtable, FareHarbor, Wherewolf, PassKit). Report those to the vendor. If you've found one of their keys or tokens exposed in our code, that IS in scope. Tell us and we rotate.

## Supported versions

We ship from `main` and run the latest tagged release of each service. Fixes land on `main` and go out in the next tag; there's no back-porting to old tags.
