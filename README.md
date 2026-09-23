# AUTA-RAZU Digital Village

Lecture-sharing site for Levels 2-5, Department of Radiography and Radiation Sciences, FUHSA Azare.

## How students use it
- You give each class ONE link: their level page (e.g. .../level3/)
- On that page they see all four level icons, but only THEIR level is active
- Each level page has: Announcements, Results, current semester lectures (2025/2026 Semester 1), and a Past Semesters archive

## How to publish (GitHub Pages)
1. Create a GitHub account and a new PUBLIC repository named e.g. `auta-razu-digital-village`
2. Upload ALL files/folders from this zip
3. Settings -> Pages -> Source: main branch -> Save
4. Your site goes live at https://YOURUSERNAME.github.io/auta-razu-digital-village/
5. Your level links are:
   - https://YOURUSERNAME.github.io/auta-razu-digital-village/level2/
   - https://YOURUSERNAME.github.io/auta-razu-digital-village/level3/
   - https://YOURUSERNAME.github.io/auta-razu-digital-village/level4/
   - https://YOURUSERNAME.github.io/auta-razu-digital-village/level5/
Share each level's link with only that class.

## How to update content (edit in browser on github.com)
### Add an announcement
Open the level's index.html, find the Announcements list, copy a line like:
  <li style="padding:6px 0"><b>DATE</b> &mdash; Your message</li>
and paste it at the TOP of the list. Commit the change.

### Post a lecture PDF
1. Upload the PDF into the level's folder (e.g. level3/)
2. In that level's index.html, find the session row and replace:
   <a class="pdf missing" href="#">PDF soon</a>
   with:
   <a class="pdf" href="session1.pdf" target="_blank">Open PDF</a>
   (use your PDF's actual file name)

### Post results
Same as a PDF: upload results PDF and link it in the Results section, changing the title text.

### Start Semester 2 (or a new session)
1. Rename the current "Lectures - Semester 1" card content into the Past Semesters details block (keep it, don't delete)
2. Change the tag to: CURRENT - 2025/2026 Session - Semester 2
3. Replace session rows with the new semester's sessions

## Important note
GitHub Pages is public. The inactive level icons are visual separation only -
anyone with the direct file URL could view it. Keep results to roll numbers/IDs
rather than full names if that matters to you.
