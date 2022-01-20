# Notes

Android application made on Android Oreo 8.1 version (API 27).
The application aims to create, edit, delete and save notes.
We use a ListView to display all notes, whether existing or created, and when we select a note from the list, a new window will open allowing us to edit and save the changes as we close the note.
To delete a note from the list, the term "LongClick" will be used, after which a message will appear asking us if we are sure or not to delete the note.
For storage we used objects such as "SharedPreferences" that will store the notes created, edited or deleted, both during the use of the application and after closing it and when restarting we will have saved the last activity in the application.
