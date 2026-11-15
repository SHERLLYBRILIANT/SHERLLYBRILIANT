# Hi, I'm Sherlly Briliant! 👋

I am an **Informatics Student** at Universitas Teknologi Yogyakarta (UTY) specializing in **Intelligent Systems**. I have a strong passion for data-driven applications, machine learning, and decision support systems.

---

### 🚀 Top Projects

* [**GiziLens — Toddler Nutritional Status & Stunting Detection System (Tugas Akhir**](https://github.com/SHERLLYBRILIANT/projek-TA-Vercell) ([Live Demo](https://projek-ta-vercell.vercel.app)) Clinical decision support web application for early stunting detection and toddler nutritional monitoring powered by multi-output TabNet deep learning models tuned via Optuna on >42,000 anthropometric records from Jeneponto Regency, achieving 95.31% test accuracy on Weight-for-Age (BB/U), 94.04% on Height-for-Age/Stunting (TB/U), and 95.72% on Weight-for-Height (BB/TB). Engineered for serverless production by exporting PyTorch TabNet checkpoints to lightweight ONNX Runtime (~15 MB) with a tiered WHO Z-Score rule-based fallback, supporting individual and bulk batch CSV/Excel screening, interactive WHO growth curves (-3SD to +3SD), clinical anomaly cross-validation, and automated PDF/Excel medical reporting.
  * Tools & Technologies:
    * **Python & Flask 3.0:** Core MVC backend handling Bcrypt-secured authentication, role-based access control, clinical anthropometric range validation, and batch spreadsheet ingestion.
    * **PyTorch, TabNet, ONNX Runtime & Optuna:** Deep learning training pipeline with Optuna Bayesian hyperparameter tuning, exported to lightweight ONNX Runtime for fast serverless inference with a WHO Z-Score fallback engine.
    * **TiDB Cloud Serverless & MySQL 8.0 (PyMySQL):** TLS-encrypted cloud relational database (AWS Singapore) storing toddler profiles and multi-output diagnostic logs via a pure-Python PyMySQL adapter.
    * **Bootstrap 5, Chart.js & SweetAlert2:** Responsive Neo-Brutalism pastel UI rendering interactive WHO standard deviation growth trajectories, model evaluation metrics, and searchable child selectors.
    * **ReportLab & OpenPyXL:** Automated generation of printable PDF medical examination sheets and `.xlsx` health department recaps.
    * **Docker & Vercel:** Multi-container local orchestration (Flask, MySQL, phpMyAdmin) and stateless serverless cloud deployment.

* [**Weather Analytics — Dashboard & Prediction (MLP)**](https://github.com/SHERLLYBRILIANT/projek-siscer-prediksi-cuaca-mlp) ([Live Demo](https://projek-siscer-prediksi-cuaca-mlp.vercel.app)) Database-less weather analytics and classification system powered by a Multilayer Perceptron (`19 → 72 → 104 → 5`) trained on 10,255 records with 19 engineered features, achieving 98.86% test accuracy and 0.9112 Macro F1 across 90 Bayesian Optimization trials. Executes pure Go inference at runtime with an interactive analytics dashboard, automatic missing-value imputation, derived feature explanations, and out-of-range warnings.
  * Tools & Technologies:
    * **Go 1.21 (Golang):** Core backend language executing pure serverless inference (imputation, feature engineering, standard scaling, and MLP forward pass) with embedded model weights and zero Python runtime dependencies.
    * **Python & scikit-learn:** Offline machine learning pipeline performing data preprocessing, 90-trial Bayesian hyperparameter optimization, and automated Go source code generation for trained weights and EDA metrics.
    * **HTML5, CSS3 & Vanilla JavaScript:** Structuring the dark-blue 4-tab analytics dashboard and interactive weather prediction interface.
    * **Chart.js:** Locally bundled visualization library rendering class distributions, Bayesian optimization histories, and model evaluation metrics.
    * **Vercel:** Cloud platform hosting serverless Go API endpoints (`/api/predict` and `/api/dashboard`) with continuous deployment from GitHub.

* [**Cek Akun Fake — Dashboard & Fake Account Detection (SLP)**](https://github.com/SHERLLYBRILIANT/projek-siscer-cek-akun-slp) ([Live Demo](https://projek-siscer-cek-akun-slp.vercel.app)) Database-less, self-contained social media classification system powered by a Single Layer Perceptron (Tanh activation) trained on 10,000 X (Twitter) accounts using 4 Mutual Information-selected features (`post_count`, `friends_count`, `followers_count`, and `verified`), achieving 93.75% test accuracy, 95.03% fake account recall, and 0.9704 ROC-AUC across 100 5-Fold CV optimization trials. Executes pure Go inference at runtime with embedded model weights (`embed.FS`), an interactive analytics dashboard with confusion matrix and borderline error analysis, and a real-time simulator displaying decision scales and feature-level weight contributions.
  * Tools & Technologies:
    * **Go 1.22 (Golang):** Core backend language executing pure serverless inference (StandardScaler normalization, SLP dot-product forward pass, and Tanh activation) with embedded JSON weights and static web assets via `embed.FS`—requiring zero external libraries or Python runtime dependencies.
    * **Python & scikit-learn:** Offline machine learning pipeline performing exploratory data analysis, Mutual Information feature selection (21 → 4 features), 100-trial 5-Fold Cross-Validation tuning, and exporting trained parameters.
    * **HTML5, CSS3 & Vanilla JavaScript:** Structuring the dark-indigo analytics dashboard and interactive prediction simulator featuring a dynamic decision scale and per-feature contribution breakdown.
    * **Chart.js:** Locally bundled visualization library rendering test scatter plots, profile metric comparisons, and hyperparameter tuning histories without external CDN dependencies.
    * **Vercel:** Cloud platform hosting serverless Go web pages and public REST API endpoints (`/api/predict`, `/api/dashboard`, `/api/model`, `/api/health`) with continuous deployment from GitHub.

* [**KosTrini — Boarding House Information System (Trini, Yogyakarta)**](https://github.com/SHERLLYBRILIANT/projek-web-sistem-informasi-kos-trini) ([Live Demo](https://projek-web-sistem-informasi-kos-trini.vercel.app)) Web-based boarding house (kos) catalog and facility management platform designed for students and residents in the Trini area of Yogyakarta. Features real-time room availability tracking, multi-criteria filtering (Putra/Putri/Campur, pricing, and facilities), property photo galleries, instant WhatsApp booking integration with pre-filled message templates, and a protected administrative CRUD dashboard built with multi-layer security (PBKDF2/SHA256 hashing, SQLAlchemy parameterized queries, Jinja2 XSS auto-escaping, and strict file upload sanitization).
  * Tools & Technologies:
    * **Python 3.11 & Flask:** Lightweight backend framework managing Blueprint routing, `@login_required` session protection, PBKDF2/SHA256 password hashing, and secure image upload validation (max 5 MB).
    * **SQLAlchemy ORM & PostgreSQL (Neon.tech):** Serverless SSL-encrypted cloud relational database persisting boarding house records and real-time room statuses independently of Vercel's ephemeral filesystem.
    * **Cloudinary CDN:** Cloud media storage delivering persistent, fast-loading property photo galleries directly via CDN URLs.
    * **Tailwind CSS & Google Fonts:** Crafting a clean, responsive UI/UX across both the public room-finder catalog and administrative management dashboard.
    * **Docker & Vercel:** Containerized local development via Docker Compose and automated serverless Python deployment on Vercel.

* [**Gudeg Yu Djum — Culinary & Menu Information System (Yogyakarta)**](https://github.com/SHERLLYBRILIANT/projek-web-sistem-informasi-rm-gudeg-yudjum) ([Live Demo](https://projek-web-sistem-informasi-rm-gudeg-yudjum.vercel.app)) Web-based culinary heritage and menu catalog platform showcasing Gudeg Yu Djum in Wijilan, Yogyakarta. Features real-time product availability across traditional variants (Nasi Gudeg, Gudeg Besek, Kendil, Kaleng, and Frozen), interactive category filtering, brand history timeline, outlet location details, and instant WhatsApp ordering with pre-filled message templates—engineered with a stateless modular data architecture (`MENU_DATA`) and Jinja2 XSS auto-escaping for seamless serverless hosting.
  * Tools & Technologies:
    * **Python 3.11 & Flask:** Lightweight server-side microframework managing route validation, category query filtering, safe static asset resolution (`url_for`), and modular `MENU_DATA` catalog storage without external database overhead.
    * **Jinja2, HTML5 & Vanilla CSS:** Server-side templating with automatic XSS escaping paired with responsive custom CSS, Google Fonts (`Playfair Display` & `DM Sans`), and Font Awesome 6 iconography.
    * **JavaScript (ES6+):** Delivering interactive UI behaviors including parallax hero sections, scroll-reveal animations, animated counters, and a responsive mobile navigation drawer.
    * **Docker & Vercel:** Containerized local development via Docker Compose and continuous serverless Python deployment on Vercel.

* [**Sistem Inventori Gedung Serbaguna — Facility & Booking System (Yogyakarta)**](https://github.com/SHERLLYBRILIANT/projek-web-sistem-inventori-gedung) ([Live Demo](https://projek-web-sistem-inventori-gedung.vercel.app)) Web-based multipurpose hall inventory and facility management platform in Yogyakarta designed to digitize hall catalogs and prevent double bookings. Features district-level search and filtering, an interactive real-time availability calendar, detailed capacity and pricing showcases, instant WhatsApp booking integration with pre-filled message templates, and a protected administrative CRUD dashboard for managing halls, rental schedules, and maintenance logs—hardened with Bcrypt password hashing, anti-CSRF form tokens, PDO prepared statements, and XSS output escaping.
  * Tools & Technologies:
    * **PHP 8.x Native (PDO):** Lightweight server-side architecture executing parameterized PDO queries, Bcrypt (`password_hash`) authentication, anti-CSRF form validation, `htmlspecialchars` XSS mitigation, and cURL API uploads without framework overhead.
    * **PostgreSQL (Neon.tech):** Serverless SSL-encrypted cloud relational database persisting hall inventories, booking schedules, and maintenance records independently of Vercel's ephemeral filesystem.
    * **Cloudinary CDN:** Cloud media storage delivering persistent, fast-loading hall photo galleries directly via CDN URLs.
    * **Tailwind CSS & Google Fonts:** Crafting a modern, responsive UI/UX across the public hall directory, interactive availability calendar, and administrative dashboard.
    * **Docker & Vercel:** Containerized local development via Docker Compose (Apache + PHP) and automated serverless PHP deployment on Vercel.

