#### Site-Goals

The website aims to help users organise their events or TO-DO items.
The website is relatively simple to use, and users can get from a part to another very easily and intuitivly.  

The site aims to provide customers with a simple and easy way to organise their future events, add items, edit and delete their own items

### Agile Planning

This project was developed using agile methodologies by delivering small features in incremental sprints. 
The users’ stories are considered software features and most of them  have been implemented in order to match the criteria.  
All projects were assigned to ToDo, prioritized under the labels, must have, should have, could have. They were assigned to sprints and story pointed according to complexity. "Must have" stories were completed first, "would haves" and then finally "would like". It was done this way to ensure that all core requirements were completed first to give the project a finished look and feel.

The Kanban board was created using github projects and can be located [here](https://github.com/users/adam-blakeney/projects/1). The issues list is also available [here](https://github.com/adam-blakeney/to-do/issues).


### Kanban image

Milestones
The project had 7 main Milestones:

- Milestone 1 - Base Setup

The base setup Milestone is for all stories needed for the base set up of the application. Without the base setup, the app would not be possible, so it was the first epic to be delivered as all other features depend on the completion of the base setup.

- Milestone 2 - Standalone Pages

The standalone pages Milestone is for small pages that did not have enough stories to warrant their own full epics. Instead of creating epics for tiny features, these small deliverables were all added under this epic.

- Milestone 3 - Authentication 

The authentication Milestone is for all stories related to the registration, login and authorization of views. This epic provides critical functionality and value as without it the users won’t be able to see the blog posts, post or register to the website.

- Milestone 4 – Subscribe to our newsletter

User with an account can subscribe to the website newsletter and they can be updated at all times with everything happening around the company from updates on the website to future events happening where they can attend and have a good time. 

- Milestone 5 – Get in touch with us

The get in touch with us button located in the first page has been created to offer users the possibility to get in touch with the management ASAP. The users can use this button If they are new visitors of this website / users with an account. Once the form has been completed and the send button was clicked, an email will be received by the Finesse managment which will be dealing with the enquire further. 

- Milestone 6 - Deployment 

This Milestone is for all stories related to deploying the app to heroku so that the site is live for staff and customer use.

- Milestone 7 - Documentation

This Milestone is for all document related stories and tasks that are needed to document the software development lifecycle of the application. It aims to deliver quality documentation, explaining all stages of development and necessary information on running, deploying and using the application.

User Stories
The following user stories (by epic) were completed:

- Milestone 1 - Base Setup

As a developer, I need to create the base.html page and structure so that other pages can reuse the layout.

As a developer, I need to create static resources so that images, CSS and JavaScript work on the website.

As a developer, I need to set up the project so that it is ready for implementing the core features.

As a developer, I need to create the footer with social media links and contact information.

As a developer, I need to create the navbar so that users can navigate the website from any device.

- Milestone 2 - Standalone Pages

As a developer, I need to implement a 404-error page to alert users when they have accessed a page that doesn't exist

As a developer, I need to implement a 500-error page to alert users when an internal server error occurs

As a developer, I need to implement a 403-error page to redirect unauthorised users to so that I can secure my views

As an Event Management online platform owner, I would like a home page so that customers can view information about the Finesse website. 

- Milestone 3 - Authentication Epic

As a developer, I need to implement allauth so that users can sign up and have access to the website’s features.

As a site owner, I would like the allauth pages customized to that they fit in with the sites styling

- Milestone 4 – Subscribe to our newsletter

As a site owner, I would like to keep all the website users informed with everything happening around the company such as future events.
As a developer I want to provide an easy way for my users to subscribe to the newsletters and limit the users to use the subscribe button just one time with an email address. This function has been implemented in order to prevent users from supra solicitate the system with the same email address more then once. 

- Milestone 5 – Get in touch with us

As a developer I want to allow users to be able to get in touch with the site owners via email.
As a site owner I want users to complete a form and be able to detail what type of events they are looking for and receive an email with their inquiries. 
As a site user I want to be able to get in touch with the site owners asap and therefore completing the form will be very easy. 

- Milestone 6 - Deployment Epic

As a developer, I need to set up white noise so that my static files are served in deployment

As a developer, I need to deploy the project to heroku so that it is live for customers

- Milestone 7 - Documentation

Also, after this has been completed, I have decided to add a profile section where users can add, or edit their profile, and alow them and other users to preview their profile. 

On the blog page I as a developer, implemented an edit and delete button, so users can edit or delete their own posts.

Tasks:

Complete readme documentation.
Complete testing documentation write up.

# Testing 
- Test 1



Errors during deployment.

During deployment I have encounter some errors. Firstly the static files wasan't loading. Secondly the debug buton has been changed from os.environ('DEVELOPMENT') to True, to be able to see where the errors are coming from. After that, the debug button has been changed back into False, trying to check again if the deployment works, and after came back to os.environ('DEVELOPMENT').


Database-Design

The database was designed to allow CRUD functionality to be available to registered users when signed in. The user model is at the heart of the application as it is connected the blog side and linked by primary/foreign key relationships many to many and so on.

Security

Environment variables were stored in an env.py for local development and for security purposes to ensure no secret keys, api keys or sensitive information was added the repository. In production, these variables were added to the heroku config vars within the project.


