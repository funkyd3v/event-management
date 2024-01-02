## This is a REST API project for event management.

## Description
API is developed with the latest version(10.x) Laravel framework and uses its features. Here is the list of what is implemented.
1. The user must be logged in to create an event or attend an event.
2. Authentication and Authorization. Sensitive routes are protected.
3. CRUD(create, read, update, delete) system.
4. Rate limit is implemented for certain routes.
5. Notify the attendees of events via sending email that will start within 24 hours. Laravel `Schedule` feature is used for checking events every day and notifying using the `Notification` feature.
