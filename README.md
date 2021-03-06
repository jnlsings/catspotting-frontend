# Catspotting Project Proposal

## Overview

Inspired by the popular Reddit and Facebook communities, Catspotting is an app for cat lovers, by cat lovers! Users can post photos, descriptions, and locations of cats they spot out in the wild, as well as comment on other posts. They can even sign in using their social media credentials, and see all their posts on one page.

## Mockups

## User Stories

## Planned Workflow and Responsibilities

The Catspotting team will primarily use a centralized git workflow, with an emphasis on pair programming. Since there are only two of us, we will collaborate on planning in lieu of having a project manager/SCRUM master. Jordan has more experience using a centralized workflow, so she will be directing the workflow. We will each work on both ends of the project. In the case where one person has more experience, the other will pair with them to learn. All planning and task tracking will be handled through our Trello Team Board. The team has set a rough schedule and will meet over Zoom.

## Technologies

Front end:

-   React, React Router, React Hooks
-   Fetch for API calls
-   Material UI + media queries for responsivity

Back end:

-   Database
    -   PostgreSQL
    -   Django, Django Rest Framework
-   Functionality
    -   Python
    -   JWT authentication
    -   Social authentication
-   Connection between back and front ends
    -   Cors
    
Deployment:
-   Heroku on front and back ends

## Component Hierarchy

![Component Hierarchy](https://user-images.githubusercontent.com/57021062/75944467-6c4a4e80-5e5d-11ea-9608-0e5fb963e377.jpg)

## Models

![Models](https://user-images.githubusercontent.com/57021062/75944638-d7942080-5e5d-11ea-8b76-3da6443d7510.png)


## App Tiers

#### Bronze (MVP)

- Welcome page has animated cat, buttons for signup and login
- User can post photos of cats they spot, with an image url, and edit/delete posts
- User can comment on posts and edit/delete comments
- User manually adds author for posts/comments
- Page to see posts filtered by author, when author name matches username
- Responsive design using Material UI & media queries
- Social and JWT auth

#### Silver

- User can access their posts on a user profile type page
- User can only edit/delete their own posts and comments
- Images are uploaded files, not urls
- Google maps for location integration - user can pin the spotted cat's location
- More advanced color palette transitions

#### Gold

- Testing on front and back ends
- Integrate Google Maps to search posts by location/display map on post detail page

#### Platinum

- Map view showing all posts as pins, can click a pin and will show post
- Sort by cat? May need to update model to include space for a name/id
- Pin would then represent the cat's most recent location so as not to have duplicates
- Groups for cat spotters based on location
- Cat related resources linked
