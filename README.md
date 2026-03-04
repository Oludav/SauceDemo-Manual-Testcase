# SauceDemo – Manual Test Case Documentation

Manual QA test case suite for the [SauceDemo (Swag Labs)](https://www.saucedemo.com/) web application, covering core e-commerce flows across four functional modules.

---

## Test Coverage

| Module | Test Cases |
|---|---|
| Login | 12 |
| Adding Product to Cart | 7 |
| Removing Product from Cart | 7 |
| Checkout Process | 12 |
| **Total** | **38** |

**Test credentials used:**
- `standard_user` / `secret_sauce` — full access
- `locked_out_user` / `secret_sauce` — blocked (expected to fail login)

---

## File Structure

```
├── README.md
└── SauceDemo_TestCase_Sheet.xlsx
```

Each test case includes: TC ID · Test Title · Test Case · Execution Steps · Test Data · Expected Result · Actual Result · Status · Defect Severity · Comments.

**Status values:** `P` Pass · `F` Fail · `NE` Not Executed · `NA` Not Applicable

---

## How to Use

1. Open `SauceDemo_TestCase_Sheet.xlsx` and navigate to the **SauceDemo** tab
2. Execute each test against https://www.saucedemo.com/
3. Log results in the **Actual Result**, **Status**, and **Defect Severity** columns

---
