# 🖥️ Tauri + Vue 3 + TypeScript
 - A lightweight, high-performance desktop application boilerplate.
---
## ⚙️ Installation

### 🛠️ Install node package
```
npm install
```

### 🛠️ Install and Launch Tauri
```
npm run tauri dev
```

## ⚙️ Build .exe file

### 🛠️ Build the Frontend (Vue)
```
npm run build
```
Tauri uses this built version for packaging the app.

### 🛠️ Building the Application
```
npm run tauri build
```

### 📦 Where to Find the .exe?
After a successful build, the .exe will be here:
```
src-tauri/target/release/bundle/msi/
```