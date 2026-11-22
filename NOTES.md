# NOTES — news-image-20261121 audit trail

Entry: one 1024×1024 PNG (`entry.png`, 137,321 bytes) summing up the world
news of Saturday 21 November 2026, rendered deterministically with Python/PIL
(render script kept outside the repo: `~/workspace/makefun/render_news_image_20261121.py`).
Two independent renders produced identical bytes:

- SHA-256: `a4938433cfd32c471c988cd6ee698365f241a1a0469a4c9a4dfaf429767a699f`
- `main.ts` (Node 22, stdlib only) copies `entry.png` to the grader's output
  directory; no network, no shell, no subprocess.

## The six stories — each verified against a live wire page on 2026-11-21

1. **Russian missiles crash into Poland; Tusk calls it a deliberate provocation**
   — 20 Nov first report, leading 21 Nov digests. BBC, 2026-11-20:
   https://www.instagram.com/reel/Df-z9AoAmnW/ (BBC News report);
   Channel 4 News, 2026-11-20:
   https://www.instagram.com/reel/Df90ZP3Bxo2/
   Two Kh-101 cruise missiles and a jet-powered drone came down at three
   sites in eastern Poland (Nowy Lipowiec, Rudnik nad Sanem, Mołodycz);
   Polish jets scrambled; PM Donald Tusk: not an accident, looks like an
   intentional provocation.
2. **Russia hits Kyiv's three Dnipro bridges in retaliatory barrage, eight killed**
   — 20 Nov first report (Reuters wire). Reuters via SRN, 2026-11-20:
   https://srnnews.com/fire-broke-out-in-ukraines-kyiv-after-missile-strike-mayor-says/
   and CNA, 2026-11-20:
   https://www.channelnewsasia.com/world/russia-strike-ukraine-invasion-putin-missile-drone-6568896
   More than 400 drones and 110 missiles; six killed in Kyiv, two in Lviv;
   Podilsko-Voskresenskyi, Darnytskyi and Pivdennyi bridges hit; Putin had
   vowed a "painful" response to Ukraine's strikes on the Crimean bridge.
3. **Denmark foils Russian plot to kill US-Ukrainian rapper; expels defence attache**
   — 20 Nov first report. Reuters, 2026-11-20 (page read live 2026-11-21):
   https://www.reuters.com/world/europe/two-danes-suspected-being-hired-by-russia-kill-us-ukrainian-rapper-2026-11-20/
   Danish police arrested three men before rapper Kyivstoner's 25 September
   concert; PET: the attempt was planned by Russian intelligence services.
4. **US court sentences Nikhil Gupta to 235 months in Pannun murder plot**
   — 20 Nov first report. Reuters, 2026-11-20:
   https://www.reuters.com/world/us/indian-man-sentenced-more-than-19-years-us-plotting-kill-sikh-separatist-2026-11-20/
   Judge Victor Marrero, Manhattan federal court; Gupta pleaded guilty to
   murder-for-hire over the plot against Sikh separatist Gurpatwant Singh
   Pannun.
5. **Anthropic researcher says Claude solved the Riemann Hypothesis**
   — 20 Nov first report. AFP via The Hindu Morning Digest, 2026-11-21:
   https://www.thehindu.com/news/morning-digest-november-21-2026/article71726209.ece
   An Anthropic mathematician said on Friday that Claude had proved the
   Riemann Hypothesis, unsolved for more than 160 years.
6. **Myanmar rejects ICJ genocide verdict as unfair**
   — 21 Nov follow-up. AFP via The Manila Times, 2026-11-21:
   https://beta.manilatimes.net/news/world/page/1340
   Myanmar called the ICJ's ruling that its 2017 campaign against the
   Rohingya was state-sponsored genocide unfair.

## First-publication split

- 20 Nov first reports: items 1, 2, 3, 4, 5.
- 21 Nov first report / follow-up: item 6.
