
# Enterprise Website Auditor

A **web-based tool** for auditing websites on **security, performance, and SEO compliance**.  
It provides an interactive dashboard, issue detection, charts, AI-powered fix suggestions, and PDF report export.

---

## 🚀 Features

- **Quick Audit Form** – enter a website URL, audit type, and device type.  
- **Progress Tracker** – shows scanning status for security, performance, and SEO.  
- **Interactive Dashboard**:
  - Overall score with gauge chart.
  - Security, Performance, and SEO scoring with detailed issue lists.
  - Trend charts using **Chart.js**.
- **AI Fix Suggestions** – get actionable steps to resolve issues.  
- **Saved Websites** – save frequently audited websites.  
- **Audit History** – view and revisit past audits.  
- **Settings Panel** – manage theme (light/dark), API key, auto-update preferences.  
- **PDF Export** – export complete audit reports.  
- **Suggestion Panel** – request expert review via email.  

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, TailwindCSS  
- **Charts**: Chart.js  
- **PDF Export**: jsPDF, html2canvas  
- **Storage**: LocalStorage (for saved sites & history)  
- **Interactivity**: Vanilla JavaScript  

---

## 📂 Project Structure

├── 086 -Praudtech.html # Main application file

├── logo.jpg # Logo used in header (optional)


---

## ⚙️ Installation & Usage

1. Clone or download the repo.  
2. Place all files (HTML + logo) in a single folder.  
3. Open the `086 -Praudtech.html` file in your browser.  
   - No server setup is required – works as a static HTML file.  

---

## 📖 How It Works

1. Enter a **website URL** and choose the audit type (Full, Security, Performance, SEO).  
2. Watch the **progress bar** while simulated scans run.  
3. Review the **results dashboard** with scores and charts.  
4. Check detailed findings and click **Fix** for AI-powered suggestions.  
5. Save sites for quick re-audits or export reports to PDF.  

---

## 📊 Example Metrics Analyzed

- **Security**: HTTPS, CSP, cookies, headers, XSS protection, SSL/TLS version.  
- **Performance**: Load time, FCP, LCP, TTI, TBT, caching, unoptimized images.  
- **SEO**: Meta description, alt text, structured data, mobile friendliness, sitemaps, robots.txt, broken links.  

---

## 🔮 Future Enhancements

- Real API integration for live website scanning.  
- Waterfall chart for request analysis.  
- Advanced AI integration for automated fixes.  
- Multi-user support with authentication.  

---

## 📄 License

This project is open-source. You are free to use and modify it.  


