# -Basic-To-Do- 📝

A simple, beginner To-Do application implemented as a Google Colab notebook. This project is an early learning exercise and intentionally kept small and simple.

## What this project is

- A basic To-Do list app written in Python inside a Colab notebook.
- Supports adding, listing, editing and deleting tasks.
- Saves tasks to a plain text file (`TO-DO.txt`) and can load them back on startup.
- Includes a small monthly calendar helper for planning.

> Note: The notebook and code contain Turkish-language comments and prompts. The README is provided in English for broader visibility.

## Files in this repository

- `To_Do_Uygulaması_Azra_Şevval_Küpeli.ipynb` — the Colab notebook with the application code and example runs.
- `README.md` — this file.

## How to open and run

1. Open the notebook in Google Colab by clicking the "Open in Colab" badge at the top of the notebook file on GitHub, or visit:
   https://colab.research.google.com/github/azvval/-Basic-To-Do-/blob/main/To_Do_Uygulamas%C4%B1_Azra_%C5%9Eevval_K%C3%BCpeli.ipynb

2. The notebook contains multiple code cells. To run the app interactively, run the cells in the following order:
   - First run the cells that define helper functions (the cells labeled 2–8 in the notebook). These set up the calendar and task save/load functions.
   - After those cells have been executed once, run the main menu cell (labeled 1) to start the interactive menu.

3. When the menu starts, follow the on-screen prompts (the prompts are in Turkish).

## Notes and known limitations

- This is a learning project and intentionally simple. There are no advanced validations or error handling in some places (for example, menu input expects numeric values).
- Tasks are stored in a plain text file (`TO-DO.txt`) in the Colab environment. If you restart the Colab runtime, you may need to re-upload or re-run to restore files.
- The notebook file name and some contents include non-ASCII characters (Turkish letters). In some shells or tools this can cause issues — consider renaming if needed.

## How you can use or adapt it

- Keep it as a Colab notebook for interactive learning.
- Convert the notebook into a Python script or small CLI app if you want to run locally (example: move functions into a `todo.py`).
- Replace the plain text storage with JSON or SQLite if you want structured task data.
- Add basic input validation and unit tests to make the app more robust.
