# ExplorerNow Mobile App

**ExplorerNow** is a mobile application designed to help users find places in their vicinity and organize data so that the end-user has easy access to nearby locations. The app retrieves data from the internet and displays it in a user-friendly table format. Users can view place details, images, ratings, and get navigation directions through Google Maps. Users can also adjust the search radius from 1km to 10km using a slider.

## Features

- **Location-Based Search**: Retrieves and displays places within a 10km radius of the user's current location.
- **Adjustable Distance**: Users can change the search radius from 1km to 10km using a slider.
- **Interactive Table**: Shows a table with place details including name, city, description, image, rating, and a link for navigation.
- **Image Viewing**: Users can click on images to view them in full screen.
- **Filters**: Allows users to filter places by distance and rating.
- **Pagination**: Supports pagination to browse through large sets of data.
- **Navigation**: Provides a link to open the place location in Google Maps.

## Project Structure

- **`lib/`**
  - `main.dart`: Entry point of the application, setting up the app and its theme.
  - `ListElement.dart`: Defines the `ListElement` class for managing individual tasks in the To-Do List.
  - `Menu.dart`: Manages task addition, notification creation, and task removal.
  - `notice.dart`: Contains the `createNotice` function for generating notification elements.
  - `widgets/`
    - `image_viewer.dart`: Contains the `ImageViewer` widget for displaying images.
    - `location_service.dart`: Manages location retrieval and distance calculations.
  
- **`assets/`**
  - `images/`: Directory for storing images used in the application.

## How It Works

1. **Fetching Data**: The app fetches place data from a remote server using an HTTP GET request.
2. **Displaying Data**: Data is displayed in a table with columns for name, city, description, image, rating, and a link to Google Maps.
3. **Adjustable Distance**: Users can use a slider to adjust the search radius from 1km to 10km.
4. **Filtering and Sorting**: Users can filter results based on distance and rating and sort them accordingly.
5. **Pagination**: Data is paginated to improve user experience with large datasets.
6. **User Interaction**: Users can click on table rows to view descriptions, tap on images to view them in full screen, and use the slider to adjust the search radius.

## Setup

1. **Clone the Repository:**
   ```bash
   
   git clone https://github.com/your-username/explorer-now.git
