# Gaard

**Vagtplan, check-ind og løn til bemanding.**

Gaard er bygget til danske vagtfirmaer, eventbureauer og festivals. Hver begivenhed får sit hold, sine roller og sine krav — med check-ind, kontrakter og løn i samme flow, så kontoret slipper for regneark og dobbeltarbejde.

[www.fendr.dk](https://www.fendr.dk) · [Åbn appen](https://app.fendr.dk) · [App Store](https://apps.apple.com/dk/app/fendr/id6805802017?l=da) · [hello@gaard.app](mailto:hello@gaard.app)

## Produkter

| Overflade | Repo | Rolle |
| --- | --- | --- |
| **Web** | [`gaard-webapp`](https://github.com/gaard-app/gaard-webapp) | Kontor: vagtplan, bemanding, check-ind, kontrakter og løn |
| **iOS** | [`gaard-ios`](https://github.com/gaard-app/gaard-ios) | Native medarbejder-app (SwiftUI) — vagter, stempel og kontor |
| **Android** | [`gaard-android`](https://github.com/gaard-app/gaard-android) | Native medarbejder-app (Kotlin + Compose) — samme flow som iOS |
| **Incidents** | [`gaard-incidents`](https://github.com/gaard-app/gaard-incidents) | Stadium incident logging for klubber — [incidents.fendr.dk](https://incidents.fendr.dk) |

Apprepos er private. Produktet er dansk og hostes i EU.

## Stack (kort)

- **Web / Incidents** — Next.js, TypeScript, Supabase (Auth + Postgres RLS), Vercel
- **iOS** — SwiftUI, samme API og Supabase-projekt som web
- **Android** — Kotlin, Jetpack Compose, samme API og Supabase-projekt som iOS

## Links

- Produkt: [www.fendr.dk](https://www.fendr.dk)
- Status: [www.fendr.dk/status](https://www.fendr.dk/status)
- Sikkerhed & DPA: [www.fendr.dk/sikkerhed](https://www.fendr.dk/sikkerhed)
- Support: [hello@gaard.app](mailto:hello@gaard.app)
- Sikkerhedshændelser: [security@fendr.dk](mailto:security@fendr.dk)
