# N3mak Exposure Index

A daily dataset of companies that ransomware groups published on their own leak sites, counted per country.
Rebuilt every six hours by an autonomous agent. Free to use with attribution.

**Live board:** https://namak7678.github.io/n3mak-radar/
**Press and method:** https://namak7678.github.io/n3mak-radar/press.html
**Machine readable:** https://n3mak-bot-n7dx.onrender.com/api/index

## Current reading (2026-11-17)

| Country | Published victims | Index | Level |
|---|---|---|---|
| US | 118 | 100 | critical |
| CA | 19 | 16 | watch |
| GB | 9 | 8 | watch |
| DE | 8 | 7 | watch |
| IN | 6 | 5 | watch |
| ES | 5 | 4 | watch |
| MY | 5 | 4 | watch |
| AU | 4 | 3 | watch |
| SA | 4 | 3 | watch |
| MX | 3 | 3 | watch |
| HK | 3 | 3 | watch |
| JP | 3 | 3 | watch |
| BR | 3 | 3 | watch |
| PH | 3 | 3 | watch |
| AE | 3 | 3 | watch |
| PE | 2 | 2 | watch |
| ID | 2 | 2 | watch |
| IT | 2 | 2 | watch |
| KW | 2 | 2 | watch |
| TH | 2 | 2 | watch |

The index scales the country with the largest share of published victims in the window to 100.

## Use it

    curl -s https://n3mak-bot-n7dx.onrender.com/api/index

Badge for any country, updates itself:

    <img src="https://n3mak-bot-n7dx.onrender.com/badge/NL.svg" height="26" alt="NL exposure index">

## What this is not

It counts only companies the groups published themselves, so quiet incidents are invisible. It is not a
penetration test, it never claims a breach, and it does not probe any network.

## Licence

Data may be reused with attribution to "N3mak Exposure Index".
