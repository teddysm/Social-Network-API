# Social-Network-API

This is a social network API

<br>

## Table of Contents

- [Description](#description)
- [Usage](#usage)
- [Links](#links)
- [Features](#features)
- [Installations](#installations)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)

<br>

## Description

- This is an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.

<br>

## Usage

- Use Insomnia or similar software to hit each GET, POST, PUT, DELETE routes
- Start the server with 'npm start'

  ![Screenshot](./Assets/Screenshot1.png)
  ![Screenshot](./Assets/Screenshot2.png)

<br>

## Links

Github Repo: https://github.com/teddysm/Social-Network-API
Video walkthrough: https://drive.google.com/file/d/1nFgl4rVLRg_N-vtLCBUvCjNlCRyTrQvP/view

<br>

## Features

- User can create, update and delete users, thoughts, friends and reactions to thoughts

<br>

## Installations

- Users need to install the dependencies with the command "npm i".
- Users need to install Insomnia or similar software.

<br>

## User Story

```md
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```

## Acceptance Criteria

```md
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```
