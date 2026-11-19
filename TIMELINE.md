# Timeline

The pace of the fork, day by day. Each phone build changes one variable from the build before,
with its predictions written down first. What each fix changed stays private until it goes
upstream.

| Date | Phone builds | What happened |
|---|---|---|
| Nov 3 | 2 | Fork set up so test builds install beside stock Winlator; guest errors routed to the Android log; first Mewgenics hypotheses tested |
| Nov 4 | 6 | Mewgenics: two hypotheses refuted, the third confirmed; a second failure found and fixed. **Mewgenics renders and plays.** StS2 work starts |
| Nov 5 | 19 | StS2: 14 builds, many logging-only. **StS2's menu renders** on the ninth. Then 5 builds of input fixes found while playing |
| Nov 6 | - | Unit tests run on every build; app-update and desktop fixes |
| Nov 9-12 | 2 | FPS counter (77 tests, mutation gate); probe suite harness, Mac gate and first Vulkan probes |
| Nov 15-18 | 2 | DualSense pass-through (codec, USB parsing, socket server, Wine-side driver); more probes; FPS log rotation |
