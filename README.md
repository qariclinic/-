# 🕌 شعیب اسلامک سکول - موبائل ایپ

![Build APK](https://github.com/your-username/your-repo-name/actions/workflows/build-apk.yml/badge.svg)

## 📱 تعارف
**شعیب اسلامک سکول** ایک مکمل اسلامی فقہی موبائل ایپ ہے جو مفتی حافظ محمد شعیب خان آلائی کے فتاویٰ اور تعلیمات پر مبنی ہے۔ یہ ایپ اردو زبان میں اسلامی مسائل کا حل فراہم کرتی ہے۔

## ✨ خصوصیات
- 📖 **20+ اسلامی ماڈیولز** (ایمانیات، طہارت، نماز، زکوٰۃ، حج، نکاح، وراثت وغیرہ)
- 🤖 **AI مفتی چیٹ** - اپنے مسائل فوری پوچھیں
- 🔍 **سرچ انجن** - کسی بھی مسئلے کو تلاش کریں
- 🌙 **ڈارک موڈ** - دن اور رات کے لیے الگ تھیم
- 📄 **PDF ڈاؤن لوڈ** - تفصیلی احکامات ڈاؤن لوڈ کریں
- 🔊 **آڈیو وضاحت** - مسائل کو سنتے ہوئے سمجھیں
- 📱 **موبائل فرینڈلی** - ہر سکرین کے لیے موزوں

## 🛠️ ٹیکنالوجیز
- HTML5
- CSS3 (Tailwind CSS)
- JavaScript
- GitHub Actions (خودکار APK بلڈ)
- Capacitor/Cordova (Android App)

## 📥 APK ڈاؤن لوڈ کیسے کریں؟

### طریقہ 1: GitHub Actions سے
1. اس ریپوزٹری کے **Actions** ٹیب پر جائیں
2. **"Build APK"** ورک فلو پر کلک کریں
3. تازہ ترین رن (Run) پر کلک کریں
4. نیچے **Artifacts** سیکشن سے APK ڈاؤن لوڈ کریں

### طریقہ 2: براہِ راست
[APK ڈاؤن لوڈ کریں](https://github.com/your-username/your-repo-name/releases)

## 🚀 خودکار بلڈ کیسے کام کرتا ہے؟

یہ ریپوزٹری **GitHub Actions** کے ذریعے خودکار APK بلڈ کرتی ہے:

1. جب بھی `main` برانچ پر کوڈ Push ہوتا ہے
2. GitHub Actions خودکار طور پر چلتا ہے
3. Android APK تیار ہوتا ہے
4. APK **Artifacts** میں محفوظ ہو جاتا ہے

### ورک فلو کی تفصیل
```yaml
name: Build APK
on: push to main
jobs:
  - Checkout code
  - Setup Node.js
  - Install Cordova
  - Create Android Project
  - Copy HTML files
  - Build APK
  - Upload APK# -
