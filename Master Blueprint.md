# Master Blueprint: Personal Academic Companion & Mentor Platform

## 1. The Big Vision & Product Positioning

We are building a **Personal Academic Companion and Student Operating System (OS)** designed specifically for students—starting with a **55-student pilot at NST Hyderabad**, expanding across all four NST campuses, and scaling into engineering colleges and schools (Classes 8–12).

### Why We Don't Call It "Just Another AI"

Students today have "AI fatigue." If we call this an "AI tool," people assume it is just a lazy wrapper around ChatGPT. Instead, we position it as a **dedicated academic workspace and mobile companion app**—an always-available digital teaching assistant and smart senior peer that knows our exact syllabus, diagnoses our mistakes without us having to explain them, and manages our entire study routine.

* **The Core Promise:** *"A regular AI dumps code you can't use in exams; our platform teaches you from a blank screen, reads your failed test attempts to see what you were thinking, and guides you in your teacher's exact format."*

---

## 2. The NST Hyderabad Pilot Wedge (Solving Real Portal & Friday Contest Pain Points)

Right now, 55 students at NST Hyderabad use the **NST Portal** for daily homework and take **weekly contests every Friday**. Even though the portal has built-in hints or a "Review Code" feature, it fails students in two critical moments:

### A. Fixing "Blank Screen Paralysis" (When You Can't Even Start Writing Code)
* **The Problem:** Built-in "Review Code" tools require you to already have code written. When a student reads a complex portal question and doesn't even understand how to start, they stare at a blank editor completely stuck.
* **Our Solution (Logic-First Scaffolding):**
  1. **Sentence-by-Sentence Deconstruction:** Before asking for code, the mentor breaks the problem prompt down into plain-English inputs, rules, and outputs.
  2. **Paper Dry-Run First:** The mentor walks the student through a small example manually (*"Forget Python syntax for a second—if the list is `[4, 2, 7]`, how would your brain find the answer step-by-step?"*).
  3. **Classroom Blueprint:** Once the student understands the manual logic, the mentor maps those steps directly to the loops and commands taught in NST lectures.

### B. The "Friday Contest Post-Mortem" Engine
* **The Problem:** During Friday contests, students get stuck on problems and often **cannot even explain to a teacher or friend where they went wrong**—they just know their code failed or timed out.
* **Our Solution (Silent Mistake Diagnosis & Weekly Fix):**
  1. **Reading the Wrong Attempt:** Right after Friday's contest, the student drops their failed or incomplete code into the app.
  2. **Reverse-Engineering the Student's Thought Process:** Instead of just saying *"Wrong Answer on Test Case 4,"* the platform reads the broken code to understand **what the student was trying to do** and pinpoints the exact mental slip (e.g., *"You assumed the input array was sorted, which broke your loop on negative numbers"*).
  3. **Saturday-to-Thursday Targeted Drills:** Based on Friday's diagnosis, the system automatically serves tailored follow-up questions throughout the week—all locked to the classroom syllabus—so the student fixes that exact gap before next Friday's contest.

---

## 3. Why Normal AI & Existing EdTech Platforms Fail Students

1. **Unapproved Code & Wrong Formats:** ChatGPT gives complicated internet shortcuts (like complex `awk`/`sed` one-liners or external libraries) that professors never taught, causing marks to be deducted in labs and exams.
2. **Copy-Pasting Causes Exam Failure:** Dumping full code blocks stops students from learning, leaving them blank during offline lab exams and vivas.
3. **No Help When You Can't Articulate Your Doubt:** Standard AI requires you to write a good prompt explaining your confusion. When you don't even know *what* you don't know, a blank chat box is useless.
4. **Zero Memory of You:** Normal chatbots start from scratch every session—they don't remember your Friday contest failures, weak topics, or learning style.
5. **Fragmented Market:** Khanmigo is locked to its own school videos, Embibe feels like a cold test database without natural voice or burnout care, and Chegg promotes cheating. Nobody combines classroom-locked guidance, wrong-answer thought diagnosis, voice mentorship, and routine management under one roof.

---

## 4. Complete Feature List (23 Features in 6 Simple Buckets)

### Bucket 1: Getting to Know You (Onboarding & Learning Style)
*How the platform learns your habits from Day 1 so it treats you like a real student, not a stranger.*

