# Internal Protocols

Treeland compositor internals — not for general application developers. Installed via `TREELAND_PROTOCOL_INTERNAL_XML_FILES`.

| File | Protocol | Interfaces | Purpose |
|------|----------|-----------|---------|
| `treeland-app-id-resolver-unstable-v1.xml` | `treeland_app_id_resolver_unstable_v1` | `treeland_app_id_resolver_manager_v1`, `treeland_app_id_resolver_v1` | Resolve process (pidfd) to application ID for sandboxed apps |
| `treeland-prelaunch-splash-unstable-v2.xml` | `treeland_prelaunch_splash_unstable_v2` | `treeland_prelaunch_splash_manager_v2`, `treeland_prelaunch_splash_v2` | Application pre-launch splash screen control |
| `treeland-screensaver-unstable-v1.xml` | `treeland_screensaver_unstable_v1` | `treeland_screensaver_v1` | Screensaver activation and configuration |
| `treeland-wallpaper-shell-unstable-v1.xml` | `treeland_wallpaper_shell_unstable_v1` | `treeland_wallpaper_notifier_v1`, `treeland_wallpaper_shell_v1`, `treeland_wallpaper_surface_v1` | Wallpaper source notification and per-surface wallpaper binding |

