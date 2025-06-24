# Command-Line-Note-Taking-App
Terminal note-taking app with Node.js - add, list, read &amp; delete notes. 

----------------------------------------------------------------------------------------

  
A command-line application to manage notes, built with Node.js & JavaScript (ES6)  

Images  

 Features  
✅ CRUD Operations – Create, read, update, and delete notes via CLI commands.  
✅ Persistent Storage – Notes saved to a JSON file using Node.js `fs` module.  
✅ User-Friendly Commands – Supports `add`, `list`, `read`, `remove` with `--title` and `--body` flags.  
✅ Error Handling – Validates user input and displays clear error messages.  

 Tech Stack  
- Runtime: Node.js  
- Core Modules: `fs`, `path`, `os`  
- Dependencies: `yargs` (command-line argument parsing)  
- Language: JavaScript (ES6+)  

 Installation & Usage    
1. Install dependencies:    
   npm install  
    
2. Run commands:    
   node app.js add --title="Groceries" --body="Milk, Eggs"  # Add a note  
   node app.js list                                         # List all notes  
   node app.js read --title="Groceries"                     # View a note  
   node app.js remove --title="Groceries"                   # Delete a note  
     

 Why I Built This  
- To master Node.js core modules (File System, CLI arguments).  
- Practice  modular code design  (separate functions for each operation).  



