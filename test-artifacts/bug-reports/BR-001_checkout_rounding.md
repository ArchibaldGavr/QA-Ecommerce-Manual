# BR-001: Checkout total rounding issue

**Env:** Windows 10, Chrome 126  
**Preconditions:** Cart has items with fractional prices  
**Steps:**  
1) Go to /cart → checkout  
2) Apply COUPON10 (10% off)  

**Actual:** Total shows 49.989 (3 decimals)  
**Expected:** Total rounded to 49.99 (2 decimals)  

**Severity:** Medium • **Priority:** High  
