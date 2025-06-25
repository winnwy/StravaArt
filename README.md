# Strava Art AI Generator

 <!-- Replace with a real GIF or screenshot of your app -->

An intelligent web application that automatically generates a route based on the shape of an object in a picture.


## ✨ Features

-   **Image Upload**: Upload any PNG or JPG image.
-   **Semantic Object Recognition**: Uses Google Cloud Vision API to automatically detect and label distinct objects in the image (e.g., "cat", "bicycle", "house").
-   **Interactive Shape Selection**: Presents the user with all identified objects, allowing them to choose which one to turn into a route.
-   **Vector Tracing**: Converts the pixels of the selected object into clean, scalable vector paths using Potrace.
-   **Interactive Map**: Users can pan and zoom to select any area in the world to draw their art.
-   **Route Generation**: An advanced algorithm fits the vector shape onto the road and path network from OpenStreetMap.