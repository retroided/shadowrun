# Shadowrun

## Revitalization Hack

### Overview

In the tabletop *Shadowrun* lore, removing cyberware initially left behind an "Essence Hole" — a void of spent Essence capacity that could only be refilled with new implants, never restored to your
natural biological total. It wasn't until "4th Edition" ("Augmentation") and "5th Edition" ("Chrome Flesh") that biotech clinics introduced "Revitalization" therapy — a costly, month-long cellular
treatment capable of slowly regenerating lost `Essence` back to natural meat. Because the *Sega Genesis* original predates these mechanics, it permanently locks runners into whatever cyberware setup
they start with.

Unfortunately, both the vanilla game and many ROM hacks saddle recruitable runners with inefficient or flat-out broken cyberware that permanently wastes their `Essence` capacity:

- `Hand Razors` & `Spurs`: Useless on non-melee combat oriented runners.
- `Muscle Replacement`: `Quickness` bonuses in vanilla only affect *movement speed*, not targeting (`Target Number`) or *combat rolls*.
- `Dermal Plating`: `Body` bonuses in vanilla only apply to raw *defense*, failing to expand *health pool*, improve `Medkit` healing efficiency (which scales every `3` `Body`), or boost *physical
  magic resistance*.

Even when bug-fix patches resolve these mechanical issues, runners remain stuck with suboptimal implants - like `Deckers` locked into `Hand Razors`, or `Street Samurai` left with just `0.1` `Essence`,
forcing them to rely on inferior `Smart Goggles` instead of proper `CyberEyes`.

**"Revitalization"** wipes **ALL** starting cyberware from **EVERY** `mundane` runner and resets their `Essence` to a clean `6.0`.

### Key Trade-offs

**Pros:**

- Complete freedom to build and customize every `Street Samurai` and `Decker` exactly as you see fit.

**Cons:**

- Building up runners from scratch requires a significant nuyen investment, making team progression considerably more expensive without money cheats.

### Affected Shadowrunners

Starting cyberware removed and `Essence` restored to `6.0` for all `mundane` runners:

| Shadowrunner         | Vanilla Starting Cyberware                                                       | Essence |
|:---------------------|----------------------------------------------------------------------------------|:-------:|
| **Ilene Two Fists**  | Datajack, Hand Razors, Wired Reflexes (1)                                        |   3.4   |
| **Joshua (Decker)**  | Datajack                                                                         |   5.5   |
| **Joshua (Samurai)** | Datajack, Hand Razors                                                            |   5.4   |
| **Petr Uvehr**       | Datajack                                                                         |   5.5   |
| **Phantom**          | Datajack, Hand Razors, Wired Reflexes (1)                                        |   3.4   |
| **Rianna Heartbane** | Datajack, Smartlink, Wired Reflexes (2)                                          |   0.5   |
| **Stark**            | CyberEyes, Spurs, Muscle Replacement (1), Dermal Plating (3), Wired Reflexes (2) |   0.1   |
| **Winston Marrs**    | Hand Razors, Muscle Replacement (1), Wired Reflexes (1)                          |   2.9   |

Original: [GitHub Repository](https://github.com/retroided/shadowrun/)
