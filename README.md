---
title: Supervised Vibe Coding Framework
version: 1.0.0
---
---

# 🌟 **Supervised Vibe Coding Framework**

*A structured workflow for creatively coding with LLMs while staying technically accurate, consistent, and in control.*

---
This framework blends the free-flowing creativity of vibe coding with the discipline of traditional software engineering. It guides you through exploring ideas with multiple models, refining architecture with precision, supervising code generation, and validating results through rigorous testing. By combining human judgment with LLM-powered assistance, it ensures that projects remain innovative without sacrificing reliability, maintainability, or technical correctness.

---

## 🧭 **1. Project Scoping & Exploration Phase**

### 🌐 **1.1 Start Broad**

* Begin with a **high-level overview** of the project.
* Avoid premature technical details. Let creativity breathe.
* Define the “vibe” you want: fast & sloppy prototype vs clean production-ready vs experimental research spike.
* Decide success criteria upfront (works locally, passes X tests, deploys without errors, looks good, etc.).

### 🤖 **1.2 Multi-Model Discovery**

* Ask **multiple LLMs** the same early questions.
* Use **high temperature** to encourage diverse ideas.
* Collect different architectural options and creative solutions.

### 📚 **1.3 Technical Baseline Requirement**

* You must have at least **intermediate knowledge** of:

  * The main programming language
  * Core frameworks and tools
  * Your understanding guides and corrects the LLM.

### 🔍 **1.4 Comparative Evaluation**

* Compare LLM responses and choose:

  * The **best single approach**, OR
  * A **hybrid** combining strongest elements.
* Watch for:

  * Outdated APIs
  * Over-engineering
  * Missing modules

* Compare suggestions side-by-side (literally paste them into one document). Highlight unique ideas, patterns, and red flags.
* Synthesize: either pick one winner or Frankenstein the best parts from everyone (you decide, not the LLM).


---

## 🏗️ **2. Specification & Architecture Phase**

### 🎯 **2.1 Shift to Specificity**

* Lower the temperature.
* Give precise instructions:

  * Tech stack
  * Library versions
  * Coding style
  * Constraints and goals

### 📁 **2.2 Define the File & Directory Structure**

* Explicitly guide the LLM by outlining:

  * `/src`
  * `/components`
  * `/api`
  * `/utils`
  * `/config`
  * `/assets`
* Adjust based on framework or platform.

### 🖼️ **2.3 UI / Frontend Requirements**

* Define UI needs early:

  * Components
  * Screens
  * User flows
  * Layouts and styling approaches

### 🧩 **2.4 Manual Module Breakdown**

* Break the system into small modules **yourself**:

  * Data models
  * Services
  * Components
  * API endpoints
  * State management
* LLMs tend to hallucinate module boundaries. You provide the structure.

---

## 🧪 **3. Implementation Phase**

### 🛠️ **3.1 Controlled Prompting**

* For each module, tell the LLM:

  * Exact inputs
  * Exact outputs
  * Dependencies
  * File path
  * Whether to generate full code or pseudocode

### 🧵 **3.2 Code Review (Your Supervision Matters)**

* Skim but verify:

  * Correct imports
  * Correct API signatures
  * Naming consistency
  * No missing variables
  * Logical flow matches the specification

### 🔗 **3.3 Integration Logic**

* Integrate modules **manually whenever possible**:

  * Event flows
  * Data wiring
  * API linking
  * State synchronization
* LLMs often fail in integration — ensure correctness yourself.

### 📘 **3.4 Manual Documentation Check**

* Manually check important libraries:

  * Latest stable APIs
  * Breaking changes
  * Correct usage patterns
* Correct the LLM:

  * Provide actual function signatures
  * Provide minimal working examples

---

## 🧹 **4. Testing & Iteration Phase**

### 🧾 **4.1 Multi-Layer Verification**

* Perform:

  * Manual testing
  * LLM-guided reviews
* Ask LLM:

  * “List potential edge cases.”
  * “Find logical errors in this code.”

### 🐞 **4.2 Error-Driven Correction**

* Provide:

  * Exact error logs
  * Module names
  * What was expected vs. what happened
* Let the LLM propose fixes based on precise context.

### 🔄 **4.3 Iterative Refinement**

* Keep all LLMs updated with:

  * Latest file structure
  * Most recent snippets
  * Known bugs
* Continue refining until:

  * Tests pass
  * Integration stabilizes

---

## 🧩 **5. Finalization Phase**

### 🧼 **5.1 Cleanup & Optimization**

* Ask the LLM for a final pass:

  * Remove unused code
  * Simplify conditionals
  * Improve naming
  * Suggest performance improvements

### 📖 **5.2 Documentation**

Create:

* README
* Setup guide
* API documentation
* Developer notes
* Example usage snippets

### 🛡️ **5.3 Multi-Model Audit (Optional)**

* Ask additional LLMs to review:

  * Architecture
  * Code quality
  * Potential vulnerabilities
  * Missing optimizations

---

## 🧠 **6. Additional Best Practices**

### 📝 **6.1 Maintain a Knowledge Log**

* Track decisions, versions, issues, and rejected paths.

### 📦 **6.2 Use a “Golden Source Prompt”**

Keep a master prompt including:

* Overview
* File structure
* Naming conventions
* Coding guidelines
* Framework versions

### 🚫 **6.3 Avoid Full-Project Generation**

* Always do **module-by-module** development.

### 🧊 **6.4 Freeze Architecture Early**

* Once coding begins, avoid constant architectural pivots.

### 🌲 **6.5 Use Version Control Religiously**

* Commit early, commit often.
* Use branches for feature development.

### 🔐 **6.6 Handle Critical Logic Manually**

* For cryptography, payments, migrations, or security-sensitive systems — avoid vibe coding.

---
## 🎉 **7. Additional Critical Rules**

### 🧪 **7.1 Versioning and Code Refactor**
* Version control every 5–10 minutes during intense sessions (commit messages = gold for later debugging).
* Refactor aggressively yourself after the vibe phase ends — LLMs rarely produce clean refactored code.

### 📦 **7.2 Log your "Thoughts”**
* When in doubt, reduce scope. A working small thing > a broken big thing.
* End every session with a 2-minute summary in your own words: “What works, what doesn’t, next step.”

---

## 🏁 **Conclusion**

Supervised Vibe Coding blends creativity with structure.
By supervising the LLM and controlling the workflow, you get the best of both worlds:
**creative ideation + reliable engineering**.

---
