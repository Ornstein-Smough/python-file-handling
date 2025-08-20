This module demonstrates file handling in Python — reading, writing, and appending to files — through practical tasks.

⸻

1. Save/Load Student Grades
	•	Uses a text file (grades.txt) to persist grades.
	•	add: Appends a new name,grade entry to the file.
	•	view: Reads all grades and displays them.
	•	Ensures file exists before reading.

⸻

2. Word/Line/Character Counter
	•	Takes a filename as input.
	•	Reads entire file text.
	•	Counts:
	•	Lines: using splitlines().
	•	Words: using split().
	•	Characters: length of text.
	•	Useful for analyzing text documents.

⸻

3. Shopping List
	•	Stores shopping items in shopping_list.txt.
	•	add: Writes each new item on a new line.
	•	view: Reads all items and displays them.
	•	Uses append mode (a) so items aren’t overwritten.

⸻

4. Persistent To-Do List (Mini Project)
	•	Stores tasks in todo.txt in the format:
task_name|True/False.
	•	On start: Loads existing tasks from file.
	•	Options:
	•	Add task
	•	Mark task complete
	•	Save & Exit (writes back to file).
	•	Demonstrates:
	•	Persistent storage (data saved across runs).
	•	Reading and writing structured data.

⸻

5. Main Menu
	•	Menu-driven program for all four tasks.
	•	Keeps running until Exit is chosen.
