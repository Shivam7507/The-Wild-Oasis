🌴 The Wild Oasis: Full-Stack Hotel Booking System
The Wild Oasis is a comprehensive hotel booking system that includes:

A customer-facing website for booking stays.
An internal management app for hotel staff to manage reservations and customer data.
✨ Features
Customer-Facing Website:
Room Listings: View available rooms with images, pricing, and features.
Booking System: Reserve rooms in real-time with date and guest selection.
User Authentication: Secure login and account management.
Payment Integration: Process payments seamlessly (add details if implemented).
Internal Management App:
Dashboard: Overview of current reservations, availability, and revenue metrics.
Customer Management: View and update customer information.
Reservation Management: Add, modify, or cancel bookings.
🛠️ Tech Stack
Frontend:
React.js: Dynamic UI for customer and admin interactions.
Next.js: Server-side rendering for faster load times and SEO optimization.
Tailwind CSS: Customizable and responsive styling.
Backend:
Supabase:
Database: PostgreSQL for storing reservations, customers, and room data.
Authentication: Secure user login and session management.
🚀 Getting Started
Prerequisites:
Node.js (v16+ recommended)
Supabase Account
Git
Installation:
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/the-wild-oasis.git
cd the-wild-oasis
Install dependencies:

bash
Copy code
pnpm install
Configure environment variables:
Create a .env file in the root directory and add:

env
Copy code
NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_KEY=your_supabase_anon_key
Start the development server:

bash
Copy code
pnpm dev
The app will be running at http://localhost:3000.


