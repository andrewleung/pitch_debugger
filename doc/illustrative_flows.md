# I**llustrative flows**

- each highlights a different “interaction loop” between components.

## **Flow 1: First build of a Decision Pack (cold start)**

1. **Founder inputs** (deck, notes, call transcript, product docs) → **Pitch Debugger**

2. Pitch Debugger **compiles v0** Decision Pack \+ tags gaps (missing evidence, fuzzy claims)

3. **Workflow OS** applies rubrics (completeness, verifiability, risk coverage) → creates task list

4. Founder/team completes tasks (evidence, metrics, customer quotes)

5. Pitch Debugger re-compiles → **Decision Pack v1** (more “underwritable”)

**Good for showing:** compiler \+ rubric gates \+ versioning.

---

## **Flow 2: Diligence deepens (investor questions → evidence plan → recompile)**

1. Investor asks questions / raises concerns → captured as **Diligence Qs**

2. **Workflow OS** converts Qs into: risk entries \+ evidence tasks \+ decision options

3. Evidence produced (tests, LOIs, pilot results, references)

4. **Pitch Debugger** pulls the new artifacts \+ updates “Receipts” sections

5. **Decision Pack v(n+1)** becomes forwardable again (with fewer open loops)

**Good for showing:** the “underwritable ⇄ forwardable” loop.

---

## **Flow 3: Patent Intelligence enriches the pack (IP layer update)**

1. Decision Pack has a “Secret Sauce hypothesis map” → sent to **Patent Intelligence**

2. Patent Intelligence runs: landscape snapshot \+ closest prior art \+ claim-hook options

3. Patent Intelligence outputs:

   * “Novelty delta” bullets

   * design-around map

   * file / publish / hold recommendations

4. **Workflow OS** turns outputs into: IP risks \+ mitigations \+ next tasks

5. **Pitch Debugger** compiles into the Decision Pack IP section (and updates risk register)

**Good for showing:** IP isn’t a side doc—it's a feed that updates underwriting.

---

## **Flow 4: Material change detected (change control \+ safe disclosure)**

1. A “material change” happens (pivot, new competitor, new model capability, new pricing)

2. **Material Change Publisher** records it (timestamp, what changed, impact areas)

3. Publisher emits “delta packet” to:

   * **Workflow OS** (re-score rubrics, open impacted risks)

   * **Pitch Debugger** (update narrative \+ numbers \+ assumptions)

   * optionally **Patent Intelligence** (re-run landscape if needed)

4. Output:

   * **Decision Pack v(n+1)** (internal)

   * optionally a **public-facing delta** or defensive publication (if chosen)

**Good for showing:** version diffs \+ governed updates.

---

## **Flow 5: “Underwritable gates” (rubrics as go/no-go checkpoints)**

1. Pitch Debugger compiles → Decision Pack draft

2. **Workflow OS** runs rubric checks:

   * Evidence coverage threshold met?

   * Top 5 risks bounded with mitigations?

   * Differentiators mapped to proof?

   * IP exposure acceptable?

3. If fail → tasks assigned

4. If pass → “Forwardable” status \+ export/share bundle

5. Investor feedback loops back into Workflow OS and repeats

**Good for showing:** the rubric is the “quality engine,” not just project management.

---

## **Flow 6: Two-track output (Investor pack vs Attorney pack)**

1. Same source Decision Pack → **Pitch Debugger** generates two views:

   * **Investor view:** decision options, risk/evidence, traction, economics

   * **Attorney/IP view:** invention disclosures, claim hooks, prior art deltas, filing plan

2. **Workflow OS** ensures shared consistency rules (numbers, definitions, scope)

3. **Material Change Publisher** propagates updates to both views automatically

**Good for showing:** one canonical artifact, multiple “renders.”

---

## **Flow 7: Continuous “Evidence Plan → Evidence Index” pipeline**

1. Workflow OS creates an **Evidence Plan** (what to prove \+ how)

2. Team uploads proof items (screenshots, call notes, benchmarks, contracts)

3. Pitch Debugger builds an **Evidence Index** (claim → receipts → confidence score)

4. Decision Pack surfaces “confidence” per claim \+ remaining gaps

5. As diligence deepens, the index becomes the internal “truth table”

**Good for showing:** how “underwritable” becomes measurable.

# Master Flow (mermaid)

flowchart LR  
 %% \========== Actors / Inputs \==========  
 F\["Founder / Team Inputs  
(deck, notes, docs, transcripts)"\] \--\> PD\["Pitch Debugger  
Front-end \+ Compiler"\]

 %% \========== Canonical Artifact \==========  
 PD \--\> DP\[(Decision Pack  
Canonical Artifact)\]  
 DP \--\> V\["Versioned Pack  
v0 → v1 → v2..."\]

 %% \========== Quality \+ Iteration Loop \==========  
 DP \--\> WOS\["Workflow OS  
Rubrics \+ Gates \+ Tasking"\]  
 WOS \--\> T\["Evidence & Tasks   
(metrics, calls, pilots, demos, benchmarks)"\]  
 T \--\> PD

 %% \========== Underwriting / Diligence \==========  
 INV\["Investor / Partner Diligence Qs"\] \--\> WOS  
 WOS \--\> RR\[(Risk Register \+ mitigations)\]  
 WOS \--\> EP\[(Evidence Plan  
what to prove next)\]  
 RR \--\> PD  
 EP \--\> PD

 %% \========== IP Enrichment Loop \==========  
 DP \--\> PI\["Patent Intelligence  
Landscape \+ Claim Hooks \+ Gaps"\]  
 PI \--\> IPDELTA\[(IP Delta Packet  
prior art, novelty deltas,  
design-around risk,  
file/publish/hold)\]  
 IPDELTA \--\> WOS  
 IPDELTA \--\> PD

 %% \========== Material Change Control \==========  
 CHG\["Material Change Event  
(pivot, competitor, numbers, disclosure)"\] \--\> MCP\["Material Change Publisher  
Change log \+ impact map"\]  
 MCP \--\> DELTA\[(Delta Packet  
what changed \+ impact areas)\]  
 DELTA \--\> WOS  
 DELTA \--\> PD  
 DELTA \--\> PI

 %% \========== Outputs / Renders \==========  
 V \--\> OUT1\["Investor View  
Forwardable Decision Pack"\]  
 V \--\> OUT2\["Attorney/IP View  
Invention \+ Claim Hooks \+ Plan"\]  
 MCP \--\> OUT3\["Optional External Publish  
(defensive publication / updates)"\]

