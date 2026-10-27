
---

### 3️⃣ Repo: `python-bugs`
🔗 **URL:** `https://github.com/ishi5656/python-bugs`

```markdown
# Fixing Buggy Python Script Using AI & Unit Testing

A debugging and software quality assurance project following the **RED ➔ FIX ➔ GREEN** test-driven cycle using Python's `unittest` framework and Cursor AI.

## Author
- **Ishika Choudhary** (Enrolment No: `25BCON1173`)
- BTech Computer Science & Engineering
- GitHub: [@ishi5656](https://github.com/ishi5656)

---

## Repository Contents
- `student_utils.py` — Utility functions for grade calculations, pass/fail status, and grade allocations.
- `test_student_utils.py` — Unit tests covering boundary values and edge cases.
- `bug_notes.md` — Detailed breakdown of identified defects and root causes.
- `audit.md` — Verification logs and test results.

---

## Bugs Identified & Resolved
1. **Wrong Denominator in Average**: Division was using hardcoded or incorrect list lengths.
2. **Division by Zero**: Calculation crashed when handling empty or single-element datasets.
3. **Boundary Condition Off-by-One**: Passing marks threshold check evaluated strict inequality (`>`) instead of greater than or equal to (`>=`).
4. **Incorrect Branch Evaluation Order**: Grade boundary ladder (`A`, `B`, `C`) was evaluated out of order, misclassifying scores.

---

## Running the Unit Tests
```bash
python -m unittest -v test_student_utils.py
