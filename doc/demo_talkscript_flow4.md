Here’s a talk track you can read while clicking through the **Flow 4** demo (Material change detected → change control \+ safe disclosure). It matches the Flow 4 app buttons: **Seed example change → Add to Change Log → Process Changes → Delta → Compile / Recompile → Mark done → Run Rubrics**.

## **Flow 4 Demo Talkscript (≈2–3 minutes)**

**0\) Setup (before first click)**

“Flow 4 is about governance.  
In real diligence, the artifact breaks not because you don’t have answers—but because things change: competitor moves, new metrics, product pivots, IP discoveries.  
So we add a Material Change Publisher: it detects and records material changes, routes them to the right components, and produces a *safe disclosure* view.”

**(Open DevTools → Console)**

“I’ll keep the console open so you can see the change event becoming a delta packet.”

---

## **1\) A material change arrives**

**Click: *Seed example change***

“Here’s a realistic example: a competitor shipped something similar.  
This is exactly the kind of event that can make yesterday’s narrative misleading.”

Point at the form:

“Notice we’re capturing: change type, severity, impacts, and—most importantly—disclosure sensitivity.”

**Click: *Add to Change Log***

“When we add it, it becomes an immutable change-log entry.  
This is change control: we can’t ‘forget’ the change happened—we can only process it.”

---

## **2\) Material Change Publisher emits a Delta Packet (and routes it)**

**Click: *Process Changes → Delta***

“Now the Material Change Publisher processes the log and emits a delta packet.  
The delta contains: severity summary, an impact map, and routing instructions—like ‘update risk register’, ‘generate evidence tasks’, ‘recompile’.”

Point at Delta Packet panel:

“This is the key: instead of humans arguing ‘did we update the deck?’, the system produces a structured delta that downstream components can consume.”

---

## **3\) Workflow OS generates tasks from the delta**

Point at the Tasks panel that appears after processing:

“Now Workflow OS turns the delta into concrete tasks.  
If the change is high severity, it creates blocker tasks—because forwardability is now at risk until those are done.”

Optional sentence:

“This is how you keep the pack underwritable: changes become explicit work, not invisible drift.”

---

## **4\) Pitch Debugger recompiles the Decision Pack with delta applied**

**Click: *Compile / Recompile***

“Now Pitch Debugger recompiles the Decision Pack with delta applied.  
You’ll see updated risks, updated assumptions, and a delta summary so anyone reading understands what changed and when.”

Point at Decision Pack:

“This prevents stale narratives. The artifact always reflects the latest known state—with an audit trail.”

---

## **5\) Safe disclosure view (what we can share externally)**

Point to “Safe External Publish View”:

“Now here’s the part most teams don’t have: safe disclosure.  
The same delta packet can generate an external-safe summary—redacted—so we can update stakeholders without leaking sensitive details.”

Emphasize:

“We’re separating internal truth from external shareability.”

---

## **6\) Produce receipts by completing tasks**

**Click: *Mark done*** on 1–2 blocker tasks (e.g., competitor adjacency update, IP refresh decision)

“As we complete tasks, the system produces evidence receipts—so the updated narrative isn’t just ‘trust us’.  
It’s linked to work outputs.”

Point at Evidence Vault:

“The evidence vault grows and stays structured, so later recompiles stay consistent.”

---

## **7\) Re-run rubrics to restore “forwardable”**

**Click: *Run Rubrics***

“Finally we run rubrics again.  
The gate answers: is the pack forwardable right now, given this material change?”

Point at gate/score:

“If it fails, it fails for specific reasons—open blocker tasks, missing safe publish stub, missing evidence.  
That gives the team a clear path to get back to ‘PASS’.”

---

## **8\) Close (what Flow 4 proves)**

“Flow 4 proves the Decision Pack can survive reality.  
Material changes don’t quietly invalidate the artifact—they create deltas, tasks, recompiles, and safe stakeholder updates.  
That’s change control \+ safe disclosure—the missing layer that keeps diligence artifacts underwritable over time.”

### **Optional one-liners depending on audience**

**Investors:**

“This prevents ‘deck drift’—you’re not underwriting last month’s story.”

**Counsel / IP:**

“Disclosure sensitivity is enforced at the delta level—so we don’t accidentally leak claim hooks or filing intent.”

**Operators:**

“It’s like Git for diligence: changes are logged, routed, and gated.”

If you paste your Flow 4 button labels (in case you tweaked them), I can align the script word-for-word to your exact UI.

