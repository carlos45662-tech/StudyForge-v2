STUDYFORGE VERSION 2

WHAT'S NEW
- Question Bank Manager
- Add questions manually from iPad/Safari
- Edit built-in and added questions
- Disable built-in questions or delete added questions
- Import question updates from JSON files
- Export a complete active question bank as JSON
- Export local progress/custom-data backup
- Full Sergeant General Order titles appear with GO numbers throughout quizzes and tests
- Existing Civic Literacy and Sergeant question banks remain intact
- Progress and custom questions are stored locally in Safari

FILES
- index.html: app entry point
- styles.css: interface
- app.js: study, quiz, and question-bank engine
- data.js: built-in Civic Literacy and Sergeant study data
- manifest.webmanifest + sw.js: install/offline support

UPDATING GITHUB PAGES FROM VERSION 1
1. Unzip this Version 2 package.
2. In the GitHub repository currently hosting StudyForge, replace the existing files with ALL files in this folder.
3. Commit the changes to the main branch.
4. GitHub Pages will redeploy automatically.
5. Open StudyForge in Safari and refresh. If the old interface remains, close the Home Screen app/Safari tab and reopen it. Version 2 uses a new offline cache name.

ADDING QUESTIONS
Open a study pack > Manage > + New Question.

IMPORTING QUESTIONS
Open a study pack > Manage > Import JSON.
A compatible file can be either an array of question objects or an object containing a "questions" array.

EXPORTING
Manage > Export Bank creates a JSON file containing all currently active questions for that pack.
Manage > Export Progress creates a backup of progress and custom question data.

IMPORTANT
Your original built-in questions remain in data.js. Editing a built-in question stores an override in Safari. Disabling a built-in question hides it but does not remove it from data.js.

Progress and custom questions are stored in Safari local storage. Clearing website data can erase them, so use Export Progress periodically.
