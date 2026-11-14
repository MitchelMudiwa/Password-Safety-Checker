# Password Safety Checker

A single-purpose website that helps students check how strong a password is and gives short, plain-English tips to improve it. Built as a Human Computer Interaction (HCIN6222) Portfolio of Evidence prototype.

## How to run
1. Download or clone this repository.
2. Open `index.html` in a web browser. No installation is needed.

## What it does
- Strength bar with a word label (Weak, Fair, Good, Strong), so colour is never the only signal
- Plain-English tips (maximum three) and a rough time-to-guess message
- Show/Hide and Clear buttons
- Passphrase suggestion (five random words, for illustration only)
- Quick tips page and a button that copies the website link
- Privacy: the check runs in the browser. The password is never sent or stored.

## Accessibility
Skip link, visible focus outline, labelled controls, live region for results, `role="alert"` for the empty-box message, relative text sizes and controls at least 44 px high. Designed to WCAG 2.0 Level AA.

## Tests carried out
- 40-password test set: 37 of 40 received an acceptable label (92.5%). Three hard cases were rated too high.
- Privacy check: no network requests after the page loads, and nothing saved in browser storage.
- Keyboard test: logical tab order with a visible focus outline.
- Automated page audit: no unlabelled inputs, no unnamed buttons, no duplicate IDs.

## Limitations
- The word and password lists are small (83 common passwords, 344 words and names, 453 passphrase words).
- The usability test with students and the screen reader test were not carried out.
- The strength result is an estimate only.

## Files
- `index.html`: the prototype (HTML, CSS and JavaScript in one file)
- `screenshots/`: screenshots used in the report
- `docs/HCI_POE_Research_Report.docx`: the research report

Student number: ST10496035
