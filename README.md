# My Life — ADHD Dashboard V2

This is a standalone Progressive Web App (PWA) starter.

## What is included
- Today dashboard
- Brain dump
- Time estimates
- Energy levels
- "I'm Stuck" mode
- Quick wins
- Make Smaller starter steps
- Goals and next actions
- Done/progress view
- Export/import backup
- PWA manifest
- Offline service worker
- App icons

## Important
V2 stores data locally on the device. This means the same data does NOT automatically sync between devices yet.

For true multi-device sync:
1. Create a Supabase project.
2. Add authentication.
3. Create a tasks/goals database with Row Level Security.
4. Replace localStorage operations in index.html with Supabase calls.
5. Host the PWA over HTTPS (GitHub Pages is one simple option).
6. Install the PWA on each device.

Do not put sensitive information in a public GitHub repository.
