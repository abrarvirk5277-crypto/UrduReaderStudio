# Urdu Reader Studio — اردو ریڈر اسٹوڈیو (Mobile GitHub Auto-APK Builder)

## موبائل فون (OPPO Reno 11 / Motorola G35) سے مفت APK بنانے کا مکمل طریقہ

آپ کو کسی کمپیوٹر یا لیپ ٹاپ کی ضرورت نہیں ہے۔ صرف اپنے موبائل کے **Chrome** براؤزر سے نیچے دیے گئے مراحل پر عمل کریں:

1. **GitHub پر مفت اکاؤنٹ بنائیں:**
   - موبائل براؤزر میں [github.com](https://github.com) کھولیں اور اپنا مفت اکاؤنٹ بنائیں (یا لاگ اِن کریں)۔

2. **نیا Repository بنائیں:**
   - اوپر دائیں جانب **`+`** کے نشان پر کلک کریں اور **New repository** منتخب کریں۔
   - نام رکھیں: `UrduReaderStudio` اور **Create repository** پر کلک کریں۔

3. **فائلیں اپ لوڈ کریں:**
   - پہلے اپنے فون کے File Manager میں `Urdu_Reader_Studio_GitHub_AutoAPK.zip` کو **Extract (Unzip)** کریں۔
   - GitHub پر **uploading an existing file** لنک پر کلک کریں۔
   - Extract کیے گئے فولڈر کے اندر موجود تمام فائلیں اور فولڈرز (`app`, `.github`, `docs`, `build.gradle.kts`, `settings.gradle.kts`, `README.md`) منتخب کر کے اپ لوڈ کریں اور **Commit changes** دبا دیں۔
   *(نوٹ: یقینی بنائیں کہ `.github/workflows/build_apk.yml` فائل ضرور اپ لوڈ ہو۔)*

4. **خودکار APK بلڈ اور ڈاؤن لوڈ:**
   - اپ لوڈ ہوتے ہی اوپر **Actions** ٹیب پر کلک کریں۔
   - وہاں **Build Android APK** خودکار طور پر چل رہا ہوگا (تقریباً 3 سے 5 منٹ لگیں گے)۔
   - جب سبز ٹک (✅) آ جائے تو اس پر کلک کریں، نیچے **Artifacts** سیکشن میں **UrduReaderStudio-APK** پر کلک کر کے ZIP ڈاؤن لوڈ کریں۔
   - اس ZIP کو Extract کریں — اندر **`app-debug.apk`** موجود ہوگی، جسے آپ سیدھا اپنے **OPPO Reno 11** یا **Motorola G35** پر انسٹال کر سکتے ہیں!
