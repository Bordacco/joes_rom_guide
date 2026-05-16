---
name: Guide build status
description: Current state of guide.html build and what remains to be done
type: project
---

guide.html was built and committed (commit e458b1a). It contains the full Rome guide with map, filters, and restaurant data.

**What still needs doing:**
The restaurant `desc:` fields in guide.html were written in condensed third-person ("Joe fik...", "Joe anbefaler..."). Joe wants the full original first-person text from "Rom guide.txt" restored in every card. One edit was done (Armando al Pantheon desc updated). The rest of the restaurants still need their desc fields replaced with the full original Danish text.

The restaurant descriptions in the JS `RESTAURANTS` array (starting around line 710 in guide.html) need to be updated one by one. The original source text is in `Rom guide.txt`.

**Also needs fixing:**
- All "Joe" references in desc fields → first-person "jeg/mig"
- Neighborhood intro paragraphs in HTML should use Joe's original text (not paraphrased)
- Guide intro section should use Joe's full original welcome text
- Sights descriptions also reference "Joe" in third person — fix those too

**Why:** Joe = the guide author. The guide is intentionally personal and the anecdotes are the whole point.
