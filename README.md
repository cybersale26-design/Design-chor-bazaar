Digital Chor Bazaar 🏺🛍️

Digital Chor Bazaar is a modern web marketplace inspired by Mumbai’s legendary Chor Bazaar, one of India’s oldest and most iconic flea markets.

This project digitizes the traditional offline bazaar experience and brings it online with a hybrid vintage + modern + minimal UI.

---

🌍 Project Vision

Chor Bazaar has existed for over 150 years, famous for:

- Rare antiques
- Vintage collectibles
- Old phones and electronics
- Books and magazines
- Clothes and shoes
- Car parts and scrap deals
- Friday market bargain hunting

This platform aims to preserve that culture while enabling digital access for global buyers.

---

✨ Features

Buyer Features

- Responsive homepage
- Product listings
- Category browsing
- Friday Market deals page
- Product detail pages
- Make Offer API (MVP haggling system)
- Mobile-friendly design

Product Categories

- Antiques
- Clothes
- Shoes
- Books
- Phones
- Car Parts
- Cheap Finds

Special Marketplace Experience

- Vintage-themed branding
- Friday flash sale concept
- Chor Bazaar storytelling

---

🛠 Tech Stack

Frontend

- Next.js
- React
- Tailwind CSS

Backend

- Next.js API Routes

Deployment

- GitHub
- Vercel

---

📁 Project Structure

digital-chor-bazaar/
│
├── app/
│   ├── page.tsx
│   ├── products/
│   ├── friday-market/
│   ├── about/
│   └── api/
│
├── components/
│   ├── Navbar.tsx
│   ├── Hero.tsx
│   ├── ProductCard.tsx
│   └── Footer.tsx
│
├── data/
│   └── products.ts
│
├── public/
├── package.json
└── README.md

---

🚀 Installation

Clone repository:

git clone https://github.com/cybersale26-design/Design-chor-bazaar.git

Install dependencies:

npm install

Run development server:

npm run dev

Open:

http://localhost:3000

---

API Example

Make Offer Endpoint

POST /api/offer

Request:

{
  "product": "Vintage Gramophone",
  "offer": 3000
}

Response:

{
  "success": true,
  "message": "Offer received"
}

---

🔮 Future Improvements

Planned Version 2:

- Real product images
- AI-powered haggling engine
- Seller dashboard
- Admin panel
- Search and filters
- Payment gateway integration
- Escrow system
- Logistics and shipping tracking
- Multi-vendor marketplace

---

👨‍💻 Developer

Built by Cyber Santosh
GitHub: https://github.com/cybersale26-design

---

📜 License

This project is for educational and portfolio purposes.
