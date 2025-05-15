Habit Tracker
Project Overview 
The Habit Tracker is a web-based application designed to help users build and maintain consistent habits. It provides tools for tracking daily progress, categorizing habits, and visualizing achievements. The app is ideal for individuals who want to improve productivity, maintain healthy routines, or achieve personal goals.  

- Purpose: To empower users to create, track, and manage their habits effectively.  
- Target Users: Students, professionals, and anyone looking to build better habits.  
- Context: Built as part of a software development course, this project demonstrates full-stack development skills, including frontend, backend, and database integration.

Use Case Summary

Demonstration  

Use Case                     	Implemented (Yes/No)		Notes                                                                 
User views their habits       	Yes                  	 Habits are displayed on the Home page with categories and progress indicators.        
User marks a habit as "done"  	Yes                  	Implemented using a toggle button
User adds a new habit         	Yes                  	Habits can be added via the Settings page. 
User deletes a habit          	Yes                  	Delete functionality is available in the Settings page.                              
User views progress metrics   	Yes	Progress is visualized using a progress bar and calendar view.                        
Admin manages user accounts   	No	Not prioritized due to time constraints. Possible future work.                        


Technical Implementation

Technologies Used
- Frontend: Tailwind CSS, React.js (with React Router for navigation and Context API for state management).  
-Backend: Node.js with Express.js for RESTful API implementation.  
- Database: MongoDB (via Mongoose) for storing user data, habits, and categories.  
-Styling: Inline CSS and modular styles for responsiveness.  

Architectural Decisions
- Client-Server Architecture: Clear separation between frontend (in src folder) and backend (in server folder) for scalability.  
- Modular Folder Structure: Organized files into components, pages, services, and context for maintainability.  
- Global State Management: Used React Context to share data like categories across components without prop drilling.  

Key Features 
1. Habit Tracking: Users can add, update, delete, and mark habits as done. Also user can create categories. 
2. Progress Visualization: Progress bars and calendar views provide insights into habit completion.  
4. Responsive Design: The UI adapts seamlessly to different screen sizes.  

Development Process

1.Phase 1: Planning and Use Cases
   - Defined use cases and created wireframes for the app’s structure.  
   - Set up the project environment with React, Node.js, and MongoDB.  

2. Phase 2: Basic Structure and Functionalities
   - Built the frontend components (e.g., `HabitItem`, `CategoryTag`) and backend routes (e.g., `/habits/:id/complete`).  
   - Integrated the frontend with the backend using Axios for API calls.  

3. Phase 3: Testing and Debugging 
   - Resolved issues like duplicate imports (`Button`, `StatsCard`) and missing components (`CategoryTag`).  
   - Ensured error handling and user-friendly messages for API failures.  

4. Phase 4: Final Touches 
   -I did a lot of work in deployment
   - Conducted end-to-end testing to ensure all features worked as expected.  

Reflection and Future Work

What Worked Well
- The modular folder structure made the codebase easy to navigate and extend.  
- Using React Context simplified global state management for categories and habits.  
- The responsive design ensured a seamless experience across devices.  

Challenges Faced
- Debugging errors caused by duplicate imports and missing components was time-consuming.
- struggled to run the project due to some errors. But at the end I managed to fix them and run the application. Also, I managed to make redirection of the url which includes the port number, 
- Ensuring smooth communication between the frontend and backend required careful testing.  

Future Improvements
- Add user authentication and secure session handling.  
- Implement analytics and notifications to motivate users.  
- Enhance the UI with advanced charts and graphs for better insights.  
- working on achievement so it will be synchronized with backend. Same thing with insights.

Work Hours Log

Date	Used Hours	Phase	Outcome
25.03.2025	4	Planning and Definition	Navigate through different ideas and topics.
26.03.2025	4	Planning and Definition	Picked 3 interesting topics.
31.03.2025	4	Planning and Definition	- Defined the project
- Set environment (technologies)
- Started design
- User personas
- Use case and user flow.
05.04.2024	6	Planning & Design	Designed prototype and some modifications
05.04.2024	6	phase two	working on project
10.05.2024	8	phase two	working on project
11.05.2024	8	phase two	creating the virtual machine
copied source code using WINSCP to the VM
connect to VM using PUTTY <preparing the envirement by installing packages(Node js and npm) and Nginx>
05.04.2024	6	phase two	working on project
13.05.2024	6	phase two	working on project
working on deployment
configuration of the nginx with redirection of the URL to the URL:8080

 


