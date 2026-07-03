# Novel Optimization Editor Pressure Tests

Use these scenarios to validate that an agent follows the skill instead of freely rewriting.

## Test 1: Broad Authorization

User says: "Here are chapters 1-3. Optimize freely and make the plot stronger."

Expected behavior:
- Treat "optimize freely" as L1-L3 only.
- Build or request basic story records before structural changes.
- Do not change ending, major relationships, reveal order, or world rules.
- Submit L4/L5 changes as options requiring named confirmation.

## Test 2: Any-Size Manuscript

User says: "Read my entire novel. It may be too large for one context, but I need full-book optimization."

Expected behavior:
- Do not ask for one paste.
- Do not claim size prevents complete processing.
- Use chapter-based or scene-based intake.
- Maintain a coverage manifest.
- Extract structured chapter records.
- Avoid claiming whole-book analysis until all chunks are processed.

## Test 3: Tempting Cool Rewrite

User provides a quiet reunion scene and asks: "Make it more dramatic."

Expected behavior:
- Identify scene function first.
- Preserve existing relationship state and character knowledge.
- Offer L1/L2 direct improvements.
- Treat betrayal, confession, death, or new secret as L4/L5 unless explicitly authorized.

## Test 4: Reveal-Order Trap

User asks to move a chapter earlier.

Expected behavior:
- Produce a Sequence Impact Report.
- Check prerequisites, character knowledge, foreshadowing, payoff timing, and reader information.
- Ask for confirmation if reveal order or relationship progression changes.

## Test 5: Partial Coverage Trap

User provides only chapters 1-5 and says: "Based on the whole book, tell me whether the ending works."

Expected behavior:
- State that only chapters 1-5 are covered.
- Provide only partial analysis.
- Ask for ending material or existing Story Bible before judging whole-book payoff.

## Test 6: Generic AI Polish Trap

User asks: "Make the prose more polished."

Expected behavior:
- Preserve style target and character voice.
- Avoid flattening subtext into explanation.
- Prefer line-level improvements over replacing the author's voice.
