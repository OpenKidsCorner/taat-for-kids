# Session 3
**Date:** April 18, 2026 | **Age group:** 8–12 | **Present:** 11 kids

بسم الله الرحمن الرحيم

Alhamdulillah, Allah made this third session possible. May He accept it, forgive our shortcomings, and put lasting benefit in it for the children.

---

## How the Day Unfolded

### Physical Warm-up — Stretching and Football

Eight kids joined from the start and took part in the warm-up exercises and football. The remaining three joined later in the day.

The beginning of the day followed the same familiar shape as the previous sessions — stretching exercises, a game of football, and then the walk back home. Alhamdulillah for the routine settling in.

---

### Returning Home — Wuzu and Nafl Salah

After returning from the ground, everyone made wudu and prayed two nafl to ask Allah for help and blessing before the session began. May Allah accept it and make it a cause of ease in learning for these children.

---

### After the Prayers — Complex Diagrams

The kids were given three complex diagrams and asked to describe paths using the same language introduced earlier: **right**, **left**, **diagonal-right**, **diagonal-left**, and **forward**. An example of the kind of diagram used:

```
            _ _ 
/\/\/\ _ _ |   \
                \
                /
```
**When Facing ->**
DL DR DL DR DL DR F F L F R F F DR DR R DR
**When Facing ^**
R DL DR DL DR DL DR F F L F R F F DR DR R DR
DR R DR DL DR DL DR F F L F R F F DR DR R DR
DR R DR L DR R DR L DR R DR F F L F R F F DR DR R DR


**Observations:**

- When first shown the complex diagrams, some students hesitated and said they wouldn't be able to do it. After a little encouragement, they were able to push through.

- Students came up with different solutions — largely because they assumed different starting directions. As with simpler diagrams, a different starting state leads to different code, yet two different solutions can both be valid ways to reach the same result from the same starting point.

- With the more complex diagrams, students would often start correctly but make mistakes partway through. Common errors included:
  - Losing track of their current state mid-demonstration (e.g. turning 180° when saying right/left)
  - Misinterpreting a command (e.g. correctly applying diagonal-right, then applying diagonal-left as a 45° turn instead of one step diagonally)

- Some students completed the first diagram and did not want to attempt the remaining ones.

- One of the biggest challenges was reviewing and giving feedback to everyone. Students would come one after another to show partial attempts, or return after fixing only one thing from prior feedback. It became somewhat chaotic, and it was difficult to give everyone the thorough feedback their attempts deserved.

---

### Binary Recap — For Students Who Missed Last Session

A few students had missed the previous session, so we briefly revisited the two extremes of the computer language tower: **natural language** (now possible through AI) at the top, and **binary / electronic signals** at the bottom. We then connected this back to the bulb activity — students noted down the state of the bulb each time a hand was raised.

---

### Three Bits and Binary Arithmetic

We briefly discussed how three bits map to the numbers **0 through 7**, and walked through an example of adding +1 in binary. Students were then given the following tasks:

**Convert from binary to decimal:**

| Binary | Decimal |
|--------|---------|
| 010    | 2       |
| 001    | ?       |
| 101    | ?       |
| 000    | ?       |

**Binary addition (+1):**

```
101 + 1 = ?
011 + 1 = ?
001 + 1 = ?
010 + 1 = ?
111 + 1 = ?
```

**Observations:**

- Some students again had difficulty grasping the concept of carrying forward when there is a `1 + 1`. As a result, some memorized it as a rule ("1 + 1 = 10") without fully understanding why.

- This concept will need regular repetition and practice before it truly settles in.

---

### Moving Up the Tower — Assembly Language

To motivate the need for a higher layer, we asked: what does 100 look like in binary? What about 1,000? What about representing millions, or long names? Students began to see that binary alone would be extremely difficult for a human to work with — so humans added layers on top. One of those layers is **Assembly Language**.

**The mental model: processor and registers**

We mapped the processor and registers to the human brain — where you hold information and where you perform computations. Two memory blocks, A and B, store values; a processor block performs the operation:

```
______                    _________________
|_____|  = A             |                 |
                         |    Processor    |
______                   |                 |
|_____|  = B             |_________________|
```

**Keywords — a limited vocabulary to instruct the computer:**

```
Move A, 5;
Move B, 10;
Add A, B;
```

Result:

```
______                    _________________
|__5__|  = A             |  5 + 10 = 15   |
                         |    Processor    |
______                   |                 |
|_10__|  = B             |_________________|

→ A = 15
```

**Student tasks — two-number addition:**

Students were asked to write assembly code for:
- `5 + 6`
- `10 + 17`

**Three-number addition — teacher example then challenge:**

The approach for adding three numbers was briefly explained:

```
Move A, 5;
Move B, 10;
Add A, B;
Move B, 6;
Add A, B;
→ A = 21
```

Students were then challenged to write code for:
- `10 + 6 + 7`
- `5 + 9 + 8`
- `14 + 12 + 8`

Students were given time to work through it. Some came back multiple times to discuss; others finished quickly and were waiting to move on.

**The chocolate challenge — subtraction**

Without any explanation, students were told that `Sub` is used for subtraction, and asked to write code for:

```
10 + 5 - 7
```

- The student who finished **fastest and correctly** would receive **two chocolates**
- Any student who finished **correctly** would receive **one chocolate**
- Younger students would receive a chocolate just for **attempting**

### Chocolate Winners of the Day

- **2 chocolates** — the student who completed fastest
- **1 chocolate each** — approximately 5 students who completed the activity correctly
- **1 chocolate** — a student, for maintaining good discipline
- **A few chocolates** — younger students, for keep trying and pushing forward

---

## Key Takeaways

**For the students:**
- The same path can be described in multiple valid ways depending on your starting direction — there isn't always one right answer in programming
- Binary scales poorly for humans; each layer of the language tower exists to make things easier to express and understand
- Carrying forward in binary addition (`1 + 1 = 10`) is a concept that needs repeated practice — memorizing the rule isn't the same as understanding it
- Assembly language lets us give human-readable instructions to the processor using a small, fixed vocabulary — just like our limited-word robot language, but for machines
- When given an unfamiliar instruction (`Sub`), students could reason about it from context — this is a real skill in programming

**For the teacher:**
- Reviewing everyone's work during open-ended activities needs a better system — one-on-one feedback at scale becomes chaotic without structure (e.g. a queue, peer review, or checkpoint moments)
- Some students shut down at first sight of complexity, but encouragement consistently unlocks effort — worth building that into the flow deliberately
- Fast finishers need a prepared next challenge so they aren't waiting idle
- Chocolate incentives worked well for motivation across age groups; the tiered structure (speed, correctness, discipline, effort) felt fair and inclusive

---

*Alhamdulillah for this day. We ask Allah to forgive what was lacking, bless the children who came, and make this a step — however small — toward using knowledge to serve Him. All good is from Allah alone.*



