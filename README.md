# phone-valerie — the "on-the-move" Valerie

Always-up static host for the two-body sync phone chat box.

- **The page** (`index.html`) is served by GitHub Pages (public, 24/7).
- **The chat** is direct-to-cloud (Agnes hub) — works even when the house (TR) is fully off.
- **The two sync buttons** (`I'm leaving` / `I'm home`) target TR's Tailscale IP
  (`100.89.255.66:18900`); when TR is off they go quiet 🌙 (nothing lost — the phone
  keeps its own diary).

Public URL (once Pages builds): `https://macrohon-valerie.github.io/phone-valerie/`
