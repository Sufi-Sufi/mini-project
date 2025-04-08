
# 🍽️ Silver Spoon Restaurant System

**A Full-Stack Restaurant Reservation & Takeaway Platform**  
Modern solution for table bookings and food orders with powerful admin management.

## 🌟 Features

### 🎯 Core Functionality
- **Table Reservations**
  - Real-time availability checking
  - DateTime selection with validation
  - Party size customization
- **Takeaway Orders**
  - Menu browsing system
  - Order customization
  - Contactless pickup scheduling
- **Admin Dashboard**
  - Complete reservation management
  - Order tracking system
  - Secure authentication

### ✨ Technical Highlights
- Responsive design across all devices
- Google Maps integration
- Form validation with error handling
- Real-time data synchronization

## 🛠️ Tech Stack

### Frontend
- React.js (Vite)
- Tailwind CSS
- React Router
- React Icons

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- RESTful API design

### Development Tools
- ESLint (Code quality)
- PostCSS (CSS processing)
- Git/GitHub (Version control)

## 📂 Project Structure

```
silver-spoon/
├── Backend/
│   ├── server.js         # Express server entry
│   ├── package.json      # Backend dependencies
│   └── node_modules/     # Backend packages
├── public/               # Static assets
├── src/
│   ├── assets/           # Images/media
│   ├── components/       # React components
│   │   ├── AdminDashboard.jsx
│   │   ├── Carousel.jsx
│   │   ├── DateTimeSelection.jsx
│   │   └── [Other components...]
│   ├── App.jsx           # Root component
│   └── main.jsx          # Application entry
├── package.json          # Frontend config
├── vite.config.js        # Build configuration
└── README.md             # Documentation
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v16+)
- npm/yarn
- MongoDB (Atlas or local)

### Installation
1. Clone repository:
   ```bash
   git clone https://github.com/your-username/silver-spoon.git
   cd silver-spoon
   ```

2. Install dependencies:
   ```bash
   # Frontend
   npm install
   
   # Backend
   cd Backend
   npm install
   ```

3. Configure environment:
   ```bash
   # Create .env in Backend/
   MONGODB_URI=your_connection_string
   SECRET_KEY=your_secret_key
   ```

### Running the Application
```bash
# Frontend (port 5173)
npm run dev

# Backend (port 3000)
cd Backend
node server.js
```

## 🔑 Admin Access
- Route: `/admin`
- Default Credentials:
  - Username: `admin`
  - Password: `password123` *(Change in production!)*

## 🛠️ Available Scripts
| Command          | Description                     |
|------------------|---------------------------------|
| `npm run dev`    | Start development server        |
| `npm run build`  | Create production build         |
| `npm run lint`   | Run ESLint analysis            |
| `npm run preview`| Preview production build       |

## 🧩 Challenges & Solutions
1. **Real-time Availability**  
   Implemented MongoDB queries with date-time validation to prevent overbooking.

2. **Form Validation**  
   Created custom validation hooks for phone numbers and reservation conflicts.

3. **Responsive Design**  
   Used Tailwind's responsive utilities with mobile-first approach.

## 🔮 Future Roadmap
- Payment gateway integration
- Real-time notifications
- Customer review system
- Advanced analytics dashboard
- Multi-language support


## 🙏 Acknowledgments
- [Tailwind CSS](https://tailwindcss.com) for utility-first styling
- [Vite](https://vitejs.dev) for blazing fast builds
- [React Icons](https://react-icons.github.io) for beautiful icons
- MongoDB Atlas for cloud database hosting


