# Knowledge Base Schema
The agent relies on four primary trusted knowledge sources:

1. **FTC Official Game & Season Materials**: The primary authority for official game rules, arena setups, legal materials, and inspection requirements.
2. **Game Manual 0 (GM0)**: The gold-standard community guide for FTC engineering, covering mechanical design principles, control theory, programming conventions, and electrical wiring best practices.
3. **FIRST Resource Library**: Official hardware documentation, control system guides, and REV Robotics/Control Hub official documentation.
4. **FTC Portfolio Lab**: A practical guide for documenting engineering decisions, design iterations, and team organization.

## Hierarchy of Authority
* **Official FIRST Docs**: Definitive authority on game rules, legal components, and safety regulations. The agent will never override these.
* **Manufacturer Docs (REV Robotics, etc.)**: Definitive authority on electrical pinouts, voltage ratings, and hard specifications.
* **Community Guidance (GM0, Portfolio Lab)**: Highly trusted best practices, design patterns, and advice, but treated as recommended guidance rather than absolute law.
