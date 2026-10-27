# Project Write-up: Calc & Notes

## Overview

Calc & Notes is a browser-based calculator with a local notes area. The calculator supports addition, subtraction, multiplication, division, and remainder. Entering the demo access code (`2580`) and pressing equals opens the clearly labeled Private Notes screen. Notes can be created, viewed, edited, and deleted. Each note records its creation and last-updated times, and browser local storage keeps notes between visits.

The notes are not encrypted. The access code is a demo gate, not strong authentication. Do not store sensitive information in this project.

## Tools and technologies

- HTML, CSS, and JavaScript
- Browser `localStorage` for local persistence
- No external packages or build tools

## How to run

1. Download or clone the project.
2. Open `index.html` in a current browser.
3. Use the calculator or enter `2580` and press `=` to view the notes area.
4. Select **Back to calculator** to return.

## Screenshots

Screenshots are not included yet because the supported browser session could not open the local project file. Capture these from the running app before publishing the report:

1. **Calculator:** capture the main calculator screen.
2. **Notes:** enter `2580`, press `=`, then capture the notes screen with a sample note.
3. **Persistence:** reload the app, reopen Notes, and capture the saved note.

## Step-by-step test record

See `TEST_RECORDS.md`. The JavaScript syntax check passed. The interactive test cases need to be run in a browser and their observed outcomes recorded; expected outcomes are listed in the checklist.

## Project files

- `index.html` — complete app
- `README.md` — run instructions and notes
- `TEST_RECORDS.md` — verification performed and manual checklist
- `screenshots/` — destination for screenshots from the running app
