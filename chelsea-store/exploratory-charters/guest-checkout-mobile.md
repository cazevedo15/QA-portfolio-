# Charter — Guest Checkout (Mobile)

**Mission:**  
Find problems that could make a new user abandon checkout.

**Timebox:** 45 minutes  
**Areas:** search, product size selection, cart totals, postcode validation, cookie “reject”  
**Notes:** test on Safari and Chrome mobile view; try slow network and refresh/back





 [17:00] Home page - layout, navigation, and cookies banner working correctly  
 [17:03] Empty search - page loads but "no results" message shown 
 [17:05] [BUG] Search "fulham" - blank results, no empty-state feedback (see B-001)
 [17:09] [BUG] Women > Equipment menu opens empty/incorrect listing (see B-002)
 [17:15] Filters and sort options functioning as expected 
 [17:20] Product pages - prices, images, size selection, add-to-cart responsive
 [17:25] Cart - totals update, remove item, and persistence all working 
 [17:30] Checkout - valid/invalid email validation messages correct
 [17:34] [ISSUE] Postcode "ZZ1 1ZZ" accepted (format-only validation, see B-003)
 [17:36] Refresh/back keeps entered data (checkout stable) 
 [17:40] Cookies & privacy — Accept/Reject tested, site functional in both states
