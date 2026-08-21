# Null Sovereign Parameter Analysis

## Goal

Extract experience-driving parameters instead of copying implementation values.

## Timing Parameters

```yaml
attack:
  telegraph_time:
  active_time:
  recovery_time:

parry:
  reaction_window:
```

## Resource Parameters

```yaml
combat_resources:
  health:
    purpose: long_term defeat
  posture:
    purpose: create vulnerability
```

## Feedback Parameters

Important events should have stronger feedback intensity.

Example hierarchy:

```
normal_hit
 <
parry_success
 <
posture_break
 <
execute
```
