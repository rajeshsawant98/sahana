# Sahana Meetup App

Welcome to the Sahana Meetup App repository! This app allows users to create and join meetups based on their interests, with features such as user authentication, category selection, event notifications, and more.

## About

Sahana is a feature-rich application designed to simplify the process of organizing and participating in meetups. It leverages modern technologies to provide a seamless and efficient user experience.

### Technical Details
- **Technologies Used**: Firebase, Google SSO, Microsoft Graph API, Zoom API, Slack API, JavaScript, CSS, Firebase Cloud Messaging
- **Duration**: 10 weeks development timeline

### Key Features Implemented
- **User Authentication and Profile Management**: Users can create accounts, log in using Google SSO, and manage their profiles.
- **Meetup Creation and Management**: Users can create and manage meetups, specify details, and track attendance.
- **Event Notifications and Reminders**: Send notifications and reminders to users about upcoming events.
- **Event Rating and Reviews**: Users can rate and review events they've attended.
- **Meetup Type Selection**: Users can select the type of meetup (online or offline) and integrate with various online meeting platforms.
- **Find Friends**: Users can discover and connect with nearby users who share similar interests.

## Features

- **User Authentication and Profile Management**: Allow users to create accounts or log in using Google SSO. Users can manage their profiles, including profile picture, bio, and contact information.
- **Category Selection**: Upon account creation, users choose their preferred categories of interest (minimum 3, maximum 5), such as sports, arts, literature, etc.
- **Meetup Creation and Management**: Users can create meetups specifying details like category, location, description, date, and maximum attendees. Organizers can track event attendance and mark attendees as "attended" or "no show".
- **Event Notifications and Reminders**: Send notifications and reminders to users based on their event participation and preferences. Reminders include event details and links to add events to Google Calendar.
- **Event Rating and Reviews**: Users can rate and review events they've attended, providing feedback for organizers and helping other users make informed decisions.
- **Meetup Type Selection**: When creating a meetup, users can select the type of event (online or offline). For online events, integrate with Microsoft Graph APIs for Teams meeting invites, Zoom APIs for Zoom meeting invites, and Slack APIs for Slack channel invites.
- **Subcategories**: Allow users to select subcategories under main categories to further refine their interests and meetup suggestions.
- **Find Friends**: Users can discover and connect with nearby accounts who share similar interests. Users can send friend requests and accept incoming requests to build their network within the app.

## Getting Started

To get started with Sahana, follow these steps:

```bash
# Navigate to the project directory
cd sahana-meetup-app

# Install dependencies
npm install

# Set up environment variables:
# Create a .env file and add your Firebase, Google API, and other necessary configurations.

# Start the development server
npm start

```
## Documentation

For detailed documentation on installation, usage, and customization, please refer to the [Wiki](wiki-link) section of this repository.

## Contributors

- Rajesh Sawant

## Issues

If you encounter any issues or have suggestions for improvement, please open an issue on the [Issues](issues-link) page.

## License

This project is licensed under the [MIT] License - see the [LICENSE](LICENSE) file for details.
