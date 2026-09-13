# Zamino Cafe - Food App

Telegram Web App uchun buyurtma berish ilovasi va Admin Panel.

## 🚀 Tavsifi

- **Mijozlar Applikatsiyasi**: Telegram Web App orqali taomlarni ko'rish va buyurtma berish
- **Admin Panel**: Menyu boshqaruvi va buyurtmalarni ko'rish (PIN: 7777)
- **Firebase Integration**: Real-time ma'lumotlar bazasi

## 📋 Talab qilinadigan narsalar

- Node.js 14+
- npm yoki yarn
- Firebase hisob

## 🔧 O'rnatish

```bash
# Klonlash
git clone https://github.com/shohjahonxoliqulov5100-pixel/zamino-cafe-food-app.git
cd zamino-cafe-food-app

# Dependencies o'rnatish
npm install

# Server ishga tushirish
npm start
```

## 📌 Linklar

- **Mijozlar App**: `http://localhost:3000/`
- **Admin Panel**: `http://localhost:3000/admin/`
- **Admin PIN**: `7777`

## 🌐 Deployment

### Heroku
```bash
heroku create your-app-name
git push heroku main
```

### Railway
1. Railway.app saytiga kirish
2. New Project → Deploy from GitHub
3. Bu repositoriyani tanlash
4. Deploy tugmasini bosish

### Render
1. Render.com saytiga kirish
2. New → Web Service
3. GitHub reposini ulash
4. Environment: Node
5. Build command: `npm install`
6. Start command: `npm start`

## 📂 Fayl Struktura

```
.
├── index.html           # Mijozlar uchun asosiy sahifa
├── admin/
│   └── index.html       # Admin Panel
├── server.js            # Express server
├── package.json         # Dependencies
├── .env                 # Environment variables
└── README.md            # Bu fayl
```

## 🔐 Firebase Sozlash

Firebase fayllarida `firebaseConfig` o'zgartirilgan. O'z Firebase projectingizni qo'shish uchun:

1. Firebase Console: https://console.firebase.google.com
2. Yeni project yaratish
3. Firestore Database yaratish
4. API keys olish
5. `index.html` va `admin/index.html` dagi `firebaseConfig` ni o'zgartirish

## 📞 Bog'lanish

Savollar bo'lsa GitHub issues orqali yozing.

---

**⭐ Foydali bo'lsa yulduzcha bosing!**
