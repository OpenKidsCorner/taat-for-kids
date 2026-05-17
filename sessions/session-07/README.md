# Session 7
**Date:** May 16, 2026 | **Age group:** 8–12 | **Present:** ~9 kids

بسم الله الرحمن الرحيم

Alhamdulillah, Allah made this seventh session possible. May He accept it, forgive our shortcomings, and put lasting benefit in it for the children.

---

## How the Day Unfolded

### Physical Warm-up — Football

The warm-up was a short game of football. Only the teacher and three kids were present at the start, with one more joining toward the end. The heat cut the game shorter than usual — alhamdulillah for whoever showed up and gave it their energy. May Allah make it easy for those who could not come.

---

### Wuzu and Nafl Salah

Everyone prayed two nafl before the session. A couple of the kids had already prayed before arriving, which was noted with appreciation. May Allah accept the salah from all of them and make this a consistent habit that grows with each session.

---

### Revision Worksheet

The session had roughly 1.5 hours of activity time. The plan was to use the first 30 minutes for five revision questions, then move into new activities for the remaining hour. The worksheet is below.

Two students joined late — the older one among them also managed to complete the worksheet in time. A couple of fast finishers completed the revision early and, while waiting for others, started playing games on their laptops.

---

**Instructions key for Q1:**

| Instruction | Meaning |
|-------------|---------|
| **F** | Move one step Forward |
| **R** | Turn Right (90°) |
| **L** | Turn Left (90°) |
| **DR** | Move one step diagonally right while keeping the same direction |
| **DL** | Move one step diagonally left while keeping the same direction |

---

**Q1 — Write the instruction set to draw the following diagram:**

```
  _ _ _ _ _ _ _ _
| \             /|
|  \           / |
|  /          /  |
| /           \  |
|/_ _ _ _ _ _ _\ |
```

---

**Q2 — Think of any interesting diagram you can draw using the above instructions, and write its instruction set.**

---

**Q3 — Perform the following binary additions:**

```
  1111       0101       0100
+  111      + 101      + 011
```

---

**Q4 — Fill in the next three numbers in the sequence:**

0101, 0110, ___, ___, ___

---

**Q5 — Write assembly code for the following expression:**

`5 + 10 - 11 + 6 + 8 - 7`

*Syntax reminder: `MOV A, 3;` &nbsp; `ADD A, B;` &nbsp; `SUB A, B;`*

---

#### Observations

- For Q1, students were generally able to figure out the path, but hit a mental block when they realised completing the diagram would require walking over a line they had already drawn. They assumed this was not allowed. Once told there is no such restriction — the robot can retrace an existing line — they were able to work through it. There were still some minor mistakes afterward, largely from carelessness rather than a gap in understanding.

- Only a couple of students completed all five questions within the first 30–40 minutes. The rest needed more time, and the timeline did not hold as planned.

- Q5 was the most significant sticking point. Most students either forgot the assembly language syntax or had missed the sessions where it was introduced. Explanations had to be given individually and in small groups. The concept is not yet settled — more dedicated revision will be needed in the next session before it can be treated as background knowledge.

- Fast finishers defaulted to playing games on their laptops while waiting. This is a recurring gap — there was no prepared next challenge ready for them.

---

### Python — First Steps with `print`

The plan had included three new learning activities, but given the time remaining after the worksheet, only the second — Python — was reached.

Students were asked to open the W3Schools Python editor (the "Try It Yourself" page with the `print` example). The task was simple: print any dialogue.

The responses varied:
- Some printed random lines across multiple `print` statements without a clear structure
- A few printed a proper dialogue — two characters exchanging lines
- A couple had only managed a single `print` line by the time the session ended

The session had a hard stop at 11:00 AM and closed before any of the three planned activities could be completed in full.

---

**The planned activities — for reference and future sessions:**

**Activity 1 — AI builds a custom language interpreter**

Ask AI to build a Python interpreter for the custom robot language (F, R, L, DR, DL) that draws diagrams when instruction sequences are given as input.

**Activity 2 — Python `print` practice** *(covered today)*

Use Python's `print` command to reproduce formatted output. Examples:

