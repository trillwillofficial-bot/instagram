# Instagram agent

The skills in `.claude/skills/` keep their working files in `~/.instagram-agent/`
(voice.md, log.md, plan.md, swipe.md). Cloud sessions start with an empty home
folder, so the repo keeps a copy in `instagram-agent/`.

At the start of any Instagram task, if `~/.instagram-agent/voice.md` is missing,
copy it over first:

    mkdir -p ~/.instagram-agent && cp -n instagram-agent/*.md ~/.instagram-agent/

`instagram-agent/voice.md` is the voice profile for @trillwillofficial. Every
caption, script, comment, reply and DM follows it.
