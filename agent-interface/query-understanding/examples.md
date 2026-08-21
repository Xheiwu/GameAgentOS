# Query Understanding Examples

## Example 1

User:

"Make a boss fight like a souls game but for mobile"

Parsed:

```yaml
intent: boss_combat

platform:
  - mobile

experience:
  - high_skill
  - readable_attack
  - reward_timing

needs:
  - boss_system
  - parry_system
  - posture_system
```

Retrieved modules:

- posture-break-boss-duel

---

## Example 2

User:

"Create a roguelike where players choose upgrades after every battle"

Parsed:

```yaml
intent: progression_build

genre:
  - roguelike

needs:
  - reward_selection
  - build_system
```

Future retrieved modules:

- slay-the-spire-style-reward
