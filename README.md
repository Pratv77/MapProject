# Mapbox Event Finder

This web app allows computer science students to easily find upcoming events related to their field. The app uses the Mapbox API to display events on a map and provides users with a search function to filter events based on different criteria.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [APIs](#apis)
- [Contributing](#contributing)
- [License](#license)

## Features

- Display events on a Mapbox map
- Filter events based on location, date, and event type
- Add new events to the map
- Edit or delete existing events
- User authentication to secure event adding and editing
- Responsive design for desktop and mobile devices

## Installation

To install and run the app locally, follow these steps:

1. Clone the repository:
`git clone https://github.com/Pratv77/MapProject.git`

2. Install the dependencies:
`cd mapbox-event-finder`
`npm install dotenv express axios moment nodemon`  
> Note: need to add the full list of dependencies*


3. Create a `.env` file and add your Mapbox API key and MongoDB connection string:

`MAPBOX_API_KEY=<your-mapbox-api-key>`
`MONGODB_URI=<your-mongodb-connection-string>`

4. Run the app: `npm start`

The app will be running at `http://localhost:3000`.

## Usage

To use the app, simply navigate to the home page and browse the events on the map. You can use the search function to filter events based on location, date, and event type. To add a new event, click on the "Add Event" button and fill out the form. To edit or delete an existing event, click on the event marker on the map and select the appropriate option.

## APIs

The app uses the following APIs to retrieve event data:

- Eventbrite API: https://www.eventbrite.com/platform/api
- Meetup API: https://www.meetup.com/meetup_api/
- Facebook Events API: https://developers.facebook.com/docs/graph-api/reference/event/

## Contributing

Contributions to the project are welcome! If you find a bug or have a feature request, please open an issue or submit a pull request.

