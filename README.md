# Hi, I'm Fede

Software engineer in Córdoba, Argentina. I build web and mobile products, and these days a lot of that happens with AI agents in the loop.

Right now I'm a Mobile Engineer at **Darwoft**, building a virtual wallet for a major Argentine bank and leading the mobile design system its other apps share.

## Things I build on my own

### Novella

<img src="assets/novella.jpg" alt="Novella: an AI edit shown as an inline diff, waiting to be accepted" width="100%">

A Mac app for writing novels. Its assistant, Odette, can only propose edits: nothing touches a chapter until the writer accepts it.

**The hard part:** running Claude and Codex inside the app, locked down. They read the story only through an MCP server the app owns, with keys in the Keychain and the provider rules written down before the first line of code.

<sub>Swift · SwiftUI · MCP · SQLite FTS5 · macOS 26</sub>

### Spider Solitaire

<p>
  <img src="assets/spider-game.png" alt="Klondike in the greenhouse chapter, with the dog companion" width="32%">
  <img src="assets/spider-companion.png" alt="Spider with the tabby cat companion" width="32%">
  <img src="assets/spider-story.png" alt="Story screen with chapter progress and quests" width="32%">
</p>

A cozy pixel solitaire for iPhone and Mac, Klondike and Spider, with a pet that talks to you and a story that unfolds across three chapters.

**The hard part:** keeping pixel art crisp on every screen. Whole-number scaling, bitmap fonts drawn in code, a five-tone palette, and around 1,100 tests holding it together.

<sub>Swift · SwiftUI · SpriteKit · iOS · macOS</sub>

### Worms

<img src="assets/worms.png" alt="Worms: a bazooka shell carving a crater in the hillside" width="100%">

The game I played as a kid, rebuilt from scratch in Godot without looking at the original. Seven weapons, wind, water and up to four teams on one keyboard.

**The hard part:** ground that breaks pixel by pixel, and a simulation deterministic enough that tests replay a whole match and land on the same result.

<sub>Godot · GDScript</sub>

### More

- [**LaterVault**](https://latervault.vercel.app) — Save now, decide later: links you might buy or read, on Pinterest-inspired cards with a pixel cat for company. <sub>Next.js · Drizzle · Neon</sub>
- **Lunara** — An offline sleep companion for iPhone, with soundscapes generated on the device. <sub>SwiftUI</sub>
- **Nupcia** — A wedding vendor marketplace for Argentina. <sub>Next.js · Supabase</sub>
- [**ESAM**](https://esam-instituto.vercel.app) — An editorial site for a fashion school in Córdoba. <sub>Astro</sub>
- [**Hook Hub**](https://hook-hub.vercel.app) — A catalogue of Claude Code hooks. <sub>Next.js</sub>

## Things I've built at work

- **A virtual wallet** for a major Argentine bank, using the full Expo suite (sensors, haptics, sound), plus the mobile design system behind its retail, corporate and event-ticket apps. <sub>Expo · Tamagui · Nx · Turborepo · SQLite</sub>
- **Customer and vendor apps** for a home-maintenance SaaS company, from scratch. <sub>React · Next.js · Expo · TanStack Query</sub>
- **A lending platform's MVP**, which I led on the front end from zero. <sub>Next.js · Prisma · PostgreSQL</sub>
- **A patient app** for a health association, where people track their condition, its severity and their documents. <sub>Expo · lead front end</sub>
- **Anthelios League**, a dermatology quiz league for hospitals and clinics, with teams, weekly rankings and prizes. <sub>Angular · Node.js · Prisma</sub>
- **An outsourcing marketplace** where freelancers join a talent pool and companies post projects matched by skill. <sub>React · Material UI</sub>
- **A B2B self-service panel** for a telecom's corporate customers. <sub>.NET · C# · SQL</sub>

---

[LinkedIn](https://www.linkedin.com/in/fedealetti) · [fedaletti@gmail.com](mailto:fedaletti@gmail.com)
