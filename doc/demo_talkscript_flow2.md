Here’s a talk track you can read while clicking through the **Flow 2** single-file demo (Investor questions → evidence plan → recompile). It’s written to match the UI/buttons from the Flow 2 app: **Seed example Qs → Generate Evidence Plan → Mark done → Recompile Pack → Run Rubrics**.

## **Flow 2 Demo Talkscript (≈2–3 minutes)**

**0\) Setup (before first click)**

“In Flow 1 we cold-started a Decision Pack.  
Flow 2 is what happens when diligence deepens: investors ask sharper questions, and instead of throwing those into Slack, we convert them into an evidence plan that keeps the pack *underwritable*.”

**(Open DevTools → Console)**

“I’ll keep the console open so you can see the trace logs as each component fires.”

---

## **1\) Investor questions arrive**

**Click: *Seed example Qs***

“Here are realistic diligence questions: defensibility vs fast followers, proof someone will pay, GTM, risk bounds.  
This is the moment where decks usually break—because the questions get specific and the answers are scattered.”

Point at the Questions list:

“These aren’t ‘FAQ content’. They’re underwriting questions. Each one demands receipts.”

---

## **2\) Workflow OS converts questions → Evidence Plan (tasks)**

**Click: *Generate Evidence Plan***

“Now Workflow OS turns questions into a structured evidence plan—concrete tasks.  
The key is: we don’t just ‘answer’ the question. We define what *proof* would close it.”

Point at Tasks:

“See how the plan creates blocker tasks like a novelty-delta memo, willingness-to-pay signal, and a 90-day risk plan.  
This is the rubric layer converting ambiguity into a checklist of verifiable work.”

(Optionally mention the system concept)

“Think of this as converting ‘investor curiosity’ into ‘artifact requirements’.”

---

## **3\) Team produces receipts (evidence)**

**Click: *Mark done* on 2–3 tasks (choose at least one blocker)**  
Suggested order:

* “Add 2 receipts: interview notes \+ WTP signal”  
* “Write ‘novelty delta’ paragraph”  
* “Add top 3 risks \+ 90-day mitigation”

As you click:

“When we mark tasks done, the system produces evidence objects—receipts—and links them back to the question they answer.”

Point to Evidence Vault:

“Notice the evidence vault is structured JSON. That’s on purpose—because it makes the pack recompilable and auditable.”

---

## **4\) Pitch Debugger recompiles the Decision Pack**

**Click: *Recompile Pack***

“Now Pitch Debugger recompiles the Decision Pack.  
This is the key move: instead of updating slides manually, we regenerate the artifact so it stays internally forwardable.”

Point to Decision Pack sections:

“You can see Diligence Q\&A now shows status and evidence refs.  
Risk Register updates. Evidence Index grows.  
And the ‘gaps’ section tells us what still blocks forwardability.”

Optional one-liner:

“This is how you keep the artifact underwritable as diligence deepens.”

---

## **5\) Rubrics score “forwardability” as a gate**

**Click: *Run Rubrics***

“Finally, rubrics run as a gate.  
This gives us a score and a pass/fail decision on whether this is something an investor can forward internally without embarrassment.”

Point at score \+ gate:

“If it’s FAIL, it’s not a vibe check—it’s specific: unanswered questions, thin evidence coverage, open blocker risks.  
And the system routes us back into tasks.”

---

## **6\) Close (what Flow 2 proves)**

“So the point of Flow 2 is: diligence isn’t chaos.  
It becomes a loop: questions → evidence plan → receipts → recompile → gate.  
That’s how the Decision Pack stays forwardable as diligence deepens—without relying on heroics or bespoke consulting.”

**Optional last line (if audience is investors):**

“If you receive 100 ‘credible’ decks a month, this is the layer that makes one of them underwritable.”

---

### **Mini backup lines (if someone asks “why not a data room?”)**

“Data rooms store documents. This system *binds claims to receipts* and keeps a forwardable narrative artifact up to date as questions change.”

### **Mini backup lines (if someone asks “why the console?”)**

“Because we want the system to be inspectable—so people trust the compiler decisions, not just the output.”

If you want, paste your Flow 2 UI labels if you tweaked them, and I’ll align the talkscript to the exact button names/sections.

