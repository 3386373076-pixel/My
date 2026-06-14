# Codex Skills Backup

Backup of user-installed Codex skills from `C:\Users\袁锐\.codex\skills`, excluding the built-in `.system` skills.

To restore, copy the directories under `skills/` into your Codex skills directory:

```powershell
Copy-Item -Recurse .\skills\* $env:USERPROFILE\.codex\skills\
```

Restart Codex after restoring.
