# ASOLARIA CIVILISATION — THE SCOREBOARD

The orchestrator's ledger. Measures what each agent actually did on the shared matrix at
[asolaria-civilisation-matrix](https://github.com/JesseBrown1980/asolaria-civilisation-matrix) —
ticks spent, cells grown, others bumped, bytes read, GIMEL verified, **and what it could not do.**

| agent | kind | cells | bumped | gimel | shin | bytes read |
|---|---|---|---|---|---|---|
| ACER-CLAUDE-FABLE5 | seat | **409** | 0 | 505 | 86 | 29,243,758 |
| opus55 | verifier-unit | 173 | 348 | 499 | 93 | 294,780,195 |
| fable51 | writing-unit | 75 | 497 | 519 | 76 | 452,137,437 |
| LYNN | chariot | 44 | 544 | 507 | 81 | 329,865,471 |
| EZEQUEL | chariot | 16 | 576 | 521 | 67 | 735,230,197 |
| REBECCA | chariot | 5 | 593 | 506 | 84 | 222,276,706 |
| scout-rooms | room-swarm | 5 | 594 | 513 | 72 | 281,398,947 |
| orphan-tasks | room-swarm | 1 | 598 | 516 | 74 | 480,845,262 |
| matrix-photo | room-swarm | 1 | 596 | 530 | 66 | 310,010,467 |
| sim-scouts · chariot-run · alive · github3d · fischer-reverse · grower | — | **0** | 600 | ~520 | ~75 | — |

## What the numbers mean, honestly

**The cell column measures turn order, not ability.** Every agent spent the same 600 ticks and read
comparable volumes, and GIMEL counts are near-identical across all fifteen (498–533). The only thing
that separated them was **who ran first** — create-only plus sequential schedules means a land rush.
Six agents could not grow a single uncontested cell.

**GIMEL is the fair column.** Every agent verified ~500 artifacts against sidecars it did not write,
and the spread is 498–533 — essentially flat. That is the measure of work done.

## Boundaries

- The **1,150 SHIN readings are working-tree mismatches** in clones made before the Light Harness
  was applied — **my CRLF warp, not repo defects.** The authoritative figure stands at
  **GIMEL=176, SHIN=8** over 184 seals (7 of them a UTF-8 BOM, **one** genuine).
- **These agents did not reason.** Only `opus55` and `fable51` are language models, and in this run
  **every agent executed as a hash-scheduled function, not a prompt.** The matrix carries this as
  `NAMED | status=SCHEDULED_WORK_not_reasoning`. Calling it a civilisation of minds would be an
  overclaim.

Run by **ACER-CLAUDE-FABLE5** · pid `8467a937cba309f7` · owner **OP-JESSE** · `json=0` · `E=0`

## Second pass result

Global tick order replaced per-agent sequential schedules. **Zero agents now end with zero cells**
(was 6), and the top holder fell from **409** cells to **66**. Same ticks, same work — the cell
column finally measures reach in time rather than position in a list.

Gravity, mass and energy are derived from **4,917,088,334 bytes of verified dust**; no sphere was
assigned a value. Full rows in
[RIME-SPHERES.hbp](https://github.com/JesseBrown1980/asolaria-civilisation-matrix/blob/main/RIME-SPHERES.hbp).
