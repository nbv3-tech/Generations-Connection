Project title: [ Generations Connect: A Collaborative Family History Platform]


Name: [Naga Babu Velisala]

Project description:
[Generations Connect is a Web-platform that builds family trees and media for multiple generations of user collaboration. This project involves CRUD-based functionality where users can create, read, update, and delete family members, relations, events, and images. It provides role-based access control for privacy and security, allowing family members to collaborate while keeping ownership of their data.]

List of requirements (objectives):
Essential:


[1.User Authentication & Role Management:
*Users can register,login and manage profiles.
*Role-based access(Admin,Contributor,Viewer) to control edit/view permissions.]


[2.Family Tree Management(CRUD Operations):
*Users can add, update, and delete family members.
*Relationships between family members (parent-child, spouse, siblings) are managed.]


[3.Event Tracking & Timeline:
*Operations for significant family events (birth, marriage, death,      migration).
*Users can search & filter events to retrieve specific history.]


[4.Merge Duplicate Family Members:
*Detect and merge duplicate entries in the family tree.]


[5.Backup&Restore Feature:
*Users can save and restore snapshots of their family tree.]


Desirable:

[1.User Comments on Profiles:
*Users can leave notes or comments on family member profiles.]
[2.Basic Analytics:
*Display statistics (e.g.,"Largest family group").]
[3.Notifications & Activity Log:
*Track recent changes (e.g., "New member added by [User]").]

Optional:


[1.Voice Recording for Family Stories:
*Users can record and store voice clips of family members sharing stories.]


[2.Interactive Map View:
*Show where different family members have lived over time.]



Steps to Run the Appication

Run Spring Boot Backend

•	Open the terminal and navigate to the backend .jar file directory.
•	Execute the following command to start the Spring Boot application.
“java -jar filename.jar”
•	Wait until you see: “Started Application in X seconds”.
•	This confirms the backend is running typically on http://localhost:8080.

Connect Neo4j Database :

•	Open Neo4j Desktop or Browser http://localhost:7474.
•	Open Neo4j and create a new database called FamilyTree with a password 12345678. The password and the database name has been fixed as the application is being run with the jar file to avoid other complexities.
•	Ensure the database is running.
•	You should see graph nodes if data is already inserted.
•	Double check in backend server application.properties.

Start Frontend in VS Code :

•	Open the frontend project folder (family_tree_front) in VS Code.
•	Open the terminal (Ctrl + `) and run: “npm install”.
•	Once all dependencies installed then run : “npm run dev”.
•	The frontend will be available at: http://localhost:3000
