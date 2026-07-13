# ============================================================
# AI Video Director Prompt Engine
# Module 05 : AI Video Quality Check
# Version : V1.0
# Status : Stable
# ============================================================

## Mission

Before exporting prompts,
the engine must verify that every shot is suitable for AI video generation.

The goal is not artistic evaluation.

The goal is generation stability.

If a shot is difficult to generate,
simplify it before output.

Never output unstable prompts.

------------------------------------------------------------

## Input

Story Bible

Visual Decision List

Shot List

Prompt List

------------------------------------------------------------

## Output

Quality Report

If all checks pass

↓

Output Prompt

If any check fails

↓

Revise Shot

↓

Generate New Prompt

------------------------------------------------------------

# Check 01

Character Consistency

Verify

Character Name

Appearance

Costume

Hair

Accessories

Age

Identity

Emotion Continuity

------------------------------------------------------------

Pass

Same appearance across shots.

Fail

Hair suddenly changes.

Costume changes.

Face changes.

Gender changes.

------------------------------------------------------------

Action

Automatically reuse previous appearance.

------------------------------------------------------------

# Check 02

Scene Consistency

Verify

Location

Architecture

Furniture

Weather

Time

Lighting

Objects

------------------------------------------------------------

Fail

Morning suddenly becomes night.

Temple suddenly becomes office.

Rain suddenly disappears.

------------------------------------------------------------

Action

Maintain previous scene unless story changes.

------------------------------------------------------------

# Check 03

Visual Focus

Each shot must contain

ONE primary subject.

If multiple primary subjects exist

↓

Split shots.

------------------------------------------------------------

Pass

Tea Cup

Fail

Tea Cup + Door + Sword + Horse

------------------------------------------------------------

# Check 04

Action Complexity

Estimate action difficulty.

Low

Walking

Standing

Looking

Picking up object

Medium

Running

Turning

Opening door

High

Fight

Explosion

Crowd movement

Flying while attacking

------------------------------------------------------------

Rule

If High

↓

Recommend splitting.

------------------------------------------------------------

# Check 05

Environment Complexity

Estimate object density.

Low

Simple room

Forest path

Temple

Medium

Market

Street

Restaurant

High

Battlefield

Festival

Army

Crowded city

------------------------------------------------------------

Rule

Reduce unnecessary objects.

------------------------------------------------------------

# Check 06

Camera Stability

Verify

Movement

Angle

Transition

------------------------------------------------------------

Fail

Pan

↓

Crane

↓

Drone

↓

Handheld

within one shot.

------------------------------------------------------------

Rule

One shot

One movement.

------------------------------------------------------------

# Check 07

Prompt Density

Count visual information.

Maximum recommendation

Subject

1

Main Action

1

Emotion

1

Environment Focus

1

Lighting

1

Camera

1

Composition

1

Style

1

------------------------------------------------------------

Too many descriptions

↓

Simplify.

------------------------------------------------------------

# Check 08

Shot Rhythm

Verify sequence.

Environment

↓

Character

↓

Action

↓

Emotion

↓

Transition

Avoid

Emotion

↓

Environment

↓

Emotion

↓

Environment

without narrative reason.

------------------------------------------------------------

# Check 09

Generation Risk

Estimate

Low

Medium

High

Risk Factors

Crowd

Animals

Fire

Water

Fast Motion

Magic

Particles

Smoke

Reflection

Mirror

Rain

Explosion

Complex Camera

------------------------------------------------------------

If High

↓

Recommend simplification.

------------------------------------------------------------

# Check 10

Regeneration

Every shot must be independently regeneratable.

Requirements

Independent Prompt

Independent Camera

Independent Subject

Independent Lighting

Independent Composition

If one shot fails

Only regenerate that shot.

------------------------------------------------------------

# Final Report

Character

PASS

Scene

PASS

Action

PASS

Camera

PASS

Prompt Density

PASS

Generation Risk

LOW

Ready for Export

YES

------------------------------------------------------------

End.
