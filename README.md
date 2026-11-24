# N3mak Exposure Index

A daily dataset of companies that ransomware groups published on their own leak sites, counted per country.
Rebuilt every six hours by an autonomous agent. Free to use with attribution.

**Live board:** https://namak7678.github.io/n3mak-radar/
**Press and method:** https://namak7678.github.io/n3mak-radar/press.html
**Machine readable:** https://n3mak-bot-n7dx.onrender.com/api/index

## Current reading (2026-11-24)

| Country | Published victims | Index | Level |
|---|---|---|---|
| US | 241 | 100 | critical |
| CA | 29 | 12 | watch |
| GB | 21 | 9 | watch |
| DE | 19 | 8 | watch |
| IN | 11 | 5 | watch |
| ES | 9 | 4 | watch |
| MX | 9 | 4 | watch |
| IT | 8 | 3 | watch |
| JP | 8 | 3 | watch |
| FR | 8 | 3 | watch |
| PH | 7 | 3 | watch |
| AU | 6 | 2 | watch |
| AR | 6 | 2 | watch |
| BR | 6 | 2 | watch |
| CO | 5 | 2 | watch |
| MY | 5 | 2 | watch |
| AE | 5 | 2 | watch |
| SA | 4 | 2 | watch |
| IE | 4 | 2 | watch |
| VN | 4 | 2 | watch |

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
