# ADHD Life Dashboard V7 — Fixed

This fixed V7 build resolves two issues in the previous V7:

1. The app was still using the V4 storage key at runtime, which could cause imported V5 data and the Today screen to use different data stores.
2. Today task cards did not expose their task IDs, so the V7 inline editor could not reliably attach.

The fixed build:
- Uses `adhd_dashboard_v7` as the active runtime store.
- Migrates V3/V4/V5/V6 data into V7 on startup.
- Imports V5 JSON backups into the same active V7 store.
- Adds `Edit details` to Today task cards.
- Lets you edit probable time, energy, and priority directly from Today.
- Keeps the existing habit tracker, themes, goals, backup, and PWA features.

## Important
If you already imported your V5 backup into the previous V7, that backup is not lost. This build reads the existing V7/V6/V5/V4/V3 local storage data and migrates it into the fixed V7 store.

Recommended test:
1. Open the fixed V7.
2. Go to Today.
3. Find an open task.
4. Click `⚙️ Edit details`.
5. Change time/energy/priority and click Save.
6. Refresh the page and confirm the changes remain.
