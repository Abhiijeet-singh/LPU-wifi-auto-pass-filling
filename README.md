# 🚀 LPU Auto Login Extension

A simple and efficient Chrome/Edge extension that automatically logs you into the LPU WiFi portal, saving time and eliminating repetitive login hassles.

---

## ✨ Features

- 🔐 Securely stores your credentials using Chrome local storage  
- ⚡ Automatically fills username & password  
- ✅ Auto-checks Terms & Conditions checkbox  
- 🚀 Automatically clicks login button  
- 🎨 Clean and modern UI (orange & black theme)  
- 👁️ Toggle password visibility  

---

## 🛠️ Tech Stack

- JavaScript (Vanilla JS)
- HTML5 & CSS3
- Chrome Extension Manifest v3

---

## 📂 Project Structure

---

## ⚙️ How It Works

1. User enters credentials in the popup UI  
2. Credentials are saved using `chrome.storage.local`  
3. When LPU login page loads:
   - Fields are automatically filled  
   - Checkbox is selected  
   - Login button is clicked  

---

## 📥 Installation (Manual)

1. Download or clone this repository  
2. Open browser and go to:
   - Chrome: `chrome://extensions/`
   - Edge: `edge://extensions/`
3. Enable **Developer Mode**
4. Click **Load unpacked**
5. Select the project folder  

---

## 🔒 Permissions Used

- `storage` → To store user credentials locally  
- `host_permissions` → Access LPU login page  

---

## ⚠️ Note

- This extension works specifically for:
- - Make sure your username/password fields match the portal structure.

---

## 💡 Future Improvements

- 🔐 Encryption for stored credentials  
- 🌐 Multi-site support  
- 📱 Better UI/UX enhancements  
- ☁️ Sync across devices  

---

## 🤝 Contributing

Feel free to fork this project and improve it!

---

## 👨‍💻 Author

Developed by **Abhijeet Singh**
