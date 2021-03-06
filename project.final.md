## FINAL PRESENTATIONS 05/06 AND 05/13 - 4:00PM to 6:30PM - KH Lecture Hall 2

## PROJECT DUE DATE - 05/13 - 11:59PM - CSNS

#### As a team create a custom app. The app must have a Node.js server and a Vue.js frontend.

Students should work with their Midterm groups to create an App of their choosing which demonstrates your team's understanding of Javascript, Node.js and Vue.js.

Options:
- Extend the midterm to create an App that interacts with your API [Guidelines](/ProjectRequirements/api.md)
- A Dropbox style App (File Sharing) [Guidelines](/ProjectRequirements/dropbox.md)
- A Real-Time Trivia App [Guidelines](/ProjectRequirements/trivia.md)
- A Collaborative To-Do App [Guidelines](/ProjectRequirements/todo.md)

---
### Node Server Requirements

**package.json** <br/>
The server should have a package.json file that is properly filled out.
  - It should include but not limited to (name, version, author, contributors, dependencies, etc)

**Server** <br/>
    - Responsible for serving the Vue frontend.
    - Responsible for data. Meaning delivering data from API or databases, maintaining data between users, etc.

**Additional Guidelines**
Your Node.js server is responsible communicating with your Vue.js frontend via HTTP or Sockets.
  - API interactions should go through the server.
  - Database transactions should go through the server.
  - Socket messages should go through the server.

---
### Vue Requirements

**App &  Components**
The Vue frontend should have at least (1) component.

**CSS**
The Vue frontend should be styled. Use a css framework (bootstrap, materilize) or create your own custom styles.

**HTML**
Use HTML5. Proper indentations. Ensure all html elements are properly closed.

**Additional Guidelines**
The frontend should allow for user interaction - button clicks, input, forms, uploads, etc.  The actions should call a Vue app method which then interacts with your Node.js server. The frontend should not be making any third-party (external) HTTP calls, database connections or socket connections.

---

### GRADING FINAL

**Preparedness**
  - Team has the Zoom link and is ready to be host.
  - Team knows who is covering which parts of the presentation.
  - Team has code files ready for the presentation (No slides.  .JS files).

***Timing**
  - Each team member has 2 minutes to present on a portion of the module
  - Going over time loses points.
  - Going WAY under time would also lost points. (example: presenting for 30 secs)

**Code Presentation**
  - Present on a small amount of code (20-30 lines)
  - The code presented on should be code written by you.  Not an example from class or some external module.
  - The code presented on should not be the same from the midterm
  - The code presented on should be explained in detail, clearly and most importantly correctly.


**Q&A**
  - Team is able to answer questions from class or professors

---

### GRADING PROJECT

**App**
    - Submitted by EACH student on time to CSNS.
    - Includes all the contents/files needed to run the app.
    - IF you have a db then include clear instructions on setup. Or use a cloud DB.
    - Folder structure is clear and organized (client versus server)

**Code**
  - Code meets the requirements outlined.
  - Code is organized and readable.
  - Code meets the standards taught in class.
    - let versus const
    - proper Javascript indentation
    - meaningful variable names
    - correct use of promises and callbacks
    - correct use of sockets, http
    - not using setTimeout
    - not hard coding
    - not using global variables
    - etc
    
**Extra Credit**
  - Not required.
  - Applied to the Project portion of the grade.
  
The more code your write, does not mean a good grade. The code written and submitted as the project should be clean, well written and not necessarily verbose.

