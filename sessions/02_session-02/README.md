# Session 2 — The Tower of Computer Languages
**Date:** April 11, 2026 | **Duration:** ~4.5 hours | **Age group:** 8–12 | **Present:** 7 kids

بسم الله الرحمن الرحيم

Alhamdulillah, Allah made this second session possible as well. Though some kids were unable to join today, and we had to change our venue; Alhamdulillah, we came back together in a single room to continue our journey — and again, Allah blessed the day beyond what we had planned. May He accept it, forgive our shortcomings, and make it a source of lasting benefit for these children.

---

## Learning Outcomes

By the end of this session, if Allah willed it for them, students were able to:

- Revisit the concept of **language** from the previous session — that every machine has a fixed vocabulary, and you cannot go beyond what it understands
- Begin to appreciate that there is not just one computer language, but a whole **tower of languages** — each layer built on top of the one below it
- Understand what **binary** is — that at the very bottom of this tower, a machine only understands two things: **0 and 1**
- Connect the idea of the light switch from Session 1 (on/off) to the concept of binary — that the simplest machine language is nothing more than a long sequence of ons and offs
- Begin to explore how meaning — numbers and letters — can be represented using only 0s and 1s

---

## How the Day Unfolded

### Before the Session — A Smaller Group, A New Venue

The day started with news that four of the kids would not be able to join, and one would be late. Alhamdulillah — whatever Allah arranges is what is best. The rest of us grouped together at the new venue and then made our way to the ground, one kid on bicycle and the others on foot.

On reaching the ground, we walked around looking for a suitable open space. A small thing, but it set a relaxed tone for the morning.

---

### Stretching (~10–15 min)

Before football, we started with stretching exercises. The kids participated — but with the kind of honest impatience only children can show. Every few seconds: *"Is this the last one?"* *"Are we done yet?"*

Alhamdulillah for that impatience, actually. May Allah help them — through small experiences like this — understand why the boring prerequisites exist before the real work begins. And may Allah give them the patience and discipline to move through such steps happily, not grudgingly. May He make it easy for them.

---

### Football (~30 min)

When the stretching finally ended, the kids were relieved and ready. They set up goals with wooden sticks and formed two teams — three on one side, including the instructor, and four on the other.

The match ended, by best recollection, at a tie: **2–2**. Alhamdulillah for the energy and the laughter.

---

### Returning Home — Water and Rest

After the match, everyone walked back. Water was the first thing on everyone's mind, and rightly so. Kids freshened up and the room settled into a quieter pace.

---

### Wuzu and Nafl Salah — Asking Allah for Help

Everyone made wudu and prayed two nafl to ask Allah for help before the session. This time, without any particular plan, we each ended up praying individually rather than in congregation. However it happens, the intention is the same — to begin by asking Allah, and not to rely only on ourselves. May Allah accept it.

---

### The Lesson Begins — Revision Activity

While the kids were still in salah, the activity was written and drawn on the board so it would be ready when they turned around.

**Instructions key:**

| Instruction | Meaning |
|-------------|---------|
| **F** | Move one step Forward |
| **R** | Turn Right (90°) |
| **L** | Turn Left (90°) |
| **DR** | Move one step Diagonally to the Right |
| **DL** | Move one step Diagonally to the Left |

**Example given:**

```
+--+
|  |
+--+

Square — 1×1 | Instructions: F-R-F-R-F-R-F
```

**Activity — find the instruction sets for each shape:**

```
+---+        +----+
|   |        |    |
+---+        |    |
             +----+

Square 2×2   Rectangle 1×3
```

```
  /--/                 /\
 /  /                 /  \
/--/                  \  /
                       \/

Parallelogram 1×2    Rhombus 1×1
```

---

### Everyone Gets to Work

Everyone was asked to work out the instruction sets in their notebooks or on paper. And alhamdulillah — everyone made their attempt. Some finished quickly. Others took their time, not always because the problem was hard, but because there were conversations to be had and distractions to be enjoyed. That is just how it is with kids, and there is something honest about it.

What was good to see: almost everyone at some point stood up and physically walked through their own instructions — testing it on their feet before bringing it for review. Some raised their hands, some just walked over. Each at their own pace, in their own way.

May Allah steadily grow everyone's enthusiasm, understanding, and discipline — and may He make learning a source of joy for them, not burden.

---

### Common Mistakes — and What We Learned from Them

Alhamdulillah, the mistakes were the most valuable part.

#### 1 — "F × 2"

One student wrote `F x 2` to mean "move two steps forward." A natural shorthand — but the computer does not understand `x 2`. It only knows what it has been told. The result would be something like:

> *Error: something went wrong — please try again.*

The instruction has to be written out explicitly: `F-F`. Every step counts as its own command.

#### 2 — Same "F" for All Shapes

Some students used a single `F` for every side of every shape — not noticing that the shapes were drawn at different sizes. The discussion that followed: a computer does exactly what you write. It does not look at the shape and think, *"oh, this side is longer, I should take more steps."* If you write one step, it takes one step. Nothing more. The instruction has to be as detailed as the task requires.

