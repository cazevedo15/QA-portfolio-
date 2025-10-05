# B-003 — Checkout postcode accepts non-existent code “ZZ1 1ZZ” (format-only validation)

**Severity:** Medium | **Priority:** P2  
**Env:** Windows 11, Chrome 140 (DevTools iPhone 14 Pro)

**Steps to Reproduce**
1) Proceed to checkout as guest  
2) Enter postcode **ZZ1 1ZZ** (syntactically valid but not allocated)  
3) Continue

**Expected**  
Either stricter validation (e.g., real postcode check/lookup) or guidance to confirm address before shipping.

**Actual**  
Postcode passes validation without warning; user can continue.

**Evidence**  
evidence/B-003-postcode-zz1-1zz-accepted.mp4

**Notes**  
This isn’t a hard blocker (format is valid), but looser validation can increase failed deliveries/CS load. Consider address lookup (PAF) or a soft warning.
