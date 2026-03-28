# Install Feature Request Decoder

This skill is a folder that contains **`SKILL.md`**. Put that folder where your editor or agent loads skills, then restart. Folder name can be anything (e.g. `feature-request-decoder` or `feature-request-decoder-skill`); only the location of `SKILL.md` matters.

**Note:** Do not put custom skills in `~/.cursor/skills-cursor/`. Cursor reserves that directory for its own built-in skills.

---

## Get the files

On GitHub, use **Code** and either copy the clone URL or **Download ZIP**. If you use Git:


```bash
git clone <https://github.com/KhoshnazKazemian/feature-request-decoder-skill>
```

---

## Cursor

1. Create the skills directory if it does not exist:

   ```bash
   mkdir -p ~/.cursor/skills
   ```

2. Copy or move your project folder into `~/.cursor/skills/`, for example:

   `~/.cursor/skills/feature-request-decoder/SKILL.md`

3. Restart Cursor, or run **Developer: Reload Window** from the Command Palette.

4. In Agent chat, invoke it explicitly, for example:  
   *Use the feature request decoder skill on this stakeholder ask.*

**Per-project install:** Copy the same folder to `.cursor/skills/<your-folder-name>/` at the root of a repository so teammates get the skill with the project. Restart Cursor after it is in place.

---

## Claude

Layouts and paths depend on your Claude product (e.g. Claude Code). A common pattern is a personal skills directory:

`~/.claude/skills/<your-folder-name>/SKILL.md`

Copy this repository into that location if your setup documents it, then restart the app or start a new session.

If you have no skills directory, **attach `SKILL.md`** to a conversation or paste the relevant sections — the instructions still work.

---

## Uninstall

Delete the skill folder from `~/.cursor/skills/` or `.cursor/skills/` (and from `~/.claude/skills/` if you added it there), then restart the application.

---

For what the skill does and when to use it, see [README.md](README.md).
