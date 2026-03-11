# Ripple Effect Model

A lightweight framework for making career growth concrete — for engineers, managers, and teams.

```mermaid
---
title: "The Ripple Effect — Impact Spreading Outward"
---
graph LR
    You["You<br/>━━━<br/>The source"] -->|"work spreads"| R1["Ring 1<br/>━━━<br/>Core"]
    R1 -->|"helps others"| R2["Ring 2<br/>━━━<br/>Team"]
    R2 -->|"owns areas"| R3["Ring 3<br/>━━━<br/>Domain"]
    R3 -->|"shapes culture"| R4["Ring 4<br/>━━━<br/>Organization"]
    style You fill:#95e1d3,stroke:#16a085,stroke-width:2px
    style R1 fill:#e5ffe5,stroke:#388e3c,stroke-width:2px
    style R2 fill:#fff9c4,stroke:#f57f17,stroke-width:2px
    style R3 fill:#e3f2fd,stroke:#0066cc,stroke-width:2px
    style R4 fill:#f5f5f5,stroke:#95a5a6,stroke-width:2px
```

## What it is

The **Ripple Effect Model (REM)** maps how individual impact grows outward. Like a stone dropped in water, your work starts at the center and spreads out — from your own tasks, to your team, to your whole domain, to the organization.

It answers a question most engineers hit at some point:

> "My manager says I'm doing well. But what does _the next level_ actually look like in practice?"

REM gives you a concrete answer for any topic you care about.

```mermaid
---
title: "What REM Answers"
---
graph TB
    Q["The question<br/>━━━<br/>What does the next level<br/>actually look like?"] --> REM["Ripple Effect Model<br/>━━━<br/>Maps impact per topic"]
    REM --> T1["Topic A<br/>━━━<br/>Ring 2"]
    REM --> T2["Topic B<br/>━━━<br/>Ring 1"]
    REM --> T3["Topic C<br/>━━━<br/>Ring 3"]
    style Q fill:#ffe5e5,stroke:#c0392b,stroke-width:2px
    style REM fill:#e3f2fd,stroke:#0066cc,stroke-width:2px
    style T1 fill:#e5ffe5,stroke:#388e3c,stroke-width:2px
    style T2 fill:#e5ffe5,stroke:#388e3c,stroke-width:2px
    style T3 fill:#e5ffe5,stroke:#388e3c,stroke-width:2px
```

## Who it is for

- **Engineers** who want to grow but don't know what to do differently
- **Managers** who want consistent, fair conversations about growth
- **Teams** trying to define what "senior" or "staff" means in real work, not just titles
- **New hires** learning what success looks like over time

```mermaid
---
title: "Who Uses REM"
---
graph TB
    REM["Ripple Effect Model"] --> E["Engineers<br/>━━━<br/>Grow without<br/>guessing what to do"]
    REM --> M["Managers<br/>━━━<br/>Fair and consistent<br/>growth conversations"]
    REM --> T["Teams<br/>━━━<br/>Define what senior<br/>means in real work"]
    REM --> N["New hires<br/>━━━<br/>Learn what success<br/>looks like over time"]
    style REM fill:#e3f2fd,stroke:#0066cc,stroke-width:2px
    style E fill:#95e1d3,stroke:#16a085,stroke-width:2px
    style M fill:#fff9c4,stroke:#f57f17,stroke-width:2px
    style T fill:#e5ffe5,stroke:#388e3c,stroke-width:2px
    style N fill:#f5f5f5,stroke:#95a5a6,stroke-width:2px
```

## What's in this repo

| File                                                       | What it contains                                                                                    |
| ---------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| [010-ripple_effect_model.md](010-ripple_effect_model.md)   | The full REM framework: four rings, the Impact Plan method, worked examples, and writing guidelines |
| [020-impact-plan-template.md](020-impact-plan-template.md) | A blank template to build your own Impact Plan                                                      |

