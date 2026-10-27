# Calc & Notes

A small, dependency-free browser app with a calculator and local notes. Notes support create, view, edit, and delete, include creation/update timestamps, and are saved in browser `localStorage`.

## Run it

1. Download or clone this repository.
2. Open `index.html` in a current browser. No build step or server is required.
3. Use the calculator normally. Demo access code: **2580**. Enter it and press `=` to open Private Notes.
4. Use **New note**, **Save note**, select a saved note to edit, and **Delete** to manage notes. **Back to calculator** returns to the calculator and clears its display.

Change `ACCESS_CODE` in the script in `index.html` before sharing. This demo access gate is not strong authentication. Notes are stored locally and are not encrypted; anyone with access to the same browser profile may be able to access them. Clearing browser data removes them. This is not a secure vault.

## Features

- Addition, subtraction, multiplication, division, and remainder.
- Readable handling of division by zero.
- Responsive desktop/mobile layout.
- Create, view, edit, and delete notes, with timestamps.
- Persistent local storage.

## Files

- `index.html` — complete application.
- `README.md` — setup and usage.
- `TEST_RECORDS.md` — manual test steps and outcomes.
- `screenshots/` — screenshots of the running app.
