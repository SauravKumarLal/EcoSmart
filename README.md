# EcoSmart: Waste Management App

An innovative waste management and community engagement platform, *EcoSmart* allows users to report, verify, and track waste, while promoting sustainability and earning rewards. Built with modern web technologies, this app leverages AI and blockchain to encourage eco-friendly practices.

---

## Features

### 1. **Homepage Impact Metrics**
   - Displays:
     - Total waste collected.
     - Number of reports submitted.
     - Total tokens earned.
     - CO2 offset statistics.

### 2. **User-Friendly Sign-Up**
   - Multiple sign-up options:
     - **Web3 integration**.
     - **Social media login** via a modal.

### 3. **Waste Reporting**
   - Upload an image of waste and click **"Verify Waste"**.
   - AI-powered verification:
     - Identifies types of waste (e.g., plastic, metal, organic).
     - Estimates waste quantities.
   - Location input with Google Auto-Suggestion for precise geotagging.

### 4. **Reward System**
   - Earn tokens for reporting waste.
   - Recent reports and notifications (e.g., "Earned 10 points for reporting waste").

### 5. **Waste Collection Management**
   - Users can track and collect reported waste for additional rewards.

### 6. **Database Setup**
   - Powered by **Drizzle ORM** for intuitive database management.
   - Key tables include:
     - **Report Table**: Tracks reports with fields for user ID, waste type, and timestamps.

---

## Tech Stack

- **Frontend**: Next.js, TypeScript, TailwindCSS.
- **AI Integration**: Gemini AI for waste identification.
- **Database**: Drizzle ORM with PostgreSQL.
- **Authentication**: Web3 and social login options.
- **Maps and Geotagging**: Google Maps API.

---

## Getting Started

### Prerequisites
- Node.js (v16+).
- PostgreSQL database.
- Wallet or social media accounts for login.

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/SauravKumarLal/EcoSmart.git
   cd EcoSmart
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Set Up Environment Variables**:
   - Create a `.env` file in the root directory.
   - Add the following keys:
     ```env
     NEXT_PUBLIC_GEMINI_API_KEY=your-gemini-api-key
     DATABASE_URL=your-database-url
     GOOGLE_MAPS_API_KEY=your-google-maps-api-key
     ```

4. **Run the Development Server**:
   ```bash
   npm run dev
   ```
   Visit [http://localhost:3000](http://localhost:3000) to view the app.

---

## Usage

1. **Sign Up**:
   - Use Web3 or social media to create an account.

2. **Report Waste**:
   - Upload an image.
   - Verify waste using Gemini AI.
   - Enter location and submit the report.

3. **Track Rewards**:
   - View notifications and track points earned.

4. **Manage Waste Collection**:
   - Collect waste and contribute to the community.

---

## Folder Structure
```
.
├── components
├── pages
│   ├── api
│   ├── index.tsx
├── public
├── styles
├── utils
└── drizzle-config.ts
```

---

## Contributing
We welcome contributions to enhance the platform! To contribute:

1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Submit a pull request with a detailed explanation of your changes.

---

## Acknowledgments
- [Gemini AI](https://gemini-ai.com) for waste detection.
- [Drizzle ORM](https://drizzle-orm.com) for database management.
- [Google Maps API](https://developers.google.com/maps) for location services.

---

Happy coding! Let’s make the world cleaner together 🌍.

