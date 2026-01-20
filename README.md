# Puttty

Puttty is a Windows 11+ SSH client project focused on a clean WinUI 3 experience and a reliable session core.

## Current Scope

- Quick-connect flow with host, port, and username validation.
- Session profile model for storing basic connection metadata.
- WinUI 3 scaffold with a quick-connect input row and status output area.

## Repository Layout

- `src/core`: core models and quick-connect logic.
- `src/ui`: WinUI 3 XAML and code-behind.

## Next Steps

- Add persistence for session profiles.
- Implement SSH transport/protocol layers.
- Expand UI for saved profiles and session tabs.
