# EasyText – Text Utility Platform (Frontend)

EasyText is a frontend-only, scalable single-page web application built using HTML, CSS, JavaScript, and React. The project provides multiple text-related utility tools through a modular, feature-based architecture and focuses on frontend engineering, scalability, and clean application structure.

This repository contains only the client-side implementation and is designed to be backend-ready for future API integration.

## Features

- Multiple independent text utility tools, including:
  - Blog title, summary, and content utilities  
  - Paragraph text utility  
  - Social media post content utility  
  - Promotional content utility  
  - YouTube title and description utilities  
  - Job role and text formatting utilities
- Modular, feature-based routing using React Router
- Responsive and accessible UI design
- Environment-based configuration for backend readiness
- Production-ready build and deployment setup

## Tech Stack

- **Languages:** HTML, CSS, JavaScript (ES6+)
- **Framework & Libraries:** React, React Router
- **Styling:** Chakra UI, Tailwind CSS, Custom CSS
- **Build Tool:** Vite
- **Deployment:** Netlify (SPA routing configured)

## Architecture Overview

- **Single Page Application (SPA):** All features are handled on the client side with seamless navigation.
- **Modular Design:** Each text utility is implemented as an independent route/component, enabling easy scalability and feature expansion.
- **Context API:** Used for global configuration management (e.g., environment-based backend URL).
- **Backend-ready Structure:** The application is structured to support future API integration without requiring architectural changes.

## Important Note

This project is a frontend-only implementation.  
There is no backend or AI logic included in this repository. The application is intended to act as a frontend client that can integrate with external APIs in the future.
