Objective
Build a video management application using the MERN stack, with all services running locally
inside Docker containers. This app will allow users to upload, view, and manage their own
video collections, which are stored in a backend database.
Requirements
1. Environment Setup
● Use Docker Compose to manage all services (frontend, backend, and database) as
separate containers.
● Ensure each service can be spun up and run independently through Docker Compose,
with clear documentation on how to start the application.
2. Authentication & User Access
● Implement user authentication (using a library such as Passport.js or JWT-based).
● Ensure that each user sees only their own uploaded videos when logged in.
3. Video Uploading & Storage
● Implement a feature that allows users to upload videos directly from Google Drive.
● Store uploaded videos’ metadata (e.g., title, description, tags, file size) in a database of
your choice.
● For the database, consider using MongoDB (given the MERN stack), but you’re free to
select any DBMS, with justification.
4. Video Management Features
● Filtering and Pagination: Implement filtering capabilities (e.g., by title, date uploaded,
tags) and pagination to efficiently navigate through a user’s videos.
● Generate metadata for each video (title, description, tags, duration, etc.) based on a
logic or randomization approach of your choice.
5. Frontend
● Build a responsive UI using React to display and manage uploaded videos.
● Provide a video player for viewing videos directly within the application.
