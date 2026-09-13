# Iba High School — Science Remediation App

A gamified, interactive web application for Senior High School students taking remediation or enrichment for their Term 1 Science Exam.

## 🎯 Features

- **Student App** (`student.html`): Login, review modules, mock exam, final exam, results, and data export via QR code.
- **Instructor Dashboard** (`instructor.html`): Import student records, view progress, grant extra attempts, edit initial scores, export to CSV.
- **Gradebook** (`gradebook.html`): Consolidated view with statistical summary, printable layout.

## 📚 Subjects Covered

- **General Science** (Grade 11) — 5 review modules, 60 questions
- **Physical Science** (Grade 12) — 8 review modules, 60 questions

## 🎮 Gamification

- XP points for reviewing modules and correct answers
- Badges (Mock Pass, Final Pass, etc.)
- Progress bar across the whole journey
- Confetti animation on passing

## 📊 DepEd Alignment

- Proficiency levels based on the latest DepEd Order (SY 2026-2027)
- Passing threshold: **43/60** (Transition Period: Corresponds to Passing)
- Adjusted Transmutation Table applied during transition year

## 🔐 Data Persistence

- Student data is stored in the browser's **localStorage** (per device).
- Students can **export** their data as a **QR code** or **copyable code**.
- Instructors can **import** the code into the Instructor Dashboard.
- No server or database required — fully offline-capable.

## 🚀 How to Deploy

### Option 1: GitHub Pages (Free Hosting)

1. Create a new GitHub repository (e.g., `iba-science-remediation`).
2. Upload all files in this package.
3. Go to **Settings → Pages**.
4. Under **Source**, select `main` branch and `/ (root)` folder.
5. Click **Save**.
6. Your app will be live at:  
   `https://<your-username>.github.io/iba-science-remediation/`

### Option 2: Local Use

1. Download all files.
2. Open `index.html` in any modern browser.
3. No internet required after initial load.

## 📱 How Students Use It

1. Open `student.html`.
2. Log in with name, student ID, grade level, section, term, subject, and initial score.
3. Review all modules.
4. Take the mock exam (unlimited attempts, immediate feedback).
5. Score **43/60** or higher to unlock the Final Exam.
6. Take the Final Exam (3 attempts max, 90 minutes each).
7. View results with proficiency level.
8. Export data as a QR code or copyable code.

## 👨‍🏫 How Instructors Use It

1. Open `instructor.html`.
2. Paste the student's export code into the Import field.
3. View the student's record.
4. Optionally grant extra attempts or edit initial scores.
5. Export all student data to CSV.

## 🖨️ How to Print the Gradebook

1. Open `gradebook.html`.
2. Apply filters (grade level, subject, etc.).
3. Click **Print Gradebook**.
4. Use the browser's print dialog to save as PDF or print.

## 👨‍💻 Developer

**JEMUEL C. MARI, MAN, RN, LPT**  
Senior High School, Teacher II  
Iba High School • San Jose, Tarlac

## 📜 License

For educational use within Iba High School. All rights reserved.