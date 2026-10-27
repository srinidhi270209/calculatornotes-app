# Manual test records

## Verification performed

- JavaScript syntax check: passed using Node.js `--check` on the inline app script.
- Visual/manual browser checks: not run. The supported browser control blocked opening the local project file, so there are no observed UI outcomes or screenshots to report.

## Manual test checklist

| # | Steps | Expected result | Observed result |
|---|---|---|---|
| 1 | Enter `8 + 4 =` | Display shows `12` | Not run — browser access blocked |
| 2 | Enter `9 ÷ 0 =` | Display shows `Error` and “Cannot divide by zero.” | Not run — browser access blocked |
| 3 | Enter `2580 =` | Private Notes screen opens | Not run — browser access blocked |
| 4 | Create a titled note with body text and save | Note appears with timestamp | Not run — browser access blocked |
| 5 | Select note, edit its title/body, save | Updated text and timestamp appear | Not run — browser access blocked |
| 6 | Reload, enter code again | Saved note remains available | Not run — browser access blocked |
| 7 | Select and delete note | Note disappears | Not run — browser access blocked |
| 8 | Return to calculator | Display is cleared | Not run — browser access blocked |

Capture screenshots of the calculator, notes screen, and persistence check from a running browser before presenting the work as fully tested.
