# Crawles plugin starter

An example plugin for the Crawles directory: two ready-made automations and two AI skills.

- `crawles-plugin.json` describes the plugin (name, version, templates, skills).
- `skills/<name>/SKILL.md` holds each skill: a short `---` block with its name and description, then the instructions.

To release an update, raise `version` in `crawles-plugin.json` and push.
