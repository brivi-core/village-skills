# Contributing to Brivi Village Skills / წვლილი Brivi-ს სოფლის უნარებში

> *A village master teaches → Robot learns → Skill gets committed → Every robot downloads it for free.*
> *სოფლის ოსტატი ასწავლის → რობოტი სწავლობს → უნარი ინახება → ყველა რობოტი ჩამოტვირთავს უფასოდ.*

---

## Core Principles / ძირითადი პრინციპები

1. **Teach once, replicate infinitely** — Skills are open-source and free
2. **Georgian first** — Village skills originate from Georgian traditions
3. **Safety-critical** — Robot skills must be safe for human environments
4. **Bilingual by default** — English + Georgian for documentation

## How to Contribute / როგორ შევიტანოთ წვლილი

### Adding a New Skill / ახალი უნარის დამატება

1. Create a directory with your skill name (e.g., `brick-layer/`)
2. Add a `README.md` describing the skill
3. Include any demonstration data, task decompositions, or configuration
4. Follow the skill framework (see main README)
5. Open a pull request

### Skill Requirements / უნარის მოთხოვნები

Each skill should include:
- **Description** — What the skill does
- **Prerequisites** — What the robot must already know
- **Tasks** — Step-by-step decomposition
- **Safety constraints** — Boundaries and failure modes
- **Demonstration data** — Video, joint angles, force profiles (if available)

### Unitree Skills / Unitree უნარები

For skills following Unitree SDK format, add YAML skill definitions to `unitree/skills/`. See the [wash-dishes.yaml](unitree/skills/wash-dishes.yaml) template.

## Code of Conduct / ქცევის კოდექსი

We follow the Code of Paktobrivi:

- 🤝 **Good faith** — Teach and learn together
- 🌱 **Expansion** — Help each other master crafts
- 💚 **Flourishing** — Skills serve humans, not the other way around
- 🔓 **Transparency** — Share your methods openly
- 🏠 **Family** — Villages are built on trust

## Getting Help / დახმარება

- Open an issue for skill questions
- Visit [brivi.ge](https://brivi.ge) for project overview
- See [golden_trust](https://github.com/brivi-core/golden_trust) for our ethical framework

---

*სოფლის ხელოსნობის უნარები — Open source, community-taught.*
