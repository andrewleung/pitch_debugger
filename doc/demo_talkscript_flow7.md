## **Flow 7 Demo Talkscript (≈2–3 minutes) — Continuous “Evidence Plan → Evidence Index” pipeline**

**0\) Setup (before clicking)**

“Flow 7 is the engine room: we turn diligence from a one-off document scramble into a continuous pipeline.  
The core loop is: **Claims \+ investor questions → Evidence Plan → Evidence Objects → Evidence Index**.  
The Evidence Index is what makes a Decision Pack *underwritable*: you can inspect what’s supported, what’s missing, and how confidence changes over time.”

**(Open DevTools → Console)**

“I’ll keep the console open—every step emits structured logs so you can see what the pipeline is doing.”

---

## **1\) Start with claims and diligence questions**

**Click: *Seed example data***

“Here we have a few key claims we want investors to underwrite—like ‘underwritable gates keep the pack forwardable’—and a few common diligence questions.”

Point at left side:

“These are the *inputs*. At this stage, we haven’t proven anything—we’ve just stated what must be true.”

---

## **2\) Generate the Evidence Plan (tasks)**

**Click: *Generate Evidence Plan***

“Now Workflow OS generates an Evidence Plan.  
This is important: it’s not a freeform checklist. It’s tasks that are explicitly linked to either a claim or a question.”

Point at task list:

“For each claim, you’ll see a ‘collect receipt’ task—and sometimes an interview task.  
For each investor question, there’s a ‘answer with receipts’ task.”

One-liner:

“So the plan is structured around *what needs to be underwritten*, not around whatever doc happens to be available.”

---

## **3\) Build the Evidence Index (it starts mostly unbound)**

**Click: *Rebuild Evidence Index***

“Now we build the Evidence Index.  
Notice most items are **UNBOUND**—that means we don’t have receipts yet. That’s why coverage is low.”

Point at coverage pill \+ index:

“Coverage is computed from claim bindings.  
This is the difference between ‘we have docs’ and ‘our claims are actually supported.’”

---

## **4\) Produce evidence (simulate doing the work)**

**Click: *Produce Evidence (simulate)***

“Now we simulate completing a few tasks.  
Each completed task produces an Evidence Object with metadata that says which claim or question it supports.”

Point at Evidence Vault JSON:

“Here’s the evidence vault: each item is an object—type, timestamp, and binding target.”

One-liner:

“This is what makes the pipeline compilable: evidence is structured.”

---

## **5\) Re-index and show coverage rising**

**Click: *Rebuild Evidence Index***

“Now we rebuild the index. Watch what changes:  
items flip from **UNBOUND** to **BOUND**, and the index shows references for each binding.”

Point at diagnostics:

“Diagnostics shows unbound claims and blockers.  
That’s basically your real-time diligence dashboard.”

---

## **6\) Show the continuous loop: Tick runs plan → evidence → index**

**Click: *Pipeline Tick (run)***

“This is the continuous part. A tick simulates a time step:  
it checks whether the evidence plan is still aligned to current claims/questions, produces a small amount of evidence, and re-indexes.”

**Click: *Pipeline Tick (run)* again**

“After another tick, you’ll see more bindings and higher coverage.  
In a real system, ticks happen whenever: new diligence questions arrive, new receipts are uploaded, or the team completes tasks.”

---

## **Close (what Flow 7 proves)**

“Flow 7 proves you can operationalize diligence:  
Instead of ‘write a doc once and hope it holds,’ you continuously maintain an Evidence Index that makes the Decision Pack inspectable and forwardable.  
That’s how you keep the artifact *underwritable* as diligence deepens—because it always shows what’s supported and what’s still missing.”

### **Optional 10-second bridge to Flow 6**

“And once you have a clean Evidence Index, Flow 6 can compile two views: investor-safe vs attorney-deep—both backed by the same bindings.”

