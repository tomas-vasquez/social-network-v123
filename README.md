# Open Social Network 

Repository is divided into three main packages:

- **api** This package contains API for Social Networking App, built with Nodejs, Express, GraphQL, Apollo Server and MongoDB with Mongoose.
- **frontend** Is a frontend for Social Networking App, built with React, GraphQL, Apollo Client and Styled Components.

## Features

- **Messenger** Real time messaging system.
- **Notifications** Get instant notification when someone follows/messages you or likes/comments on your post.
- **User Status** Check if user is Online or not in real time.
- **News Feed** Fresh posts from people you are following.
- **Explore** New Posts and People.
- **Follow** a particular user and get notified for their activity.
- **Personalize Profile** With profile/cover photo and personal posts.
- **Authentication & Authorization** with Password reset functionality.

## Demo

https://social-network-v123.vercel.app/

## Screenshots of the app

|             Login             |             Home              | Profile                       |
| :---------------------------: | :---------------------------: | ----------------------------- |
| ![](./assets/capture (1).png) | ![](./assets/capture (2).png) | ![](./assets/capture (3).png) |



## Configuration

### Replacing Mongo URL

Replace `MONGO_URL` value in `api/.env` file with your `mLab` database url or with local one.

### Replacing Cloudinary API Key

Grab `Cloud name` `API Key` and `API Secret` from Cloudinary dashboard and replace corresponding values inside `api/.env` file.

### Mail Provider

For password reset functionality you will need to replace Email Provider values also in `api/.env` file.
