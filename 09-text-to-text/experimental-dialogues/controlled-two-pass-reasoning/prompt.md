---
title: Controlled Two-Pass Reasoning
id: RPL-TXT-EXP-009
category: Text-to-Text
subcategory: Experimental Dialogues
type: Two-pass answer comparison
keywords:
  - two pass reasoning
  - first intuition
  - self correction
  - answer comparison
  - error analysis
  - controlled mistake
  - مراجعة على مرحلتين
  - الحدس الأول
  - تصحيح الإجابة
  - مقارنة الإجابات
---

# Prompt

Solve the problem twice.

PASS 1:
Produce the most plausible answer you might give if you were answering too quickly.

PASS 2:
Now assume the first answer may contain a subtle mistake.
Solve the problem again from scratch.

Then compare the two:
- What changed?
- What assumption caused the difference?
- Which answer survives verification?

Do not assume PASS 2 is correct merely because it came second.
Verify both.
