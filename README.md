# Combat Tokens 1.4.0 (Owlbear Rodeo extension)

## On the map
- **Health ring** on every token (everyone sees it): green 75%+ of Max HP, amber 25–74%, red 1–24%.
  **Down** (0 HP or less): dark-red ring, red tint, blood-drop marker. **Dead** (−Max HP or less): grey,
  skull marker, badges removed.
- **Badges** (GM sees all; a player sees only their own characters): top tray HP, Defense, Armor,
  Shield; bottom tray to-hit of the weapon in hand | Resist sorcery.
- **Click a token** to see its public note beside it (everyone). Its player and the GM also see
  dashed circles: movement (pale) and the in-hand weapon's range (amber, only if range > 1). 1 hex = 1 grid space.

## Right-click menus
- **Combat stats** — tabs: Stats (HP, Max, Def, Armor, Shield, Resist, Move, Initiative L/M/H),
  Weapons (name, to-hit, range, damage L/M/H; "use" sets the weapon in hand), Notes (public).
  GM extras: assign a Player, load a creature from the Béthorm bestiary, Save as template, Remove.
- **Damage / Heal** (GM only) — type a number, press Damage or Heal (healing stops at Max).
- **Attack this target** — attacker list (nearest first; GM: hidden tokens only if ticked; the downed
  and dead can't attack), weapon buttons if the attacker has more than one. The weapon used becomes
  the weapon in hand.

## Rules
- To hit: 2d10 must be UNDER weapon to-hit − target Defense − target Shield.
- Damage: d10 → 1–2 Low, 3–8 Medium, 9–10 High weapon damage, minus target Armor (never below 0).
- Initiative: d10 → 1–2 Low, 3–8 Medium, 9–10 High initiative value, highest first.

## Panel (toolbar icon)
- **Initiative** — Start combat, Next round (re-rolls automatically every 3 rounds; change in Setup),
  End combat. Downed characters drop to the bottom; the dead leave the list.
- **Attacks** — log of attacks and damage/healing; GM can Undo any entry.
- **Setup** (GM) — give stats to all; re-roll interval; monster templates (list, apply, import,
  export); backup / restore of this scene's stats, notes, assignments and templates.

## Players and ownership
A token belongs to a player only when the GM assigns it (Combat stats → Player). Players' edits and
attack damage are applied by the GM's browser, so the GM must be in the room. With the GM open in two
windows, only one applies anything.


## Béthorm bestiary (1.4.0)
All 243 creatures from the Béthorm bestiary are built in (bestiary.json). Two ways to use them (GM):
- Name a token after the creature, e.g. "Ahoggyá, Medium/Soldier" or "Ahoggya, Medium/Soldier 3" —
  accents and a trailing number don't matter. It gets the creature's stats as soon as it is on the map.
- Or open Combat stats on any token and use the Bestiary box: type a few letters, pick, press Load.
Your own templates (Setup) win over the book when the names are the same.
Conversion: Hits → HP and Max; Melee defense → Defense (the book already counts shields, so Shield 0);
first Armor number → Armor; Magic defense → Resist; Initiative a/b/c → Low/Med/High; first Movement
number → Move; each attack with damage → a weapon (to-hit as printed, range from "N” range", else 1).
