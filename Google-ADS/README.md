
# 🚫 MIKROTIK-ADS – حلول متكاملة لحظر الإعلانات باستخدام MikroTik

## 🧠 لمحة عامة:
`MIKROTIK-ADS` هو مشروع مطوّر لحظر الإعلانات الخارجية بكفاءة عالية جدًا، مستوحى من نظام DNS الشهير السابق، وتم تعديله وتحسينه بشكل شخصي واحترافي لضمان أعلى أداء واستقرار.  
تمت إعادة بنائه ليكون بديلًا قويًا ومتكاملًا 💪

---

## 🎯 الهدف من المشروع:

- ✳️ تقديم حلول متكاملة ومفتوحة المصدر لحظر الإعلانات
- 📡 تحسين تجربة التصفح وتقليل استهلاك البيانات
- 🧱 دعم MikroTik RouterOS 7+
- 🤝 تطوير جماعي بإشراف مباشر من مختصين لضمان الجودة
- 🔧 تحديثات مستمرة وتطوير تدريجي

---

## 📂 محتويات المشروع:

- `block-ads` – قائمة DNS لحظر الإعلانات الخارجية
- `youtube-ads-block` – قواعد لحظر إعلانات YouTube (نسبة الحظر جيدة)
- `dns-sources` – مصادر للقوائم المعتمدة
- `auto-update-script` – سكريبت لتحديث القوائم تلقائيًا

---

## ✅ مميزات:

- 🔐 ملفات نظيفة وخالية من الأخطاء
- ⚙️ سهلة التثبيت ولا تؤثر على أداء الشبكة
- 🧼 تركيز خاص على حظر إعلانات Google وسيرفراتها
- 📄 لا تشمل المحتوى الإباحي – فقط الإعلانات

---

## 🛠️ طريقة الاستخدام (MikroTik 7+):

1. 🔼 **رفع الملف إلى MikroTik:**
   - افتح Winbox أو WebFig
   - انتقل إلى **Files**
   - ارفع `block-ads.rsc`

2. 💻 **استدعاء الملف:**
   - افتح **Terminal**
   - نفّذ:

     ```bash
     import file-name=block-ads.rsc
     ```

3. ✅ سيتم تطبيق الإعدادات تلقائيًا

---## 🖼️ صور توضيحية من داخل المشروع

<div align="center">

<table style="border-collapse: separate; border-spacing: 20px;">
  <tr>
    <td align="center" style="background-color: #f0f8ff; padding: 15px; border-radius: 12px; box-shadow: 0 0 10px rgba(0,0,0,0.1);">
      <strong style="color: #007acc;">🔹 رفع ملف الحظر داخل MikroTik</strong><br>
      <img src="images/upload2.png" width="250" style="border-radius: 10px;"/>
    </td>
    <td align="center" style="background-color: #fff0f5; padding: 15px; border-radius: 12px; box-shadow: 0 0 10px rgba(0,0,0,0.1);">
      <strong style="color: #cc3366;">🔹 تنفيذ أمر الاستيراد `import`</strong><br>
      <img src="images/upload3.png" width="250" style="border-radius: 10px;"/>
    </td>
    <td align="center" style="background-color: #f5fff0; padding: 15px; border-radius: 12px; box-shadow: 0 0 10px rgba(0,0,0,0.1);">
      <strong style="color: #228b22;">🔹 تفعيل وتعطيل الحظر</strong><br>
      <img src="images/eneble-disable.png" width="250" style="border-radius: 10px;"/>
    </td>
  </tr>
</table>

</div>

---

## 📬 انضم إلى مجتمعنا على تيليجرام:

<div align="center" style="margin-top: 20px;">
  <a href="https://t.me/star1ink_1raq" target="_blank">
    <img src="https://img.shields.io/badge/انضم%20إلينا%20على-تيليجرام-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Group" height="60" style="border-radius: 8px; box-shadow: 0 0 10px rgba(0,0,0,0.2);">
  </a>
</div>

> 💬 شارك أفكارك، استفسر، وساهم في تطوير أدوات حظر الإعلانات معنا

