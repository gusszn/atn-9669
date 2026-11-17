# ADHD Life Dashboard V7 — Gear Edit Fix

This build fixes the duplicate edit controls on the Today screen.

## What changed
- Removed the legacy V6 `✏️ Edit` button injection.
- Kept only the V7 `⚙️ Edit` control.
- Changed the label from `Edit details` to `Edit`.
- Fixed the V7 inline editor task lookup so the gear/Edit control opens correctly.
- Existing V5/V6/V4/V3 migration and V5 JSON import support remains intact.

## Important
You do NOT need to delete your V5 backup or manually rebuild your tasks.

If you are currently running an older V7 build, replace it with this build so the old V6 button code is no longer running.