1. **Intake Chat on Signup:** When you first join, the mentor interviews you to learn your daily schedule, available study hours, prior background, and target scores or exams.
2. **Reality Check & Difficulty Score (1 to 10):** Evaluates your target goals against your actual available hours. If a goal is unrealistic, it warns you honestly and outputs a **Difficulty Score out of 10** so you know the exact effort required.
3. **Remembering How Your Brain Learns:** Observes what clicks best for you—visual diagrams, step-by-step code, real-world analogies, or math proofs—and automatically adapts all future explanations to match your style.
4. **Goal & Deadline Tracker:** Keeps all your upcoming semester exams, Friday contests, lab submission dates, and target milestones organized in one place.

### Bucket 2: Daily Homework & Classroom Guidance
*What happens when you sit down to solve a tough assignment or college lab problem.*

5. **Blank-Screen & Line-by-Line Question Breakdown:** For big, confusing homework problems where you don't know how to start, it breaks down each line of the question statement first, walks through a manual dry-run example, and builds up your understanding step-by-step.
6. **Logic First, Syntax Second (Subject Adaptation):** The teaching approach changes depending on the subject. In Python or C++, it explains the core logic flow and loop conditions first before writing any code; in Math or Physics, it walks through the derivation sequentially.
7. **Classroom-Format Solution Engine:** Strictly locked to our college lecture slides and syllabus. It only uses the commands, loops, and syntax our professors taught in class so we never lose marks. (Includes a dual-tab view: *Tab 1: Exam-Ready Classroom Format*, *Tab 2: Optional Industry/Real-World Way*).
8. **Natural Voice Mode:** No need to type long paragraphs. Put on headphones, toggle voice mode, and talk back and forth naturally with the mentor like you are sitting next to a helpful senior in the lab.
9. **Socratic Hints (No Spoiling Answers):** The mentor never gives away the full code. It uses tiered hints—first a small clue, then a guiding question, and finally a breakdown—to push you to solve it yourself.
10. **1-Click Helper Buttons (Zero-Prompt UI):** Instead of typing out long prompts when stuck, you get fast action buttons on screen: *"Break Down Question"*, *"Explain the Logic"*, *"Give Me a Clue"*, or *"Show Intuition"*.
11. **Instant Comprehension Check ("Twin Problem"):** Once you solve a tricky question with help, it immediately gives you an identical "twin problem" with different numbers or variables to verify that you truly understood it on your own.

### Bucket 3: Test & Wrong-Answer Diagnosis (Finding the Root Cause)
*What happens after you submit homework or finish a Friday contest.*

12. **Wrong-Code Thought Diagnosis (Contest & Homework Post-Mortem):** Reads your failed or wrong attempts even when you can't explain where you got stuck. It figures out what logic you were attempting, pinpoints the exact mistake (silly syntax slip vs. edge-case blind spot vs. conceptual gap), and teaches you how to fix it.
13. **Prerequisite Gap Tracing:** Models subjects like a connected family tree. If you keep failing an advanced topic (like recursion or rotational mechanics), it traces backward to find the missing root foundation (like basic loops or vector algebra) and fixes that first.
14. **Traffic-Light Mastery Scorecard:** A clean visual dashboard rating every syllabus topic:
    * **Green:** Mastered and solid.
    * **Yellow:** Shaky, needs review.
    * **Red:** Critical weak spot where you keep dropping marks.

### Bucket 4: Targeted Practice & Smart Revision ("The Medicine")
*Fixing your exact weak spots without wasting time on 50 random textbook problems.*

15. **Targeted "Medicine" Practice:** Instead of overwhelming you with 50 random questions, it prescribes only the exact 2 or 3 micro-questions needed to fix your red topics from Friday contests and homework.
16. **Custom Mock Tests on Demand:** Generates personalized practice tests weighted heavily toward the specific topics where you historically make mistakes.
17. **Memory Vault (Smart Spaced Revision):** Uses spaced-repetition algorithms (FSRS) to track when your brain is about to forget an older topic, popping up a quick 2-minute recall question right before the memory fades.
18. **3-Phase Topic Breakdown:** Every chapter is structured into three clear phases:
    * *Phase 1:* Learning the concept.
    * *Phase 2:* Active problem practice.
    * *Phase 3:* Timed spaced revision before exams.

