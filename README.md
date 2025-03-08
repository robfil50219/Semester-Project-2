# Auctionary - Bid Smart, Win Big

Auctionary is a user-friendly auction platform where you can browse, bid on, and list auction items with ease. The platform features a dynamic carousel for featured auctions, a powerful search system, and a streamlined interface for creating new listings.

---

## Features

- **Featured Auctions Carousel:**  
  Easily browse highlighted auction items through a dynamic carousel.

- **Search Functionality:**  
  Filter auctions in real-time using keywords for a tailored browsing experience.

- **Bid Smart:**  
  Place bids on active auction listings effortlessly.

- **Create New Listings:**  
  Registered users can create new auction listings using an intuitive form.

- **Responsive Design:**  
  Optimized for seamless access on desktops, tablets, and mobile devices.

---

## Technologies Used

- **HTML5:** For structuring the application.
- **CSS3:** For styling and responsive design.
- **JavaScript (ES6+):** For dynamic content and interactions.
- **Noroff Auction API:** For fetching and creating auction listings.
- **Netlify:** For deployment and hosting.

---

## Getting Started

### Prerequisites

- A modern web browser.
- Internet connection to interact with the external API.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/robfil50219/Semester-Project-2.git
   cd auctionary

2. **Run the application:**
   Open the index.html file in your browser, or if using a development server:

   npm install
   npm run start

   API Integration
Auctionary uses the Noroff Auction API to retrieve and create auction listings. The following endpoints are key:

GET /auction/listings:
Fetches all active listings.

POST /auction/listings:
Allows users to create new auction listings.

For more details, please refer to the Noroff API Documentation.

Functionality Overview
Carousel
The carousel dynamically displays up to 8 featured auction items. Users can navigate using "Previous" and "Next" buttons.

Search
A search bar enables users to filter auctions by title or description, with results updating dynamically.

Bidding
Each auction listing features a "Place Bid" button for users to bid on available items. Future updates will expand the bidding functionality.

Create New Listing
Registered users can create new auction listings by filling out a simple form, providing details such as title, description, and image URL.

Deployment
This project is deployed on Netlify. Visit the live version here: Auctionary.

License
This project is licensed under the MIT License.

Contact
For questions or feedback, please reach out via email:
robfil50219@stud.noroff.no


