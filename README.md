# 📄 PDF Merger Web App

A simple web-based application to merge multiple PDF files into one directly in the browser.

## 🚀 Features
- Merge multiple PDFs
- No server required (client-side only)
- Fast and secure
- Easy to use UI

## 🛠️ Technologies Used
- HTML
- CSS
- JavaScript
- pdf-lib (library)

## ▶️ How to Run Locally
1. Download or clone the repository
2. Open in VS Code
3. Install Live Server extension
4. Right click `index.html` → Open with Live Server

## 🌐 Deployment (GitHub Pages)
1. Upload project to GitHub
2. Go to Settings → Pages
3. Select branch `main` and folder `/root`
4. Your app will be live

## 🐳 Docker Setup

### Create a Dockerfile
```Dockerfile
FROM nginx:alpine
COPY . /usr/share/nginx/html
