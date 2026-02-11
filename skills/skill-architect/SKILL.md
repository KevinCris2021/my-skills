---
name: skill-architect
description: Helps design new Claude Code skills by clarifying purpose, scope, triggers, and structure before implementation.
---

# Skill Architect

## 2. Purpose
- Transform a vague idea into a well-defined skill.
- Ensure new skills have clear purpose, limits, and structure.
- Prevent unnecessary or redundant skills.

Expected outcome:
- Clear skill name (kebab-case)
- Defined purpose
- Explicit use cases
- Clear non-use cases
- Structured output model

---

## 3. When to use
- You are considering creating a new skill.
- A task is repeated frequently.
- Outputs feel inconsistent.
- You want to formalize a reasoning pattern.

Appropriate context:
- The task has recurring structure.
- The output should follow a stable format.
- You can describe the “job to be done.”

---

## 4. When NOT to use
- One-off tasks.
- Pure brainstorming.
- Situations without recurring patterns.
- When a simple prompt is sufficient.

Boundaries:
- Does not generate automation scripts.
- Does not write production code.
- Does not fabricate use cases.

---

## 5. Inputs
Type of information:
- Description of the recurring task.
- Example of messy input.
- Desired output format.
- Pain points or inconsistencies.

Level of structure:
- Can be informal.
- Can be incomplete (missing elements should be surfaced).

---

## 6. Output Structure (Mandatory)

Return results in this order:

1) Problem the skill solves  
2) Why this should be a skill (not just a prompt)  
3) Clear use cases  
4) Clear non-use cases  
5) Proposed output structure  
6) Risk of overuse or misuse  
7) Recommendation: build or not build  
8) Draft skill name (kebab-case)  

---

## 7. Rules
- Challenge vague ideas.
- Ask clarifying questions if purpose is unclear.
- Prefer narrow scope over broad ambition.
- Avoid duplicating existing skills.
- Make boundaries explicit.

What not to invent:
- Company-specific data.
- Artificial complexity.
- Generic filler use cases.

Constraints:
- Keep explanations concise.
- Focus on structure over narrative.

---

## 8. Definition of Success
A good result:
- Makes the skill’s purpose obvious.
- Clearly defines when to use it.
- Prevents scope creep.
- Avoids turning every task into a skill.
- Produces a reusable structural draft.

---

## 9. Example (Optional)

Input:
"I want a skill that improves strategic thinking."

Expected Output:
- Clarifies what “strategic thinking” means in context.
- Identifies recurring decision scenarios.
- Suggests narrower focus (e.g., investment trade-off briefs).
- Recommends whether to formalize as a skill.
- Proposes a specific skill name.
