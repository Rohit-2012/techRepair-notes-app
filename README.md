# Tech Repair Notes App

Welcome to the Tech Repair Notes App repository! This is the frontend part of our application designed for managing technical repair tasks and notes within a tech repair shop. Employees can log in and manage their work by adding, updating, and deleting notes for specific repair tasks. There are three distinct roles assigned to employees: Employee, Manager, and Admin, each with varying levels of access and permissions.

## Features

- **Authentication**: Users can log in with their credentials, and their access and permissions are determined by their assigned role.
- **User Management**: Managers and Admins can create, read, update, and delete users. This includes activating or deactivating users.
- **Note Management**: Users can create, read, update, and delete notes assigned to them. Managers and Admins have the additional capability to manage notes for all employees.
- **Tagging System**: Notes can be tagged as open or completed, indicating the status of the repair task.
- **User Status**: Users are tagged as active or inactive to indicate their current status within the system.

## Technologies Used

- **React**: Frontend framework for building user interfaces.
- **React-Redux**: Library for managing application state.
- **Redux Toolkit**: Redux utilities for simplifying state management.
- **React Router**: Library for handling routing in React applications.
- **React Spinners**: Collection of loading spinner components for React.
- **Font Awesome**: Icon set and toolkit used for icons in the application.

## Deployment

The frontend of the Tech Repair Notes App is deployed on Render and can be accessed at [Tech Repair Notes App](https://techrepair-notes-app.onrender.com).

## Getting Started

To set up the project locally, follow these steps:

1. Clone this repository to your local machine.
2. Install dependencies using `npm install`.
3. Create a `.env` file and configure environment variables such as API endpoints, authentication secrets, etc.
4. Run the development server using `npm start`.

## Contributing

I welcome contributions from the community. If you have any suggestions, bug fixes, or new features to add, please open an issue or submit a pull request following our contribution guidelines.

## Contributors

- Rohit Kirti (@rohit-2012)


## Contact

For any inquiries or support, please contact me at rohit.kirti1219@gmail.com.
