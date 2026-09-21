# Decision Log

This file records the scope decisions that keep the project experimentally feasible.

## Current decisions

### 1. Mechanism before application
The first project should not depend on migraine, chronic pain, AI, or clinical deployment. It should establish whether a remote mechanical antinociceptive effect exists.

### 2. Healthy participants first
Use controlled experimental pain before moving to clinical populations.

### 3. Avoid an oversized haptic parameter search
Begin with approximately 4–5 controlled conditions rather than dozens of patterns.

A reasonable first comparison:

1. No stimulation
2. Simple continuous vibration
3. Spatially moving haptic pattern
4. Irregular / unpredictable pattern
5. Sham or attention-matched control

### 4. Separate analgesia from distraction
A haptic stimulus is inherently salient. Experimental controls should help distinguish a change in nociceptive processing from a change in attention.

### 5. Measure more than subjective pain
Where practical, combine pain ratings with quantitative sensory testing, after-effects, reflex-based measures, or neurophysiology.

### 6. Personalization comes after reproducibility
Do not build a machine-learning optimizer until a measurable and repeatable response exists.

### 7. Closed-loop sensing is future work
HRV, EDA, skin temperature, activity, and sleep are interesting but nonspecific. A control signal should only be pursued once there is an intervention worth triggering and a plausible measurable state associated with timing.

## Why this matters

The project previously expanded rapidly toward migraine prediction, closed-loop wearables, endometriosis, neuropathy, and AI. These remain useful application directions, but allowing them to define the first study would make the scientific question too diffuse.
