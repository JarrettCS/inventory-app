# Inventory Management System

A full-stack application for managing inventory with advanced search capabilities and saved search functionality.

## Features

- User authentication and authorization
- Inventory item management (CRUD operations)
- Advanced search functionality
- Saved searches management
- Customizable column configurations
- Loading states and skeletons for better UX
- Responsive Material-UI design

## Tech Stack

### Frontend
- React
- TypeScript
- Material-UI
- Redux Toolkit
- React Router
- Axios

### Backend
- Node.js
- Express
- TypeScript
- MongoDB
- JWT Authentication
- Winston Logger

## Prerequisites

- Node.js (v14 or higher)
- MongoDB (v4.4 or higher)
- npm or yarn

## Installation

1. Clone the repository
```bash
git clone <repository-url>
cd inventory-app
```

2. Install backend dependencies
```bash
cd backend
npm install
```

3. Install frontend dependencies
```bash
cd ../frontend
npm install
```

4. Set up environment variables:

Backend (.env):
```env
PORT=5001
NODE_ENV=development
MONGODB_URI=mongodb://localhost:27017/inventory-app
JWT_SECRET=your-secret-key
CORS_ORIGIN=http://localhost:3000
```

Frontend (.env):
```env
REACT_APP_API_URL=http://localhost:5001/api
```

## Running the Application

1. Start MongoDB
```bash
mongod
```

2. Start the backend server
```bash
cd backend
npm run dev
```

3. Start the frontend development server
```bash
cd frontend
npm start
```

The application will be available at http://localhost:3000

## Development

### Backend Structure
- `/src/config` - Configuration files
- `/src/controllers` - Request handlers
- `/src/middleware` - Custom middleware
- `/src/models` - Database models
- `/src/routes` - API routes
- `/src/types` - TypeScript type definitions

### Frontend Structure
- `/src/components` - Reusable React components
- `/src/pages` - Page components
- `/src/services` - API services
- `/src/store` - Redux store and slices
- `/src/types` - TypeScript type definitions
- `/src/layouts` - Layout components
- `/src/contexts` - React contexts

## Testing

```bash
# Run backend tests
cd backend
npm test

# Run frontend tests
cd frontend
npm test
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## License

This project is licensed under the MIT License.
