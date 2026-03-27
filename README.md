# EpiDemIQ

**EpiDemIQ** is a modern epidemiological surveillance and forecasting platform designed for public health research. It leverages real-world datasets and Google's Gemini AI to predict trends, model scenarios, and provide actionable insights into disease spread.

## 🚀 Key Features

- **AI-Driven Forecasting:** Uses the Gemini 3 Flash model to analyze historical trends and predict future case growth, mortality, and recovery rates.
- **Regional Surveillance:** Real-time monitoring of regional hotspots with risk level categorization (Critical, High, Moderate, Low).
- **Scenario Modeling:** Interactive simulation of mitigation strategies, including vaccination rates, mobility restrictions, and mask compliance.
- **Custom Data Analysis:** Upload your own epidemiological datasets in CSV format for instant AI-powered summary and trend analysis.
- **Mobility Insights:** Integration of population movement data to understand the correlation between mobility and infection rates.
- **Dark/Light Mode:** Fully responsive, theme-aware interface designed for both high-precision data review and low-light environments.
- **API Transparency:** Dedicated API Access page to manage your own Gemini API keys and monitor engine status.

## 🛠️ Tech Stack

- **Frontend:** [React](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/) + [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **Animations:** [Motion](https://motion.dev/) (Framer Motion)
- **Charts:** [Recharts](https://recharts.org/)
- **AI Engine:** [Google Generative AI SDK](https://ai.google.dev/) (Gemini API)
- **Backend:** [Firebase](https://firebase.google.com/) (Authentication & Firestore)
- **Icons:** [Lucide React](https://lucide.dev/)
- **Data Parsing:** [PapaParse](https://www.papaparse.com/)

## 📊 Data Sources

EpiDemIQ aggregates data from trusted global health organizations:
- **WHO** (Global Health Observatory)
- **Johns Hopkins University** (CSSE Data)
- **Our World in Data** (Vaccination & Mortality)
- **Google Community Mobility Reports**
- **CDC** (Public Health Statistics)

## ⚙️ Setup & Configuration

### Environment Variables
To run the full AI-powered experience, ensure the following environment variables are configured:
- `GEMINI_API_KEY`: Your Google AI Studio API key.

### Local Development
1. Install dependencies:
   ```bash
   npm install
   ```
2. Start the development server:
   ```bash
   npm run dev
   ```

## 🛡️ Privacy & Security

- **No PII:** We do not collect personally identifiable information.
- **Local Processing:** Custom CSV uploads are processed locally in your browser.
- **Secure Storage:** User-provided API keys are stored only in your browser's local storage.

---
*Developed as a student research project for modernizing epidemic surveillance.*
