# 💸 Expense Tracker – Browser Extension (React + CSS))

Expense Tracker is a lightweight and simple browser extension built with React that lets users quickly add, view, and manage expenses directly inside their browser.  
It uses `localStorage` for data persistence so your expenses remain saved even after closing the browser.

---

## ✨ Features

- ➕ Add new expenses with description and amount  
- 🗑 Delete individual expenses  
- 📊 View total expenses in real-time  
- 💾 Persistent `localStorage` storage  
- 🖥 Clean and responsive UI 

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/todolist-extension.git
cd todolist-extension

```
### 2. Install Node Modules
Make sure you have Node.js installed.

Then install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

### 3. 💻 Run the Project in Development
To run the React app locally:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```
This will start the app on http://localhost:5173 by default (if you're using Vite).

### 4. 📦 Build for Production
To generate a production build (for deployment or Chrome extension packaging):
```bash
npm run build
# or
yarn build
# or
pnpm build
```
This will generate a dist/ folder containing the build output.

### 5. 🧩 Load as Chrome/Brave Extension
To load the extension in Chrome or Brave, follow these steps:
1. Go to chrome://extensions/ (or brave://extensions/ for Brave).
2. Enable Developer Mode.
3. Click "Load unpacked".
4. Select the dist/ folder.
5. The extension should now be loaded and visible in the browser.
6. You can also load the extension directly from the `manifest.json` file by clicking the "Load unpacked" button and selecting the `manifest.json` file.
7. To update the extension, simply reload the extension by clicking the reload button in the extensions pag
8. To remove the extension, click the "Remove" button in the extensions page.
9. To load the extension in a different browser, follow the same steps as above.

## 📁 Folder Structure
The project follows a standard structure:

``` bash
src/
public/
  ├── preview.png       # Extension preview image (screenshot of popup)
  ├── manifest.json     # Extension manifest file
src/
  ├── App.js            # Main React component
  ├── ExpenseTracker.css# Styles
  ├── index.js          # Entry point
```
## 📌 Notes
1. The extension uses localStorage for persistence (data remains after refresh or restart).
2. Works seamlessly in Chrome, Brave, and Edge (any Chromium-based browser).
3. Reload the extension from the Extensions page after making code changes and rebuilding.

## 🧠 Tech Stack
1. React
2. Tailwind CSS
3. Vite
4. HTML5 LocalStorage
5. Chrome Extension APIs

## 📸 Screenshot

Here’s a preview of the extension in action:

![ Expense Tracker Screenshot](https://github.com/hellman53/ExpenseTracker/blob/df9962971c50588a67e4517391336f48ab2f6788/public/preview.png)
