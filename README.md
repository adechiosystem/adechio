# OASIS OS - Enterprise Multi-Tenant SaaS Platform

منظومة متكاملة لإدارة المنشآت (Multi-Tenant)، بوابات التقييم الذكي المرتبطة بخرائط جوجل، حجز المواعيد، ونظام CRM مع إرسال حملات واتساب المباشرة.

## الهيكل والمحتويات
- **public/**: يحتوي على ملف `.htaccess` المخصص للسيرفرات (Apache) لضمان عمل مسارات React وتوجيه الصفحات بنجاح، بالإضافة للملفات العامة.
- **src/assets/images/**: مجلد مخصص لأي صور أو أصول ثابتة ترغب في إضافتها لاحقاً.
- **src/App.tsx**: كود التطبيق الأساسي بكافة وظائفه ومزامنة البيانات في `localStorage`.
- **.gitignore**: مُعد مسبقاً لاستثناء `node_modules` والملفات المؤقتة عند الرفع على GitHub.

## خطوات التشغيل المحلي

1. تثبيت الحزم المطلوبة:
   ```bash
   npm install
   ```

2. تشغيل السيرفر المحلي:
   ```bash
   npm run dev
   ```

3. تجهيز ملفات الإنتاج (Production Build):
   ```bash
   npm run build
   ```

## خطوات الرفع على GitHub

افتح موجه الأوامر داخل هذا المجلد ونفذ:

```bash
git init
git add .
git commit -m "Initial commit: Oasis OS Multi-Tenant SaaS"
git branch -M main
git remote add origin https://github.com/USERNAME/oasis-os-platform.git
git push -u origin main
```
