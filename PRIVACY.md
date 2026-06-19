# Salida — Privacy Policy

_Last updated: 19 June 2026_

Salida is a macOS app for pre-trip travel research. It is designed to
work without an account, without analytics, and without sending your
personal data anywhere.

## What we collect

**Nothing.** Salida has no servers, no analytics, no advertising SDKs,
no crash reporters, and no account system. The developer has no
visibility into who uses the app or how it is used.

## What stays on your Mac

Everything you create or configure in Salida is stored locally in the
app's sandbox container on your device:

- Notes you write against cities
- Pinned/favourited cities
- Your chosen home (anchor) city
- Your passport selection and any held-visa records
- App preferences and onboarding state

None of this is transmitted off your device by Salida.

## Location

If you grant location permission during onboarding, Salida uses your
approximate location **once**, on-device, to suggest a starting city.
Your coordinates are not stored, logged, or sent to the developer or
to any third party. You can decline this permission and pick a
starting city manually instead.

## Third-party services Salida queries

To enrich the city catalogue with live information, Salida makes
direct requests from your Mac to a small number of public services.
These requests include standard HTTP metadata (your IP address and a
generic User-Agent string) but no personal identifiers from the app.

| Service | Used for | Data sent |
|---|---|---|
| `en.wikipedia.org` | City summary text | City title |
| `api.open-meteo.com` | Weather forecast | Latitude/longitude of the city you're viewing |
| `www.gov.uk` | UK FCDO travel advisories | Country slug |
| `ra.co` | Resident Advisor music events | City/area identifier |
| `raw.githubusercontent.com` | Optional downloadable data bundles | Bundle filename |

Each of these services has its own privacy policy that governs what
they do with incoming requests. Salida does not share your identity,
notes, pins, or any other local data with them.

## Children

Salida is not directed at children and does not knowingly collect any
information from anyone.

## Changes

If this policy ever changes, the updated version will be published at
the same URL with a new "Last updated" date.

## Contact

Questions or concerns: please open an issue at
<https://github.com/faizanbhat/salida-data/issues>.
