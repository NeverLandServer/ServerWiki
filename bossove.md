<div align="center">

# Bossové a Mythicmobs
Všichni momentální bossové jsou vytvoření v pluginu MythicMobs.
Zde najdeš jejich seznam a informace, odkaz na [MythicMobs Wiki](https://git.mythiccraft.io/mythiccraft/MythicMobs/-/wikis/home)

</div>

> [!NOTE]
> Všichni bossové se spawnují tak že jsou Schedulerem volány příkazy, v určitý čas.
> Každý den se spawnuje jiný vedlejší boss, celkově jich je 5.

### Warpy & Kde je Najít
- /warp hlboss - Zde najdeš arénu s hlavním bossem.
- /warp dungeon - Zde najdeš dunegony kde se spawnují vedlejší bossové.

### Seznam bossů:

> [!NOTE]
> DamageModifiers: Jsou modifikace příchozího DMG.
> Poznámka: (x + x) Skilly = Je DMG které indikuje dva různé skilly.

#### Sauron

Den: **Každý den**\
Čas Spawnu: **20:00**\
Čas Despawnu: **21:00**

HP: **10000**\
DMG: **9 Základ + (8 + 5 + 5) Skilly**\
Armor: 45\
DamageModifiers:
- ENTITY_ATTACK 0.85
- PROJECTILE 0.75
- FIRE -1
- LAVA -4
- FIRE_TICK 0 

#### Ztracený Horník

Den: **Pondělí**\
Čas Spawnu: **18:00**\
Čas Despawnu: **19:00**

HP: **900**\
DMG: **20 Základ + 10 Skilly**\
DamageModifiers:
- PROJECTILE 4.5
- ENTITY_ATTACK 2.50
- FIRE -1
- LAVA -1

#### Slizoun

Den: **Úterý**\
Čas Spawnu: **18:00**\
Čas Despawnu: **19:00**

HP: **900**\
DMG: **25 Základ + 50 Skilly**\
DamageModifiers:
- PROJECTILE 3.5
- ENTITY_ATTACK 1.75
- FIRE -1
- LAVA -1

#### Zlý Muja

Den: **Středa**\
Čas Spawnu: **18:00**\
Čas Despawnu: **19:00**

HP: **900**\
DMG: **26 Základ + 15 Skilly**\
DamageModifiers:
- PROJECTILE 2.5
- ENTITY_ATTACK 1.35
- FIRE -1
- LAVA -1

#### Mrakomůrka

Den: **Čtvrtek**\
Čas Spawnu: **18:00**\
Čas Despawnu: **19:00**

HP: **900**\
DMG: **15 Základ + (5 + 10) Skilly**\
DamageModifiers:
- PROJECTILE -1
- ENTITY_ATTACK 2.35
- FIRE -1
- LAVA -1

#### Ufo

Den: **Pátek**\
Čas Spawnu: **18:00**\
Čas Despawnu: **19:00**

HP: **900**\
DMG: **24 Základ + (10 + 10 + 8) Skilly**\
DamageModifiers:
- PROJECTILE -1
- ENTITY_ATTACK 1.75
- FIRE -1
- LAVA -1

## Odměny u Bossů
Odměny jsou u bossů předefinovány podle žebříčku DMG.

Počítají se 3 nejlepší hráči kteří udělí bossovi co největší DMG.

> [!Note]
> Existuje také šance že vám padne kus nějaké zbroje či meče.
> Šance u hlavního bosse je větší, protože je silnější a má větší výdrž.
> U vedlejších bossů je šance menší protože jsou slabší.

Odměny ze Saurona:
- **1. Místo**
   - +4 Kredity
   - +600 Exp
   - +$3500
   - +1 Náhodná vstupenka do dimenze.
- **2. Místo**
   - +$2500
   - +350 Exp
   - +2x Klíče k BasicBoxu
   - +1 Náhodná vstupenka do dimenze.
- **3. Místo**
   - +$1000
   - +100 Exp
   - +1x Klíče k BasicBoxu
   - +1 Náhodná vstupenka do dimenze.

Odměny z vedlejších bossů:
- **1. Místo**
   - +2 Kredity
   - +50 Exp
   - +$2500
   - +1 Náhodná vstupenka do dimenze.
- **2. Místo**
   - +$1000
   - +40 Exp
   - +1x Klíče k BasicBoxu
   - +1 Náhodná vstupenka do dimenze.
- **3. Místo**
   - +$500
   - +30 Exp
   - +1x Klíče k BasicBoxu