# WanderLust

**WanderLust** is a travel-focused web application designed to help users explore various destinations, create itineraries, and share their travel experiences with others. The application offers a rich user experience, including features like search, filtering, and user-generated content.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [API Endpoints](#api-endpoints)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Destination Search**: Search for destinations by name, type, or region.
- **Itinerary Planning**: Create and customize itineraries based on personal preferences.
- **User Accounts**: Register and log in to save favorite destinations and itineraries.
- **Reviews and Ratings**: Share your travel experiences and rate different destinations.
- **Responsive Design**: Optimized for various devices, from mobile to desktop.

## Installation

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [MongoDB](https://www.mongodb.com/) (for database) Note-Currently MongoAtlas is used as database which is a cloud data base.
  if you want to run it in your local system you should replace the dburl in app.js with this 'mongodb://127.0.0.1:27017/test'.
- [Git](https://git-scm.com/)

### Clone the Repository

```bash
git clone https://github.com/crazypunk08/WanderLust.git
cd WanderLust
```
### Install Dependencies
```bash
npm install
```
### Environment Variables
Create a .env file in the root directory and add the following:
PORT=3000
MONGODB_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/wanderlust?retryWrites=true&w=majority
SESSION_SECRET=your_secret_key
API_KEY=your_api_key

Replace <username>, <password>, and your_secret_key with your MongoDB credentials and desired session secret.

## Start the application using npm:
```bash
npm start
```
Now got to your fav browser and check it on this URL  http://localhost:3000/listings







