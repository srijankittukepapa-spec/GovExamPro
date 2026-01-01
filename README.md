
# GovExam Pro - CBT Simulator

A professional-grade Computer-Based Test (CBT) simulator optimized for Indian government exam aspirants, featuring AI-powered study insights and real-time news.

## 🚀 How to Deploy

### 1. Upload the Files
Make sure your GitHub repository contains the following structure:
- `index.html` (at the root)
- `index.tsx` (at the root)
- `App.tsx` (at the root)
- `package.json` (at the root)
- `components/` (folder with all .tsx components)
- `services/` (folder with API services)
- `types.ts` & `data.ts`

### 2. Connect to Hosting
We recommend using [Vercel](https://vercel.com) or [Netlify](https://netlify.com) for the best experience:
1. Log in to Vercel/Netlify.
2. Click **"Add New Project"**.
3. Import this GitHub repository (`GovExamPro`).
4. **CRITICAL:** In the "Environment Variables" section, add:
   - `API_KEY`: Your Google Gemini API Key.

### 3. Google Sheets Integration
To enable the **User Responses Tracking**:
1. Open the [Google Apps Script Editor](https://script.google.com/).
2. Paste the provided backend script.
3. Click **Deploy > New Deployment > Web App**.
4. Set "Who has access" to **"Anyone"**.
5. Copy the **Web App URL** and paste it into the **Admin Studio > Settings** inside the app.

## 🛠 Features
- **CBT Simulation:** Realistic exam interface with timer and question palette.
- **AI Insights:** Automated performance analysis and custom study plans via Gemini API.
- **Daily News:** Latest current affairs for UPSC/SSC/Banking aspirants.
- **Cloud Sync:** Fetch questions and save results directly to Google Sheets.

## ⚖️ Disclaimer
This is an independent educational tool. We are not affiliated with any government recruitment board (SSC, UPSC, IBPS, etc.). Always verify exam dates and data with official government portals.
