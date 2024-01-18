# **Virtual Help Lab**
This Web Program will serve as an opportunity for students to identify other students who are at similar parts of an assignment, allowing them to interact with one another and work through the assignment together. This will also allow TAs to identify where students are struggling and adjust their efforts accordingly.
## Specification Deliverable
### Elevator Pitch
Many students struggle with the various assignments and as an educator, it can be difficult to ensure that every student gets the opportunity to meet with an instructor or TA to receive the help that they need. Collaborating with other students is a commonly overlooked resource that can be a powerful tool in college and the workforce. My site connects students to their peers at similar points of any assignment, encouraging engagement between students and allowing them to take the role of teacher as they work to complete a given assignment. Additionally, it allows TAs to monitor students' progress and offer help where it's most needed. Guided learning has never been easier than it is now.
### Design
![Help Lab User Interface](https://github.com/dillon-t-paul/Startup/assets/156498150/642cfba1-041c-485b-b786-448518accc44)
### Key Features
- Secure login over HTTPS
- Ability to join other students at similar stages in a given assignment
- Observe where other students are at on any given assignment
- Interact and work with classmates on current assignments
- Read TA tips for current problems
- Request one-on-one help from a TA
### Technologies
- **HTML** - Web structure created using HTML. Three HTML pages: One to create an account, one to log in, and one for the Online TA Lab
- **CSS** - Application is styled to match window size, has a complimenting color scheme, and centers focus on group chat and TA tips
- **JavaScript** - Provides login, homework and section choices, links to assignment instructions, and chat features.
- **Authentication** - Users will create an account with a username and password that they can later log in with. Their name will be displayed in messages and in an icon that serves as a hyperlink to their account info on the top right.
- **Database Data** - Stores Users and their credentials, as well as what part of the assignment they are on. It stores how many students are in each section and the TA tips for future use.
- **Web Services** - Application uses chatWithPeers function to interact with other students
- **Web Framework** - Using React to add components and request routing
- **WebSocket Data** - When a user joins a section, the student count is updated for all users. Messages are broadcast to all users in the current section.
