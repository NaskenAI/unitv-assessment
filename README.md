# Unit V — Network Security Practical Assessment

This is the student-facing page for the Unit V network-security practical assessment. It is a **static site**: `index.html` is fully self-contained (inline HTML, CSS and JavaScript, with no build step, framework or server code) and is served as-is.

## Contents

- `index.html`: the assessment page, served at the site root
- `data/`: synthetic lab data files for the exercises
  - `cred_00.txt` … `cred_09.txt`: salted SHA-256 credential records (`user:salt:hash`)
  - `leaked_plain.txt`: a "leaked" list of plaintext `user:password` pairs
  - `access.log`: login events (`timestamp user result`)

All accounts (`u00001` …) and passwords are invented for this exercise. None of it is real personal data.

## How students use it

1. Open the site.
2. Download the files in the `data/` folder.
3. Enter your name, roll number and assigned vault on the page.
4. Work through the tasks in Python on your own machine.
5. Submit your answers through the instructor's form.

## Important

This repository is public. It must **never** contain answer keys, reference solutions or grading scripts (for example `answer_key.csv`, `grade_*.py`, `reference_solution.py`, `model_solutions.md`, or any `.zip` of answers). `.gitignore` excludes these, but check before every commit.
