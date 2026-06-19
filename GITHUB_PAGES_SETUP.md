# رفع الموقع على GitHub Pages

## الخطوات:

### 1. إنشاء مستودع جديد على GitHub
- اذهب إلى https://github.com/new
- اسم المستودع: `torx-dev-site` (أو أي اسم تفضله)
- اختر "Public"
- اضغط "Create repository"

### 2. رفع الملفات
بعد إنشاء المستودع، ستظهر لك تعليمات. نسخ الأوامر التالية واستخدمها:

```bash
cd /path/to/this/folder
git remote add origin https://github.com/YOUR_USERNAME/torx-dev-site.git
git branch -M main
git push -u origin main
```

### 3. تفعيل GitHub Pages
- اذهب إلى إعدادات المستودع (Settings)
- اختر "Pages" من القائمة الجانبية
- تحت "Source"، اختر "Deploy from a branch"
- اختر الفرع "main" والمجلد "/ (root)"
- اضغط "Save"

### 4. الرابط النهائي
سيكون رابطك: `https://YOUR_USERNAME.github.io/torx-dev-site/`

---

**ملاحظة:** قد يستغرق ظهور الموقع 1-2 دقيقة بعد الرفع.
