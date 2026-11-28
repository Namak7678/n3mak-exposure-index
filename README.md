# N3mak Exposure Index

A daily dataset of companies that ransomware groups published on their own leak sites, counted per country.
Rebuilt every six hours by an autonomous agent. Free to use with attribution.

**Live board:** https://namak7678.github.io/n3mak-radar/
**Press and method:** https://namak7678.github.io/n3mak-radar/press.html
**Machine readable:** https://n3mak-bot-n7dx.onrender.com/api/index

## Current reading (2026-11-28)

| Country | Published victims | Index | Level |
|---|---|---|---|
| US | 290 | 100 | critical |
| CA | 37 | 13 | watch |
| DE | 29 | 10 | watch |
| GB | 24 | 8 | watch |
| IN | 16 | 6 | watch |
| IT | 15 | 5 | watch |
| ES | 12 | 4 | watch |
| MX | 11 | 4 | watch |
| JP | 9 | 3 | watch |
| FR | 9 | 3 | watch |
| AU | 7 | 2 | watch |
| PH | 7 | 2 | watch |
| AR | 6 | 2 | watch |
| BR | 6 | 2 | watch |
| CO | 6 | 2 | watch |
| VN | 5 | 2 | watch |
| MY | 5 | 2 | watch |
| CH | 5 | 2 | watch |
| ID | 5 | 2 | watch |
| TW | 5 | 2 | watch |

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
