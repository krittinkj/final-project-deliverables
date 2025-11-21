# ✅ **Revised Presentation Structure (15–20 Main Slides + 20 Appendix)**

## **0. Title Slide (1 slide)**

* Project name
* Your name, advisor, program
* One simple image (e.g., system diagram/photo)

> *Keep it clean—this acts as your “start” since you cannot use an outline slide.*

---

## **1. Problem, Goal, Final Target (1 slide)**

**Slides: 1**

* Clear statement of the final goal
* What the system *must* achieve (success criteria)
* One diagram showing input → system → output

> *Advisor said start with COMPLETE GOAL.*

---

## **2. Application Domain & Motivation (2–3 slides)**

**Slides: 2–3**

* What domain your project lies in
* Why the domain matters
* What users need / real-world challenges
* Visual-heavy: photos, diagrams, scenarios

> *Advisor said “can go OVERBOARD” on domain.*

---

## **3. Related Work + Gap Analysis (2 slides)**

**Slides: 2**

* Existing approaches (industry + academia)
* What they can do
* What they cannot do (your gap)
* Bullet-point comparison chart

> *Keep it honest: “DONT MAKE STUFF UP.”*

---

## **4. System Requirements & Engineering Process (2 slides)**

**Slides: 2**

* Requirements (functional + non-functional)
* Methodology:

  * iteration cycles
  * experiments
  * failures + how you fixed them
* A timeline / flowchart showing how the project evolved

> *Advisor wants PROCESS + methodology emphasized.*

---

## **5. Overall System Architecture (2 slides)**

**Slides: 2**

* Main diagram of the entire pipeline
* Data flow from microphone/camera → models → planner → robot
* Subsystem responsibilities

> *Make sure structure matches your final report.*

---

## **6. Subsystem Results (ASR / Vision / Planning) (4–6 slides)**

### 6.1 ASR Module (1–2 slides)

**Slides: 1–2**

* Model choice, dataset
* Benchmark accuracy/WER
* Limitations
* Spectrogram or model diagram

### 6.2 Vision Module (1–2 slides)

**Slides: 1–2**

* What detections you perform
* Metrics/benchmark
* Pipeline diagram

### 6.3 Planning + Integration (1–2 slides)

**Slides: 1–2**

* How planning works in your system
* Performance, constraints
* Latency, success rate

> *Keep each subsystem visually intuitive.*

---

## **7. Simulation Setup + Hardware (1–2 slides)**

**Slides: 1–2**

* Simulation environment
* Real hardware configuration
* Images, connection diagrams
* Key constraints you solved (latency, safety, coordinate transform issues)

---

## **8. System-Level Results (1 slide)**

**Slides: 1**

* End-to-end performance
* Success rates, timings
* Before/after improvements

> *This section shows that the whole system works, not just parts.*

---

## **9. Demo (1 slide)**

**Slides: 1**

* A video or image sequence
* System performing the final task

> *Short & focused.*

---

## **10. Future Work / Improvement (1 slide)**

**Slides: 1**

* Clear next steps (realistic)
* No speculation

> *Advisor said “don’t make stuff up.”*

---

## **11. Thank You / QA Slide (1 slide)**

**Slides: 1**

* No text except “Thank you” and contact info

**TOTAL MAIN SLIDES: ~16–19**

Fits the advisor’s target.

---

# 📚 Appendix Slides (for Q&A) — 20 slides allowed

Your appendix should contain:

### A. Technical Details (6–8 slides)

* Model architectures
* Hyperparameters
* Data preprocessing
* Training curves
* Hardware communication details
* ROS2 action flow diagrams

### B. Failure Cases (3–4 slides)

* What failed in ASR, vision, planning
* How you debugged it

### C. Additional Experiments (3–4 slides)

* Ablation studies
* Different architectures tested

### D. Engineering process extras (3–4 slides)

* Logs
* Testing methodology
* Edge cases
* Validation steps

### E. Misc. Backup Slides (2–3 slides)

* Definitions
* Additional diagrams
* System block comparisons

**TOTAL APPENDIX: ~20 slides**

These exist ONLY to answer questions.

---

# 🔥 Summary of Improvements (What Changed from Your Current Structure)

| Current Structure                | Improved Structure Based on Feedback                                      |
| -------------------------------- | ------------------------------------------------------------------------- |
| Introduction/background          | → Goal + domain + problem → strong contextual start                       |
| Architecture overview            | ✔ Still included, but expanded and placed AFTER motivation & related work |
| ASR, Vision, Planning results    | ✔ Still included but reorganized under “Subsystem results”                |
| Simulation + hardware            | ✔ Still included                                                          |
| Demo                             | ✔ Still included                                                          |
| ❌ No related work                | ✔ Added related work + gap analysis                                       |
| ❌ No process methodology         | ✔ Added engineering process section                                       |
| ❌ No application domain emphasis | ✔ Added domain section with extra depth                                   |
| ❌ No future plans                | ✔ Added a realistic “Future work” slide                                   |
| ❌ No appendix                    | ✔ Added 20-slide appendix for Q&A                                         |


Just tell me!

