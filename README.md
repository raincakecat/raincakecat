# Hi, I'm Jonathan 👋

I Enjoy building web apps, Minecraft tools, and Discord bots as **raincakecat**.

## Featured project: RestrictTiers

**Minecraft tier-list restriction information across the web, Discord, and in-game tools.**

RestrictTiers brings player restriction lookups into one connected project. It gives players and community staff a way to check restriction information, view active and past records, and open a player's website profile from Minecraft.

### One project, several ways to use it

| Component | What it provides |
| --- | --- |
| **Website** | A central place to look up players and browse their active and past restriction records. |
| **Discord tools** | Restriction lookup commands and record information within Discord communities. |
| **Fabric client mod** | On-demand checks from your own Minecraft client, without requiring a server plugin. |
| **Paper server plugin** | In-game lookup commands for players on a Paper server, without requiring the client mod. |

### In-game lookups

- Run `/check <IGN or UUID>` or `/restrictcheck <IGN or UUID>` to request a lookup.
- See restriction counts, open the linked website profile, and browse the returned details.
- Results go to the person running the command; they are not broadcast to the server.
- Lookups happen when requested. Browsing cached detail pages does not issue another lookup.
- Use the client mod or the server plugin independently. If both are installed, the client commands run locally; `/restricttiers:check` explicitly calls the server plugin.

The public Minecraft integrations connect to the RestrictTiers website. The core service is maintained separately in a private repository.

**[Visit RestrictTiers](https://restricttiers.raincakecat.com)** · **[Fabric mod & installation](https://github.com/raincakecat/RestrictTiers-Mod)** · **[Paper plugin & installation](https://github.com/raincakecat/RestrictTiers-Plugin)**

## What I'm working on

### ClassParlor · In progress

**Your class. One shared notebook.**

I'm developing ClassParlor, a collaborative classroom platform growing out of my Commonroom / StudyHub project. The goal is to bring classmates' notes and uploaded materials into one organised place, with shared editing, revision history, and links back to original sources.

The planned structure runs from schools and classes down to individual lesson sessions, with access managed within each school workspace.

### Commonroom / StudyHub · The idea behind ClassParlor

Commonroom / StudyHub began as a private space I built for my class to collect learning materials and using a self-hosted LLM, turn them into organized, searchable notes. ClassParlor builds on that foundation, with the aim of making shared class notebooks available to more schools and study groups.

The ideas I'm developing include:

- **One shared notebook per class:** classmates contribute photos, PDFs, documents, and notes to the same collection.
- **A clear lesson structure:** School → Year → Term → Class → Session, so materials stay connected to the lesson they belong to.
- **Help turning uploads into study material:** text extraction, handwriting recognition, and AI-assisted notes and summaries, with links back to the original sources for checking.
- **Collaborative editing with history:** class members can improve shared notes, see who changed what, and restore earlier revisions.
- **Private school workspaces:** invitations, class access, and roles keep each group's materials within its own community.

These are the direction and goals for the project as it develops. The focus is on useful shared notes, traceable sources, and a calm, approachable interface.

## More projects

| Project | What it does |
| --- | --- |
| [Combat Audio Mixer](https://github.com/raincakecat/minecraft-combat-audio-mixer) | A Fabric mod with live volume controls, previews, and shareable presets for Minecraft combat sounds. |
| [Crystal PvP Events](https://github.com/raincakecat/crystal-events) | A Paper plugin for running Crystal PvP tournaments, with arena setup, event controls, and results. |
| [TierList Bot](https://github.com/raincakecat/TierList-bot) | A configurable Discord bot for tier testing, queues, rankings, support tickets, and staff workflows. |
| [Cat Tiers Tagger](https://github.com/raincakecat/Cat-Tiers-Tier-Tagger) | A Fabric mod that displays combat tiers and gamemode icons on player nametags. |
| [Misery Optimizer](https://github.com/raincakecat/Misery-Optimizer) | A configurable Fabric mod that previews combat actions locally and reconciles with server results. |

## Languages I work with

Java · TypeScript · JavaScript · Python
