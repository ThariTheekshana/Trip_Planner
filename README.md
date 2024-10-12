# Trip Planner

TripPlanner is a Swift-based iOS app that enables users to search for locations, view them on the map, and get directions from their current location to the selected destination. Built using SwiftUI and MapKit, it offers a seamless experience with various map-related features, including route plotting and Apple Maps integration.

Features

	•	Search Locations: Users can search for any location using a search bar, which displays relevant search results on the map.
	•	Map Annotations: Displays location markers for the user’s current position and search results. Custom annotations are used to differentiate the user’s location.
	•	Get Directions: Provides step-by-step directions from the user’s current location to the selected destination, with the route displayed on the map.
	•	Apple Maps Integration: Allows users to open the selected location directly in Apple Maps and access the “Look Around” feature (where available).
	•	Dynamic Camera Positioning: Automatically adjusts the map view to focus on the route and destination.

Code Overview

ContentView.swift

	•	Manages the main map interface, including user location, search functionality, and route plotting.
	•	Contains the searchPlaces() method to search for locations and fetchRoute() to calculate directions.
	•	Utilizes various map controls, annotations, and overlays to enhance the map experience.

LocationDetailsView.swift

	•	Displays details about the selected location, including its name and address.
	•	Offers options to open the location in Apple Maps or get directions within the app.
	•	Integrates the “Look Around” preview, using MapKit’s MKLookAroundScene to show street-level views where available.

Requirements

	•	iOS 17 or later
	•	Xcode 15 or later