#### 3 — The Rhombus and Forgetting Direction

This was the most common and the most instructive mistake. Most students wrote `DL-DR-DL-DR` for the rhombus — and it would not draw a diamond. It would leave a zig-zag:

```
 \  /\  /
  \/  \/
```

What was missing: after completing the first two sides, the robot is still facing the same direction. To trace the other two sides, it needs to turn around first. The correct approach requires keeping the full context in mind — where the robot is, and which way it is facing — before writing each new instruction.

One working solution, after working through it together:

```
        /\
       /  \      DL - DR  (left side, going down-right)
       \  /      R - R    (turn to face the opposite direction)
        \/       DL - DR  (right side, completing the diamond)
```

May Allah help us learn from our mistakes — not be discouraged by them — and let each correction be a step forward in understanding.

---

### While the Others Waited

While the instructor moved between kids reviewing their work, the ones who had finished — or were waiting — found their own entertainment at the board.

One kid changed all the values in the examples from single digits to numbers in the thousands. Another drew a circle on the board and asked: *"Can we draw this?"*

*"No,"* came the reply.

*"Yes we can,"* he said — and pointed to the instruction set, where he had quietly added a new line when no one was looking:

> **CR** — Circle

Alhamdulillah. The instinct was exactly right — if the language cannot do something, extend it. Define a new instruction. That is precisely how every layer of computer language above the first one was built. May Allah grow that kind of thinking in all of them.

---

### A New Student Joins — Revision on the Spot

At some point during all of this, a new student arrived. It was their very first session — they had missed the previous one entirely.

So we paused and went back to the beginning. The whole arc from Session 1, quickly but honestly:

- How do we communicate? Through **language** — a shared vocabulary.
- The electric bulb: one switch, two states — **on** or **off**. That is its entire language.
- The AC remote: more buttons, more instructions. A richer language, but still fixed.
- The robot: with only **F, R, L** — we can draw a square. But not a triangle. Not a parallelogram. The language runs out.
- Adding **DR** and **DL** — now more shapes become possible. The language grew.

Alhamdulillah, the student was sharp and already carried some background knowledge. The concepts landed quickly, and we were able to move on without much delay. May Allah continue to bless that student with clarity and eagerness to learn.

---

### The Tower of Computer Languages — Top and Bottom

With the activity done and everyone back together, the discussion shifted to a bigger question: we now know the robot's language of F, R, L, DR, DL — but how do we actually talk to a real computer?

The point was made: there are many ways. Today, with AI, you can describe what you want in plain English — or Urdu — and the computer will act on it. At the other extreme, something very different is happening at the electronic and circuit level. And everything in between is a layer of language built on top of another.

---

#### What Actually Flows Inside a Computer?

Since a computer is an electronic device, the question was put to the room: *what actually flows through its wires?*

Answers came from different directions. One of them was: **electron**. Good. And what does it mean when electrons flow? Most paused. Then the answer arrived: **electricity**.

So we turned back to the bulb.

A computer, at its core, is not so different. Electricity either flows — or it does not. The wire is either carrying current or it is not. The machine reads that state at regular intervals and builds meaning from it. On. Off. On. On. Off.

That is the entire vocabulary of the hardware.

---

#### On and Off — The Signal

What this looks like in practice:

```
        _____           _________
_______|     |_________|
 0 0 0  1 1 1  0 0 0 0  1 1 1 1 1
```

The computer reads each position — high or low, on or off — and records it as a **1** or a **0**. A long enough sequence of these becomes a number. A number becomes a letter. A letter becomes a word. And so on, layer by layer.

We call this **binary** — a language with exactly two symbols: **0** and **1**.

---

#### The Tower — Two Extremes

So now we had both ends of something:

```
Natural Language (talk to a computer the way you talk to a person — through AI)
       |
       |
       |
       |
      \ /
       V
Binary Language   (the hardware level — electricity on or off, 0 or 1)
```

At the top: the language most natural to us. At the bottom: the language the machine actually runs on. Everything in between — and there is quite a lot in between — is a tower of languages, each one translating from the layer above into something the layer below can understand.

This was where the session was headed all along. Alhamdulillah.

---

### Experiencing Binary — The Flashlight Activity

With the idea of on/off signals introduced, it was time to feel it rather than just see it on the board.

The plan was to use a light bulb: turn it on and off at regular intervals, and ask the students to write down a 1 each time it was on and a 0 each time it was off. One of the kids raised a concern — that the bulb would fuse from being switched on and off so rapidly. A fair worry, and an honest one. So the light bulb was set aside and the phone torch was used instead.

The instructor held the phone and toggled the torch. At regular intervals — marked by raising a hand — the students had to look at the torch and record its current state:

```
  | | | |         | | | |         | | | |         | | | |         | | | |
\        |      \        |      \        |      \        |      \        |
  |    |           |    |         |    |          |    |          |    |

    ON              ON             Off              Off             On
```

Each raised hand was the clock tick — the moment to observe and record. The torch was either on or off. Nothing in between. And the students wrote it down: **1 1 0 0 1**.

