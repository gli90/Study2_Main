# Metacognitive Confidence under Illusion & Compensation


## Purpose

This experiment investigates whether subjective confidence can be dissociated from objective physical correctness.

Unlike conventional perceptual decision tasks, the present study manipulates the physical difference between two stimuli while using illusion compensation to minimize their perceived difference.

The goal is to create situations in which participants confidently judge physically different colors as identical, allowing confidence and physical correctness to be experimentally dissociated.


## Theoretical Background

Study 2 builds directly upon the illusion calibration obtained in Study 1.

Study 1 estimates:

Δ_illusion

which represents the physical color shift required to perceptually cancel the simultaneous color contrast illusion.

Study 2 uses this participant-specific illusion magnitude to generate several experimental conditions with different levels of physical compensation.

This allows physical stimulus differences and perceptual similarity to be manipulated independently.


## Experimental Logic

The experiment contains five conditions.


### Control

No illusion.

Both center patches are physically identical.

Neutral surrounds are presented.

Expected response:

Same


### Illusion

No physical color difference is introduced.

Illusion-inducing surrounds create an apparent perceptual difference.

Expected response:

Different


### Compensation

Physical differences are introduced along the D2 axis while illusion-inducing surrounds remain present.

Compensation levels:

0.5 × Δ_illusion

1.0 × Δ_illusion

1.5 × Δ_illusion

When compensation approaches the participant's illusion magnitude, physically different colors should appear increasingly similar.

The critical prediction is that participants may confidently report that physically different stimuli are the same.


## Stimulus Design


### Center Colors

Center colors vary along the calibrated blue–purple D2 axis in CIELAB space.

L* is fixed at:

75

Five anchor colors are sampled across the axis:

Anchor 1 = (4.0, -29.0)

Anchor 2 = (5.0, -28.0)

Anchor 3 = (6.0, -27.0)

Anchor 4 = (7.0, -26.0)

Anchor 5 = (8.0, -25.0)

For compensation conditions, the right center patch is shifted along the D2 axis by the specified compensation amount.


### Surround Colors

Two surround configurations are used.

Neutral condition:

Gray surrounds on both sides.

Illusion condition:

Left surround

Green-biased

(-60, 25)

Right surround

Red-biased

(60, 25)

This surround pair induces a strong simultaneous color contrast illusion.


## Experimental Procedure

Each trial consists of four stages.


### 1. Fixation

A central fixation cross is presented.

Duration:

Random

1000–1500 ms


### 2. Stimulus Presentation

Two center patches are displayed simultaneously.

Participants judge whether the two center patches are physically identical or physically different while ignoring the surrounding colors.

Response keys:

F

Same

J

Different

Reaction time is recorded.


### 3. Confidence Rating

Participants report confidence using a four-point scale.

1

Very Low

2

Low

3

High

4

Very High

Confidence reaction time is also recorded.


### 4. Inter-Trial Interval (ISI)

Blank screen.

Duration:

800 ms


## Trial Structure

Current pilot version (v1.0):

5 Anchors × 5 Conditions × 8 Repetitions = 200 Trials

Conditions:

Control

Illusion

Compensation_0.5

Compensation_1.0

Compensation_1.5

All trials are randomized before the experiment begins.


## Compensation Mechanism

Study 1 estimates:

Δ_illusion

Study 2 computes the physical compensation as:

Physical Shift

=

Compensation Level × Δ_illusion

The right center patch is translated along the D2 axis by this amount.

Current pilot version:

Δ_illusion = 8.5

This temporary fixed value is used only for interface and workflow testing.

Future versions will automatically load each participant's calibration result from Study 1.


## Recorded Variables

For each trial:

participant

trial

condition

anchor_id

illusion_used

physical_shift

response

correct_answer

accuracy

confidence

rt_response

rt_confidence


Definitions:

physical_shift = physical color displacement applied to the comparison patch.

accuracy = whether the participant's judgment matches the physical stimulus relationship.

confidence = subjective confidence rating (1–4).

rt_response = decision reaction time.

rt_confidence = confidence rating reaction time.


## Outcome Measures

Primary measures:

Decision accuracy

Confidence rating

Decision reaction time

Confidence reaction time

Secondary analyses may examine:

Accuracy–confidence dissociation

Effects of compensation level

Anchor-specific performance

Reaction time distributions

Individual differences


## Expected Results

If illusion compensation successfully dissociates perception from physical stimulus properties,

participants should increasingly judge physically different colors as identical under the compensation conditions.

The strongest effect is expected near:

1.0 × Δ_illusion

where the perceived color difference approaches zero despite the presence of a physical color difference.

Consequently,

confidence is expected to remain high,

while objective physical correctness decreases,

providing evidence that subjective confidence can become partially independent of objective stimulus correctness.


## Relationship Between Studies

Study 1 estimates:

Δ_illusion

Study 2 uses:

Δ_illusion

to construct compensated stimuli.

Together, the two experiments allow direct investigation of whether:

Physical Difference

≠

Perceived Difference

and whether:

Confidence

can become dissociated from

Objective Correctness.
