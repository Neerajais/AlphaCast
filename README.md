# AlphaCast
**📌 Overview**

This project is an end-to-end Stock Price Prediction Web Application built using a modern full-stack stack.
It integrates machine learning models (LSTM, Prophet, ARIMA) with a Node.js backend and an interactive Next.js dashboard to forecast market trends.

The system covers the complete lifecycle—from data collection to prediction visualization, making stock insights simple and accessible.

**⭐ Features**

📊 Interactive dashboard built with Next.js & Tailwind

🤖 Multiple ML models implemented in Node (LSTM, ARIMA, Prophet)

🔄 Historical + future forecast visualization

⚙️ API-driven prediction system

🗂️ Organized modular code structure

🚀 Deployable on Vercel

**🧰 Technology Stack**

-> Frontend
1. Next.js (App Router)
2. TypeScript
3. TailwindCSS
4. shadcn/ui
5. Custom components (components/)

-> Backend / ML

1. Node.js
2. Custom ML logic (inside /multiple and /utils)
3. Data preprocessing (/utils)
4. Dataset (/data)

<pre>
**📁 Folder Structure**
project-root/
│
├── app/                 # All pages & routes (Next.js App Router)
├── components/          # UI components
├── hooks/               # Custom React hooks
├── lib/                 # Helper libraries & config
├── multiple/            # ML model scripts (LSTM, ARIMA, Prophet)
├── utils/               # Data processing, helpers, model utilities
├── data/                # Stock dataset files
├── public/              # Static assets
├── styles/              # Global & Tailwind styles
├── types/               # TypeScript types
│
├── package.json
├── pnpm-lock.yaml
├── tsconfig.json
└── next.config.mjs
</pre>



**⚙️ Installation & Running Locally**
1️⃣ Install Dependencies
pnpm install

2️⃣ Start Development Server
pnpm dev


Your app will run at:
➡️ https://alphacast.vercel.app/

3️⃣ Production Build
pnpm build
pnpm start

**🔮 Machine Learning Models**

All ML logic is implemented inside:

/multiple
/utils
/data

**Models Used:**

1. LSTM → For short-term deep-learning trend prediction

2. Prophet → For trend + seasonality understanding

3. ARIMA → For statistical baseline forecasting

**How It Works:**

1. Data is read from /data
2. Processed in /utils
3. Model functions run from /multiple
4. Predictions sent to UI via API routes in /app/api/
5. UI charts visualize actual vs predicted values

**🚀 Deployment**

This project is optimized for Vercel deployment.

Steps:

1. Push repository to GitHub

2. Import project into Vercel

3. Add environment variables if required

4. Deploy

**⚠️ Challenges Faced**

1. Collecting clean historical data

2. Real-time data API limitations

3. Tuning LSTM & Prophet for stability

4. Backend + ML + UI integration

5. Deployment constraints on serverless environments

**🔭 Future Improvements**

1. Real-time stock prediction with live feeds

2. News + event sentiment integration

3. Auto-refresh dashboard

4. Trend alerts & push notifications
  
5. More advanced ML models (Transformers, XGBoost)

**🤝 Contributing**

Pull requests are welcome.
For major changes, please open an issue first to discuss your ideas.

📞 Contact

Author: Kamal
LinkedIN : https://www.linkedin.com/in/kamalanalytics/ 
E - Mail : kamal84041@gmail.com 
