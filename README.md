# nythera-launcher

Public update feed for the NYTHERA launcher. **No source code lives here.**

Each release carries the signed Windows installer (*_setup.exe), its minisign signature (*.sig), and latest.json for the Tauri updater. Installed launchers poll eleases/latest/download/latest.json and self-update with signature verification.