```mermaid
---
title: "Repository Contents"
---
graph TB
    Repo["Ripple Effect Model<br/>━━━<br/>Repository"] --> F1["010-ripple_effect_model.md<br/>━━━<br/>Full framework - four rings,<br/>Impact Plan method, examples"]
    Repo --> F2["020-impact-plan-template.md<br/>━━━<br/>Blank template to build<br/>your own Impact Plan"]
    style Repo fill:#e3f2fd,stroke:#0066cc,stroke-width:2px
    style F1 fill:#e5ffe5,stroke:#388e3c,stroke-width:2px
    style F2 fill:#fff9c4,stroke:#f57f17,stroke-width:2px
```

## How to use it

**For yourself:** Read [010-ripple_effect_model.md](010-ripple_effect_model.md), pick two or three topics you want to grow in, and use [020-impact-plan-template.md](020-impact-plan-template.md) to build your Impact Plans. Bring them to your 1-on-1s.

**For your team:** Copy and adapt this repo. Replace the example with your team's real topics. Fill in the template for each person. Use it in quarterly reviews.

**For managers:** The framework is not a performance review replacement. It's a shared language for growth conversations. Use it alongside your existing review process.

```mermaid
---
title: "How to Use REM"
---
graph TB
    subgraph Self["For yourself"]
        direction TB
        S1["Read the framework"] --> S2["Pick 2-3 topics"] --> S3["Build Impact Plans"] --> S4["Bring to 1-on-1s"]
    end
    subgraph Team["For your team"]
        direction TB
        T1["Copy and adapt"] --> T2["Replace examples<br/>with real topics"] --> T3["Use in quarterly reviews"]
    end
    subgraph Mgr["For managers"]
        direction TB
        M1["Shared language<br/>for growth conversations"] --> M2["Alongside existing<br/>review process"]
    end
    style S1 fill:#95e1d3,stroke:#16a085,stroke-width:2px
    style S2 fill:#95e1d3,stroke:#16a085,stroke-width:2px
    style S3 fill:#95e1d3,stroke:#16a085,stroke-width:2px
    style S4 fill:#95e1d3,stroke:#16a085,stroke-width:2px
    style T1 fill:#e5ffe5,stroke:#388e3c,stroke-width:2px
    style T2 fill:#e5ffe5,stroke:#388e3c,stroke-width:2px
    style T3 fill:#e5ffe5,stroke:#388e3c,stroke-width:2px
    style M1 fill:#fff9c4,stroke:#f57f17,stroke-width:2px
    style M2 fill:#fff9c4,stroke:#f57f17,stroke-width:2px
```

## Quick look: the four rings

| Ring       | Name         | What it means                        |
| ---------- | ------------ | ------------------------------------ |
| **Ring 1** | Core         | Doing your own work well             |
| **Ring 2** | Team         | Helping the people around you        |
| **Ring 3** | Domain       | Owning a whole area of work          |
| **Ring 4** | Organization | Changing how the whole company works |

You don't have one ring. You have a ring per topic, and they can all be different.

```mermaid
---
title: "The Four Rings at a Glance"
---
graph LR
    You["You<br/>━━━<br/>The center"] --> R1["Ring 1 — Core<br/>━━━<br/>Doing your own<br/>work well"]
    R1 --> R2["Ring 2 — Team<br/>━━━<br/>Helping the people<br/>around you"]
    R2 --> R3["Ring 3 — Domain<br/>━━━<br/>Owning a whole<br/>area of work"]
    R3 --> R4["Ring 4 — Organization<br/>━━━<br/>Changing how the<br/>whole company works"]
    style You fill:#95e1d3,stroke:#16a085,stroke-width:2px
    style R1 fill:#e5ffe5,stroke:#388e3c,stroke-width:2px
    style R2 fill:#fff9c4,stroke:#f57f17,stroke-width:2px
    style R3 fill:#e3f2fd,stroke:#0066cc,stroke-width:2px
    style R4 fill:#f5f5f5,stroke:#95a5a6,stroke-width:2px
```

## License

MIT — use it, adapt it, share it. See [LICENSE](LICENSE).

## Contributing

Ideas, fixes, and real-world examples are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).
