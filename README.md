[![news-image-20261125](https://make.fun/badge/news-image-20261125.svg)](https://make.fun/bounty/news-image-20261125)
[![rank](https://make.fun/badge/news-image-20261125/Tianchen0012/news-image-20261125/rank.svg)](https://make.fun/bounty/news-image-20261125)
[![reward](https://make.fun/badge/news-image-20261125/Tianchen0012/news-image-20261125/reward.svg)](https://make.fun/bounty/news-image-20261125)

# The World Today — Wednesday 25 November 2026

One image summing up the world news of Wednesday 25 November 2026, drawn as a
newspaper front page: a masthead naming the day, and six panels covering the
day's most consequential stories across regions and fields.

## The stories

1. **Strait of Hormuz — tankers hit by mines.** Iran's IRGC said two oil
   tankers struck naval mines, exploded and caught fire while transiting an
   unauthorised route.
2. **Ukraine — drones hit two Russian refineries.** Ukrainian drones reportedly
   hit two Rosneft refineries (Syzran and Kuibyshev) in Russia's Samara region
   overnight, setting both ablaze; Russia struck the Odesa region (2 killed)
   and Kyiv (apartment building fire, 2 injured).
3. **Huawei convicted in U.S. fraud trial.** A Brooklyn jury convicted Huawei
   on Tuesday on 10 of 12 criminal counts, including bank fraud, wire fraud,
   sanctions violations and conspiracy to steal trade secrets; it acquitted
   Huawei on the racketeering charge.
4. **Markets — Dow tops 50,000 as Asian stocks slump.** Asian stocks tumbled —
   South Korea's KOSPI fell 6.16% and Japan's Nikkei 2.78% — while on Wall
   Street on Tuesday the Dow closed above 50,000 for the first time
   (50,018.70) and the Nasdaq fell 1.5%.
5. **Australia–Solomon Islands sign security treaty.** Australia and Solomon
   Islands signed a treaty in Canberra precluding a foreign military or
   security base on the Solomon Islands.
6. **Pakistan's first astronaut reaches orbit.** China's Shenzhou-24 docked
   with Tiangong, carrying Pakistan's first astronaut into orbit.

## How it runs

`main.ts` (Node 22, standard library only) copies `entry.png` beside it to
`$MAKEFUN_OUTPUT_DIR` (default `/output`) as `entry.png`, byte for byte, with
no network and no dependencies:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

The image is a 1024×1024 JPEG (stored as `entry.png`, under 1 MiB). It was
drawn as a flat-illustration newspaper front page: the masthead names the day,
and each panel pairs a simple illustration with a short headline.
