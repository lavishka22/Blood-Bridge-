# Blood Bridge

Blood Bridge is a modern web platform that connects blood donors with recipients efficiently, enabling quick search and real-time communication during emergencies.

---

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [Tech Stack](#tech-stack)
- [License](#license)

---

## Features

- 🔍 **Search for Donors:** Find blood donors by blood type and location  
- 📝 **Easy Registration:** Sign up as a donor or recipient  
- 📢 **Emergency Requests:** Broadcast and respond to urgent blood needs  
- 💬 **Real-time Communication:** Connect instantly during emergencies  
- 🛡️ **Secure & Modern:** Authentication and data safety  
- 📊 **Profile Management:** Manage donor and recipient profiles

---

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/lavishka22/Blood-Bridge-.git
   cd Blood-Bridge-
   ```

2. **Install dependencies:**
   ```bash
   npm install
   # or, if using bun:
   bun install
   ```

3. **Set up environment variables:**  
   Copy `.env.example` to `.env` and update with your credentials.

4. **Start the development server:**
   ```bash
   npm run dev
   # or
   bun run dev
   ```

---

## Usage

- Open your browser at [http://localhost:5173](http://localhost:5173) (default Vite port)
- Register as a donor or recipient
- Use the dashboard to search or respond to requests

---

## Contributing

Contributions are welcome!  
To contribute:

1. Fork the repository  
2. Create a new branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes  
4. Open a pull request

---

## Tech Stack

- **Frontend:** React (TypeScript)
- **Build Tool:** Vite
- **UI:** Tailwind CSS, Radix UI
- **State/Data:** React Query, Supabase (for backend/auth)
- **Maps:** Leaflet, react-leaflet  
- **Testing:** Vitest, Testing Library

---

## License

This project is licensed under the [MIT License](LICENSE).

---
