
# 🎓 Syllabot 

**Syllabot** is a Discord bot designed to help students track their academic performance, calculate current grades, and figure out exactly what they need to pass—or hit a specific goal—before it’s too late.

Think of it as a grade calculator, syllabus interpreter, and reality-check machine, all living in your Discord server.

---

## ✨ Core Features

### 📘 Course & Syllabus Setup

* Define a course and its grading breakdown

  * Example: Homework 25%, Midterm 30%, Final 45%
* Supports:

  * Weighted categories
  * Multiple assignments per category
  * Optional “drop lowest” rules

---

### 📝 Assignment Grade Tracking

* Submit grades for individual assignments
* Automatically updates category and overall averages
* Handles missing / ungraded assignments gracefully

---

### 🧮 Automatic Grade Calculation

* Calculates:

  * Current overall grade
  * Category-level averages
* Updates dynamically as new grades are added

---

### 🎯 Goal & Final Exam Calculator

* Ask questions like:

  * “What do I need on the final to pass?”
  * “What do I need for a B+?”
* Supports:

  * Multiple target grades
  * Edge cases (already guaranteed / mathematically impossible)

---

### 🚨 Reality Checks

* Detects when:

  * A course is no longer mathematically passable
  * A target grade is unrealistic
* Responds honestly and clearly—no sugarcoating

---

### 📉 Attendance & Lecture Skips (Optional)

* Track skipped lectures
* Apply attendance penalties if applicable
* Estimate grade impact from missed classes

---

## 🔍 Advanced / Recommended Features

### 📊 What-If Simulations

Simulate outcomes before they happen:

* “What if I get a 75 on the midterm?”
* “What if I ace the final but bomb the quiz?”

---

### 📈 Grade Trajectory Tracking

* View how your grade changes over time
* Spot downward trends early instead of panicking at finals week

---

### 📅 Multi-Course Support

* Track multiple courses at once
* Quick overview of your entire semester in one command

---

### 🧠 Brutally Honest Mode

Optional mode that tells it like it is:

> “You need a 96.8 on the final. Lock in.”

---

## 🛠 Example Commands (Conceptual)

```text
/course create CS2110
/course weight homework 30
/course weight midterm 30
/course weight final 40

/grade add homework HW3 88
/grade add midterm Midterm1 72

/grade current
/grade goal A-
/final needed pass

/attendance skip
/whatif final 90
```

(Exact command structure subject to change.)

---

## 🧩 Planned Enhancements

* Graphical grade breakdowns
* Export summaries (CSV / image)
* Per-server or per-user privacy controls
* Integration with reminders and deadlines
* Configurable grading scales (A/A-/B+ etc.)

---

## ⚠️ Disclaimer

This bot is a **decision-support tool**, not a replacement for official gradebooks or instructor policies. Always double-check syllabi and confirm grading rules with your professor.

---

## 💡 Why This Exists

Because students deserve to know:

* where they stand,
* what they need,
* and when it’s time to lock in—or let go.

