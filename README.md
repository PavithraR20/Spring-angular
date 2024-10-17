# Spring-angular
Spring boot and angular projects
Task-2:
--------
This application is a simple Event Scheduler that allows users to create and view daily events with start and end times. The stack consists of a Spring Boot backend and an Angular frontend.

Features
Create Event: Users can create events by specifying a name, start time (0-23), and end time (1-24).
View Events: All scheduled events are displayed in a list.
Conflict Handling: Events cannot overlap. Additionally, the start time must be earlier than the end time.
Tech Stack
Backend:
--------
Java, Spring Boot (REST API)
Hibernate for database management
Mysql
Frontend:
---------
Angular for the user interface
Bootstrap for styling

Commands used:
--------------
npm install -g @angular/cli
ng new task2-frontend --no-standalone
npm install bootstrap
ng g class events
ng g c event-list
ng g s event
ng g c create-event

