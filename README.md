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
