# Daily Check-in Web App

A clean, responsive web application configured to run directly on **GitHub Pages**.

## Features

---

## 1. Setting up Email Delivery (Free via Formspree)

Since GitHub Pages hosts static files (HTML/CSS/JS), it uses [Formspree](https://formspree.io) to deliver emails securely without exposing passwords or needing a private backend server.

1. Sign up for free at [formspree.io](https://formspree.io).
2. Click **Create new form**:
   - Name it (e.g., `Daily Report`).
   - Set the destination email to: `buckeyekevin1983@gmail.com`.
3. Copy your Form ID (e.g., `mqkrgyep`) or full Endpoint URL (`https://formspree.io/f/mqkrgyep`).
4. Enter this ID/URL directly in the web app input field (saved in your browser's localStorage) or edit the default value in `index.html`.

---

## 2. Hosting on GitHub Pages

1. Initialize git and commit:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of daily report app"
   ```
2. Create a new repository on GitHub (e.g. `daily-report`).
3. Push your repository:
   ```bash
   git branch -M main
   git remote add origin https://github.com/<YOUR-USERNAME>/daily-report.git
   git push -u origin main
   ```
4. In your GitHub repository:
   - Go to **Settings** > **Pages**.
   - Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
   - Select branch `main` and folder `/ (root)`, then click **Save**.
5. Your web app will be live at `https://<YOUR-USERNAME>.github.io/daily-report/`.
