# Test Report — Chelsea FC Megastore (Mobile Guest Checkout)

**Session date:** 04 Oct 2025  
**Duration:** 40 min  
**Tester:** Carina Azevedo  
**Environment:** Windows 11, Chrome 140 (DevTools — iPhone 14 Pro emulation)

---

## Scope
Exploratory testing of the **mobile guest checkout flow** on the Chelsea FC Megastore:
Home → Search → Product → Cart → Checkout → Cookies & Privacy.

---

## Coverage Summary
| Area | Status |
|------|--------|
| Home page | OK |
| Search | Minor UX issue |
| Product page | OK |
| Cart | OK |
| Checkout | 1 validation issue |
| Cookies & Privacy | OK |

---

## Key Findings
| ID | Title | Severity | Evidence |
|----|--------|-----------|-----------|
| **B-001** | Search shows blank results for unrelated terms (no empty-state message) | Medium | `evidence/B-001-search-fulham-no-empty-state.mp4` |
| **B-002** | Women > Equipment page opens empty on mobile | High | `evidence/B-002-women-equipment-menu-broken.mp4` |
| **B-003** | Checkout postcode accepts non-existent code “ZZ1 1ZZ” | Medium | `evidence/B-003-postcode-zz1-1zz-accepted.mp4` |

---

## 🔍 Recommendations
- **Add empty-state feedback** for search results (e.g., “No results found” message + suggestions).  
- **Fix category routing/data source** for Women > Equipment; ensure empty categories show a clear message.  
- **Improve address validation** using postcode lookup or soft user warning.  
- Optional: add **mobile performance test** under Slow 3G.

---

## Reflection
This 40-minute exploratory session covered the full e-commerce flow from homepage to checkout.  
Core functionality works well, but usability gaps remain in search results feedback and address validation.  
Next steps: retest after fixes; add API layer test or cross-browser verification.
