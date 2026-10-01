# RADXtra — A Radiography Student Learning Hub

Academic session: 2026/2027

RADXtra is a static GitHub Pages learning hub for Radiography students. The site uses a clean navigation flow:

1. Student opens their level link.
2. Student confirms the level card.
3. Student selects a lecturer.
4. Student opens course materials and lecture PDF cards.

## Main structure

- `index.html` — RADXtra main landing page.
- `home.html` — redirect compatibility page.
- `level2/`, `level3/`, `level4/`, `level5/` — level-specific entry folders.
- `levelX/lecturers/` — lecturer directory and lecturer workspace pages.
- `levelX/pdfs/lecturer-name/` — PDF upload folder for that lecturer.

## Lecturer identity

- Platform name: RADXtra
- Workspace name / nickname: AUTA-RAZU
- Formal academic name: Abdulrazaq A. Zubair

## PDF filename rule

Use hyphens only. Do not put `/` in the PDF filename.

Correct filename example:

```text
rad-201-session-1.pdf
```

Correct folder example:

```text
level2/pdfs/auta-razu/
```

So the full upload location becomes:

```text
level2/pdfs/auta-razu/rad-201-session-1.pdf
```

In that full location, the `/` characters are folders. They are not part of the PDF filename.

## Current AUTA-RAZU courses

- Level 2: RAD-201 — Radiation Physics
- Level 4: RAD-423 — Imaging Informatics
- Level 4: RAD-447 — Radionuclide Imaging / Nuclear Medicine
- Level 5: RAD-541 — Magnetic Resonance Imaging II

See `UPLOAD-GUIDE.md` for the exact PDF names to upload.
