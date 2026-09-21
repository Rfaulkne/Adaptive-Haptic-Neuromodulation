# Adaptive Haptic Modulation of Pain Processing

> **Aim:** To investigate whether programmable mechanical stimulation applied to the body can reproducibly influence nociceptive processing and pain perception.

## Context

Pain is not determined solely by tissue damage or peripheral nerve activity. It is shaped by sensory input, attention, central processing, and endogenous pain-modulation mechanisms.

Existing work in vibration analgesia, conditioned pain modulation, and remote electrical neuromodulation suggests that peripheral stimulation can influence pain processing. What remains less well understood is whether the **design of mechanical touch itself** — its location, intensity, rhythm, movement, and spatial structure — can be engineered to produce stronger or more reliable effects.

This creates a research opportunity at the intersection of **haptics, neuroscience, and mechatronics**: using touch not only to communicate information, but as a controlled experimental input to study and potentially influence sensory processing.

Longer-term possibilities include personalized stimulation, wearable systems, migraine and chronic pain applications, sensory dysfunction, and adaptive or closed-loop neuromodulation. The immediate project is intentionally narrower: establish whether a reproducible effect exists and characterize it well.

## Scope

The initial project will focus on a healthy-participant study using controlled experimental pain and a programmable haptic prototype.

Core questions include:

- Can mechanical stimulation at one body location alter pain experienced elsewhere?
- Do different haptic patterns produce measurably different effects?
- Which stimulus parameters matter most: frequency, amplitude, rhythm, spatial motion, location, or predictability?
- Can effects be distinguished from simple distraction or attentional competition?
- How much variability exists between individuals and sessions?
- Are individual responses stable enough to motivate later personalization?

Possible outcomes include pain intensity, pain unpleasantness, pressure or thermal pain threshold, temporal effects before/during/after stimulation, stimulus tolerability, and test-retest repeatability.

The first project is **not** intended to prove a clinical treatment, predict migraine attacks, or build a finished closed-loop medical device.

## Team

The intended team combines three complementary areas:

### Haptics
- Vibrotactile stimulation
- Spatial and temporal haptic patterns
- Psychophysics
- Apparent tactile motion
- Human-machine interaction
- Wearable haptic interfaces

### Neuroscience
- Sensory and nociceptive processing
- Pain modulation
- Experimental design
- Quantitative sensory testing
- Physiological / neurophysiological measurement
- Interpretation of individual variability

### Mechatronics / Prototyping
- Rapid electromechanical prototyping
- Actuator integration
- Embedded control
- Wearable system development
- Sensors and data acquisition
- Mechanical fabrication
- Experimental hardware

## Relation to our research environment

The central question exists between the participating disciplines rather than belonging to one field alone.

For **haptics**, the project extends tactile-interface research beyond communication toward active interaction with sensory processing.

For **neuroscience**, it provides a programmable method for investigating how non-nociceptive sensory input interacts with pain perception and endogenous modulation.

For **mechatronics**, it creates a wearable-interface challenge in which actuator behavior, body coupling, sensing, repeatability, and human perception must be considered together.

```text
Haptic design
      ↓
Controlled physical stimulation
      ↓
Neural + perceptual response
      ↓
Measurement + interpretation
      ↓
Improved stimulation design
```

## Current project principle

**Mechanism before application.**

Before pursuing migraine prediction, AI personalization, or a therapeutic wearable, the project should first establish:

1. Does remote mechanical stimulation produce a reproducible antinociceptive effect?
2. Can that effect be separated from distraction?
3. Which stimulus properties determine it?
4. Is the response stable within individuals?

Only then does personalization or closed-loop intervention become a meaningful next step.

## Repository map

- [Project brief](docs/project-brief.md)
- [Research questions](docs/research-questions.md)
- [Literature map](docs/literature-map.md)
- [Decision log](docs/decision-log.md)
- [Future directions](docs/future-directions.md)
- [Design and wearable precedents](docs/design-precedents.md)

## Long-term direction

If the underlying effect proves robust, the research can expand toward:

```text
sense
  ↓
estimate state
  ↓
select stimulation
  ↓
intervene
  ↓
measure response
  ↓
adapt
```

Potential future applications include migraine, chronic or recurrent pain, endometriosis-associated pain, sensory augmentation, and diabetic peripheral neuropathy.

---

**Working umbrella question:**  
*How can engineered physical interaction with the body be used to understand — and potentially influence — the way the nervous system processes sensory information?*
