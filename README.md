## JSJournal README.md

To get started with JSJournal, install from your terminal using the command:

- npx jsjournal serve

This application will allow you to write Javascript and React code, and excecute it in the browser.  

You can add code cell components as well as text based components to annotate your JSJournal entries.

### Code Cells

React and React-DOM are enabled by default, so they do not need to be imported every time (though it will not break if you do import)

To display your ouput or a React Component in the output window, call the command show() to do so. If you want to log to the browser's console, you can console log normally.

All variables are cached, so you can reference previously declared variables at any time.

### Text Cells

In the text cell editor, you will enter your text via markdown on the left, and it will be displayed in rich text on the right.  Click out of the box to save the cell.

### Data Persistence

All data is written to your local file system, so if you close JSJournal, you can reopen it from the terminal and pick up right where you left off.  Just be sure to launch from the same location each time.
