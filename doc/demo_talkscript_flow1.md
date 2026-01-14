Here’s a **demo talkscript** you can read while screen-sharing the single-file app. It’s written for **\~3–4 minutes**, with optional shorter cuts.

---

## **Flow 1 Demo Talkscript (3–4 min)**

**(Open with browser \+ DevTools console visible.)**

**0:00 — Setup / framing**  
“Let me show a quick demo of Flow 1—**cold start**—how we go from messy founder inputs to a **Decision Pack** that becomes *underwritable* instead of just ‘credible-looking.’  
In this demo, everything is hardcoded mock data, but the interactions reflect the real architecture: **Pitch Debugger** compiles, **Workflow OS** applies rubrics and creates tasks, and we iterate until the pack becomes forwardable.”

**0:20 — Point to the layout**  
“Left side is our **Pitch Debugger inputs**—think: deck bullets, transcript snippets, traction metrics, competitors.  
Right side is the **Decision Pack**—the canonical artifact—and below that you’ll see the **Workflow OS rubric output** and **version history**.”

**0:35 — Show the console**  
“Also keep an eye on the console—this is important. You’ll see trace logs that show exactly what the compiler and rubric engine are doing.”

---

### **Step 1: Compile v0 (Pitch Debugger as compiler)**

**0:45 — Click ‘Compile Decision Pack’**  
“I’m going to hit **Compile**. This is Pitch Debugger doing what it does best: turning messy inputs into a structured pack.”

**(Pause: let the pack render.)**

**1:00 — Narrate the output**  
“Now we have **Decision Pack v0**.  
You’ll see five sections that matter for underwriting:

1. **Landscape snapshot** — what buckets we’re in and adjacency  
2. **Secret sauce hypothesis map** — differentiators framed as testable hypotheses  
3. **Risk register** — what could kill it and mitigations  
4. **Evidence plan** — what proof we need next and who owns it  
5. **Evidence index** — receipts we actually have today”

**1:25 — Point to ‘Compiler gaps’**  
“And because it’s a cold start, the compiler flags **gaps**—like ‘insufficient receipts linked to core claims.’  
This is a key shift: instead of pretending confidence, we **surface uncertainty** in a structured way.”

**(Optional console line)**  
“In the console you can see `compileDecisionPack()`—inputs in, pack out.”

---

### **Step 2: Run rubrics (Workflow OS as quality gate)**

**1:45 — Click ‘Run Rubrics’**  
“Next, I run **Rubrics**. This is Workflow OS.  
The rubrics are basically underwriting gates: how strong is evidence coverage, how complete is the risk register, how clear is secret sauce, how clear is ICP.”

**(Pause.)**

**2:00 — Narrate rubric output**  
“Here you’ll see a **score** and a **PASS/FAIL gate**.  
At v0 we usually fail, not because the idea is bad—but because the pack isn’t *underwritable yet.*”

**2:15 — Point to tasks list**  
“Then Workflow OS converts that failure into **tasks**—very specific actions to produce missing evidence.  
This is the ‘iteration loop’: compile → score → tasks → evidence → recompile.”

---

### **Step 3: Complete tasks (produce evidence)**

**2:35 — Click “Mark done” on 1–2 blocker tasks**  
“I’ll mark a couple of these as done.  
In a real system, these would be interview notes, pilot results, exports—here we simulate evidence being created.”

**2:50 — Call out the evidence counter**  
“Notice the evidence count increases.  
The important thing is the evidence is **linked** back to claims—so it becomes underwritable, not just more content.”

**(Optional: mention console)**  
“And again, the console shows exactly what evidence objects were produced.”

---

### **Step 4: Recompile v1 (closing the loop)**

**3:05 — Click ‘Compile’ again**  
“Now I recompile. That creates **Decision Pack v1** with updated evidence index and fewer gaps.”

**3:20 — Run rubrics again**  
“And if I run rubrics again—this is the key—you’ll see the score climb, and eventually we pass the gate.”

**3:35 — Explain the ‘forwardable’ outcome**  
“When it passes, the pack becomes **forwardable**—meaning an investor can confidently send it internally because:

* the claims are tied to receipts,  
* the risks are explicit and bounded,  
* the next evidence steps are clear.”

---

### **Close (what this proves)**

**3:50 — Closing statement**  
“So Flow 1 is basically: **Pitch Debugger compiles a Decision Pack**, and **Workflow OS keeps it underwritable** through rubrics and tasking.  
It’s not a prettier deck—it's a living underwriting artifact.”

**4:05 — Optional ask**  
“If you’re open to it, the next step is: give me one real pitch or transcript, and we’ll run it through this loop and see how quickly we can make it forwardable.”

---

## **60–90 sec “quick demo” version**

“Here’s Flow 1 cold start. Left is messy inputs, right is the Decision Pack artifact. I hit Compile—Pitch Debugger creates v0: landscape, secret sauce hypotheses, risk register, evidence plan, and an evidence index. It also flags gaps. Then I run Rubrics—Workflow OS scores underwriting readiness and fails v0, then generates tasks to produce missing evidence. I mark a couple tasks done, which produces receipts and links them to claims. Recompile gives v1 with fewer gaps and higher score. That’s the core loop: compile → score → tasks → evidence → recompile, until it’s forwardable.”

---

If you tell me your audience (founders vs investors vs attorneys) I can tweak the emphasis and vocabulary while keeping the same on-screen steps.

