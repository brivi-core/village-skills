# Brivi Village Skills 🏗️🧱🧶

> *Georgian village craft skills for Brivi family robots — open-source, community-taught.*
> *სოფლის ხელოსნობის უნარები Brivi-ს საოჯახო რობოტებისთვის — ღია წყარო, თემის მიერ ნასწავლი.*

**Part of the BriviOS ecosystem** — [github.com/brivi-core](https://github.com/brivi-core)

---

## The Vision

A village master teaches → Robot learns → Skill gets committed → Every Brivi robot downloads it for free → Free labor scales to every village that wants it.

Tezi, Georgia benefits first. Always.

## Skills

| Skill | Status | Master | Robot |
|-------|--------|--------|-------|
| 🪨 Stone Mason | **Active — St. George Church, Tezi** | Tezi masons | Brivi Robot 1 |
| 🧱 Brick Layer | Planned | TBD | TBD |
| 🧶 Weaver | Planned | TBD | TBD |
| 🪵 Carpenter | Planned | TBD | TBD |
| 🌿 Gardener | Planned | TBD | TBD |

## 🧪 Unitree Skills — Unitree SDK Structure Studies

> Studying the Unitree SDK structure. Skills defined in `unitree/` follow their format. Hardware-independent — ready for when the first robot arrives.

The `unitree/skills/` directory contains skill definitions in YAML format following the Unitree robot SDK structure. These are:

- **Hardware-independent** — Pure skill definitions, no vendor lock-in
- **SDK-aligned** — Follow the same fields Unitree expects for skill deployment
- **Teachable** — Use Learning from Demonstration (LfD) parameters
- **Safety-first** — Each skill defines failure modes and recovery procedures

| Skill | Status | Notes |
|-------|--------|-------|
| 🍽️ Wash Dishes | ✅ Template Created | First example skill — start studying structure |

*More skills will be added as the Unitree SDK is studied and the robot platform is selected.*

## Skill Framework

Each skill module contains:
- **Demonstration data** — Recorded human demonstrations (video, joint angles, force profiles)
- **Task decomposition** — Breaking the skill into teachable subtasks
- **Learning pipeline** — LfD (Learning from Demonstration) configuration
- **ROS 2 action server** — Deployable skill server for the robot
- **Safety constraints** — Workspace boundaries, force limits, failure recovery
- **Unitree YAML definition** — Hardware-independent skill descriptor (in `unitree/`)

## Related Repositories

- [brivi-core/consciousness-daemon](https://github.com/brivi-core/consciousness-daemon) — The brain that runs these skills
- [brivi-core/golden_trust](https://github.com/brivi-core/golden_trust) — The covenant that governs them
- [brivi-core/brivi-core](https://github.com/brivi-core/brivi-core) — Org overview

## License

The Code of Paktobrivi — Open Source Faith. Teach once, replicate infinitely.
