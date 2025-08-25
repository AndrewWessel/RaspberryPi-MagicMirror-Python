# Mirror

Touchscreen smart mirror (Raspberry Pi 4, Python). Modules:
UI (PyQt/Kivy), phone control (FastAPI), LEDs, air quality sensors,
Google Calendar, Face/PIN lock.

## Quick start
1. `cp config.example.yaml config.yaml` and `cp .env.example .env`
2. `python3 -m venv .venv && source .venv/bin/activate`
3. `pip install -r requirements.txt`
4. `python -m src.main`   # run
5. (Optional) install systemd service in `deploy/systemd/mirror.service`

## Repo map
See folder tree above.

## Hardware
See `docs/HARDWARE.md`.

## Security
LAN-only, tokens, hashed PINs — `docs/SECURITY.md`.
