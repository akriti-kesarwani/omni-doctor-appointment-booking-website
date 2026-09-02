## 🩺 Project Overview
**OmniDoctor** is a ReactJS-based telemedicine platform focused on providing users with seamless access to medical services online. From registration to live video consultation with doctors, everything is built into the user interface for a full-fledged experience, even without a backend API.

## ▶️ Steps to Run the Project

1. **Download the ZIP File:**  
   Extract it to your desired folder.

2. **Open a Terminal in the Project Directory**  
   Navigate to the extracted folder.

3. **Install Dependencies:**  
   npm install
   
Start the Development Server: npm run dev

Open in Browser:

Visit http://localhost:5173 (or the port Vite provides) to view the application.

👣 User Flow
Sign Up – The user registers using the sign-up page.

Health Details Page – User enters health data, stored in profile and local storage.

Profile Page – Displays editable user data with persistence.

Home Page – Includes modular components: About Us, Testimonials, Services, Why Choose Us, FAQ.

Services Page – Explore doctors and navigate to video consultation.

Video Consultation Page – Chat and face-to-face consultation.

Doctors Page – Filter and book appointments (saved in local storage).

My Appointments Page – View booked appointments.

Contact Us Page – User support and queries.

About Us Page – Information about the platform.

🧰 Tech Stack
Frontend: ReactJS

Build Tool: Vite

Routing: React Router DOM

State Management: React Hooks & Context API

Styling: CSS

Data: db.json for dummy data

Persistence: localStorage

🔗 Why No API Was Used?
No APIs were available during development, so we used db.json as a mock backend and stored user data and appointments in localStorage, providing persistence even after refreshing the page.

🎨 Design Decisions
Fonts: Clean and modern fonts for readability.

Colors: Blue (trust), Green (health), White backgrounds for clarity.

Layout: Responsive and mobile-friendly using Flex/Grid.

Components: Modular and reusable UI components.

🚀 Future Scope
Backend integration (Firebase, Node.js)

Authentication (JWT/OAuth)

Secure database (MongoDB/PostgreSQL)

WebRTC video call integration

Appointment reminders and notifications

✅ Summary
OmniDoctor provides a complete prototype experience of a telemedicine platform using ReactJS. It simulates a real-world workflow with local data handling and presents a foundation ready for API and backend integration.

