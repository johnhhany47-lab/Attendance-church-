# ✝ شباب الكنيسة

## خطوات الرفع على Vercel

### 1. Environment Variables
في Vercel Dashboard → Settings → Environment Variables أضف:

| Key | Value |
|-----|-------|
| FIREBASE_API_KEY | AIzaSyBT43B29gAgH6ufXOkXQWy-RIj9yDQXkuE |
| FIREBASE_AUTH_DOMAIN | attendance-church-1-e10c7.firebaseapp.com |
| FIREBASE_PROJECT_ID | attendance-church-1-e10c7 |
| FIREBASE_STORAGE_BUCKET | attendance-church-1-e10c7.firebasestorage.app |
| FIREBASE_MESSAGING_SENDER_ID | 773950808320 |
| FIREBASE_APP_ID | 1:773950808320:web:1c6b066915563e20ddd3e5 |

### 2. Firebase Console
فعّل:
- Authentication → Email/Password
- Firestore Database → Test mode  
- Storage → Test mode
