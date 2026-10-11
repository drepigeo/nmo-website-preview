# National Medicos Organisation (NMO) — Official Website

Official website for the **National Medicos Organisation (NMO)** (*स्वास्थ्य सेवा, राष्ट्र सेवा* — *Swasthya Sewa, Rashtra Sewa*), an all-India fraternity uniting qualified allopathic doctors, dental surgeons, medical educators, and students in service of rural, tribal, and border frontiers of Bharat since 1977.

## 1. Website Structure & Architecture

The website is engineered as a clean, cohesive, multi-page static web application designed for deployment on any standard web hosting service or **GitHub Pages**. All pages share a consistent visual identity, responsive navigation header, official NMO logo, utility bar, and institutional footer.

```
nmo-website/
│
├── index.html                  # Main Official Homepage
│                               # - 4 Core Constitutional Aims
│                               # - Founder Spotlight Card
│                               # - Complete Historical Timeline (1977–2026)
│                               # - Key Activities & Sewa Overview
│                               # - Medical Education & Publications
│                               # - Events & NMOCON Conclaves
│                               # - Office Bearers & Leadership
│                               # - Membership Framework (₹1500 / ₹2500 / ₹200)
│                               # - Verified Secretariat & Registered Office Details
│
├── founder.html                # Dedicated Founder Page
│                               # - Biography of Dr. Dhanakar Thakur
│                               # - DMCH Medical Education & Academic Record
│                               # - Role in 1977 NMO Genesis (Aug 8 Samaul, Nov 5 Varanasi)
│                               # - Editorial Legacy of Aayurvigyan Pragati (1981)
│                               # - Grassroots Clinical Practice in Rural Bihar
│                               # - Institutional Archival Advisory & Verification Notice
│
├── activities.html             # Dedicated Activities & Sewa Portal
│                               # - Interactive Category Filtering
│                               # - Current Programmes (Dhanvantari Sewa Yatra, RKSSY, Village Adoption)
│                               # - Documented Historical Relief Archives (1980s Floods, 1988 Sickle Cell, 2014 Kashmir)
│                               # - Volunteer Recruitment & Delegation Linkages
│
├── styles.css                  # Unified Global Stylesheet
│                               # - Medical Navy (#0b2545) & Saffron (#d97706) Palette
│                               # - CSS Grid & Flexbox Layouts
│                               # - Responsive Breakpoints (320px, 360px, 390px, 430px, 768px, 1024px, 1280px, 1440px)
│                               # - Clean Typography, Buttons, Badges & Modals
│
├── nmo_logo.png                # Official Circular NMO Seal (400×400 PNG, Transparent Alpha)
│
├── assets/                     # Mirrored Directory Structure (for flexible paths)
│   └── images/
│       └── nmo_logo.png        # Mirrored Logo Asset
│
└── verification_report.md      # Archival Fact-Verification & Executive Ratification Report

```

## 2. GitHub Pages Deployment Steps

Follow these steps to publish the complete website to **GitHub Pages**:

### Step 1: Create or Initialize Git Repository

In your terminal, navigate to the folder containing these files:

```
git init
git add .
git commit -m "Initial commit: Complete unified NMO official website"

```

### Step 2: Push to GitHub

Create a new public repository on GitHub (e.g., `nmo-official-website` or `nmoindia`), and push your local branch:

```
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main

```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub.

2. Click on **Settings** (top navigation tab).

3. In the left sidebar, click on **Pages** (under the "Code and automation" section).

4. Under **Build and deployment**:

   * **Source**: Select `Deploy from a branch`.

   * **Branch**: Choose `main` and folder `/ (root)`.

5. Click **Save**.

### Step 4: Access Your Live Website

Within 1–2 minutes, GitHub Actions will build and deploy the site. Your website will be accessible at:

```
https://<your-username>.github.io/<your-repo-name>/

```

*Tip: If you configure a custom domain (e.g., `nationalmedicos.org`), add a `CNAME` file containing `nationalmedicos.org` in the root folder and configure your DNS A records pointing to GitHub Pages IP addresses.*

## 3. Verified Contact Information

* **Registered Office:** C/o Mishra Polytechnic, Leheriasarai, Bihar – 846001

  *(Regd. under Societies Registration Act, 1860, Reg. No. 21/1987-88)*

* **Working Office / Founder Desk:** C/o Dr. Dhanakar Thakur, Village: Samaul, P.O.: Bisrair, Via: Pandaul, District: Madhubani, Bihar – 847234

* **Contact Helpline:** [+91-9843376861](tel:9843376861) | **Desk:** [+91-11-41324967](tel:+911141324967)

* **Secretariat Email:** [nmosecretariat@gmail.com](mailto:nmosecretariat@gmail.com)

* **Founder Email:** [dhanakar@gmail.com](mailto:dhanakar@gmail.com)