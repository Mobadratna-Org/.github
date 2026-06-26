# 🤝 أهلاً بكم في منظمة مبادرتنا | Welcome to Mobadratna Organization

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:7c3aed&height=180&section=header&text=Mobadratna%20Organization&fontSize=40&fontColor=ffffff&fontFamily=Outfit" width="100%" />
</div>

منصة **مبادرتنا** هي بيئة عمل برمجية متكاملة ومفتوحة المصدر لربط ومساندة المبادرات الطلابية والمشاريع الجامعية بالتطوع الطلابي الفعال. تهدف المنصة لتسهيل عمليات التقديم والقبول وإصدار الإحصائيات الإدارية لمسؤولي الأنشطة.

**Mobadratna** is an integrated open-source software ecosystem designed to organize, track, and empower student initiatives and graduation projects through voluntary support. The platform facilitates registrations, volunteer matches, and administrative analytics dashboards.

---

## 🧬 النظام البيئي للمنصة | Ecosystem Architecture

يتكون النظام من مستودعين رئيسيين يتكاملان لتوفير بيئة عمل آمنة وسلسة للطلاب والإداريين:

```mermaid
graph LR
    Portal[mobadratna-student-portal<br/>Static Frontend Portal Client] -->|REST HTTP Requests| API[mobadratna-core-engine<br/>PHP REST API Backend Engine]
    API -->|PDO Connection| DB[(MySQL Database)]
```

---

## 📂 مستودعات المنصة (Our Repositories)

| المستودع (Repository) | النوع | الوصف (Description) | الشارات التقنية (Tech Badges) |
| :--- | :--- | :--- | :--- |
| 💻 **[mobadratna-student-portal](https://github.com/Mobadratna-Org/mobadratna-student-portal)** | Frontend | البوابة الإلكترونية التفاعلية المخصصة للطلاب واستعراض الأنشطة والتقديم للتطوع. | ![HTML5](https://img.shields.io/badge/HTML5-Structure-orange?logo=html5&style=flat-square) ![CSS3](https://img.shields.io/badge/CSS3-Design-blue?logo=css3&style=flat-square) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript&style=flat-square) |
| ⚙️ **[mobadratna-core-engine](https://github.com/Mobadratna-Org/mobadratna-core-engine)** | Backend | محرك خادم البيانات المبني بلغة PHP والمسؤول عن الأمان وإدارة الجلسات وقبول طلبات الطلاب. | ![PHP](https://img.shields.io/badge/PHP-v8-blue?logo=php&style=flat-square) ![MySQL](https://img.shields.io/badge/MySQL-v8-blue?logo=mysql&style=flat-square) |

---

## 🛠️ التقنيات الأساسية (Core Tech Stack)
*   **Frontend**: Semantic HTML5, Responsive CSS3 Grid/Flexbox, Cairo Web Fonts, Vanilla JS DOM controllers.
*   **Backend & DB**: Clean Raw PHP 8.x routing handlers, PDO Connection protection, custom Session handlers, MySQL relational storage.

---

## 👥 فريق العمل والمساهمون (Contributors)
*   **سيد حرز الله** - Lead Software Architect & Systems Developer.
