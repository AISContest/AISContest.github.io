---
title: "اجرای Jupyter Notebook در کامپیوتر شخصی"
# meta_title: ""
# description: ""
date: 2024-12-20T17:30:00Z
image: "/images/jupyter.png"
categories: ["راهنمای ابزارها"]
author: "Ali Yazdanifar"
tags: ["Jupyter", "آموزش", "Python"]
draft: false
---

<style>
body {
    direction: rtl;
    text-align: right;
}
</style>

Jupyter Notebook یک ابزار فوق‌العاده برای تحلیل داده، یادگیری ماشین و نوشتن کد تعاملی است. در این فایل، نحوه راه‌اندازی و اجرای Jupyter Notebook روی کامپیوتر شخصی را توضیح می‌دهیم.

## مراحل نصب و اجرا

### 1. نصب Python
ابتدا باید Python را روی سیستم خود نصب کنید. می‌توانید آخرین نسخه Python را از [سایت رسمی Python](https://www.python.org/) دانلود و نصب کنید.

### 2. نصب Jupyter Notebook
پس از نصب Python، دستور زیر را در ترمینال یا خط فرمان اجرا کنید تا Jupyter Notebook نصب شود:

```bash
pip install notebook
```

### 3. اجرای Jupyter Notebook
برای اجرای Jupyter Notebook، دستور زیر را وارد کنید:

```bash
jupyter notebook
```

این دستور یک صفحه مرورگر را باز می‌کند که در آن می‌توانید نوت‌بوک‌های خود را مدیریت و اجرا کنید.

## آموزش ویدیویی
برای مشاهده آموزش تصویری راه‌اندازی و استفاده از Jupyter Notebook، می‌توانید ویدئوی زیر را مشاهده کنید:

[لینک به ویدیو در یوتیوب](https://www.youtube.com/watch?v=-ijS8WTo8is)

## نکات تکمیلی
- برای مدیریت بسته‌های Python، پیشنهاد می‌شود از ابزارهایی مانند `virtualenv` یا `conda` استفاده کنید.
- اگر با مشکلی مواجه شدید، از دستور زیر برای بروزرسانی Jupyter استفاده کنید:

```bash
pip install --upgrade notebook
```

امیدواریم این راهنما برای شما مفید باشد. موفق باشید!
