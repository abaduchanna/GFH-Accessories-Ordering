# GFH Accessories Ordering

GFH Telecom accessories ordering automation for VidaPay — automated ordering flow with the fixed-header grid UI and GFH branding.

## App

| File | Purpose |
|------|---------|
| `GFH_Accessories_Ordering.py` | Accessories ordering automation |

## Build

- **Locally:** run `build_GFH_Accessories_Ordering.bat` — force-syncs this repo from GitHub (self-heals origin, resets to `origin/main`), then builds the exe with PyInstaller into `C:\Users\AbadUmairChanna\Downloads\GitHub`.
- **CI:** every push to `main` builds the exe on GitHub Actions and publishes a **GFH Build N** release with the exe attached.

## Support modules

- `logo_handler.py` — GFH Telecom logo/icon loading (shared)
- `theme_manager.py` — dark theme helpers (shared)
- `header_manager.py` — fixed-header grid UI manager
- `assets/`, `gfh_icon.ico`, `GFH_Telecom_Logo.png`, `stores.json` — bundled resources referenced by the `.spec` file
