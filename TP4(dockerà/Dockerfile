# Dockerfile بسيط لمشروع Python
FROM python:3.10-slim

# إعداد مجلد العمل
WORKDIR /app

# نسخ كل ملفات المشروع
COPY . /app

# تثبيت التبعيات إذا لديك requirements.txt
# (احذف السطر إن لم يكن لديك ملف متطلبات)
RUN echo "No Python dependencies to install"
# المنفذ الذي يعمل عليه التطبيق داخل الحاوية
EXPOSE 5000

# الأمر الذي يشغل التطبيق
# (عدّل هذا حسب اسم ملفك)
CMD ["python", "app.py"]
