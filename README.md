# Organizer

**Overview:** <br />
Organizer is a web application built using Node.js and React that allows users to journal their thoughts and manage their daily tasks through a to-do list.  Additionally, it integrates weather information by utilizing open-source APIs, enabling users to check the weather based on their location. The app provides full CRUD functionality for managing journal entries and tasks using a MongoDB database, and REST API requests are handled through Express.js.

**Features:** <br />
Journal and To-Do List: Users can create, edit, and delete journal entries and to-do list tasks. <br />
Weather Integration: Users can check weather conditions such as temperature and description, along with an image of their location. <br />
CRUD Functionality: Fully implemented create, read, update, and delete operations for journal entries and to-do tasks. <br />
RESTful API: Routes for all operations are structured according to RESTful principles, making it easy to manage tasks and journal entries. <br />
Responsive UI: Built with React to provide an interactive and user-friendly interface. 

**Tech Stack:** <br />
Backend: Node.js, Express.js, MongoDB <br />
Frontend: React, CSS <br />
API Integration: OpenWeather API for weather information <br />

**Getting Started:** <br />
**Prerequisites:** <br />
Before running the project, ensure you have the following installed: <br />
Node.js and npm (for the backend and frontend) <br />
MongoDB (for the database) <br />
API Key for the OpenWeather API (to fetch weather data)

**Routes and API Endpoints:**  <br />
The app utilizes Express.js to handle REST API requests with the following routes: <br />
Journal: <br />
GET /api/journal: Fetch all journal entries <br />
POST /api/journal: Add a new journal entry <br />
PUT /api/journal/:id: Update a journal entry <br />
DELETE /api/journal/:id: Delete a journal entry <br />

To-Do List: <br />
GET /api/todos: Fetch all to-do items <br />
POST /api/todos: Add a new to-do item <br />
PUT /api/todos/:id: Update a to-do item <br />
DELETE /api/todos/:id: Delete a to-do item

Weather: <br />
GET /api/weather/:location: Fetch weather information for a specific location using the OpenWeather API

**Usage:** <br />
Create Journal Entries and To-Do Items: Users can create and manage their journal entries and to-do list tasks through an interactive React frontend. <br />
Check the Weather: By entering a location, users can view the current weather, including temperature, a description, and an image based on the weather conditions. <br />
CRUD Operations: Users can add, edit, and delete journal entries and tasks seamlessly with real-time updates. <br />

**Future Enhancements:** <br />
User Authentication: Add authentication and user-specific data storage. <br />
Calendar View: Implement a calendar view for better task management and journaling. <br />
Push Notifications: Notify users of upcoming tasks or weather changes.


