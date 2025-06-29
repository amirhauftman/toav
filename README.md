# Call Management App

Welcome to the Call Management App, a full-stack solution for managing call records and associated tasks. Built with **TypeScript**, **NestJS**, **TypeORM**, and **React**, this application provides a modern, type-safe environment for tracking calls, managing tasks, assigning tags, and handling pagination. It’s designed for efficiency and scalability, with secure authentication and role-based access.

## Features

- **Call Record Management**: View, edit, and delete call records with ease.
- **Task Management**: Create, update, and assign tasks to calls with statuses (Open, In Progress, Completed).
- **Tag System**: Organize tasks and calls with customizable tags.
- **Pagination**: Efficiently navigate large datasets with customizable page sizes.
- **Authentication**: Secure access using JWT-based authentication.
- **Role-Based Access**: Restrict actions with role-based guards.
- **Type Safety**: Leverage TypeScript for robust frontend and backend development.

## Technologies

- **Frontend**: React, TypeScript, Material-UI, TanStack Query
- **Backend**: NestJS, TypeORM, PostgreSQL
- **Database**: PostgreSQL (managed via TypeORM)
- **API**: RESTful endpoints with Axios integration
- **Authentication**: Custom JWT authentication service

## Installation

### Prerequisites

- **Node.js**: v18.x or later
- **npm** or **yarn**
- **PostgreSQL**: v13.x or later
- **Git**

### Project Structure

- `client/`: React frontend with TypeScript
- `server/`: NestJS backend with TypeORM

### Steps

1. **Clone the Repository**

2. **Enviroment setting**
30 sec
 - create new postres db 
 - add to app.module file all the details (i know its should be .env file)
   
3. **run the frontend**
npm install
npm run dev


4. **run the backend**
cd backend (i know its should be server)
npm install
npm run start

create a user as admin 
create a user as regular user (recommended on a different browser)

have some fun!!
