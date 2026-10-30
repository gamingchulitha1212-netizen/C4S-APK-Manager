from pathlib import Path

content = "# [C4S-APK-Manager](https://github.com/gamingchulitha1212-netizen/C4S-APK-Manager/releases/latest)\n"
path = Path("/mnt/data/README_linked.md")
path.write_text(content, encoding="utf-8")
print(f"Created: {path}")
