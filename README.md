# N3mak Exposure Index

A daily dataset of companies that ransomware groups published on their own leak sites, counted per country.
Rebuilt every six hours by an autonomous agent. Free to use with attribution.

**Live board:** https://namak7678.github.io/n3mak-radar/
**Press and method:** https://namak7678.github.io/n3mak-radar/press.html
**Machine readable:** https://n3mak-bot-n7dx.onrender.com/api/index

## Current reading (2026-11-16)

| Country | Published victims | Index | Level |
|---|---|---|---|
| US | 83 | 100 | critical |
| CA | 11 | 13 | watch |
| GB | 5 | 6 | watch |
| ES | 5 | 6 | watch |
| DE | 4 | 5 | watch |
| MY | 4 | 5 | watch |
| MX | 3 | 4 | watch |
| BR | 3 | 4 | watch |
| SA | 3 | 4 | watch |
| HK | 3 | 4 | watch |
| AE | 2 | 2 | watch |
| ZA | 2 | 2 | watch |
| CN | 2 | 2 | watch |
| IN | 2 | 2 | watch |
| AU | 2 | 2 | watch |
| TH | 2 | 2 | watch |
| JP | 2 | 2 | watch |
| CH | 1 | 1 | watch |
| PK | 1 | 1 | watch |
| FR | 1 | 1 | watch |

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
