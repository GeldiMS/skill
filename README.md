# skill

Built by the Zodiac HQ team: Lucy (lead), Grei and Bubi (developers), with Bibi as CEO.

## How work gets here

- Each developer works on their own branch (`agent/grei`, `agent/bubi`).
- Changes reach `main` only through a pull request that passes CI (`.github/workflows/ci.yml`) and that Bibi approves.
- Agents can't push. Bibi ships a branch from the office, which pushes it and opens the pull request.
