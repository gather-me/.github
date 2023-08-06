## Hi there 👋

Graduating Project of Istanbul Technical University - Computer Engineering Department (2023)

Social media for Events. Gather.


This project set out with the goal of implementing social media for events. One of the scopes of this project is aimed to make users aware of upcoming events, to enable users to create events, suggest activities according to the tastes of users, suggest activities according to the common tastes of other users selected by users, display activity movements of other users and to create an interactive environment.

With this application, users are going to be instantly informed about all kinds of events such as concerts, festivals, parties, sports competitions, and meetings, so no one is going to be deprived of their favorite activities. Users are going to specify the types of activities they enjoy in the application and are going to be able to easily view such activities on their homepage.

With this application, users are going to be able to create events and customize these events with features such as public/private, paid/free, and unlimited capacity/limited capacity. In this way, users are going to be able to double their level of fun by organizing events that suit their style.

Along with the event recommendation system, which is another purpose of the application, the previously specified interests of the user are going to be used to make user-specific recommendations. In this way, each user is going to be able to see the activities according to their interests more prominently and are not going to be deprived of those activities.

One of the most essential features of the project is the system of suggesting events according to the common interests of a user group. The purpose of this system is to suggest activities based on the common interests of a group of friends and find the right activity for them that everyone will enjoy. This feature is aimed to recommend to users who have difficulty finding the right activity that is going to make everyone happy.

Another feature within the scope of the project is to offer users an interactive environment. Users are going to be able to follow other users they like and want to be informed about, and they are going to be able to see the activities of the people they follow on their homepage. In this way, users are not going to miss the movements of other users they like.

Along with all these features, it is aimed to appeal to people who do not want to miss any event, who want to participate in different activities, who are looking for an activity proposal according to their interests, and who have difficulty finding a common activity with their friend group, who want to see the events their friends attend, who want to create their event and find participants in their activities.

---

# Event Management Application

This project aims to solve various problems related to event participation and organization by developing an Event Management Application. The application provides features that allow users to create and participate in events of their choice, get event recommendations based on their interests, and find events suitable for groups of friends. The goal is to encourage event participation and create an interactive environment for users.

## Features

The application offers the following features:

- **Create Events**: Users can create any type of event they want, allowing them to tailor activities to their preferences.

- **Participate in Events**: Users can participate in events or request to join private events, ensuring they don't miss out on activities that interest them.

- **Follow Users**: Users can follow other users, enabling them to keep track of their friends' and loved ones' activities.

- **Event Suggestions**: The application suggests events to users based on their interests, making it easier for them to discover events they may like.

- **Group Event Recommendations**: Users can receive event recommendations for their group of friends, simplifying the process of finding events that appeal to everyone.

- **Homepage**: Users can follow the activities of the users they follow and see upcoming events that match their interests from their homepage. They can access all the content they may be interested in from this page.

## Microservices Architecture

The application is developed using the microservices architecture and consists of the following microservices:

1. **User Service**: Handles user-oriented operations such as user record creation, managing follow/unfollow operations, and updating user information.

2. **Event Service**: Manages event-oriented operations such as event creation, participation, and organization.

3. **Recommendation Service**: Hosts user interests and provides event suggestions based on those interests. It also suggests events to a group of users with common interests.

4. **Auth Service**: Handles user authentication and authorization during login, registration, and when sending requests to other services.

5. **API Gateway Service**: Acts as a gateway for external requests to access other services. All external requests must pass through the Gateway Service; there is no direct access to the microservices.

## Engineering Standards and Constraints

The project adheres to the following engineering standards:

1. **Reliability**: The system operates consistently and reliably under expected conditions, with considerations for failure rates, redundancy, and fault tolerance.

2. **Performance**: Performance standards ensure that the system meets desired functionality, efficiency, and effectiveness. Metrics and benchmarks are defined for validation.

3. **Compatibility**: Compatibility standards ensure seamless integration with other systems, following industry protocols and specifications.

4. **Ethical Considerations**: The project adheres to ethical principles and professional codes of conduct, including privacy, data protection, and ethical technology use.

Constraints considered during development:

1. **Schedule**: The project followed a realistic timeline for completion, meeting specified deadlines while maintaining quality.

2. **Usability**: User experience and usability were prioritized, with user testing and feedback incorporation.

3. **Maintainability**: A focus on designing a system that is easy to maintain and troubleshoot, using modular designs and standardizing components.

---

This `README.md` file provides an overview of the Event Management Application, its features, microservices architecture, and the engineering standards and constraints applied during development.
