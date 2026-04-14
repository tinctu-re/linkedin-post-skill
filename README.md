# LinkedIn Post Generator — Installation Guide

## What's in this download

```
linkedin-post-generator/
  SKILL.md               — The skill definition and format reference
  README.md              — This file
  examples/
    observation.md       — Worked example: The Observation format
    number.md            — Worked example: The Number format
    before-after.md      — Worked example: The Before/After format
    question.md          — Worked example: The Question format
    polarising.md        — Worked example: The Polarising Statement format
    unspoken-truth.md    — Worked example: The Unspoken Truth format
```

## Installation in Claude Code

1. Open Claude Code in your terminal
2. Run `/skills add` (or navigate to Settings → Skills)
3. Point it at `SKILL.md` in this folder
4. The `/linkedin-post` command will now be available in your Claude sessions

## Usage

```
/linkedin-post [your bullet points or rough idea]
```

Add optional flags to control format and voice:
```
/linkedin-post [idea]
format: observation
voice: direct, no corporate speak
```

If you omit the format flag, Claude will pick the best format for your input.

## Tips

- Start from something real: a customer call observation, a metric you just checked, a decision you made this week
- Paste rough notes — the skill tidies them up
- Your first draft is rarely perfect. Use "Try another format" or re-invoke with a different format flag
- Check the word count before posting — LinkedIn optimal range is 150–300 words

## From Tincture

This skill is a companion to the LinkedIn Playbook at tinctu.re/tools/linkedin-playbook.
The playbook covers the 30-minute weekly workflow, when to use each format, and how to read LinkedIn as a pipeline signal.
