# Hi, I'm Fede

Software engineer in Córdoba, Argentina. I build web and mobile products, and these days a lot of that happens with AI agents in the loop.

Right now I'm a Mobile Engineer at **Darwoft**, building a virtual wallet for a major Argentine bank and leading the mobile design system its other apps share.

## Things I build on my own

### ✍️ Novella

**A native Mac novel editor where AI suggests edits and the writer decides.**

<img src="assets/novella/hero.gif" alt="Odette rewrites a passage; the change stays a diff until accepted" width="100%">

<table>
  <tr>
    <td width="33%"><img src="assets/novella/feature-page-layouts.gif" alt="Page layouts" width="100%"></td>
    <td width="33%"><img src="assets/novella/feature-themes.gif" alt="Themes" width="100%"></td>
    <td width="33%"><img src="assets/novella/feature-canon.gif" alt="Canon" width="100%"></td>
  </tr>
  <tr>
    <td><sub>One chapter as a continuous page, pages, spread or ribbon.</sub></td>
    <td><sub>Three themes, light and dark, with small ASCII animations.</sub></td>
    <td><sub>Characters, world entries and story notes beside the chapters.</sub></td>
  </tr>
</table>

- AI rewrites land on the page as an **inline diff**: nothing changes until the writer accepts it.
- **Claude and Codex run inside the app, locked down.** Claude starts with no built-in tools and reaches the story only through Novella's own MCP server; Codex runs in a read-only sandbox.
- Keys live in the Keychain, and the provider rules were written down before the first line of code.
- SwiftUI and TextKit across ten Swift modules, with **1,966 tests**.

▶️ [**Watch the 45-second demo**](https://github.com/Fede-Aletti/Fede-Aletti/blob/main/assets/novella/demo.mp4) · <sub>Swift · SwiftUI · TextKit · MCP · SQLite FTS5 · macOS 26</sub>

<details>
<summary>More screenshots</summary>
<br>
<img src="assets/novella/shot-inline-diff.png" alt="Proposed edit as a diff" width="49%"> <img src="assets/novella/shot-odette-chat.png" alt="Asking Odette about the story" width="49%">
<img src="assets/novella/shot-ribbon-pages.png" alt="Ribbon layout" width="49%"> <img src="assets/novella/shot-character-sheet.png" alt="Character sheet" width="49%">
<img src="assets/novella/shot-dark-theme.png" alt="Grape Soda theme, dark" width="49%">
</details>

### 🃏 Spider Solitaire

**A cozy pixel-art solitaire for iPhone and Mac, built in Swift.**

<table>
  <tr>
    <td width="25%"><img src="assets/spider/hero.gif" alt="Win cascade" width="100%"></td>
    <td width="25%"><img src="assets/spider/feature-companion-hints.gif" alt="Companion and hints" width="100%"></td>
    <td width="25%"><img src="assets/spider/feature-themes.gif" alt="Themes" width="100%"></td>
    <td width="25%"><img src="assets/spider/feature-story-chapters.gif" alt="Story chapters" width="100%"></td>
  </tr>
  <tr>
    <td><sub>The win cascade, with the cat cheering.</sub></td>
    <td><sub>Hint-driven moves, with the dog chiming in.</sub></td>
    <td><sub>Paper, green and moonlit themes.</sub></td>
    <td><sub>Three story chapters: cottage, greenhouse, observatory.</sub></td>
  </tr>
</table>

- **Pixel art that stays crisp on every screen:** an integer-scaled grid, bitmap fonts drawn in code and a five-tone palette.
- **Pets that react to how you play**, and a three-chapter story with quests that unlock accessories.
- Klondike and Spider in **one SwiftUI codebase for iOS and macOS**, with around 1,100 tests.

▶️ [**Watch the 35-second demo**](https://github.com/Fede-Aletti/Fede-Aletti/blob/main/assets/spider/demo.mp4) · <sub>Swift · SwiftUI · SpriteKit · iOS · macOS</sub>

<details>
<summary>More screenshots</summary>
<br>
<img src="assets/spider/shot-home.png" alt="Home" width="19%"> <img src="assets/spider/shot-greenhouse.png" alt="Greenhouse" width="19%"> <img src="assets/spider/shot-story.png" alt="Story" width="19%"> <img src="assets/spider/shot-journal.png" alt="Journal" width="19%"> <img src="assets/spider/shot-wardrobe.png" alt="Wardrobe" width="19%">
</details>

### 💥 Worms

**My childhood favourite, rebuilt from scratch in Godot without looking at the original.**

<img src="assets/worms/hero.gif" alt="A bazooka shot blows the peak apart and the worm drowns" width="100%">

<table>
  <tr>
    <td width="33%"><img src="assets/worms/feature-airstrike.gif" alt="Airstrike" width="100%"></td>
    <td width="33%"><img src="assets/worms/feature-cluster-bomb.gif" alt="Cluster bomb" width="100%"></td>
    <td width="33%"><img src="assets/worms/feature-setup.gif" alt="Team setup" width="100%"></td>
  </tr>
  <tr>
    <td><sub>An airstrike knocks a worm into the sea.</sub></td>
    <td><sub>A cluster bomb shreds the rock arch.</sub></td>
    <td><sub>Teams, skins and accessories with live previews.</sub></td>
  </tr>
</table>

- **Ground that breaks pixel by pixel:** every blast carves the map.
- **A deterministic simulation:** seeded matches replay to the same state hash in tests.
- Seven weapons, wind, water and up to four teams on one keyboard, with **about 1,000 headless tests**.
- All the art is drawn in code from one fixed palette.

▶️ [**Watch a full match in 37 seconds**](https://github.com/Fede-Aletti/Fede-Aletti/blob/main/assets/worms/demo.mp4) · <sub>Godot · GDScript</sub>

<details>
<summary>More screenshots</summary>
<br>
<img src="assets/worms/shot-bazooka-blast.png" alt="Bazooka blast" width="49%"> <img src="assets/worms/shot-cluster-bomb.png" alt="Cluster bomb" width="49%">
<img src="assets/worms/shot-airstrike.png" alt="Airstrike" width="49%"> <img src="assets/worms/shot-victory.png" alt="Victory" width="49%">
</details>

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
