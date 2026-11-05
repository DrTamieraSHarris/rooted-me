# Rooted Me

**Muse does things for you. Rooted Me grows things in you.**

Rooted Me is a voice-first whole-woman AI companion for the woman who carries everything: home, work, money, health, and the people she loves. She talks, and the app carries what it can, shows its work, and gives her a peaceful place to land. Built solo by Dr. Tamiera Harris with her AI Dream Team for the Meta Global AI Developer Hackathon, Indie track, Build for Your World, October 27 to November 4, 2026.

## Demo Video

**[Watch the 3-minute demo (YouTube, permanent link)](https://www.youtube.com/watch?v=24cxsuOPJG8)**

The demo shows the full app walkthrough: Release, My Day, Grow, Reflect, and Catch Up tabs, with voice and type input, breathing, and the team feed.

## What it is

Five tabs, plain words, no learning curve:

- **Release:** the front door. Talk Freely, a voice-first check-in. She speaks or types how she is, and the app responds with real help, never a dead end. If it does not understand a word, it finds an answer or carries it.
- **My Day:** greeting, live weather, calendar, to-do list with a carry-it button, and a focus timer she can set for real life (laundry, a workout, deep work).
- **Grow:** her goals, challenges, the Rooted Chest, and the living tree. The tree is a living anchor visual, not navigation: it holds her year, blooms where she has grown, and speaks one calm line.
- **Reflect:** journal with prompts, the Honest Mirror (camera-based, one-tap correction), dreams, and welcome-backs for missed check-ins.
- **Catch Up:** "While you were away," what her team carried, with undo on all of it, plus the weekly report read aloud.

Underneath: the Bottleneck Engine (Momentum) that detects what is waiting on her, the Delegation Ladder (it moves things, prepares decisions, carries pre-approved work, and always asks before money, signatures, or anything irreversible), one-tap Carry Mode, and the blessings jar.

## Meta AI tooling: the 60-second version

Three Meta tools, three jobs, each honestly labeled:

- **Muse Spark via the Meta Model API (live path):** one gated live call exists, the pour-back encouragement line at the demo's climax. A "Live mode" control accepts the API key at runtime, typed in at record time. The key lives in JS memory only, never touches localStorage, never touches the file, never touches the repo. The line is tagged "live" only on a confirmed successful response. On any failure, or with no key, the seeded line plays and the tag reads "seeded." Both paths rehearse from the same control.
- **Open-weights on-device (Transformers.js):** the check-in reading runs on her phone with open weights, lazy-loaded only when tapped. The 1M-token context window is the point: her entire year fits in one context, and her inner life (journal, tree, voice) never leaves the phone. Tagged "Private tier: on-device" in the app.
- **SAM 3.1:** powers the Honest Mirror's camera layer, so she can see a scene and correct it in one tap.

## How to run it

Open `index.html` in any modern phone or desktop browser. One file, no build step, no install. Reloading resets the demo to its starting state.

The demo persona is Maya, a project manager and mom of two. Everything about Maya is sample data. No real personal details appear anywhere.

## Honesty section

- Seeded demo with one gated live path. The pour-back line can call the Meta Model API when a key is entered at runtime; every line is labeled seeded or live on screen.
- The on-device inference path is built and wired. Only a real phone proves the full path.
- The demo weather is Philadelphia, seeded at build time and labeled in the app.
- Maya's wins, suggestions, and scenarios are seeded sample data, framed as warm remembrance, never scoring. The app keeps no score, ever.
- Money moves nothing. Everything financial waits behind her explicit approval.
- The submission shows code and architecture only. Strategic underpinnings are intentionally outside it.

## License

All code and assets in this repository are original work created during the hackathon build period, October 27 to November 4, 2026, for this submission only. The one third-party runtime dependency, the Transformers.js library, is loaded lazily from a CDN at the user's tap and is Apache 2.0 licensed.

## Built by

Dr. Tamiera Harris, with her AI Dream Team.
