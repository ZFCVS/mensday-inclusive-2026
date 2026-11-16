# V22 inclusive release — QA summary

**Scope**: eight complete replacement files sourced from the current public V22 GitHub repository (specific Git blob SHAs below).

**Passed**: JS syntax; 12 standard + 12 hero geometry cases; 12 new card token roundtrips; four existing V6 card token regressions; old V1–V6 field ordering; unique HTML IDs; new controls present.

**Unverified**: live browser rendering and real Outlook integration (local Chromium navigation was blocked by administrator policy); full asset/GIF visual regression suite; V1–V5 real link samples.

The new generation choice guides starting visuals only. The selected gender identity/category does not appear in event telemetry and is not transmitted to any backend; the share token carries only necessary visual styling values.

## Source baselines (Git blob IDs)
- `index.html`: `4f6dcb8bd9044f76d875d665c35b5b9fee772dfe`
- `block-figure.html`: `85b026b53d98972e2189c8bdecf00cb4a03911f0`
- `src/block-figure.js`: `e1145c8cb56bd4cb0b39fdc38135859fb20bf34d`
- `src/block-figure.css`: `cc9f11c0d61a6221d1dc42f006b5911b69e39453`
- `src/block-figure-engine.mjs`: `5cacc828a27c716ee9e7e3c2f1391d505ec1f705`
- `src/personality-character.mjs`: `f2eb3b3cfe72a3aeb16b55c2311e5cd775160701`
- `src/superhero-engine.mjs`: `a31b37d740bf1f87bee1f652636557c732df2905`
- `src/share-card-token.mjs`: `fef37aaea1f3ed8f11b0f4840f81a33b68cce7e4`
