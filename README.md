# Class Forge 2K27

A phone-first, offline, single-file web page for generating **fictional NBA 2K27 draft classes** that you build by hand in 2K27's draft class editor (MyNBA user-created classes).

**Live:** https://browc814-spec.github.io/class-forge/

## What it does
- Pick a year, a class shape (Top heavy, Deep/balanced, Weak/flat, Bottom-loaded sleepers, Generational #1, Custom), and how many franchise stars, surprise stars, role players, busts, steals, and project bigs you want. Set 5–30 builds.
- **Fill picks 1–N** (on by default): a class of N builds takes picks 1 through N, and fates are placed by position in the class (stars near the top, busts in the top half, surprise stars, steals and projects in the back half). Turn it off to spread builds across a 60-pick draft.
- Each build gets a name, positions, size (wingspan capped at +6"), age, background, archetype, all 36 2K27 ratings, potential, Min/Max Potential, Bust/Boom %, peak ages, suggested badges with tiers, key tendencies, and appearance notes. Each build also has a hidden "true fate" behind a spoiler toggle.
- **⚡ Quick mode** (top of the Build tab): type one plain-English sentence, e.g. *"I want a generationally talented Small Forward who's 6'9 and known for his athleticism"* or *"I need a 3 and D 2 guard who never gets better than an 83 rating"*. Offline word rules (no AI, no network) pick out the position, height, talent tier and fate, caps and floors (honored exactly), skills, athleticism, weaknesses, origin, and age. A tappable "What I understood" panel lets you fix anything, and words it didn't use are listed as ignored.
- **Build a Player** tab: describe one player (height, position, school, standout skills with Good/Great/Elite levels, athletic sliders from Low end to Elite, weaknesses, or a free-text backstory that gets parsed into chips). You get a full build with an auto-picked archetype and the reason for it, plus a "why" list showing which inputs moved which ratings. You can lock ratings, re-roll, add him to a class at a pick, or save him standalone. 2K27 has no separate Acceleration or Lateral Quickness rating, so those map to Agility, Speed with Ball, and Perimeter Defense (house rule).
- Seeds make rolls reproducible. You can lock builds and re-roll one or all.
- Card mode lists fields in Edit Player order with tap-to-check progress.
- Saves multiple classes in the browser (localStorage), with JSON backup/import and CSV export.

## Important
- **House rules, not 2K's formula.** Target OVR/potential tiers, fate logic, badge tiers and tendencies are community-informed heuristics. 2K calculates the real overall. Badge requirements in the editor are unverified.
- **All players are fictional.** Names are randomly combined, so check them against real players if that matters to you.
- **Not affiliated with or endorsed by 2K, Take-Two, or the NBA.** NBA 2K is a trademark of its owners.
- Data stays on your device; nothing is sent anywhere.
