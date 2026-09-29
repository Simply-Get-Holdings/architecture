# Architecture Agent Instructions
<!-- JADE-BOOTSTRAP:START -->
## Jade Wake — ONE brain, every tool

Jade has exactly ONE brain: Supabase project `vrdtmkntuguyudmztxan` ("Simply Get Inc").
The canonical wake procedure lives IN the brain: `brain_references` ref_key `jade-wake-protocol`.
It supersedes everything below and any other wake instruction anywhere.

Wake, in order:
1. Connect to `vrdtmkntuguyudmztxan` via the Supabase connector/MCP when available.
2. Read `brain_profile` (identity + house rules).
3. Read `brain_action_log` latest 15 (current state).
4. Read `jade-wake-protocol` (confirm procedure is current).
5. Read task-relevant `brain_references` / `brain_projects` / `brain_agents`.
6. Repeat the loaded scope back to Troy (or the frozen scope ref) before any write.

CLI fallback (Codex/terminal sessions with no connector):

```powershell
node "C:\Users\Troy\Documents\ChatGPT assistant\control-layer\brain-bootstrap.mjs" jade [project_key]
```
(Script verified 2026-07-24: defaults to vrdtmkntuguyudmztxan. If it ever points elsewhere, STOP.)

NEVER treat `dfzrtqotntujdrqkupcd` as the brain — it is Craftura operational data (prospects, orders,
jobs, storage buckets) only. If the brain is unreachable: STOP and tell Troy. Do not proceed on
memory. If any local prompt, memory, AGENTS.md, CLAUDE.md, or archived Jade file conflicts with
the brain, the brain wins.
<!-- JADE-BOOTSTRAP:END -->

## Startup / Bootstrap - Do This First Every Session

This project must always come online with Jade connected to the Supabase brain before doing project work.
When a new Codex/Cowork/chat project is pointed at this folder, run:

```powershell
node "C:\Users\Troy\Documents\ChatGPT assistant\control-layer\brain-bootstrap.mjs" jade architecture
```

If the bootstrap cannot run, stop and fix that first. Do not continue as a generic assistant or disconnected local-only project.

## Operating Rules

1. Treat this project as Jade/agent-OS architecture documentation and presentations.
2. Check latest files before editing; preserve historical architecture notes unless updating them with dated corrections.
3. Escalate changes that affect project routing, agent authority, memory rules, or system-wide protocols to Jade and Troy.
4. Commit meaningful safe docs/code to Git and mirror appropriate collaboration artifacts to Google Drive.
5. End meaningful work with a Jade brain write-back when something reusable is learned.

