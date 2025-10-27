# 📘 CSV → Clean Excel Converter (Frontend Only)

**CSV Cleaner** is a fully frontend web application that allows you to **upload a CSV file**, filter specific columns, and download a **cleaned, formatted Excel file** — all directly in the browser. No backend, no server, no setup required.  

## 🚀 Features

- ✅ **Frontend-only**: Runs completely in the browser, offline-friendly  
- 📂 **Drag & Drop CSV Upload** or click to select  
- 🖊 **Excel Styling**:
  - Headers bold & center-aligned  
  - Data rows center-aligned  
  - Auto column width  
- 💎 Modern **TailwindCSS UI**  
- 📱 **Mobile-friendly**  
- 🏃 Works instantly without any backend  

## 📌 Columns Filtered

The app keeps only these columns from your CSV:

- Name  
- Email  
- External Id  
- Course  
- Estimated Learning Hours  
- Completed  
- Course Grade  

## 💻 How to Use

1. Open `index.html` in a modern browser (Chrome, Edge, Firefox).  
2. Drag & drop your CSV file into the upload box, or click to select it.  
3. Click **🧹 Clean & Convert**.  
4. Download your cleaned Excel file instantly.  

## 🛠 Folder Structure
```bash
csv-cleaner/
│
├── index.html # Main frontend file
├── xlsx.full.min.js # SheetJS library for Excel generation
├── papaparse.min.js # PapaParse library for CSV parsing
└── README.md # Project documentation
```

## 🎨 Tech Stack

- HTML5 + CSS3  
- TailwindCSS (for modern UI)  
- JavaScript  
- [SheetJS (XLSX)](https://github.com/SheetJS/sheetjs)  
- [PapaParse](https://www.papaparse.com/)  

## 🌐 Deployment (Optional)

You can host this on **GitHub Pages** or any static hosting platform:

1. Push your project to a GitHub repository.
2. Go to **Settings → Pages → Source**.
3. Select `main` branch → `/root`.
4. Your app will be live at:

## 📜 License

MIT License — Free to use and modify.
