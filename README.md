# AirBnB Clone Project

## Overview
This project is a full-stack clone of the AirBnB platform, created as part of the Software Engineering track at ALX. The goal is to build a robust web application that allows users to list, search, and book vacation rentals, similar to the real AirBnB.

## Objectives
- Understand and implement core backend concepts including data modeling, ORM, RESTful API design, and authentication.
- Build a scalable and responsive frontend that integrates seamlessly with the backend APIs.
- Follow software engineering best practices, including version control, modular design, and clean code.

## Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: Python3, Flask/Django (based on project stage)
- **Database**: MySQL or PostgreSQL
- **APIs**: Django REST Framework / Flask RESTful
- **Version Control**: Git & GitHub
- **Deployment**: GitHub Pages / Heroku / Vercel (as applicable)

## Project Structure
This repository will contain:
- All backend logic and database models
- Frontend interface and templates
- API endpoints and integration
- Documentation and feature roadmap

## 🖌️ UI/UX Design Planning

### 🎯 Design Goals

The UI/UX design for this project focuses on building a **clean, intuitive, and responsive interface** that mimics the user experience of platforms like AirBnB. The main goals are:
- Make searching and booking properties simple and quick
- Present property information in an attractive and organized way
- Optimize the flow from browsing to booking
- Ensure the interface is mobile-friendly and accessible

### 🌟 Key Features to Implement

- Property search with filters (location, dates, price, guests)
- List/grid view of available properties
- Detailed view with image gallery and amenities
- Streamlined booking/checkout process
- User account and login UI
- Mobile responsive design
- Consistent navigation and branding

### 📄 Primary UI Pages

| Page                   | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| **Property Listing View** | Displays a list or grid of available properties with thumbnails, prices, and short descriptions. Filter and sort options help users find relevant results. |
| **Listing Detailed View** | Full detail page for a selected property. Includes image carousel, amenities, host info, price breakdown, and a booking CTA. |
| **Simple Checkout View**  | Minimal form to collect guest details, payment method, and confirm the booking. Displays price summary and cancellation policy. |

### 💡 Importance of a User-Friendly Design

A user-friendly UI is vital for the success of a booking platform because:

- 🧭 **Ease of Navigation** increases user retention and engagement
- 🛒 **Simplified Checkout** encourages higher booking conversions
- 📱 **Responsive Design** ensures accessibility across devices
- 🧠 **Intuitive Interactions** reduce user frustration and help achieve goals quickly
- 🎯 **Clear Visual Hierarchy** guides the user from discovery to booking seamlessly

By focusing on intuitive layouts and smooth interactions, this project aims to deliver a satisfying and efficient booking experience for all users.

### 🖼️ Design System Exploration (Figma)

Below are the design tokens and visual properties extracted from the mockup in Figma.

#### 🎨 Color Styles

- **Primary Color:** #FF5A5F (Airbnb Coral)
- **Secondary Color:** #767676 (Medium Gray)
- **Background Color:** #FFFFFF (White)
- **Card Background:** #F7F7F7 (Light Gray)
- **Text Primary:** #222222 (Dark Gray)
- **Text Secondary:** #717171 (Light Gray)
- **Highlight Color:** #00A699 (Turquoise)

#### 🔤 Typography

| Element          | Font Family     | Font Weight | Font Size |
|------------------|------------------|-------------|-----------|
| Headings (H1–H3) | `Circular Std` or `Inter` | Bold (700)   | 32px / 24px / 20px |
| Body Text        | `Circular Std` or `Inter` | Regular (400) | 16px               |
| Small Text       | `Circular Std` or `Inter` | Regular (400) | 14px               |
| Button Text      | `Circular Std` or `Inter` | Semi-Bold (600) | 16px           |

> *Note: If `Circular Std` is not available, `Inter` or `Poppins` can be used as a clean alternative for web.*

---

### 🧠 Why Identifying Design Properties Matters

Understanding and documenting the visual properties of a mockup is essential for:

- ✅ **Design consistency**: Ensures all developers and designers use the same visual rules
- 🎨 **Accurate implementation**: Reduces visual bugs and pixel mismatch between design and final product
- 📐 **Scalable UI**: Standardizing typography, color, and spacing allows reusable UI components
- 🤝 **Better collaboration**: Makes it easier for teams to speak the same design language
- 🔍 **Accessibility & UX**: Proper color contrast, font sizing, and hierarchy improve usability for all users

By extracting these properties from the Figma file, we maintain a unified design standard across the entire project.

## Author
Gemechu Bekele
