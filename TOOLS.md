# TOOLS.md - Local Environment Notes

## CLI Tools Available

| Tool | Purpose | Auth |
|------|---------|------|
| `gh` | GitHub CLI | ✅ Authenticated as dsmithnh3 |
| `sag` | ElevenLabs TTS | ✅ API key configured |
| `whisper` | Local speech-to-text | ✅ Local |
| `peekaboo` | macOS UI automation/screenshots | ✅ Local |
| `memo` | Apple Notes CLI | ✅ Local |
| `remindctl` | Apple Reminders CLI | ✅ Local |
| `ffmpeg` | Video/audio processing | ✅ Local |
| `jq` | JSON processing | ✅ Local |
| `clawhub` | Skill marketplace management | ✅ v0.6.0 |
| `python3` | Python 3 | ✅ Local |
| `node` | Node.js v22 (via nvm) | ✅ Local |

## SSH Hosts

- `luna@openclaw.local` (10.0.0.2) — Mac Mini server, runs remote OpenClaw gateway

## Services

- **n8n:** http://localhost:5678 (automation workflows)
- **OpenClaw Gateway (local):** localhost:18789
- **OpenClaw Gateway (remote):** luna@openclaw.local:18789 (via SSH tunnel)

## GitHub

- **Username:** dsmithnh3
- **Auth:** `gh` CLI authenticated, SSH key configured

## TTS Notes

- `sag` is installed but may need ElevenLabs API key verification
- For voice storytelling, use engaging voices — surprise with character voices for stories