### Bucket 5: Routine, Schedule & Burnout Care
*Managing your daily student life so you stay consistent and don't burn out.*

19. **Dynamic Study Timetable:** Builds a realistic weekly study calendar tailored to your upcoming assignment deadlines, Friday contests, and exam dates.
20. **Auto-Adjusting Schedule:** If you fall behind because of college events or a busy day, it automatically recalculates your buffer, trims low-priority topics, and inserts catch-up blocks without shifting your final exam target date.
21. **Flexible & Active Study Sessions:** Learning sessions are interactive two-way checks (not passive videos), and you can jump in early or study asynchronously whenever you have free time between lectures.
22. **Burnout & Fatigue Guard:** If you have been grinding code for 4 hours straight or your error rates spike because you are exhausted, the mentor steps in: it tells you to stop, take a 5-minute stretch, drink water, or rest so you don't burn out.

### Bucket 6: Self-Paced Explorer (Learning Something New)
*For students who want to build extra skills beyond college.*

23. **"Learn Something New" Roadmap:** If a student wants to learn something outside their college syllabus (like web development, machine learning, or a new tool), the platform builds a complete, beginner-friendly roadmap right from scratch and guides them step-by-step.

---

## 5. Step-by-Step Student Journey (How It Works in Real Life)

1. **Login & Setup:** Student logs into the platform. The mentor runs a quick intake chat to map their schedule, baseline level, and goals (or lets them pick a brand-new skill to learn).
2. **Blank-Screen Portal Homework:** Student opens an NST portal problem and doesn't know how to start. They open our app—the mentor breaks the question down sentence-by-sentence, walks through a manual dry-run, and explains the Python/C++ logic flow before any code is written.
3. **Voice or Click-First Mentorship:** The student talks through doubts via headphones (Voice Mode) or taps quick helper buttons. The mentor highlights suspect lines and gives Socratic hints in the professor's exact format.
4. **Friday Contest Post-Mortem:** After Friday's contest, the student pastes their wrong/failed contest code. Without the student having to explain anything, the app reads the code, identifies where their logic broke, explains the fix, and adds 3 targeted follow-up problems to their weekly plan.
5. **Mastery & Routine Sync:** The student solves a quick "Twin Problem" to confirm understanding, their Traffic-Light Scorecard updates, and their timetable schedules short revision drills.

---

## 6. Under the Hood: Key Technical Concepts Explained Simply

* **LLM (Large Language Model):** The core AI reasoning engine (like GPT-4 or Claude) that powers the mentor's conversation and code diagnosis.
* **Context Window & Tokens:** The AI's short-term working memory (measured in tokens, where $1\text{ token} \approx 0.75\text{ words}$). Stuffing an entire semester of textbooks into the context window makes the AI slow, expensive, and forgetful ("context overflow").
* **RAG (Retrieval-Augmented Generation):** Think of RAG as an **open-book exam** for the AI. Instead of dumping 200 pages of notes into memory, RAG searches our private database of college slides and pulls **only the 1 exact slide** needed for the student's current question. This keeps the app fast, prevents hallucinations, and locks answers strictly to the professor's syllabus.
* **The Curriculum Dictionary (`syllabus-dictionary.json`):** A structured rulebook mapping each course topic to *Allowed Commands/Syntax*, *Banned External Shortcuts*, and *Professor Grading Notes*. Includes a **"Not Taught in Class"** button so students can upload whiteboard solutions and update the rulebook for all 55 batchmates.

---

## 7. College Portal Integration Strategy (Solving Browser Security)

Because browsers enforce strict security boundaries (**CORS / Same-Origin Policy**), an external website cannot secretly read data from the NST portal without permission. We solve this in three smart phases:

1. **Phase A (MVP — Paste & Community Cache):**
   Students paste the NST portal problem or Friday contest wrong code once. As soon as **Student 1** pastes a problem, our database saves it so all 55 batchmates see it pre-loaded automatically.
2. **Phase B (20-Line Browser Bridge Extension):**
   A tiny, invisible helper extension reads the problem description and code from the active NST portal tab and sends it straight to our web app via `window.postMessage` whenever the student clicks sync or refreshes. Zero copy-pasting needed, and no college IT permission required.
