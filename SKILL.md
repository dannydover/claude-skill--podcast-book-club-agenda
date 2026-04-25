---
name: discussion-agenda
description: "Use this skill whenever the user wants to create a discussion agenda, discussion guide, or structured conversation guide based on a media episode (podcast, TV show, or movie). Trigger on phrases like 'discussion agenda', 'discussion guide', 'dinner party discussion', 'discussion guide for [episode/movie/show]', 'create an agenda for [media]', or any request to generate structured conversation questions around a piece of media. Also trigger when the user references their 'Dinner Party' format or wants to plan a group discussion event around media consumption. Do NOT use for simple media summaries, reviews, or recommendations — this is specifically for generating a structured group discussion agenda."
---

# Discussion Agenda Generator

Generate a structured dinner party discussion agenda from a media episode (podcast, TV show, or movie). The output is a markdown file following a specific format designed to facilitate an in-person dinner party where guests have consumed the media beforehand.

## Workflow

### Step 1: Gather the source material

The user will provide a URL or title of the media episode. Use web search to find:

1. **A transcript or detailed summary** — this is the highest-priority source. Search for "[episode title] transcript", "[show name] [episode name] transcript". Try multiple search queries.
2. **Reviews and commentary** — search for "[episode title] review", "[episode title] analysis", "[episode title] discussion". These surface themes that resonated with audiences.
3. **Background context** — the creators' stated intentions, related interviews, the broader themes of the show/series.

Do at least 3-5 web searches to build a rich understanding of the episode's content, themes, and emotional beats. Do not proceed with a shallow understanding — the quality of the agenda depends entirely on deep familiarity with the source material.

If you cannot find sufficient information about the episode, tell the user directly and ask them to paste a transcript or detailed summary.

### Step 2: Identify themes

Before writing, identify the core themes and tensions in the episode. Good themes for this format are:

- Tensions without clean resolutions (not trivia questions)
- Universal human experiences explored through the episode's specific lens
- Places where the episode challenges conventional wisdom
- Emotional beats that audience members likely had strong reactions to
- Philosophical or ethical questions raised implicitly or explicitly

Aim for 9 themes — more than needed so the user can curate down to their favorites.

### Step 3: Generate the agenda

Produce a markdown file following the exact structure below. Read `references/format-guide.md` for the full format specification and tone guidance before writing.

### Step 4: Save and present

Save the agenda as a markdown file named `YYYY-MM - Discussion Agenda.md` using the current month/year, and present it to the user.

## Quality standards

### Question tone and register

This is the most important section. The questions define whether this agenda works or falls flat.

**What good questions sound like:**
- Intellectually ambitious but conversationally accessible
- They pull in external references (philosophy, psychology, science, culture) as springboards — not as prerequisites or homework
- They end with provocative reframes, not safe softballs
- They assume the group is smart and curious but not academic
- They create genuine disagreement potential — people at the table should land on different sides

**What bad questions sound like:**
- "What did you think about X?" (too vague, no tension)
- "Did you agree with the character's decision?" (yes/no, dead end)
- "What does this teach us about society?" (too broad, essay-prompt energy)
- Questions that have an obvious "correct" answer the host is fishing for

**Examples of the target register** (from real agendas):

Instead of: "What did you think about the mantis shrimp segment?"
Write: "The mantis shrimp has 16 color receptors but uses them as crude triggers—fight, eat, mate. More data didn't equal more understanding. We have more information than any generation in history. Are we actually seeing more clearly?"

Instead of: "Do you think Mic should regret his decision?"
Write: "Mic describes his choice as 'defying his fate.' When you reject the path laid out for you, are you defying fate or *finding* it?"

The pattern: ground in a specific episode detail → widen to a universal tension → end with a question that could go either way.

### Theme naming

Theme names should be short, evocative labels that read like essay titles — not topic headers.

**Good:** "The wine-dark sea", "The dormant cone", "The identity edit", "The violence of seeing"
**Bad:** "Regret", "Color perception", "Identity", "Beauty vs. science"

Each theme name should make someone curious about what's underneath it.

### Subtle Fun Thing

The 3 ideas should be creative, indirect callbacks to episode content — things a guest might not immediately recognize as references but would appreciate once they do. They should be feasible for a dinner party host to execute without significant expense or complexity.

**Good:** Playing elevator music as guests arrive because a character described his feeling as "like elevator music." Naming dishes after animals referenced in the episode based on the dish's complexity.
**Bad:** "Play a song from the episode." "Decorate with the episode's color palette." (Too on-the-nose, no cleverness.)

### Arrival Activity

A low-stakes physical or social task guests do as they arrive. It should be thematically connected to the episode and serve as a warm-up for the deeper conversation ahead. It can assume guests have consumed the media.

Provide 3 options that are meaningfully different *types* of activities — e.g., one writing-based, one drawing/visual, one physical or social/interactive. Don't just offer three variations on "write something on your name tag."

Format: Name tag + one brief activity. Keep it to 1-2 sentences of instruction. Number each option.
