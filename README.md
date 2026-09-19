# Machine-Learning-Models

<div dir="rtl">

<h1 align="center">🏠 توقع أسعار المنازل</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikit-learn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab&logoColor=white" alt="Colab">
</p>

## 📌 نبذة عن المشروع

مشروع تعلّم آلة (Machine Learning) يتوقع سعر المنزل باستخدام بيانات مبيعات المنازل في مقاطعة كينغ (King County) الأمريكية، من ملف `kc_house_data.csv`.

---

## ⚙️ ماذا يفعل المشروع؟

1. **قراءة البيانات** ومعاينتها والتأكد من القيم المفقودة.
2. **تجهيز البيانات:** حذف عمود `id`، واستخراج سنة وشهر البيع من عمود `date`.
3. **المعالجة داخل Pipeline واحد:**
   - الأعمدة الرقمية: تعويض القيم المفقودة بالوسيط + تحجيم.
   - الأعمدة النصية: OneHot Encoding.
4. **تقسيم البيانات:** 80% تدريب و20% اختبار.
5. **تدريب النموذج:** الانحدار الخطي `LinearRegression`.
6. **تقييم النموذج:** MAE و MSE و RMSE و R².
7. **مقارنة الأسعار** الفعلية بالمتوقعة لعينة من بيانات الاختبار.

---

## 🛠️ المكتبات المستخدمة

| المكتبة | الاستخدام |
|---|---|
| `pandas` | قراءة البيانات وتنظيفها |
| `numpy` | العمليات الحسابية |
| `scikit-learn` | المعالجة والتدريب والتقييم |

---


## ▶️ طريقة التشغيل

1. ارفع ملف `kc_house_data.csv` إلى Google Colab (أو عدّل مسار الملف في الخلية الأولى).
2. شغّل الخلايا بالترتيب.

</div>

<p align="center">
  من إعداد: <b>تركي الجهني</b> و<b>ثابت الرشيد</b>
</p>
