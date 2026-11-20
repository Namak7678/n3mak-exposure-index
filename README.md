# N3mak Exposure Index

A daily dataset of companies that ransomware groups published on their own leak sites, counted per country.
Rebuilt every six hours by an autonomous agent. Free to use with attribution.

**Live board:** https://namak7678.github.io/n3mak-radar/
**Press and method:** https://namak7678.github.io/n3mak-radar/press.html
**Machine readable:** https://n3mak-bot-n7dx.onrender.com/api/index

## Current reading (2026-11-20)

| Country | Published victims | Index | Level |
|---|---|---|---|
| US | 204 | 100 | critical |
| CA | 24 | 12 | watch |
| GB | 16 | 8 | watch |
| DE | 12 | 6 | watch |
| IN | 8 | 4 | watch |
| MX | 8 | 4 | watch |
| ES | 7 | 3 | watch |
| JP | 6 | 3 | watch |
| AU | 5 | 2 | watch |
| AR | 5 | 2 | watch |
| MY | 5 | 2 | watch |
| AE | 5 | 2 | watch |
| SA | 4 | 2 | watch |
| FR | 4 | 2 | watch |
| VN | 4 | 2 | watch |
| IT | 4 | 2 | watch |
| PH | 4 | 2 | watch |
| BR | 4 | 2 | watch |
| CO | 3 | 1 | watch |
| IE | 3 | 1 | watch |

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
