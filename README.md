# Yamaha
An end-to-end digital experience concept for Yamaha Motor. Features a dynamic showroom, localStorage checkout simulation, and a CRM service dashboard.

🏍️ Yamaha Motor: Digital Experience Concept
A premium, immersive front-end web experience concept for Yamaha Motor Turkey. This project serves as an end-to-end digital customer journey prototype, featuring an interactive showroom, a seamless checkout simulation, and a post-purchase service tracking dashboard.

🚀 About the Project
This project demonstrates advanced UI/UX development skills by creating a cohesive, multi-step user journey. Rather than just a static landing page, the application simulates a real-world e-commerce and CRM flow. It utilizes Vanilla JavaScript and the browser's Web Storage API to maintain state across different pages, seamlessly transitioning the user from product discovery to purchase, and finally to post-purchase ownership.

✨ Key Features & User Journey
🎬 Immersive Video Hero: A captivating first impression featuring a full-screen, brightness-filtered HTML5 video background that immediately immerses the user in the Yamaha lifestyle.

🏍️ Dynamic Showroom Filtering: Users can seamlessly filter the motorcycle catalog (e.g., Hyper Naked, Supersport, Sport Heritage) using Vanilla JavaScript, without requiring page reloads.

🛒 Mock E-Commerce Flow: Clicking "Buy Now" triggers a custom function that saves the selected motorcycle's specifications (engine, power, price) to the browser's localStorage and smoothly transitions the user to the checkout portal.

💳 Streamlined Checkout: A minimalist, grid-based order summary and payment form interface designed for high conversion rates and a premium brand feel.

🔧 "My Bike" CRM Dashboard: A dedicated post-purchase user dashboard ("Motorum | Yamaha Servis Takip") displaying critical motorcycle stats like total mileage, warranty status, estimated tire life, and a chronological service history table.

🎨 Premium Dark Aesthetic: Crafted using a custom CSS root variable system (--yamaha-blue: #003580), glassmorphism effects (backdrop-filter), and 'Inter' typography for a modern, high-speed aesthetic.

🛠️ Technology Stack
Frontend Structure: Semantic HTML5

Styling: CSS3 (Custom Properties, Flexbox, Grid, Glassmorphism)

Interactivity & Data: Vanilla JavaScript (ES6+), Web Storage API (localStorage)

📂 Project Structure
Plaintext
yamaha-digital-experience/
├── index.html           # Main landing page, video hero, and dynamic showroom
├── checkout.html        # Order summary and payment processing UI
├── my-bike.html         # Customer dashboard for service and maintenance tracking
├── yamaha-video.mp4     # Background video asset for the hero section
├── faviconn.jpg         # Brand favicon 
└── README.md            # Project documentation
⚙️ How to Run
Clone the repository to your local machine.

Ensure all HTML and media files (yamaha-video.mp4, images) are in the correct directory.

It is highly recommended to run this project via a local development server (like VS Code's Live Server extension) to ensure the background video and localStorage features function correctly without CORS or file protocol restrictions.

Start from index.html to experience the full journey!

👨‍💻 Developer
Servet Can Kılınç
Front-End Software Development Student @ Ege University
