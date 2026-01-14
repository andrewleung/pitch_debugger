Recommended demo clicks for **Flow 1 (cold start)** in the single-file app:

1. **Open DevTools → Console** (so people see the trace logs)  
2. Click **Compile Decision Pack**  
   * shows **Decision Pack v0** \+ **compiler gaps**  
3. Click **Run Rubrics**  
   * shows **FAIL gate / score** \+ generates **Workflow OS tasks**  
4. In the task list, click **Mark done** on **1–2 blocker tasks** (especially evidence-related)  
   * evidence counter increases; console logs “Produced evidence”  
5. Click **Compile Decision Pack** again (this becomes **v1**)  
   * Decision Pack updates with new **Evidence Index** and fewer gaps  
6. Click **Run Rubrics** again  
   * score goes up; gate may still fail unless you complete more tasks  
7. (Optional) Mark done on remaining key tasks → **Compile** → **Run Rubrics**  
   * aim to show the moment it flips to **PASS / Forwardable: yes**

**How to demo Flow 2 with this app (quick steps):**

1. Open the file in a browser, open DevTools → **Console**

2. Click **Seed example Qs** (or add your own)

3. Click **Generate Evidence Plan** → tasks appear

4. Click **Mark done** on 2–3 tasks → evidence gets created and linked to questions

5. Click **Recompile Pack** → see Diligence Q\&A \+ evidence index updated

6. Click **Run Rubrics** → watch score/gate improve as more questions get answered

**Recommended demo clicks (Flow 3):**

1. **Compile** (Decision Pack v0 with IP gap)

2. **Run Patent Intelligence** (generates IP Delta Packet: closest prior art \+ risk \+ recommended actions)

3. **Apply IP Delta → Tasks** (Workflow OS produces file/publish/hold \+ design-around tasks, adds delta receipt)

4. Mark 2–3 tasks **done** (creates evidence records)

5. **Compile / Recompile** (Decision Pack now includes enriched IP section)

6. **Run Rubrics** (IP-aware gate improves as tasks/evidence accumulate)

**Recommended demo clicks (Flow 4):**

1. Open DevTools → **Console**

2. Click **Seed example change** → **Add to Change Log**

3. Click **Process Changes → Delta** (delta packet \+ tasks \+ delta receipt generated)

4. Click **Compile / Recompile** (Decision Pack now shows delta summary \+ updated risks/tasks)

5. Mark 1–2 **blocker tasks** done (generates evidence records)

6. Click **Run Rubrics** (watch gate/score improve)

7. (Optional) Show **Safe External Publish View** to illustrate redaction / disclosure control

Recommended **demo clicks for Flow 5 (Underwritable Gates)** — designed for a clean 90–120s run:

1. Open DevTools → **Console** (so people see gate traces)  
2. Click **Make it thin (fail gates)**  
3. Click **Run All Gates**  
   * call out: **FAIL count**, *reasons*, and how each gate generates **remediation tasks**  
4. Scroll to **Task Board** and click **Autofix** (1st time)  
   * narrate: “we’re closing blockers \+ generating evidence”  
5. Click **Run All Gates** again  
   * show: fewer FAILs / higher overall score  
6. Click **Autofix** (2nd time)  
   * aim to complete an **IP delta** task \+ an **evidence map** task (these swing multiple gates)  
7. Click **Run All Gates** again  
   * ideally you’re near **Overall PASS**  
8. Click **Compile / Recompile**  
   * point out: compile output shows **gate summary \+ evidence index**, and now the artifact is **Forwardable: yes**

**Optional 30s “happy path” variant**

* Click **Seed decent inputs** → **Run All Gates** → **Compile / Recompile**  
  (Use this if you want to show the concept without the remediation loop.)

Recommended **demo clicks for Flow 6 (Two-track output: Investor Pack vs Attorney Pack)** — clean 90–120s run:

1. Open DevTools → **Console**  
2. Click **Seed realistic canonical data**  
3. Click **Run Underwritable Gates**  
   * point out: gate score \+ any tasks (even if PASS, mention “gates decide if forwardable”)  
4. Click **Add sensitive lines**  
   * show: **Sensitive items** counter increases; explain “\[SENSITIVE\] \= attorney-only”  
5. Click **Compile Two-Track Packs**  
6. Stay on **Investor Pack** tab  
   * highlight: secret sauce lines show **withheld/redacted/as\_is** markers  
7. Click **Attorney Pack** tab  
   * highlight: full secret sauce \+ claim hooks \+ novelty deltas \+ drafting inputs  
8. Look at **Diff** panel  
   * point out: counts of **withheld/redacted** and what policy is active  
9. Change **Disclosure policy** dropdown (Strict → Balanced)  
10. Click **Compile Two-Track Packs** again  
* show: Investor Pack now shows **redacted summaries** instead of “withheld”  
11. (Optional) Click **Autofix tasks** → **Compile**  
* demonstrate: evidence grows and both tracks inherit the same canonical updates

**30s “happy path”**

* **Seed realistic canonical data → Compile → Toggle Investor/Attorney tabs → Diff**

Recommended **demo clicks for Flow 7 (Continuous “Evidence Plan → Evidence Index” pipeline)** — designed for a tight 90–120s run:

1. Open DevTools → **Console**  
2. Click **Seed example data**  
   * call out: “3 key claims \+ 3 diligence questions”  
3. Click **Generate Evidence Plan**  
   * highlight: tasks are created per **claim** and per **question**  
4. Click **Rebuild Evidence Index**  
   * point out: most items are **UNBOUND** (no receipts yet) → coverage is low  
5. Click **Produce Evidence (simulate)**  
   * narrate: “completing tasks produces evidence objects with binding metadata”  
6. Click **Rebuild Evidence Index** again  
   * show: some claims/questions flip to **BOUND**, coverage % rises, refs appear  
7. Click **Pipeline Tick (run)**  
   * explain: “tick \= continuous loop: plan check → produce small evidence → reindex”  
8. Click **Pipeline Tick (run)** again  
   * show: more bindings, fewer blockers, coverage climbs toward green

**Optional “stress test” (30–45s)**

* Click **Make it sparse (low coverage)** → **Generate Evidence Plan** → **Pipeline Tick**  
  (shows the system bootstraps tasks \+ begins indexing even from weak inputs.)

