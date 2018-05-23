# SpaceCaseGame Assets

This repository contains game specific assets.

All assets (other than images) will are kept in json format.

## Cards

The general form of a card is:

```json
{"id":1,
"name":"",
"gamename":"spacecaseos",
"front":"filename.png",
"back":"filename.png"
}
```

A python script will be provided to ensure an added card follow this format properly and will be run by travis before a PR with any card can be added.

- Shared
    - Name
    - Schema (card type)
    - Subtype
    - Expansion
    - Collector Number
- Gear
    - Equip Cost in ÆT
    - Intrinsic Ability
    - Skill 01
    - Skill 02
    - Exotic Ability
    - Skill Tree
        - 6-12 nodes
        - Skill Node
        - Intrinsic Node
        - æt/ÆT Node
        - sm/BG Stat Node
        - rng/static
        - ELE Node
    - Supported Skills
    - Required Materials
    - Influence Cost
- Familiars
    - Summon Cost in ÆT
    - Intrinsic Ability
    - Skill
    - Cooldown
    - Skill Tree
    - 3-7 Nodes
        - Skill Node
        - Intrinsic Node
        - æt/ÆT Nodes
- Events
    - Queue Cost in ÆT
    - Rules text
