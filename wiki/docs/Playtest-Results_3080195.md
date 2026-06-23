# Playtest Results
> ℹ️ **Note:** Author: Valentino and Megan

> ℹ️ **Note:** Date: 03 Jan 2026

## Tester 1 – Erwin Bell (Fontys Lecturer)

**Test Setup:** Played all three versions consecutively without
instructions (only a hint for the mister)

### Basic Version (11:27–11:36)

**Observations & Issues**

- Task text says *“crafting”* → should be *“prepare food”*

- Reptile already exists in the terrarium → unclear why a new one must
  be built

- Builder phase inconsistency:

  - Clipboard says *topsoil*, asset labeled *dirt*

- Confusion when returning to the next day. The button is not easy to
  spot.

- Clipboard text in terrarium view feels disconnected from gameplay

- Cave asset looks like a bowl → unclear why it can’t be placed
  centrally

- Gameplay becomes tedious by the 3rd loop

- Feeding interaction missing → player only prepares food (causes
  disappointment)

- He placed the LED lamp very high

- Mister placement unclear:

  - The player dragged it into the terrarium

  - Tube placement behaves incorrectly; it’s not going through the glass

- No option to return to the menu after the ending screen

------------------------------------------------------------------------

### HC Version (11:37–11:42)

**Observations & Issues**

- Initial confusion due to lack of crafting instructions

- Soil pouring too fast → difficult to control/dose

- Clay appears yellow from the start (unclear why)

- Player workflow: Loop 1 & 2: crafted food first, then consulted the
  vet

- Builder feedback: “Feels like you always have to place everything.”

- Cave 2 sprite resembles a bowl

- Mister:

  - Placement confusing

  - Icon not to scale

------------------------------------------------------------------------

### LLM Version (~11:43–12:00, ~15 min)

**Observations & Issues**

- The player is surprised by the vet character

- Attempted to discuss food variety in Loop 1 → vet refused interaction

- Incorrect feedback: Mealworm feeding triggered a warning about not
  feeding fruit instead

- Restriction issue: Only crickets allowed, but mealworms (e.g., 3x)
  should also be valid in the first loop

- LLM broke after ~7 minutes and agreed with the player

- Vet reintroduces himself redundantly in the 2nd mini game

- “Start next day” button not obvious → should be more centered/visible

- Vet perceived as antagonistic (nagging, restrictive)

- Heat lamp collision too large

- Mister tube was not properly placed in the terrarium

------------------------------------------------------------------------

### General Feedback (Tester 1)

- Unskippable cutscenes/tutorials are frustrating

- Basic version feels boring

- Gecko lacks movement → feels lifeless

  - Suggestion: add AI-driven behavior for gecko

- Item placement in the terrarium feels physically unrealistic → breaks
  immersion

- Learning outcome: Feels like learning about geckos, but not enough to
  own one

- Missing/unclear mechanics:

  - Temperature regulation

  - Humidity management & water refilling

  - Feeding method (why mix food instead of natural hunting?)

  - Cricket behavior (dead/alive handling unclear)

  - Calcium supplementation logic unclear

  - Question: Why provide supplements instead of UV/light-based
    solutions?

------------------------------------------------------------------------

## Tester 2

**Version**: LLM

**Observations**

- Followed the tutorial instruction:

- Vet says to only feed live prey (not true?)

- Tried to break the LLM system

- Attempted to fill to the “red line.”

- Did not consult the vet

- Successfully discovered the correct recipe on Day 2 independently

- Tutorial mismatch:

  - Loop 2 & 3 builder tutorial still references Loop 1

- Used vet effectively in Builder Phase 2

- Found gameplay fun overall

**Issues**

- Wanted to interact with gecko in view → no response

- Mister unclear (purpose + placement)

- Vet initially unhelpful regarding “water tank” placement

- Vet responses:

  - Generally good at staying on topic

  - Does not fully respond to all player inputs

------------------------------------------------------------------------

## Tester 3

**Version:** Hardcoded Vet

**Observations**

- Read the tutorial thoroughly

- Explored all dialogue options in Loop 1

- Checked the clipboard for guidance across days

- He got engaged briefly with another person (\<1 min), was distracted

- Appreciated step-by-step information

