# BEACON — Women Safety Ecosystem

Live, connected safety network: member app, operator command center, Safe Haven desk, and authorized police portal. All portals share one database and update without a refresh.

## What you can demo

1. Sign in (Google, X, or email). The first account becomes SUPER_ADMIN.
2. Open **BEACON app** — start a Safe Journey, SOS, community help, ID card.
3. Open **Command Center** — live map, event feed, user/ID/Safe Haven management.
4. **Simulator → Woman feels unsafe** — Ananya’s journey, community help, SOS, Safe Haven, and police alert play in sequence. Every portal updates live.
5. **Join a demo phone** as Ananya or Priya, then open the app in another tab.

Demo records are tagged DEMO and never mix with a real emergency.

## Portals

- `/app` — member experience (Home, Journey, Safe Haven, Guardian, Copilot + SOS)
- `/operator` — command center and judge simulator
- `/haven` — Safe Haven incoming requests
- `/police` — authorized emergency desk
- `/verify/$code` — public ID check (masked name only)

## Notes

This live product is a connected web/PWA suitable for multi-device judging (phones + laptop). Location, camera, and microphone are requested only when a feature needs them. Safety scores are indicators, not crime predictions. Community helpers never receive a private home address.
