# NPC RT Target Delineation — Precision Skull Base Skill

Radiotherapy target volume delineation for nasopharyngeal carcinoma at millimeter-level anatomical precision, based on Lancet Oncology 2025 and Red Journal IG-2024 International Guidelines.

## What This Skill Does

NPC target delineation requires extreme anatomical precision — individual skull base foramina, cavernous sinus walls, perineural pathways. This skill provides:

1. **Skull base foramen boundaries** — foramen lacerum, ovale, rotundum, superior orbital fissure, optic canal (each with mm-level CT landmarks)
2. **Cavernous sinus anatomy** — four walls, Meckel's cave, stepwise coverage rules
3. **Three-tier CTV construction** — 0 → 70 Gy, +5 → 60 Gy, +5 → 54 Gy (Lancet standard)
4. **NPC-modified lymph node levels** — with explicit boundary differences from standard Robbins
5. **AJCC 9th Edition staging** — ENE → N3b, lateral pterygoid as T2/T4 cutpoint

## Quick Install

### Hermes Agent
```bash
hermes skills install https://raw.githubusercontent.com/antica1/npc-rt-target-delineation/master/SKILL.md
```

## Trigger Keywords

`NPC target` `nasopharyngeal carcinoma` `skull base foramen` `cavernous sinus` `Rosenmuller fossa` `鼻咽癌靶区`

## Key References

- Tang LL et al. *Lancet Oncol*. 2025. PMID:40907526 (Primary)
- Tang LL et al. *Lancet Oncol*. 2025. PMID:40907527 (Neck)
- Lin SJ et al. *Int J Radiat Oncol Biol Phys*. 2025. PMID:40419028 (IG-2024)
- AJCC/UICC 9th Edition. 2025.

## Author

Zhu Guopei, MD — Shanghai Ninth People's Hospital. Contact: antica@gmail.com

## License

MIT
