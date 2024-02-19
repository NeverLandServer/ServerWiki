<div align=center>

# Příkazy pro Admin Tým

Zde najdeš obecné příkazy pro Admin tým a využití.
</div>

### Seznam příkazů

#### Obecné
- /gamemode|gm <gamemode> [jméno] - Tímto změníš nastavení herního módu sobě nebo někomu jinému.
    - **Alternativní zkratky**:
    - /gmc - Nastaví creative
    - /gma - Nastaví adventure
    - /gmsp - Nastaví specator
    - /gms - Nastaví survival
- /fly [jméno] - Nastavíš létání / vypneš létání sobě nebo jinému hráči.
- /echest [jméno] - Prohlídneš si hráčovu Endertruhlu.
- /vanish [jméno] - Skryješ se před hráči.
- /socialspy [jméno] - Zapneš mód při kterém vidíš soukromé zprávy hráčů.
- /invsee [jméno] - Prohlídneš si inventář online hráče.
- /lightning <jméno> [-d], /thor <jméno> [-d] - Uhodíš hráče bleskem bez dmg nebo s dmg.
- /random world tickets <jméno> [počet] - Dáš hráči náhodnou vstupenku do Netheru, Endu.
- /random crates key <jméno> [počet] - Dáš hráči náhodný klíč od Magického Boxu / Crates.
- /random tag <typ> <jméno> - Dáš hráči náhodný tag z nějaké kategorie, [COMMON, RARE, LEGENDARY, ULTIMATE]
- /repair all [hráč] - Opraví hráči všechny věci v inventáři.
  - Ekvivalent: /fixall [hráč]
- /spawner set <typ> - Nastavíš spawner na který se díváš určitým typem Entity.
- /spawner give <typ> <počet> <jméno> - Dáš hráči spawner určitého typu.
- /tpo <jméno> - Teleportuješ se na poslední známou lokaci hráče.
- /tp <jméno> <cíl> - Teleportuješ hráče k jinému hráči. 
- /heal [jméno] - Doplníš zdraví sobě nebo hráči.
- /tphere, tpall - Teleportuješ všechny hráče k tobě.
- /warp <warp> [jméno] - Teleportuješ hráče na warp.
- /delwarp <warp> [jméno] - Odstraníš nějaký warp hráči.
- /kit <jméno_kitu> [jméno] - Dáš kit sobě nebo hráči.
- /anvil - Otevře virtuální kovadlinu.
- /workbench - Otevře virtuální výrobní stůl.
- /smithing - Otevře virtuální menu vylepšování brnění
- /loom - Otevře pracovní stůl s vylepšováním vlajek.
- /grindstone - Otevře brusný kámen.
- /stonecutter - Otevře kamennou pillu.

#### Ekonomika
- /eco add <jméno> <částka> - Přidá hráči na účet peníze.
- /eco set <jméno> <částka> - Přidá hráči na účet fixní částku.
- /eco remove <jméno> <částka> - Odebere hráči z účtu peníze.
- /eco delete <jméno> <částka> - Zruší hráči jeho účet a smaže cache ve které má úložené dočasné peníze.
- /eco gadd <částka> - Přidá všem hráčům peníze na jejich konta.
- /eco gset <částka> - Nastaví fixní částků peněz na účet všech hráčů.
- /eco gremove <částka> - Odebere všem hráčům částku peněz.

- /credits add <jméno> <částka> - Přidá hráči na účet kredity.
- /credits set <jméno> <částka> - Přidá hráči na účet fixní kredity.
- /credits remove <jméno> <částka> - Odebere hráči z účtu kredity.
- /credits delete <jméno> <částka> - Zruší hráči jeho účet a smaže cache ve které má úložené dočasné kredity.
- /credits gadd <částka> - Přidá všem hráčům kredity na jejich konta.
- /credits gset <částka> - Nastaví fixní částků kreditů na účet všech hráčů.
- /credits gremove <částka> - Odebere všem hráčům částku kreditů.

#### Hlasování
- /votes add <služba> <jméno> <počet> - Přidáš hráči hlas v určité službě.
- /votes set <sluýba> <jméno> <počet> - Nastavíš fixní počet hlasů hráči v určité službě.
- /votes reset player <jméno> - Resetuje uložené hlasy hráči.
- /votes reset all - Resetuje všem hráčům jejich hlasy.
- /votes remove vote <služba> <jméno> <počet> - Odebere hlasy hráči z určité služby.

#### Questy
- /mise admin open 

#### Tresty
- /ban <jméno> [<čas>] [<důvod>] - Hráč obdrží ban, buď časový nebo doživotní.
- /mute <jméno> [<čas>] [<důvod>] - Hráč obdrží umlčení v chatu.
- /warn <jméno> [<čas>] [<důvod>] - Hráč obdrží varování, varování se sčítají a hráč může obdržet větší trest.
- /kick <jméno> [<důvod>] - Vyhodíš hráče ze serveru.

#### Operátorské příkazy
- /op <jméno> - Nastaví hráči Operátora největší oprávnění co může člověk na serveru dostat.
  - Tento příkaz má přístupno velmi malé procento členů v at.
- /whitelist add <jméno> - Přidá na whitelist hráče, whitelist je seznam hráčů kteří se mohou připojit k serveru pokud je whitelist zapnutý.
- /whitelist remove <jméno> - Odstraní hráče z whitelistu.
- /whitelist on - Zapne whitelist serveru.
- /whitelist off - Vypne whitelist serveru.
- /tps, /tpsbar - Vypíše / zapne monitoring bar tps a ram paměti.
- /ram - Vypíše využití ram paměti.

## World Edit
Oprávnění pro world edit má pouze administrátor s rankem ADMIN.

World edit je nástroj který umožnuje správu bloků, různé manipulace s větší částí bloků.
Základní ovládání je pomocí dřevěné sekery, nebo dalších různých nástrojů třeba "štětce".

Jelikož je world edit hodně komplikovaný musíte si projít video nebo dokumentaci.
Zde nemohu popsat veškeré vymoženosti tohoto nástroje.

Link na yt návod: [Klikni na mě](https://www.youtube.com/watch?v=-RzubzupIC4)