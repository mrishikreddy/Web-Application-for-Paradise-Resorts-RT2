# Paradise Resorts Web Application

Welcome to the **Paradise Resorts Web Application**, a static web app designed to showcase the luxurious offerings of Paradise Resort, located in the Maldives. This project provides a fully responsive, visually appealing, and user-friendly interface to explore room types, resort activities, special events, and customer support, all inspired by the serene beauty of the Maldives.

[Visit Live Project](https://mrishikreddy.github.io/rishik.tech.projects/webApp)

## Table of Contents
- [Project Description](#project-description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contact](#contact)

## Project Description
The Paradise Resorts Web Application is built to provide users with a seamless browsing experience to explore the resort's offerings. It features dedicated sections for over 4 room types, 2 resort activities, and 1 special event. The application is designed with a Maldives-inspired theme, optimized for performance, and fully responsive across devices.

The app includes a login page with a beach wave background video and a home page with intuitive navigation, showcasing the resort's luxurious accommodations, activities, and events.

## Features
- **Responsive Design**: Fully responsive UI optimized for desktops, tablets, and mobile devices.
- **Comprehensive Content**: Dedicated sections for:
  - Over 10 room types (e.g., Beach Villas, Water Villas, Family Suites, Garden Villas).
  - 8 resort activities (e.g., boat parachuting, swimming, boating, surfing).
  - 3 special events (e.g., Pro DJ Night, cultural showcases, sunset cruises).
  - Customer support page with contact information.
- **Maldives-Inspired Theme**: Visually appealing design with a beach wave background video and high-quality imagery.
- **Optimized Performance**: Streamlined navigation and optimized page load times for a smooth user experience.
- **Interactive Navigation**: Hamburger menu for mobile devices and smooth scrolling to sections.
- **Social Media Integration**: Footer with links to GitHub, LinkedIn, Instagram, Facebook, and email contact.

## Technologies Used
- **Next.js**: For server-side rendering and static site generation.
- **React.js**: For building reusable UI components.
- **HTML/CSS**: For structuring and styling the application.
- **JavaScript**: For interactivity and dynamic content.
- **FontAwesome**: For icons used in ratings and social media links.
- **CSS Modules**: For scoped and modular styling (`wahome.module.css`, `wa.module.css`).

## Project Structure
```
paradise-resorts/
├── src/
│   ├── app/
│   │   ├── webApp/
│   │   │   ├── page.js              # Login page component
│   │   │   ├── wa.module.css        # Styles for login page
│   │   │   ├── home/
│   │   │   │   ├── page.js          # Home page component
│   │   │   │   ├── wahome.module.css # Styles for home page
│   ├── public
├── package.json                     # Project dependencies and scripts
├── README.md                        # This file
```

## Installation
To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MRishikReddy/paradise-resorts.git
   cd paradise-resorts
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Run the development server**:
   ```bash
   npm run dev
   ```

4. Open `http://localhost:3000` in your browser to view the application.

## Usage
- **Login Page**: Enter an email and password to access the home page. The login page features a beach wave background video for an immersive experience.
- **Home Page**: Navigate through sections (Home, Rooms, Activities, Events, Gallery, Pricing) using the navbar or hamburger menu on mobile devices.
- **Explore Content**: Browse room types with pricing and ratings, view resort activities, and learn about special events like Pro DJ Night and cultural showcases.
- **Contact**: Use the footer links to reach out via email or social media.

## Contact
Designed and developed by Rishik Reddy. Reach out for questions or feedback:
- **Email**: [malerishikreddy@gmail.com](mailto:malerishikreddy@gmail.com)
- **GitHub**: [MRishikReddy](https://github.com/MRishikReddy)
- **LinkedIn**: [rishikreddym](https://www.linkedin.com/in/rishikreddym/)

Thank you for exploring the Paradise Resorts Web Application! Book your slice of paradise today.
