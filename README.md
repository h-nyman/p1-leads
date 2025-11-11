# Micro CRM Leads (Project 1)

## Live Deployment
Live: https://p1-leads-ee7n.onrender.com

## Run Locally

### Setup Instructions
```sh
npm install

npm start
```
Open http://localhost:3000/ 

## Features
- Create and list leads
- Filter by status and search by name or company
- Update status

## Windows and macOS Notes
Open VS Code terminal. The commands are the same on both platforms.

## Reflection
I have built a Micro CRM Leads Tracker. In this tracker, you can add leads, search through the leads by using search terms, filter the leads by status and update them. The leads are stored in JSON files. The app is deployed to Render with ephemeral storage, that I’ve learned means that the data is lost when the service redeploys or restarts. 

I have learned to build a simple full stack CRUD-app. I now understand how to declare express routes as http handlers, and add logic such as data validation and persistence. I also realised that vanilla JS, HTML and CSS gets you very far.

As next improvements, I would utilize my skills from a previous study unit about databases, to migrate from the JSON file to a relational database. I have not interacted with SQL through NodeJS, but I would probably use Render’s managed Postgres to try this out. Missing features to add to this app would be the delete feature. Furthermore, I noticed the backend already supports changing the note of a lead through the PATCH method, but the frontend does not expose this functionality. To make a proper CRM, it needs to also support authentication of users, and perhaps even some kind of access control, so that for instance only admins would be able to delete leads. 
