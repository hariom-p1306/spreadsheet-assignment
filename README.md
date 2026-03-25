# Spreadsheet App (React + Vite)

## Features Implemented

### Task 1: Sorting & Filtering
- Column sorting (ascending → descending → none)
- Sorting works on computed values (formula results)
- Filtering using dropdown in column headers
- Filtering hides rows (non-destructive)
- Sorting and filtering are reversible
- Formulas remain intact (view-layer only changes)

### Task 2: Copy & Paste
- Supports multi-cell paste from Excel / Google Sheets
- Handles tab-separated data
- Internal copy-paste supported
- Ctrl+C copies computed values
- Paste integrates with undo/redo

### Task 3: Local Storage
- Auto-save with debounce (500ms)
- Restore data on reload
- Persists values, formulas, styles
- Handles corrupted data safely

## Tech Used
- React
- Vite
- Custom Spreadsheet Engine

## Notes
- Sorting and filtering implemented at UI level
- Engine logic remains untouched