## Note: The app is still under developent

# SmartBus Tracker

In Jodhpur, where city buses provide an essential mode of transport, I noticed a gap in how information about bus routes is presented. Despite having access to bus stops near my location, it's not easy to get a clear picture of where each bus route can take me on a single platform. The current options are:

* Time tables or charts that lack a visual representation of the bus route.
* Basic map resources that only allow viewing one bus route at a time, making it cumbersome to plan a journey involving multiple buses.

To address this issue, I created SmartBus Tracker, a web application that helps users visualize multiple bus routes simultaneously on a map, making it easier to plan trips across the city.

## Features of the App

* Search for multiple bus routes and add them to the map.
* View multiple routes on the same map, highlighting potential connections.
* Remove routes from the map with a single click for easy customization.

**Note:** This app is currently under construction. Features and functionalities are being actively developed to enhance user experience and provide real-time updates.

## Technologies Used

I built this application using modern web technologies:

* Next.js for server-side rendering and efficient page management.
* Mapbox for interactive and customizable maps.
* React Map GL for seamless integration with Mapbox.
* Environment variables for secure API key management.

## Running and Deploying the App

### Getting Started

1. Install the required dependencies:
```bash
npm install
```

2. Add an API key for the map services in a .env file:
```env
MAPBOX_API_KEY=[your Mapbox API key here]
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to http://localhost:3000 to view the app.

5. Build the production version of the app for deployment:
```bash
npm run build
``` 
