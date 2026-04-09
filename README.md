# 120kw_framework

The 120kw Framework is a lightweight, high-performance, and modular ecosystem designed for modern FiveM roleplay servers.

---

# 120kw_prison – Changelog

## Üldine

- MDW-st saatmine fixed  
- Aeg fixed (salvestab korrektselt)  
- Aja kontroll fixed  
- Vanglas itemid eemaldatud  
- Chat notification lisatud  
- Vangla aeg nähtav  
- Vanglast lahkumine fixed  
- Vangla söökla töötab (kandiku ja söögi võtmine)  
- Vanglast vabastamine fixed  
- Fraktsiooni job süsteem eemaldatud  
- Vangla aega saab määrata kuudes (/vanglaaeg – sekundites)  
- /jailsms (iga 40 minuti tagant koos isikukoodiga)  
- Alles jäetud 2 tööd: puhastaja ja elektrik  
- Vanglast välja bugimisel teleporteeritakse mängija tagasi ja lisatakse aega juurde  

---

## Action – Jail Release (POOLIK)

- Vajalik item: `jail_card`  
- Käivitub minigame (3 korda)  
- Seejärel 120kw_skillbar  
- Avaneb UI list  
- Tuleb valida mängija isikukood  
- Mängija teleporteeritakse vanglast välja  

---

## Action – Treeningud

- Push-up  
- Bicep  
- Dumbbell  

---

## Action – Kongid

- Kongide süsteem lisatud  

---

## Action – Elektrik & Loot

- Elektrikutööl:
  - 10% chance saada katkised metallijupid  
- Voodite otsimisel:
  - 10% chance saada puidutükid  
- Craftingus saab teha:
  - `weapon_knife`  
- Iga voodit saab läbi otsida 1 kord  

---

## Bed Locations

- Voodite asukohad lisatud

---

## Lisad

- /asetjail ID hours/seconds  
- Kui mängija ei ole vanglas, siis blipe ei kuvata  
- CreatePrisonBlips fixed  
- Vangi minnes eemaldatakse kõik itemid  
- Vanglast lahkudes saab itemid tagasi  
- Vangla doorlockid lisatud  
- PD doorlockid lisatud  
- Elektrikutööl 10% chance saada katkised metallijupid  
- Voodite otsimisel 10% chance saada puidutükk  
- Vangla crafting menu eemaldatud → asendatud UI-ga  
- Craftingule lisatud task action ja emote  
- Crafting lauale ei pääse ligi ilma vanglakaristuseta (fixed)  
- Voodite otsimise emote fixed  


# 120kw – Changelog

# Resources

- Eemaldatud `120kw_policeduty` (BETA), kuna ei ole enam vajalik  

---

# 120kw_callsign

- `/callsign` avab UI, kuhu saab sisestada kutsungi (salvestub automaatselt)  
- Callsigni saavad kasutada ainult **politsei** ja **kiirabi**  

---

# 120kw_bodycam

- Bodycami callsign fixed  
- `/bodycaminfo` kaudu saab muuta UI-s bodycami asukohta jms  

---

# 120kw_policejob

- Kutsung + nimi (Active Blip süsteem)  
- EMS sama süsteemiga (Active Blip süsteem)  
- Kahekordsed player blipid fixed (Active Blip süsteem)  
- Politsei ja kiirabi näevad üksteise blippe (Active Blip süsteem)  
- Kui mängija vallandatakse, eemaldatakse blip koheselt (Active Blip süsteem)  

---

# 120kw_mugshot + 120kw_policemdw

- MDW-sse lisatud uus nupp **"Pilt"** (tagaotsitavuse nupu juurde)  
- Avab mugshot UI tsooni → saab teha pildi kohapeal (ei pea jaoskonda minema)  
- Jaoskonnas olemas ka eraldi asukoht  

---

# 120kw_society

- ChangeRank reworked  
- LoadProfileEditRank reworked  
- PostMessage reworked  
- Log system reworked  
- Siseveeb fixed  
- Seadete valik lisatud  
- UI reworked  

---

# 120kw_process + 120kw_ambulancejob

- Kiirabi väljakutse süsteem ümber tehtud  
- Varem: `/help ID` käsklus  
- Nüüd: kui karakter vajutab surnuna **G nuppu**, tekib `120kw_process` kaudu teadvuseta isiku väljakutse  
- Võimalik koheselt saada infot ja reageerida  

---

# Radio

- Kui raadio visatakse maha või eemaldatakse inventoryst → connection katkeb automaatselt  
- Kui raadiot ei ole inventorys → `/radioinfo` käsklust kasutada ei saa  
--- 
# 120kw_driverlicense

Täiendused ja parandused.

## Muudatused

### Helikopteri maandumise kontroll
- Lisatud kontroll viimases checkpointis
- Eksami lõpetamiseks peab:
  - helikopter olema maas
  - kiirus alla 5 km/h
- Läbi checkpointi lendamine enam ei tööta
- Kuvatakse teade:
  > Maandu ettevaatlikult ja jää täielikult seisma!

### 2h cooldown peale ebaõnnestumist
- sv salvestab viimase läbikukkumise aja
- Uus katse võimalik 2 tunni pärast

### UI muudatused
- Helikopteri license valimisel:
  - Removed kiiruspiirangud
- UI kuvab ainult eksami jaoks vajaliku info

--- 
