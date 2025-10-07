# B-001 — Search for unrelated term shows blank results without a “No results” message

**Severity:** Medium | **Priority:** P2  
**Env:** Windows 11, Chrome 140 (DevTools iPhone 14 Pro)

**Steps to Reproduce**
1) From the home page, use search  
2) Enter **fulham** (or another unrelated term) and submit

**Expected**  
A clear “No results” message with suggestions (fix spelling, try different term) or relevant alternatives.

**Actual**  
Results page shows header/filters but no product grid and no empty-state guidance (feels like a blank page).

**Evidence**  
evidence/B-001-search-fulham-no-empty-state.mp4

**Notes**  
Poor UX—users can’t tell if search failed or simply has zero matches.
