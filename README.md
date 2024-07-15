# Telegram UI with React

## Overview

This project is a replica of the Telegram messaging application's user interface, developed for the Frontend React Developer assignment at BeyondChats. It aims to closely replicate the Telegram app’s appearance and functionality in both desktop and mobile views using ReactJS and Material-UI (MUI). The app retrieves chat and message data from specified API endpoints to display real-time information.

## Live Demo

You can view the live demo of the project [here](https://telegram-ui-mockup-teal.vercel.app/).


## Mobile View
<div>
<img src="src/images/img1.jpeg" alt="Mobile View" width="300"/>
<img src="src/images/img3.jpeg" alt="Mobile View" width="300"/>
<div>

## Desktop View
<img src="src/images/img4.png" alt="Mobile View" width="600"/>



## Project Structure

The project is organized as follows:

```
/src
  /components
    ChatList.js
    ChatMessages.js
    Drawer.js
    Header.js
    ToggleButton.js
  /pages
    ChatPage.js
  /services
    api.js
  /styles
    styles.css
  App.js
  index.js
  ...
```

## Kwy Features

- **Chat List:** Displays a list of chats fetched from the provided API endpoint.
- **Chat Window:** Displays messages for a selected chat, fetched from the provided API endpoint.
- **Material-UI Integration:** Uses Material-UI components for a polished and modern UI.
- **Real-time Data:**: Utilizes API endpoints to display real-time chat and message data.

## Technologies Used

- **ReactJS**
- **Material-UI (MUI)**
- **Axios**
- **React Router**


## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Saichandra2520/telegram-clone
   cd telegram-clone
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Run the Application**:
   ```bash
   npm start
   ```

4. **Build the Application**:
   ```bash
   npm run build
   ```

## Deployment

The project has been deployed using Vercel. You can view the live version of the application [here](https://telegram-ui-mockup-teal.vercel.app/).
