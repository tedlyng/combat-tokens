# Combat Tokens (Owlbear Rodeo extension)

Puts combat stats on tokens, rolls initiative, and resolves attacks with automatic damage.

## On the map
**Health ring** around every token, seen by everyone: green at 75%+ of Max HP, yellow 25–74%,
red 1–24%, grey at 0 or below. (Needs Max HP set; no ring without it.)

**Stat badges** — across the top: **HP** (red heart), **Defense** (blue ring), **Armor** (steel ring),
**Shield** (shield); below: **To-hit** (sword). The GM sees badges on every token; a player sees
them only on their own tokens. Players see nothing on hidden tokens.

## Stats (right-click a token → Combat stats)
HP, Max HP, Defense, Armor, Shield, To-hit, plus Damage Low/Med/High and Initiative Low/Med/High (not drawn
on the map). The GM can edit any token and assign a token to a player. A player can edit only their own
tokens: ones they placed, or ones the GM assigned to them. Players' changes are saved by the GM's
browser, so the GM must be in the room.

## Attacking (right-click the target → Attack this target)
Pick your attacker (players only see their own characters) and press Attack.
- To hit: 2d10 must be **under** attacker's To-hit − target's Defense − target's Shield.
- Damage: d10 → 1–2 Low, 3–8 Medium, 9–10 High damage, minus target's Armor (never below 0).
- On a hit the target's HP drops automatically (GM must be in the room). Everyone gets a notification,
  and the attack goes in the log. Hidden attackers/targets are shown to players as "unseen".
- Players see their own to-hit, their dice, and the damage dealt — never the target's defense, shield,
  armor or HP. The GM sees the full breakdown.

## Panel (toolbar icon)
- **Initiative** (GM rolls, everyone sees): d10 per token → 1–2 Low, 3–8 Med, 9–10 High initiative
  value, highest first. Players see the order for everyone but the numbers only for their own
  characters. Click a name to select the token.
- **Attacks**: log of recent attacks in this scene.
- **Setup** (GM): "Give stats to all characters" adds zeroed stats to every character token
  that doesn't have them.

## Installing or updating (version 1.2.0)

See INSTALL.txt in this folder for step-by-step instructions.
