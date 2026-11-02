# 🥖 Maison Marcel Artisan Bakery

A modern, responsive website for **Maison Marcel**, a fictional neighborhood boulangerie, built as a **Future Interns Full Stack Web Development** task (local business website). Customers can browse the bakery menu, order for pickup or delivery, check what's coming out of the oven, reserve a café table, and track their orders.

🔗 **Live Demo:** [shimmering-pony-4d490b.netlify.app](https://shimmering-pony-4d490b.netlify.app)

---

## ✨ Features

- **Boutique home page**: hero section, popular picks, and quick links to every part of the site
- **Bakery menu**: 14 products across Sourdough, Pastries, Savory, Coffee, and Pantry, with category filters, dietary filters, and search
- **Product details**: tasting notes, flour blend, fermentation time, crust and crumb profile, pairing and storage tips, slicing options, and optional add-ons
- **Cart drawer**: quantity controls, add-ons, pickup time slot selection, and promo codes (`BONJOUR10` for 10% off, `ARTISAN` for $5 off)
- **Checkout**: pickup or delivery, payment method choice (Apple Pay, card, or pay at counter), tax and delivery fee calculation, and an order confirmation
- **Live oven schedule**: see which batches are baking, cooling, proofing, or ready, with progress and oven temperature
- **Café reservations**: pick a date, time, party size, and seating area (Solarium, Main Hall, or Garden Terrace), then download an `.ics` calendar invite
- **Our Craft**: the story behind the bakery's slow fermentation and heritage grains
- **My Orders**: an order tracker with status steps from received to ready for pickup
- **Toast notifications** and fully **responsive layout** for mobile and desktop

---

## 🛠️ Tech Stack

| Area | Tools |
| --- | --- |
| Framework | React 19 + TypeScript |
| Build tool | Vite |
| Styling | Tailwind CSS v4 |
| Animation | Motion |
| Icons | Lucide React |
| Hosting | Netlify |

---

## 📁 Project Structure

```
maison-marcel-artisan-bakery/
├── index.html
├── package.json
├── vite.config.ts
├── tsconfig.json
├── public/
│   └── assets/
└── src/
    ├── main.tsx
    ├── App.tsx                  # App state and screen routing
    ├── index.css
    ├── types/
    │   └── bakery.ts            # Product, cart, order, and reservation types
    ├── data/
    │   └── bakeryData.ts        # Products and oven schedule data
    └── components/
        ├── Header.tsx
        ├── Hero.tsx
        ├── Footer.tsx
        ├── ProductCard.tsx
        ├── ProductModal.tsx
        ├── CartDrawer.tsx
        ├── CheckoutModal.tsx
        ├── OvenScheduleScreen.tsx
        ├── ReservationScreen.tsx
        ├── CraftStoryScreen.tsx
        ├── OrdersTrackerScreen.tsx
        └── Toast.tsx
```

---

## 🚀 Getting Started

**Prerequisites:** [Node.js](https://nodejs.org/) 18 or higher

1. **Clone the repository**
   ```bash
   git clone https://github.com/shivam200717/<repo-name>.git
   cd <repo-name>
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the dev server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000).

4. **Build for production**
   ```bash
   npm run build
   npm run preview
   ```

---

## 🌐 Deployment

The site is deployed on **Netlify** with these settings:

- **Build command:** `npm run build`
- **Publish directory:** `dist`

---

## 📝 Notes

- This is a front-end demo. Menu data, the oven schedule, and orders are stored in the app's state, so there is no real payment processing or backend, and orders reset on page refresh.
- All bakery names, products, and prices are fictional and created for this internship task.
- Product photos are from [Unsplash](https://unsplash.com).

---

## 👨‍💻 Author

**Shivam Yadav**
B.Tech CSE, SRM IST (2024-2028)
Full Stack Web Development Intern, Future Interns

🔗 GitHub: [@shivam200717](https://github.com/shivam200717)

---

*Built as part of the Future Interns Full Stack Web Development internship.*
