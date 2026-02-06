


# For development (live client)
npm start

# OR to build and serve production build
npm run build


npx http-server build -p 8888



open a sperate terminal ->

cd server
npm install

# Start API server (uses nodemon)
npm run start    # runs server.js
# or start chat server
npm run dev      # runs chatServer.js



*SecondSpin — Resale Marketplace*

SecondSpin is a full-stack web platform that enables users to buy and sell pre-owned products easily. The application focuses on sustainability, affordability, and accessibility by promoting reuse and reducing unnecessary consumption.
Built during a hackathon, EX2NEXT demonstrates how technology can support a circular economy and make second-hand commerce simple and trustworthy.

*Problem Statement ->* 

Millions of usable products are discarded every year due to lack of accessible resale platforms.

*Key issues ->*

Difficulty finding trusted buyers/sellers
No centralized platform for local resale
High cost of new products for students and middle-income users
Growing environmental waste

*Our Solution ->*

SecondSpin provides a digital marketplace where users can:
List pre-owned items
Discover affordable second-hand products
Connect buyers and sellers directly
Promote sustainable consumption habits
The platform simplifies the resale process through a clean interface, smart search, and secure authentication.

*Key Features* ->

Secure user authentication using JWT

Add, edit, and delete product listings
Browse resale items easily
Search and filter products
Wishlist/Favorites system
Fully responsive design for mobile and desktop
Innovation & Uniqueness
Focus on sustainability-driven commerce
Lightweight and scalable MERN architecture
Beginner-friendly listing flow
Designed keeping students and local communities in mind
Foundation for location-based resale ecosystem

*Tech Stack->*

Frontend:

React.js, 
Next.js, 
HTML, 
CSS

Backend:

Node.js, 
Express.js

Database:

MongoDB

Authentication:

JSON Web Tokens (JWT)

System Architecture
User → Frontend (React/Next.js) → Backend API (Node/Express) → MongoDB
                        ↓
                 Authentication (JWT)

*Installation & Setup:*

Prerequisites ->

Node.js
npm
MongoDB

Steps
git clone https://github.com/dilip12git/EX2NEXT-resale-marketplace.git
cd EX2NEXT-resale-marketplace
npm install


Create a .env file:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=3000


Run the project:

npm run dev


Open:
http://localhost:3000

Demo Flow ->

User registers/login
User lists a resale product
Buyers browse/search items
Users save favorites
Product interaction between buyer & seller

Impact ->

Encourages reuse and reduces waste
Makes second-hand shopping accessible
Helps students earn from unused items
Supports sustainable consumption habits

Future Scope ->

Integrated payment gateway
Real-time buyer–seller chat
Location-based recommendations
Seller ratings & reviews
AI-based price suggestions

Team ->

Developed as a hackathon project by the EX2NEXT team.

Submission Note ->

This project was developed as part of a hackathon to demonstrate practical implementation of:

Full-stack development

Authentication & APIs

Database design

User-centric product thinking

SecondSpin represents a scalable idea that can evolve into a real-world resale ecosystem.

![1ai](https://github.com/user-attachments/assets/2ddeef25-b256-49de-b754-09497e7d681a)

![2ai](https://github.com/user-attachments/assets/da433c6e-4b98-478f-b42e-0b774ea936af)

![2ai](https://github.com/user-attachments/assets/df1382dd-0a6c-417b-ae69-880fbc3f8a0c)

![4ai](https://github.com/user-attachments/assets/c90858e6-1852-4ed7-a591-2af61e2ed7b4)

![5ai](https://github.com/user-attachments/assets/26e61b0d-a635-4d13-93e6-767d6d2d0f69)

![6ai](https://github.com/user-attachments/assets/81d15795-32ec-4b4a-8ef1-6f7d6ef1e843)

![7ai](https://github.com/user-attachments/assets/ba793311-4151-40d7-b048-e5fc7a403228)

![8ai](https://github.com/user-attachments/assets/cec8beda-9d8c-4da3-ad56-3a65cec105e5)

![9ai](https://github.com/user-attachments/assets/2ab2e6fb-152d-4a2d-99f3-423fdf4aa40a)

![10ai](https://github.com/user-attachments/assets/be836c1b-9185-47ce-89db-d227b9e6456d)

![11ai](https://github.com/user-attachments/assets/adf94118-02ce-4ed2-838d-e421975f4bbe)

![12ai](https://github.com/user-attachments/assets/e18b5356-f4ba-4350-ba0a-8c7f934059b7)

![13ai](https://github.com/user-attachments/assets/1472d3f5-91e4-4d35-b53b-12d85a755a51)

![14ai](https://github.com/user-attachments/assets/09c479c3-3928-4eea-bb5e-12485d0d846e)

![15ai](https://github.com/user-attachments/assets/c26fb790-0497-4daf-85bc-155c311307d2)

![16ai](https://github.com/user-attachments/assets/04606fcd-0ace-4812-ae14-98057ab73231)

![17ai](https://github.com/user-attachments/assets/704de4db-065c-4481-b84c-90200a1a893a)

![18ai](https://github.com/user-attachments/assets/efc0e189-bfef-4153-a080-78ee3e65f914)

![19ai](https://github.com/user-attachments/assets/52b1e798-eda4-4c33-834c-91446f12d3f7)

![20ai](https://github.com/user-attachments/assets/bde0afa4-1d40-4efa-b306-67309482155a)