That sequence — just five bits — was them reading a signal exactly the way a computer does. The machine does not see meaning yet. It only reads the state, at each tick, and records it. Meaning comes later, from the layers above.

Alhamdulillah. The activity landed well. May Allah let the simplicity of it stay with them — that underneath everything the computer does, it is only ever asking one question: *on or off?*

---

### Counting in Binary — Decimal 0 to 7

With the signal idea in place, the next question was: how does meaning get built from those 0s and 1s? The first step was to map the numbers we already know to their binary equivalents.

We started from zero and added one each time:

```
000 = 0
001 = 1
010 = 2
011 = 3
100 = 4
101 = 5
110 = 6
111 = 7
```

The students were shown the first two rows and asked to complete the rest themselves up to 7.

To help build intuition, a connection was drawn to how decimal works: in decimal, once we exhaust 0–9, we rotate back to 0 and carry a 1 forward — the same way adding 7 to 16 produces 23. Binary works identically, except the rotation happens immediately after 1: there is no 2, no 3, only 0 and 1. Hit 1 and you have already run out — carry forward and reset.

The mapping between decimal and binary did not fully click for everyone straight away, which is expected — it is a new kind of thinking. Rather than dwell on it, the activity was left open for students to keep trying at their own pace. Alhamdulillah, all of them were able to complete the table, even if some uncertainty remained around *why* it worked.

---

### ASCII — Writing Your Name in Binary

With numbers mapped, the next bridge was to letters. ASCII was introduced: a standard table that assigns a number to every letter of the alphabet, and those numbers can then be expressed in binary.

Two examples were written on the board:

```
01000001 = A
01000010 = B
```

The students were asked to:
1. Complete the table from A to Z
2. Then write their own first name in binary

The ones who already had some background with numbers finished quickly. The others continued working through it — and Alhamdulillah, they all got there in the end.

What was remarkable: working through this table reinforced the adding-one exercise in a very natural way. The students were not just memorizing — they were computing each new letter by incrementing the previous one. And one student made a genuine discovery on their own: **when you add 1 to a binary number, you flip all the bits from the right until you hit the first 0 — and flip that too.** A real insight, arrived at independently. May Allah grow that kind of observation in all of them.

---

### Hangman — In Binary

As the session was drawing to a close, the plan was to briefly touch on the other layers in the tower of languages. But one of the students, clearly energized by everything so far, suggested playing **hangman** — using binary representations of words instead of letters.

The older students who had grasped the concept quickly were already at the board before the idea had finished being spoken.

It was clear that the real learning happening in that game — decoding, encoding, checking — was exactly what the session had been building toward. So the remaining teaching was set aside. The game continued. The others kept working on their names in binary, and help and review continued quietly in the background.

Alhamdulillah. That kind of spontaneous, self-driven application is worth more than any planned lesson.

---

### Closing — Zuhr at the Mosque

The session wound down, and everyone waited together for a few minutes before walking to the mosque for Zuhr. May Allah shower His mercy on these children, accept their efforts, and make them successful in this life and the next. Ameen.

---

### Chocolate Winners of the Day

Two students earned a chocolate:

- **Silence challenge** — one student was asked to stay completely quiet for 15 minutes. He held to it even when he had questions, communicating only through sign language. He earned his chocolate.
- **First name in binary** — the first student to successfully write their full first name in binary numbers.

---

## Key Ideas from This Session

- **A computer's hardware speaks only one language — binary.** At the lowest level, a wire is either carrying electricity or it is not. On or off. That is the entire vocabulary of the machine.

- **The computer reads the signal like a clock.** At every tick, it looks at the state and records a 1 or a 0. It does not see meaning — it only observes the state. Meaning is built in the layers above.

- **Binary counting follows the same carry-forward logic as decimal.** In decimal, after 9 comes 0-carry-1. In binary, after 1 comes 0-carry-1. The base is different, the rule is the same.

- **When adding 1 in binary, flip all bits from the right until you reach the first 0 — and flip that too.** One student discovered this pattern independently, through the act of building the ASCII table. That kind of observation — arriving on your own, not being told — is real understanding.

- **Numbers can represent letters.** ASCII is a shared agreement: each letter is assigned a number, and that number can be written in binary. Meaning is not stored in the machine — it is agreed upon by humans, and then encoded.

- **There is a whole tower of languages between natural language and binary.** At the top: you describe what you want in plain words. At the bottom: electricity on or off. Everything in between is a layer of translation — each language built on top of the one below it.

- **If a language cannot do something, you can extend it.** One student, faced with a shape the robot's instructions could not draw, simply added a new instruction: **CR** — Circle. That instinct — define what is missing — is exactly how every layer above binary was built.

- **Real learning sometimes looks like a game.** The hangman activity was not planned. It emerged because the students wanted it. And in playing it, they were encoding and decoding — doing exactly what the session had been building toward, without being asked.

---

*Alhamdulillah for this day. We ask Allah to forgive what was lacking, bless the children who attended, and make this a step — however small — toward using knowledge to serve Him. All good is from Allah alone.*
