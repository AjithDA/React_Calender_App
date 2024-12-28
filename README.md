## Communication Tracker

Communication Tracker is a React-based application designed to help manage and track communications with various companies. The application provides features for managing companies, communication methods, and generating reports on communication frequency and engagement effectiveness.

## Table of Contents

- Features
- Installation
- Usage
- Project Structure
- Contributing
- License
- Setup and Deployment
- Application Functionality and Known Limitations

## Features

- **Admin Dashboard**: Manage companies and communication methods.
- **User Dashboard**: View recent communications and upcoming scheduled communications.
- **Calendar View**: Visualize communications on a calendar.
- **Reports**: Generate reports on communication frequency and engagement effectiveness.
- **Notifications**: Receive notifications for overdue and today's communications.

## Setup and Deployment

1. Clone the repository:
   
   git clone https://github.com/your-username/communication-tracker.git
   cd communication-tracker
   

2. Install dependencies:
   
   npm install
   

3. Configure environment variables:
   - Copy `.env.example` to `.env`
   - Update the variables with your configuration

4. Initialize the database:
   
   npm run db:migrate
   npm run db:seed
   

5. Start the development server:
   
   npm run dev
   

6. For production deployment:
   
   npm run build
   npm start
   

## Application Functionality and Known Limitations

### Functionality
- Supports multiple user roles (Admin, Manager, User)
- Real-time notifications for communication updates
- Export reports in CSV and PDF formats
- Integration with calendar applications
- Mobile-responsive design

### Known Limitations
- Calendar sync only supports Google Calendar
- Maximum of 1000 companies can be tracked simultaneously
- Report generation limited to last 12 months of data
- Notifications may be delayed up to 5 minutes
- File attachments limited to 10MB per communication