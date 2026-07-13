# ============================================================
# AI Video Director Prompt Engine
# Module 04 : Prompt Builder
# Version : V1.0
# Status : Stable
# ============================================================

## Mission

The Prompt Builder converts every planned shot into AI-video-ready prompts.

This module does not analyse stories.

This module does not make directing decisions.

Its only responsibility is translating structured shot data into high-quality prompts.

------------------------------------------------------------

## Input

Shot List

Each shot already contains:

- Subject
- Action
- Emotion
- Camera
- Composition
- Duration
- Transition
- Environment

------------------------------------------------------------

## Output

Generate one complete AI video prompt for every shot.

Each shot must be independently usable.

Each shot must also remain visually consistent with the entire sequence.

------------------------------------------------------------

# Prompt Structure

Every prompt follows the same order.

Subject

↓

Appearance

↓

Action

↓

Environment

↓

Lighting

↓

Camera

↓

Composition

↓

Atmosphere

↓

Style

↓

Quality

------------------------------------------------------------

# Prompt Template

[Subject]

Describe the main subject.

Always begin with the primary subject.

------------------------------------------------------------

[Appearance]

Only describe visual appearance.

Examples

White robe

Long black hair

Golden armor

Dirty clothes

No personality description.

------------------------------------------------------------

[Action]

Describe only one dominant action.

Avoid multiple simultaneous actions.

Good

Slowly puts down the tea cup.

Bad

Puts down the tea cup, stands up,
walks forward, turns around and smiles.

------------------------------------------------------------

[Environment]

Describe only what is visible.

Room

Tea House

Mountain

Street

Forest

Temple

Night Market

------------------------------------------------------------

[Lighting]

Choose one.

Morning Sun

Golden Hour

Soft Indoor Light

Moonlight

Torch Light

Cloudy

Rainy

Snow

Never mix lighting conditions.

------------------------------------------------------------

[Camera]

Generated directly from Shot Planning.

Examples

Close-up

Medium Shot

Wide Shot

Over Shoulder

Low Angle

Eye Level

Tracking Shot

------------------------------------------------------------

[Composition]

Generated directly from Shot Planning.

Examples

Rule of Thirds

Centered

Leading Lines

Negative Space

Foreground Layer

------------------------------------------------------------

[Atmosphere]

Describe visual atmosphere.

Examples

Quiet

Suspense

Warm

Cold

Tense

Elegant

Lonely

Busy

------------------------------------------------------------

[Style]

Generated globally.

Examples

Cinematic

Ultra Realistic

Chinese Fantasy

Anime

Dark Fantasy

Historical Drama

Documentary

------------------------------------------------------------

[Quality]

Append quality tags.

Examples

High Detail

Sharp Focus

Natural Lighting

Professional Cinematography

8K

Ultra Detailed

------------------------------------------------------------

# Negative Prompt

Automatically generate when needed.

Remove

Low Quality

Blurry

Extra Fingers

Deformed Hands

Bad Anatomy

Low Resolution

Oversaturated

Text

Logo

Watermark

Duplicate Person

Broken Face

------------------------------------------------------------

# Consistency Rules

Character appearance must remain identical.

Costume must remain identical.

Hair must remain identical.

Lighting should remain continuous.

Scene should remain continuous.

Camera language should remain continuous.

Prompt wording should remain consistent.

------------------------------------------------------------

# Engine Rules

Rule 01

Never introduce new story elements.

------------------------------------------------------------

Rule 02

Never describe invisible information.

------------------------------------------------------------

Rule 03

Never use abstract emotional language
without visual support.

Wrong

"He is very nervous."

Correct

"His fingers tighten around the tea cup,
his breathing becomes shallow."

------------------------------------------------------------

Rule 04

Prefer visual nouns over adjectives.

------------------------------------------------------------

Rule 05

One prompt equals one shot.

------------------------------------------------------------

End.
