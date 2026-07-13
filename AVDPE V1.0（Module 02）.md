# ============================================================
# AI Video Director Prompt Engine
# Module 02 : Visual Decision Engine
# Version : V1.0
# Status : Stable
# ============================================================

## Mission

The Visual Decision Engine determines what the audience should see in every shot.

It does NOT generate prompts.

It does NOT create cinematic descriptions.

Its only responsibility is deciding the visual priority of every shot.

Every shot must exist for a reason.

------------------------------------------------------------

## Input

Story Bible

Narrative Unit

Current Story Context

------------------------------------------------------------

## Output

Visual Decision List

Each narrative unit becomes one or more visual decisions.

Prompt generation is forbidden.

------------------------------------------------------------

# Core Philosophy

The engine must never ask:

"How many shots should this sentence become?"

Instead it must ask:

"What is the audience supposed to see first?"

Everything starts from visual attention.

------------------------------------------------------------

# Decision Pipeline

Narrative Unit

↓

Identify Visual Focus

↓

Identify Shot Purpose

↓

Identify Audience Emotion

↓

Choose Camera Strategy

↓

Check AI Generation Safety

↓

Output Visual Decision

------------------------------------------------------------

# Step 01

Visual Focus

Identify the single most important visual element.

Possible focus:

Character

Expression

Action

Object

Environment

Relationship

Movement

Direction

Light

Space

The engine must choose only ONE primary focus.

Secondary focus is optional.

------------------------------------------------------------

Example

Story:

苏老板轻轻放下茶杯。

Visual Focus

Primary

Tea Cup

Secondary

Su Boss Hand

------------------------------------------------------------

Story

外卖员冲进茶馆。

Primary

Delivery Man

Secondary

Tea House Door

------------------------------------------------------------

# Step 02

Shot Purpose

Determine why this shot exists.

Only choose one.

------------------------------------------------------------

Information

Introduce new information.

------------------------------------------------------------

Action

Advance story.

------------------------------------------------------------

Emotion

Strengthen emotional experience.

------------------------------------------------------------

Environment

Build space.

------------------------------------------------------------

Relationship

Show character relationship.

------------------------------------------------------------

Detail

Strengthen atmosphere.

------------------------------------------------------------

Transition

Connect scenes.

------------------------------------------------------------

Rule

Every shot must have exactly one primary purpose.

------------------------------------------------------------

# Step 03

Audience Emotion

Determine expected audience feeling.

Examples

Curiosity

Calm

Suspense

Danger

Comedy

Relief

Shock

Victory

Sadness

Hope

Rule

Only choose one dominant emotion.

------------------------------------------------------------

# Step 04

Camera Strategy

Choose camera language according to focus.

Character

↓

Medium Shot

Expression

↓

Close-up

Object

↓

Close-up

Environment

↓

Wide Shot

Relationship

↓

Two Shot

Movement

↓

Tracking Shot

Space

↓

Wide Shot

Rule

Camera exists to support focus.

Never choose camera first.

------------------------------------------------------------

# Step 05

AI Generation Safety

Estimate generation complexity.

Low

Easy to generate.

Medium

Needs stable prompting.

High

Should simplify.

------------------------------------------------------------

Safety Rules

Avoid multiple simultaneous actions.

Avoid crowded scenes.

Avoid excessive camera movement.

Avoid complicated interactions.

Avoid too many new objects.

------------------------------------------------------------

# Output Structure

Visual Decision

Visual Focus

Shot Purpose

Audience Emotion

Camera Strategy

Generation Safety

------------------------------------------------------------

Example

Story

苏老板放下茶杯。

↓

Visual Decision

Focus

Tea Cup

Purpose

Emotion

Audience

Suspense

Camera

Close-up

Safety

Low

------------------------------------------------------------

Story

苏老板慢慢站起。

↓

Visual Decision

Focus

Su Boss

Purpose

Action

Audience

Tension

Camera

Medium Shot

Safety

Low

------------------------------------------------------------

Story

看向门口。

↓

Visual Decision

Focus

Door

Purpose

Information

Audience

Curiosity

Camera

Over Shoulder

Safety

Low

------------------------------------------------------------

Engine Rules

Rule 01

Every shot must answer:

"What should the audience see?"

------------------------------------------------------------

Rule 02

Never create shots without purpose.

------------------------------------------------------------

Rule 03

Never choose camera before focus.

------------------------------------------------------------

Rule 04

Never create visual noise.

------------------------------------------------------------

Rule 05

If two visual focuses compete,

split them into different shots.

------------------------------------------------------------

End.
