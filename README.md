# discussion-guide

A Claude skill that generates structured discussion agendas for podcast episodes, TV shows, and movies. Built for group conversations — dinner parties, book clubs, watch parties.

Give Claude an episode URL or describe the media, and it produces a ready-to-use agenda with discussion questions organized by theme, tension, and depth.

## What It Does

Transforms a podcast episode (or TV show, movie, etc.) into a conversation guide with:

- **Icebreaker** — a warm-up question to get everyone talking
- **Core Tensions** — 3–5 central conflicts or questions the episode raises
- **Deep Dive** — follow-up questions for each tension
- **Personal Connections** — how the themes relate to the group's lives
- **Wrap-Up** — a closing question to tie it together

Perfect for recurring book club dinners, watch parties, or any group that wants structure without scripts.

## Example Output

Podcast Episode Example - [Radiolab - Colors](examples/radiolab-colors.md)


**Sample prompt:**
> "Create a podcast book club agenda for the *Radiolab* episode 'Colors'"

**Sample output structure:**
```
## Icebreaker
What's one technology you've adopted in the past year that actually changed your daily routine?

## Core Tension 1: The Productivity Paradox
[Discussion questions about whether AI is actually accelerating growth...]

## Core Tension 2: Institutional Lag
[Questions about how organizations adapt to rapid change...]
```

## Installation

### Claude.ai
Upload the `SKILL.md` file via Settings → Skills

### Claude Code
```bash
# Clone into your skills directory
git clone https://github.com/dannydover/claude-skill--podcast-book-club-agenda ~/.claude/skills/podcast-book-club-agenda
```

## Usage

Just ask Claude for an agenda:
- "I'm hosting a dinner party to discuss the latest *Succession* episode — make me an agenda"
- "Generate discussion questions for the new *Hardcore History* on the Bronze Age Collapse"

Works for:
- Podcast episodes (provide URL or describe the episode)
- TV shows and movies
- Long-form interviews or documentaries

## Why This Exists

This skill was built for a recurring podcast book club dinner party format: a group of friends meets monthly to discuss a podcast episode over dinner. Rather than freeform conversation (which tends to drift) or overly rigid questions (which feel like homework), the agenda provides just enough structure to hit the interesting tensions without killing spontaneity.

If you run book clubs, watch parties, or discussion groups, this saves you 30 minutes of prep work per session.

## License

Apache 2.0
