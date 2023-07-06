Website: https://delightful-pithivier-78bddc.netlify.app/

## Project Name: Metropolitan Museum of Art Collection Viewer
![image](https://github.com/wtse1225/Artwork-Gallary-MyApp/assets/105259859/b0a04f7f-1556-40f8-ab9e-a86a42388ee5)

### Objective:
Develop a modern, responsive user interface for searching and viewing data on the publicly available Metropolitan Museum of Art Collection API. The project will utilize React, Next.js, and React Bootstrap to create a solution that allows users to explore and interact with the museum's collection.

### Technologies Used:
- React
- Next.js
- React Bootstrap
- SWR (Stale-While-Revalidate)
- Bootstrap

### Project Description:
The Metropolitan Museum of Art Collection Viewer is a web application that provides users with a user-friendly interface for searching and viewing artwork from the museum's collection. The application leverages the power of React, Next.js, and React Bootstrap to create a responsive and interactive experience.

### Key Features:
1. Creating a Next App & Adding 3rd Party Components:
- Setting up a new Next.js app with the necessary dependencies.
- Installing additional modules, including SWR, Bootstrap, and React Hook Form.
- Configuring the CSS files to ensure proper rendering of Bootstrap components.

2. MyApp, NavBar & Layout Components:
- Creating a MainNav component to display a navigation bar with the student's name and links to the Home and Advanced Search pages.
- Implementing a Layout component to provide a common layout structure for the application.
- Configuring MyApp to use the Layout component and defining the global fetcher for SWR.

3. ArtworkCard & ArtworkCardDetail Components:
- Developing the ArtworkCard component to display information about a specific artwork based on its object ID.
- Utilizing SWR to fetch data from the Metropolitan Museum of Art Collection API and handle error conditions.
- Rendering a Bootstrap Card component with details such as the artwork's image, title, object date, classification, and medium.
- Adding a button within the ArtworkCard to navigate to the detailed view of the artwork using Next.js's Link component.
- Creating the ArtworkCardDetail component, which is similar to ArtworkCard but includes additional information such as the artist's name, credit line, and dimensions.

The Metropolitan Museum of Art Collection Viewer aims to provide a seamless and visually appealing experience for users to explore the museum's collection. By leveraging the power of React, Next.js, and React Bootstrap, the application offers a modern and responsive interface for searching and viewing artwork.
