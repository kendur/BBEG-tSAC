# Injury Model

The system for tracking lasting injury and its consequences.

---

## Overview

The tSAC injury model distinguishes between **Stamina** (current capacity, recoverable) and **Injuries** (lasting conditions that affect capability). This distinction is central to the system's philosophy that consequences are durable.

A character can recover Stamina to full and still be meaningfully impaired by an injury they're carrying. This prevents the "full reset between every encounter" problem.

---

## Injury Categories

Injuries are categorized by severity:

| Category | Description | Default Recovery |
|----------|-------------|-----------------|
| **Minor** | Bruises, cuts, strained muscles | 1–3 days rest |
| **Moderate** | Broken ribs, deep wounds, partial sprains | 1–3 weeks with treatment |
| **Severe** | Broken limbs, deep organ damage, significant blood loss | Months; requires skilled treatment |
| **Critical** | Life-threatening conditions | May require specific care; risk of death |
| **Permanent** | Conditions that do not fully heal | Ongoing, managed rather than resolved |

---

## Acquiring Injuries

Injuries are acquired when:

- Stamina falls below 25% from a single combat event
- A character takes a "significant blow" — a narratively extreme attack regardless of Stamina level
- Certain environmental events (falls, crushing, drowning)
- Specific supernatural effects that deal injury directly rather than Stamina damage

### Injury Roll

When an injury is triggered, roll **2d6 + relevant circumstance modifiers**:

| Roll | Injury Severity |
|------|----------------|
| 2–4 | Severe |
| 5–7 | Moderate |
| 8–10 | Minor |
| 11–12 | Glancing — minor at worst |

Modifiers: +2 if character has armor appropriate to the attack; −2 if the attack was especially powerful or the character was especially vulnerable.

---

## Injury Effects

Each injury has a specific effect on capability:

- **Minor** — Disadvantage on actions that stress the injury
- **Moderate** — Reduced attribute scores or specific capability loss in the affected area
- **Severe** — Significant attribute reduction; certain actions impossible until recovery begins
- **Critical** — Character requires immediate treatment or begins deteriorating; some actions may be impossible entirely

---

## Treatment and Recovery

Recovery requires:

- **Rest** — Time without significant physical exertion
- **Treatment** — For Moderate and above, appropriate medical or magical treatment accelerates recovery and prevents complications
- **Resources** — Healing supplies, access to practitioners, safe conditions

**Without treatment**, Moderate injuries may worsen to Severe over time; Severe injuries risk worsening to Critical.

---

## Psychological Injuries

The injury model also covers psychological wounds:

- Significant Willpower loss events can leave **psychological injuries** (trauma, phobia, persistent anxiety states)
- These are categorized the same way (Minor through Permanent) and recover through appropriate care
- Psychological injuries are real mechanical effects, not flavor — they affect Willpower pools and specific actions

---

## Death

Death is the outcome of:

- A **Critical** injury that goes untreated for too long
- A **deliberate killing blow** against an incapacitated character
- Specific catastrophic events (plane destabilization events, Protector-level energy, etc.)

The system does not treat death as the automatic outcome of reaching 0 Stamina — it is a specific condition requiring specific circumstances.

---

## See Also

- [Stamina and Willpower](stamina_willpower.md)
- [Combat Resolution](combat_resolution.md)
- [System Philosophy](philosophy.md)
