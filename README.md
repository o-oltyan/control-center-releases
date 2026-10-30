# Control Center — release builds

Builds only; the source lives in a private repository.

## Mac
1. Download `ControlCenter-<version>.dmg` from the [latest release](../../releases/latest).
2. Open it and drag **Control Center** onto **Applications**.
3. First launch only: macOS says it can't verify the developer (the app isn't notarized). Right-click the app → **Open** → **Open**, or System Settings → Privacy & Security → **Open Anyway**.

After that, updates install from inside the app: Settings → General → **Check for updates** (or the app menu → Check for Updates…).

## iPhone (SideStore)
Add this source in SideStore: `https://raw.githubusercontent.com/o-oltyan/control-center-releases/main/source.json`, then install **Control Center**. SideStore keeps it signed on the phone. Setup steps: see the Control Center Mac app, Settings → iPhone.