3. **Phase C (Official LTI / SSO Integration):**
   Once we prove our batch's Friday contest and exam scores improved, we pitch the administration for official Single Sign-On and direct webhook access to assignments and contest submissions.

---

## 8. Tech Stack & "Vibe Coding" Execution Plan

* **Frontend Web & Mobile:** Next.js 14 (App Router), Tailwind CSS, `shadcn/ui`, and **Monaco Editor** (the VS Code editor in the browser). Configured as a **PWA (Progressive Web App)** so students can install it on iOS/Android home screens immediately.
* **Backend & AI Logic:** Next.js API Routes / FastAPI (Python) with strict Socratic & Wrong-Code Diagnosis system prompts.
* **Database & Memory:** **Supabase (PostgreSQL + pgvector)** for student login, mastery scorecards, Friday contest error logs, timetables, and RAG slide storage.
* **Natural Voice Engine:** Browser Web Speech API for push-to-talk input + **Cartesia / OpenAI Realtime API** for sub-300ms natural human-like audio responses.

---

## 9. Go-To-Market (GTM) Rollout: From NST Hyderabad to Schools

1. **Phase 1: The NST Hyderabad Pilot (55 Students — Zero Marketing Cost)**
   * Start with 5–10 close friends in the hostel during an upcoming portal deadline and Friday contest. Once batchmates see that it rescues them from blank screens and diagnoses their Friday contest mistakes automatically, all 55 students adopt it naturally.
2. **Phase 2: All 4 NST Campuses (200–500+ Students)**
   * Pune, Delhi NCR, and partner campuses share the exact same syllabus, portal, and Friday contest structure. Our Curriculum Dictionary works for them out of the box on Day 1.
3. **Phase 3: External Engineering Colleges**
   * Take hard data from our NST pilot (*"Students solved portal assignments faster, eliminated blank-screen paralysis, and improved Friday contest scores"*) to pitch outside engineering colleges.
4. **Phase 4: School Level Expansion (Classes 8–12, Boards & Coaching Institutes)**
   * The exact same engine translates directly to high school and competitive exam prep by swapping the Curriculum Dictionary:

| Core Engine Feature | How It Works at NST (College) | How It Adapts to School Level (Classes 8–12) |
| :--- | :--- | :--- |
| **Blank-Page Paralysis** | Breaks down a portal coding prompt into manual dry-run logic before writing Python/C++ syntax. | Breaks down a long Physics/Math word problem into *"Given data"*, *"Target formula"*, and *"Step 1"* before calculating. |
| **Classroom Format Lock** | Uses only loops, libraries, and commands taught by NST professors. | Strictly follows **NCERT / CBSE / Board marking schemes** (step-by-step derivations so students never lose step-marking). |
| **Weekly Test Post-Mortem** | Reads failed Friday contest code to spot logic flaws, TLE, or edge-case blind spots. | Reads uploaded photos of marked Sunday school/coaching test sheets to spot calculation slips vs. missing prerequisite concepts. |
| **Targeted Follow-Up Drills** | Serves 3 tailored coding problems before next Friday's contest. | Serves 3 targeted numericals/MCQs targeting the exact chapter where marks were lost. |

---

## 10. Pitch Scripts & One-Liners

### Short One-Liners
* **For Batchmates:** *"It’s a companion app built for our NST portal and Friday contests—when you're staring at a blank screen, it teaches the logic line-by-line in our class format, and after Friday contests, it reads your wrong code to show where your thinking broke and gives you practice questions to fix it."*
* **Shortest 8-Word Hook:** *"A voice mentor locked strictly to your classroom syllabus."*

### Casual Pitch for Your Friend Tomorrow
> *"Bro, look at what happens to all 55 of us right now: on the NST portal, the 'Review Code' button doesn't help when you can't even write the first line of code, and every Friday after the contest, we get stuck on questions and can't even explain to anyone where our logic went wrong. What if we build our own student app that fixes both? When you're staring at a blank screen, it breaks the question down line-by-line and explains the Python logic first using only what our teachers taught. And after Friday's contest, you just drop your wrong code in—it reads your code, figures out what you were thinking when you messed up, teaches you the fix, and gives you 3 targeted practice questions for the week. Plus, it manages our study timetable and burnout breaks. We test it with our 55 batchmates first, take it to all 4 NST campuses, and then expand to other colleges and schools."*