*a) A dialogue:*
```
Ali:   As Salam o Alikum! How are you?
Yasir: Alhamdulillah, I am great, thanks!
Ali:   That is wonderful to hear.
```

*b) A conversation with a bot:*
```
Bot:  What is your name?
User: My name is Sara.
Bot:  How old are you?
User: I am 14 years old.
Bot:  Where do you live?
User: I live in Lahore.
```

*c) A formatted menu:*
```
=========================
     RESTAURANT MENU
=========================
Burger         Rs. 450
Pizza          Rs. 850
Salad          Rs. 300
------------------------------
```

**Activity 3 — Drawing with p5.js**

Draw a steel-blue rectangle (200px wide, 100px tall) with a thick dark-blue border on a cream canvas.

```javascript
function setup() {
  createCanvas(300, 200);
}

function draw() {
  background(255, 250, 220);   // Cream background
  fill(70, 130, 180);           // Steel blue fill
  stroke(30, 30, 150);          // Dark blue border
  strokeWeight(4);
  rect(50, 50, 200, 100);       // x, y, width, height
}
```

---

#### Observations

- One student shared what he had built independently using AI outside of the sessions. He had made two applications: an online store for bicycle parts with an admin login to manage products across different categories, and a cycling activity tracker with a commenting feature. His accounts had exceeded the AI usage limit, hence he asked whether to pay for Claude or Replit. I recommended to move forward with replit, as it will be much easier for developing and publishing the app. Alhamdulillah — this is exactly the kind of self-driven exploration the sessions are meant to inspire. May Allah grow that initiative in him and in all the students. 

- Multiple students ran into errors during the Python activity — adding an extra line inside a string, missing a closing quote, or forgetting a bracket. Each time, the code refused to run. This was used as a direct reminder of what has been said across every session: the computer follows the rules exactly as written, with no tolerance for even small deviations. Seeing their own mistake produce a real error on screen made the point more effectively than any explanation could.

- The Python `print` activity revealed a range of understanding. Students who produced multi-line dialogues showed they had grasped that each `print` call produces its own output line. Those who only managed one line had not yet made that connection.

- Activities 1 and 3 were not reached. They carry forward to the next session.

---

### Closing — Challenge and Clean-up

Before closing, each student was given a challenge: explore and self-learn Python through the W3Schools Python learning path by working through as many tutorials as possible in the left-hand menu. A couple of students responded with visible excitement. Others took it more casually. One student said he would aim to complete all the challenges. May Allah bless them with the right motivation and make the self-learning journey easy for each of them.

Everyone then cleaned up the room, returned the chairs to their places, and left.

---

## Key Takeaways

**For the students:**
- Assembly language is a real language with a precise syntax — `MOV`, `ADD`, and `SUB` must be written exactly as defined. Not having practiced it recently means forgetting it. Revisiting something you have learned before is part of the process, not a failure.
- In Python, each `print` statement produces one line of output. Formatting — spacing, alignment, separators — has to be built deliberately, one line at a time.
- Self-learning is a skill worth developing. The W3Schools challenge is an invitation to build the habit of exploring a topic on your own, without waiting to be taught.

**For the teacher:**
- Assembly language has now resurfaced as a gap in three consecutive sessions. A short dedicated drill at the start of the next session — writing two or three expressions from scratch — would consolidate it more effectively than re-explaining it each time it appears.
- The 30-minute revision plan ran to 40+ minutes for most students and still left some incomplete. Either the worksheet needs fewer questions or the time allocation needs to be longer. Planning for a 45-minute revision block and a 45-minute activity block may be more realistic than the current split.
- Fast finishers had nothing prepared to move to and defaulted to games. A standing rule — "if you finish early, move to Activity 1" — would solve this without needing to manage it in the moment.
- Activities 1 and 3 from today's plan carry directly into the next session. They do not need to be redesigned — just picked up from where today ended.
- The self-learning challenge at the close was a good instinct. Worth following up at the start of the next session: ask who explored, what they found, and whether anyone has a question or something to show.

---

*Alhamdulillah for this day. We ask Allah to forgive what was lacking, bless the children who came, and make this a step — however small — toward using knowledge to serve Him. All good is from Allah alone.*