- Overall impression: “Pretty nice game.”

**Issues**

- The bowl appears full after placing just one item

- Dragging soil bags not intuitive initially

- Gecko did not respond after feeding (bug)

- Builder Phase 2:

  - Did not place all items initially (avoided Cave 2)

  - Carefully spaced items

- Loop 3: Unclear what to do until the vet appeared

  - Fail states are unclear in the terrarium builder

- Gecko is too static (no movement)

- Mini-games lack rewarding feedback

------------------------------------------------------------------------

## Tester 4

**Version:** LLM

**Observations**

- Soil mixing minigame:

  - Sensitive controls, but the most enjoyable part

  - Suggested improvement: click to select → click to pour

- Did not require vet help for soil mixing or Day 3 crafting

- Efficient playstyle after Day 1 (felt like speedrunning)

- Placed items neatly in Builder Phase 2

**Issues**

- Vet repeats the same message after failure (“insectivores”)

- Game crash:

  - Occurred during Loop 1 crafting when exiting full-screen by accident

- Initial crafting unclear (what actions are allowed)

- The main view does not change between days

- Clipboard issues:

  - Only one navigation arrow

  - Text cut off mid-sentence on the last row of text

------------------------------------------------------------------------

## Tester 5

**Version:** Basic

**Observations**

- Carefully read tutorials

- Thought actively about correct feeding

- Soil mixing:

  - Found it fun and engaging (laughed loudly during play)

**Issues**

- Soil ratio balancing is unclear

- Mixing process unclear (continuous animation confusion)

- Mister remains confusing

- Suggested improvement:

  - More varied gecko interactions/behaviors per day

------------------------------------------------------------------------

## Tester 6

**Version:** HC (misreported as Basic in survey)

**Observations**

- Liked the hand-drawn art style

- Engaged deeply with systems:

  - Tried to perfect soil ratios

  - Asked the vet about enrichment and supplements multiple times

**Issues**

- Incorrect assumption:

  - Thought mealworms are not insects due to Loop 1 restriction

- Gecko animation issues:

  - Jumping animation

  - No eating response after feeding

- No reptile response during the second feeding

- Confusion about the heat lamp’s purpose

------------------------------------------------------------------------

## Tester 7

**Version:** Basic

**Observations**

- Read instructions

- Learned through experimentation

- No major issues encountered

- Strong positive feedback on art style

------------------------------------------------------------------------

## Tester 8 – Wouter’s Daughter (Kid)

**Context:** Needed guidance; struggled with language barriers.

- **Observations:** Did not understand the tutorial, but understood the
  feeding button.

- **Vet Interaction:** Asked the Vet multiple questions; succeeded in
  crafting only after being prompted to ask the Vet for the recipe.

- **Issues:** English was difficult to understand. The "red line" and
  "mister" were confusing.

- **Bugs:** Substrate layer rendered over the text bubbles.

- **Design Note:** Suggestion to lock the basking rock to the middle.

------------------------------------------------------------------------

## Tester 9 – Intern 1 (LLM)

- **Observations:** Started with building; closed the Vet immediately
  but consulted him later in Loop 2.

- **Feedback:** Understood LLM feeding instructions and mister/heat lamp
  info well.

- **UI/UX:** "Mix" and "Start Next Day" buttons are not clear enough.

- **Visuals:** Cave 2 "not cavy enough." Overlapping elements in the
  building phase.

------------------------------------------------------------------------

## Tester 10 – Game Production Student 1 (Basic)

- **Observations:** Consulted the clipboard first. Played very fast.

- **Feedback:** "Learned how to feed." Art/Sound/Pacing are good.

- **Issues:** Unsure if feeding actually happened. Second cave placement
  is unclear. Clipboard resets to page 1 during building.

- **Constraint:** Suggests limiting the heat lamp movement more.

------------------------------------------------------------------------

## Tester 11 – Game Production Student 2 (Hardcoded Vet)

- **Observations:** Initially confused by feeding but engaged with the
  Vet immediately upon appearance.

- **Workflow:** Speedran the Vet dialogue. Used the clipboard in
  terrarium view.

- **Feedback:** Understood mixing and variety mechanics quickly.
  Verdict: "Pretty well built, kinda fun."
