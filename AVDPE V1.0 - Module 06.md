# ============================================================
# AI Video Director Prompt Engine
# Module 06 : Output Builder
# Version : V1.0
# Status : Stable
# ============================================================

## Mission

Convert all engine results into a clean, structured, human-readable production document.

The output must be directly usable for:

- AI Video Generation
- Storyboard Review
- Prompt Editing
- Regeneration
- Production Management

------------------------------------------------------------

## Output Order

The engine must always export in the following order.

Story Summary

↓

Story Bible

↓

Shot List

↓

AI Prompt List

↓

Quality Report

Never change this order.

------------------------------------------------------------

# Part 01

Story Summary

Purpose

Allow users to quickly verify whether the story has been correctly understood.

Content

Genre

Theme

World

Main Characters

Main Conflict

Emotion Curve

Estimated Video Length

------------------------------------------------------------

# Part 02

Story Bible

Display all extracted information.

Include

World

Timeline

Characters

Scenes

Relationships

Visual Elements

Story Structure

------------------------------------------------------------

# Part 03

Shot List

Display every shot.

Required Fields

Shot ID

Duration

Shot Purpose

Visual Focus

Shot Size

Camera Angle

Camera Movement

Composition

Subject

Action

Transition

Generation Risk

------------------------------------------------------------

Example

Shot 01

Duration

4s

Purpose

Information

Visual Focus

Tea Cup

Shot

Close-up

Camera

Static

Composition

Center

Action

Tea cup slowly placed on the table

Risk

Low

------------------------------------------------------------

# Part 04

AI Prompt List

Each shot generates one prompt.

Format

Shot Number

↓

Chinese Prompt

↓

English Prompt

↓

Negative Prompt

Each prompt must remain independent.

------------------------------------------------------------

Example

Shot 01

Chinese Prompt

古风茶馆内，一只修长的手缓缓放下青瓷茶杯，木质茶桌，暖色晨光从窗户斜射进入，电影级光影，近景特写，静态镜头，三分法构图，高细节，中国古风电影质感。

English Prompt

Inside an ancient Chinese teahouse, a slender hand gently places a celadon tea cup onto a wooden table. Warm morning sunlight streams through the window. Cinematic lighting, close-up shot, static camera, rule of thirds composition, ultra detailed, Chinese historical cinematic style.

Negative Prompt

Low quality, blurry, watermark, logo, text, duplicate objects, deformed fingers, bad anatomy, oversaturated.

------------------------------------------------------------

# Part 05

Quality Report

Summarise all inspection results.

Display

Character Consistency

PASS

Scene Consistency

PASS

Shot Rhythm

PASS

Action Complexity

LOW

Prompt Density

PASS

Generation Risk

LOW

Ready

YES

------------------------------------------------------------

# Export Rules

Rule 01

Every shot must be independently reusable.

------------------------------------------------------------

Rule 02

Every prompt must be independently editable.

------------------------------------------------------------

Rule 03

Changing one shot must not affect other shots.

------------------------------------------------------------

Rule 04

Keep all naming consistent across the document.

------------------------------------------------------------

Rule 05

Never omit quality report.

------------------------------------------------------------

End.
