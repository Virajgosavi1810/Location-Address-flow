Project Description
This assignment demonstrates a location/address flow using React, TypeScript, and TailwindCSS. It includes functionalities for managing addresses, selecting address types, and integrating with maps and geocoding utilities.

Execution Steps:-
Clone the Repository Clone this project to your local machine:
git clone <repository-url>

Set Up Environment
Add a .env file in the root directory.
Include necessary keys like MAPS_API_KEY.
Install and Run:-
To install all project dependencies:-  npm install
To start the development server and view the app:-   npm run dev
The app will be accessible at http://localhost:5173.
To implement additional features or customizations, then build for production, use:-   npm run build
To run tests that ensures functionality, use:- npm test

Features Implemented:-
Address Management
A component (AddressManagement) to manage user addresses.
Includes forms for entering address details and selecting address types.
Location Permission Modal
A modal to request and handle location permissions from users.
Map Integration
LocationMap component displays user location or selected address on a map.
Uses geocoding for address-to-coordinates conversion.
Reusable Components
Modular components like AddressForm, AddressTypeSelector, and AddressDetails for flexibility and reusability.
Context API for State Management
LocationContext provides centralized state management for location-related data.
Utility Functions
Geocoding utility (geocoding.ts) for converting addresses to geographic coordinates.

