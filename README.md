# TripPlanningSkill

Two Codex skills for designing realistic, research-backed travel plans through structured interviewing, fact verification, and execution-focused itineraries.

## Included skills

| Skill | Language | Use it for |
| --- | --- | --- |
| `trip-planning-en` | English | Interview-first travel planning, research, budgeting, and itinerary documents |
| `trip-planning-cn` | 简体中文 | 通过访谈、联网核查和风险控制制定可执行旅行计划 |

## Installation

Copy either skill directory into your Codex skills directory, or copy both:

```text
TripPlanningSkill/skills/trip-planning-en
TripPlanningSkill/skills/trip-planning-cn
```

Then invoke explicitly with `$trip-planning-en` or `$trip-planning-cn`. Automatic discovery is enabled for both skills.

## Design principles

- Interview first; do not silently guess unresolved constraints.
- Verify volatile facts such as flights, visas, hotel availability, opening hours, transport, and restaurant reviews.
- Prefer primary and authoritative sources, and show source dates and uncertainty.
- Optimize for safety, comfort, meaningful local experiences, and deliberate free time.
- Include booking deadlines, detailed budgets, contingencies, and a short immediate-action list.
- When creating a PDF, render and visually inspect the final document before delivery.

## Repository structure

```text
TripPlanningSkill/
├── LICENSE
├── README.md
└── skills/
    ├── trip-planning-cn/
    │   ├── SKILL.md
    │   └── agents/openai.yaml
    └── trip-planning-en/
        ├── SKILL.md
        └── agents/openai.yaml
```

## License

Released under the MIT License. See [LICENSE](LICENSE).
