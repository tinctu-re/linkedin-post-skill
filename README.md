# LinkedIn Post Generator - Installation

<!-- GENERATED FILE. Do not edit by hand.
     Source: src/lib/linkedinSkill.ts
     Regenerate: npm run build:linkedin-skill -->

## What's in this download

```
linkedin-post-generator/
  SKILL.md               The skill definition and format reference
  README.md              This file
  PROFILE-TEMPLATE.md    Structure for the profile written on first run
  examples/              One worked example per format
    observation.md       The Observation
    number.md            The Number
    before-after.md      The Before/After
    question.md          The Question You Already Know the Answer To
    polarising.md        The Polarising Statement
    unspoken-truth.md    The Unspoken Truth
    method.md            The Method
```

## Install in Claude Code

**From the download**, copy the whole folder into your skills directory:

```bash
cp -r linkedin-post-generator ~/.claude/skills/
```

**From the repo**, clone it straight in:

```bash
git clone https://github.com/tinctu-re/linkedin-post-skill ~/.claude/skills/linkedin-post
```

Either way `SKILL.md` must sit one level inside `skills/`, alongside its `examples/` folder. Use `.claude/skills/` inside a project instead if you only want it there.

Claude Code reads `SKILL.md` and its frontmatter on start, so restart any running session. Then invoke it:

```
/linkedin-post [your bullet points or rough idea]
```

## Install in Claude.ai Projects

Create or open a Project, then add `SKILL.md` under Project knowledge. Add the files in `examples/` too if you want Claude to match their register. Then ask for a LinkedIn post in the normal way.

## First run: about five minutes

The first time you invoke it, it does not write a post. It asks you six questions:

1. What do you do, and who for? One or two sentences, how you would say it out loud rather than how it reads on your profile.
2. What are your two or three core topics? The things you want to be known for.
3. Who do you want reading this? Roles, industries, or just the kind of person.
4. How do you talk? Give a phrase you use often, and something you would never say.
5. What can you draw on? Numbers you know, work you have done, stories you already tell people.
6. Anything off limits? Clients you cannot name, numbers you cannot share, subjects you avoid.

Your answers are saved to `linkedin-profile.md` next to the skill. Every draft after that is written against them, so you never re-explain who you are.

Short answers are fine. Skip anything you would rather not answer.

## Every run after

```
/linkedin-post [idea]
format: observation
voice: direct, no corporate speak
```

Both flags are optional. The profile does the heavy lifting.

If your idea strays outside the core topics you named, the draft still gets written, with one line at the end telling you it is off-thread. That is not style policing. LinkedIn now reads your profile and your posts as one entity, so scattering across unrelated subjects costs reach.

## Changing your profile

Edit `linkedin-profile.md` directly whenever you like, or tell the skill what changed and it will update the file. Delete it to run the interview again from scratch.

## Who it is for

Anyone posting on LinkedIn. Founders, consultants, freelancers, engineers, marketers, researchers, people changing career. It takes its subject matter from what you give it and does not assume you work in tech.

## Tips

- Start from something real: something you noticed this week, a number you just checked, a decision you made.
- Paste rough notes. Structuring them is the skill's job.
- Re-invoke with a different `format` flag to see the same material a different way.
- The draft is a draft. Edit it until it sounds like you, because the point is that it sounds like you.

## Why the rules look the way they do

LinkedIn ranks on dwell time, saves and semantic relevance now, not on likes and tags. So this skill writes no hashtags, never closes with an engagement question, keeps calls to action out of the post body, and front-loads the hook into the first 140 characters. Posts that teach something specific enough to save are the ones that travel.

## From Tincture

A companion to the LinkedIn Playbook at tinctu.re/tools/linkedin-playbook, which covers the weekly workflow, the daily engagement habit, and how to read LinkedIn as a pipeline signal.
