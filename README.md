# news-image-20261124

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/BIDGDCB/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

Sum up 24 November's world news in one image — entry for the make.fun
competition [news-image-20261124](https://make.fun/bounty/news-image-20261124)
($100 prize pool, entries close 2026-11-26T00:00:00Z).

`main.ts` (Node 22, standard library only) validates the repository's
`entry.png` — a 1024x1024 PNG front page — and copies it to
`/output/entry.png`.

## The six stories — Tuesday 24 November 2026

1. **14 nations back the ICJ genocide ruling** — the UK, Spain, Canada and
   11 more affirm the International Court of Justice found Myanmar guilty
   of genocide against the Rohingya.
2. **NATO vows space defence** — Mark Rutte pledges the alliance will
   defend space after reports Russia may launch a nuclear-armed satellite,
   dubbed Sputnik-S, within 60 days.
3. **UN chief seeks AI rules within a year** — António Guterres calls for a
   multilateral framework to manage AI risks.
4. **Quake hits Nepal** — a magnitude 5.6 earthquake strikes near the
   Chinese border.
5. **US drone helped catch El Chapo Isidro** — a US surveillance drone
   helped capture cartel boss Fausto Isidro Meza Flores; Mexico will try
   him despite a US extradition request.
6. **China sentences spy to death** — an official surnamed Ma is condemned
   for spying for a foreign country.

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
