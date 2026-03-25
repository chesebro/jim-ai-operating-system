---
name: first-principles-thinker
description: >
  Deconstruct any topic, concept, or business problem using first principles thinking.
  Use this skill whenever a user wants to challenge assumptions, strip inherited thinking,
  rebuild an idea from scratch, or find the most direct path from problem to outcome.
  Trigger on phrases like "first principles", "break this down", "challenge my assumptions",
  "rebuild from scratch", "what's actually true here", "simplest possible solution",
  "what would this look like if we started from zero", or any request to rethink a
  topic or problem from the ground up. Also trigger when someone is stuck in conventional
  thinking and needs a fresh frame, even if they don't use the exact phrase "first principles."
---

# First Principles Thinker

A structured reasoning skill for deconstructing topics and problems by stripping assumptions,
rebuilding from fundamental truths, and pressure-testing clarity through simplicity.

## When to Use Each Mode

This skill has two entry points depending on what the user gives you:

- **Topic/Concept** (e.g., "break down marketing", "first principles on management"): Use the **Concept Deconstruction** flow.
- **Business Problem** (e.g., "apply first principles to our churn problem", "rethink how we price"): Use the **Problem Solving** flow.

If the user's input could be either, default to **Problem Solving** and note the framing.

---

## Mode 1: Concept Deconstruction

Use when the user wants to understand something deeply by removing inherited thinking.

### Step 1: Assumption Inventory
List every common assumption people make about this topic. Be specific and concrete.
Aim for 5 to 10 assumptions. Label each clearly.

Format:
> **Assumption [N]:** [State the assumption as a belief most people hold]

### Step 2: Strip and Test
For each assumption, ask: *Is this provably, fundamentally true, or is it inherited convention?*
Mark each as:
- **FUNDAMENTAL** (survives stripping, it's actually true)
- **CONVENTION** (exists because "that's how it's done")
- **ARTIFACT** (exists because of historical constraints that may no longer apply)

### Step 3: Rebuild
Using only what's FUNDAMENTAL, reconstruct the concept from scratch.
State what the concept actually *is* when stripped of convention.

### Step 4: What Changes
Explicitly name 3 to 5 things that look different when you remove inherited thinking.
These are the leverage points.

### Step 5: The 12-Year-Old Test
Explain the same concept as if talking to a 12-year-old with no prior exposure.
No jargon. No assumed knowledge. If you can't do it cleanly, call out what's still
hidden complexity and keep breaking it down until you can. A concept isn't truly
understood until it can be explained simply.

---

## Mode 2: Business Problem Solving

Use when the user has a specific problem to solve and wants to find the most direct path.

### Step 1: Assumption Audit
List every assumption embedded in how the user is currently thinking about this problem.
This includes assumptions about:
- Who the solution is for
- What form the solution should take
- What constraints exist
- How success is measured
- What has to be built vs. bought vs. skipped

### Step 2: Zero-Based Path
Ask: *If none of these assumptions existed, what is the most direct path from the problem to the outcome?*

State the problem in one sentence. State the desired outcome in one sentence. Then describe
the shortest route between them, ignoring all conventional approaches.

### Step 3: Minimum Viable Truth
What is the simplest possible version of a solution that actually works?
Not an MVP in the startup sense. The genuinely minimum version that produces the outcome,
with nothing extra added.

### Step 4: Start From Zero
Reframe: *If there were no existing industry, no conventional wisdom, no inherited approach,
and you only had the fundamental truths established above, how would you build this from scratch?*

What would look completely different from how it's done today?
Name the 3 to 5 biggest departures from the conventional approach.

### Step 5: The 12-Year-Old Test
Explain the problem and your proposed solution as if talking to a 12-year-old.
No industry terms. No assumed context. If it's still murky, there's hidden complexity
remaining. Keep simplifying until it's genuinely clear.

---

## Output Principles

- **Label each section clearly** so the user can navigate the output.
- **Be concrete.** Avoid abstract statements like "challenge conventional thinking." Name the specific assumptions, specific truths, specific departures.
- **Call out the leverage.** After the full analysis, close with: *"The highest-leverage insight here is..."* and state it in one or two sentences.
- **No fluff.** This framework earns its length through substance. Cut anything that doesn't sharpen the thinking.
- **No em dashes.** Use commas, periods, or parentheses.

---

## Example Trigger Phrases

- "Break [topic] down using first principles"
- "Apply first principles to [problem]"
- "What assumptions am I making about [topic]?"
- "If we started from zero on [topic], what would change?"
- "What's actually true about [topic] once you strip away convention?"
- "What's the simplest version of a solution for [problem]?"
- "Help me rethink [topic] from scratch"
- "Challenge the way I'm thinking about [problem]"
