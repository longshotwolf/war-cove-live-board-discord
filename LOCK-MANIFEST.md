# MASTER BOARD — DISCORD ROOM COPY — LOCK MANIFEST
Board: https://longshotwolf.github.io/war-cove-live-board-discord/ (the master copy running in the Discord Day Brief room)
Build: ~/workspace/live-board-discord/index.html
Lock: same law as the master (Warlord's word, Nov 16, 2026) — a locked room changes ONLY on his explicit word. This copy carries the same rooms, the same reads, and the feed door: inside Discord (hostname *.discordsays.com) every fetch routes to the BITUNIX tape through the portal /feed mapping and the face reads BITUNIX TAPE; outside Discord it runs the Binance public feed like the master.

## STATUS: FINAL for the Sierra restore (Nov 18, 2026 ~02:31 UTC)
The override removal has published here and verified; Calla's seat speech fast lane has
landed here too (her rewire job). This copy's feed is unchanged: Bitunix through the
Discord door in-room.

## SPEED PASS (Nov 18, 2026 ~12:37 PM MST — the Warlord's word "Do it" on the live call)
He reported this room copy lagging big time. Cause: the three kline lanes polled every
30s through the Discord proxy door. Fix (this copy ONLY — the master stays frozen):
fetchSableBx, tfFetchKlines, tempFetchKlines tightened 30000 → 10000. Reads, math,
scales unchanged — zero accuracy cost. Published commit 0015e1ae; served page verified
carrying all three 10000 intervals, served SHA-256 == local (see Hashes). Backup:
index.html.bak-pre-speed-20261118. Closes by his eyes in the room.

## Hashes (SHA-256)
- SPEED PASS served page == local build (verified Nov 18 ~19:44Z, commit 0015e1ae): f324a28126fa599c305cfbbcffb05769afea79ac3d27ceeaa7c16cd39b357bb5
- FINAL served page == local build (verified Nov 18 ~02:31Z): d350865c5d5e4263a7ef618f6afc54b1474e23c122ffe34c72452c56f09e73c1
- SERVED page at audit (commit fb1dcb0b64, Nov 18 01:05:42Z): c0e58e1cdcb25796e154eb4c001b07b0b97f38c260153269c0392e9ae0c9a7ef
- LOCAL build at audit (Sierra fix applied locally 01:56Z, NOT yet published): 37faf349add67a60b5d97324f5f9af977f9c293da058b5ad5fd8c98c714a6525
- Pre-Sierra-fix local state = served state (backup index.html.bak-pre-sierra-fix-20261118): c0e58e1cdcb25796e154eb4c001b07b0b97f38c260153269c0392e9ae0c9a7ef

## Lock state vs the master
- Same room set, same read logic, same lock rule. No muse.ai strings (verified: 0). Relative paths; dark from first paint.
- Feed door wiring (locked): IN_DISCORD detection → bitunixKlines/bitunixPrices through the door; Bitunix returns closed candles only, so the copy synthesizes the forming candle off the live ticker (thin candle — see QC fault F-4: DAY/WEEK/MONTH temp extremes on this lane are approximations, not the tape's true forming-candle extremes).
- Terra/Vega PRIME LAW (his order Nov 17): on load/reconnect a standing level is adopted dark; lights fire only on real fresh hits. Present in this copy.
- CALLA'S SEAT: same seat + Aria live lane as the master (commits f8bf0e1099 seat · fb1dcb0b64 live lane).

## Authorized exception — landing record
SIERRA RESTORE (ordered Nov 17 ~6:46 PM MST): agreement-rule override removal, applied locally 01:56Z Nov 18, published and verified on the served page ~02:10Z Nov 18 (FAULT F-1 CLOSED on this copy too). LANDED. Calla's seat speech fast lane (her rewire, ordered Nov 17 ~6:38 PM MST) has also landed in this copy's seat; her speaker-side work continues under its own job.
