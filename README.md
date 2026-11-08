# 🥗 NutriSynth
### Personalized Nutrition Intelligence & Digital Wellness Platform

<p align="center">
  <strong>Turning personal health data into structured nutrition insights, practical meal planning, and sustainable wellness habits.</strong>
</p>

<p align="center">
  <a href="https://nutri-synth-black.vercel.app/"><strong>🌐 Explore Live Platform</strong></a> •
  <a href="https://github.com/astitwasi-11/NutriSynth"><strong>💻 Source Code</strong></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5.5-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-5.4-646CFF?logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-12-FFCA28?logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Deployment-Vercel-black?logo=vercel" />
  <img src="https://img.shields.io/badge/Status-Active-success" />
</p>

---

## 🌱 About NutriSynth

**NutriSynth** is a personalized nutrition intelligence and wellness platform designed to make nutritional planning more accessible, structured, and data-informed.

The platform brings together nutritional calculations, dietary profiling, meal recommendations, nutrient screening, food tracking, wellness challenges, and analytical insights within a unified digital environment.

Rather than treating nutrition as a collection of isolated calorie numbers, NutriSynth approaches it as an interconnected system involving individual requirements, dietary patterns, food composition, lifestyle factors, and long-term consistency.

Built with React, TypeScript, and Firebase integration, the platform combines a modular application architecture with a responsive interface and locally accessible nutrition tools.

**The central objective is simple:**

*Make personalized nutrition easier to understand, implement, monitor, and sustain.*

## 🎯 Core Objectives

- Develop an accessible personalized nutrition planning system.
- Translate individual characteristics into estimated nutritional requirements.
- Encourage informed food choices through structured nutritional information.
- Integrate dietary preferences and restrictions into meal recommendations.
- Provide nutrient-related educational and screening information.
- Support consistent wellness habits through daily tracking and challenges.
- Present nutritional information through understandable dashboards and reports.

---

## ✨ Platform Capabilities

### 01. Personalized Nutrition Engine

The nutrition engine calculates estimated nutritional requirements using individual profile information.

**User inputs include:**
- Age and gender
- Height and body weight
- Physical activity level
- Dietary preference
- Fitness and nutritional goals
- Food allergies and intolerances
- Female life-stage information, including pregnancy and lactation options

**Calculated outputs include:**
- Basal Metabolic Rate (BMR)
- Total Daily Energy Expenditure (TDEE)
- Daily calorie requirements
- Protein requirements
- Carbohydrate requirements
- Fat requirements
- Dietary fibre targets
- Estimated micronutrient intake

The system uses the Mifflin–St Jeor equation for its BMR calculations, followed by activity-based energy estimation and macronutrient allocation.

### 02. Personalized Meal Recommendation

NutriSynth incorporates a structured food and recipe database to generate meal recommendations according to individual dietary profiles.

**Capabilities:**
- Vegetarian, non-vegetarian, and vegan preferences
- Ingredient-based meal selection
- Dietary restriction filtering
- Breakfast, lunch, and dinner recommendations
- Macronutrient information for recommended meals
- Meal details and nutritional explanations

### 03. Nutrient Deficiency Information & Screening

A dedicated module provides nutritional screening information across 16 nutrients.

The module covers:

- Vitamin B12
- Vitamin D
- Iron
- Calcium
- Zinc
- Folate
- Vitamin A
- Vitamin C
- Vitamin E
- Vitamin K
- Magnesium
- Iodine
- Selenium
- Potassium
- Protein
- Dietary fibre

Users can explore recommended intake information, nutritional indicators, and optional laboratory-result inputs.

The purpose is to improve nutritional awareness and provide educational insights, not to diagnose medical deficiencies.

### 04. Smart Meal Planner

An integrated meal-planning module helps users explore and organize meals according to their requirements.

**Features:**
- Recipe discovery
- Meal-category filtering
- Dietary preference filtering
- Cooking-time filtering
- Budget-oriented recipe categories
- Allergy-related ingredient filters
- Daily four-meal planning
- Recipe nutritional breakdown
- Add meals to daily intake
- Transfer ingredients to grocery lists

### 05. Food Search & Nutrition Logger

The food tracking module allows users to record their daily food consumption.

**Features:**
- Searchable food database
- Nutritional information lookup
- Portion-size adjustment
- Calorie and macronutrient tracking
- Custom food entries
- One-step meal logging
- Daily nutrition progress integration

### 06. Food Photo Scanning Interface

NutriSynth also includes a photo-based food logging interface.

Users can access the scanning workflow and select suggested food items for nutritional logging.

**Implementation note:** The current recognition service uses predefined database-backed food suggestions. It is an extensible interface for future integration with an actual computer-vision recognition model.

### 07. NutriSynth Nutrition Assistant

The integrated nutrition chatbot provides conversational access to selected platform capabilities.

Its current functionality includes:

- Food and calorie lookup
- Macronutrient explanations
- Recipe recommendations
- Nutrition-related educational responses
- Contextual assistance using the active user profile
- Navigation to platform modules
- Direct meal logging through supported chat actions

The current assistant uses locally implemented rule-based logic and structured nutrition data.

### 08. Wellness Tracking & Habit Development

Nutrition is not only about calculating requirements. Consistency also matters.

NutriSynth incorporates habit-oriented modules to encourage sustainable daily practices.

**Included features:**
- Daily wellness check-ins
- Consecutive-day streak tracking
- Hydration tracking
- Daily food and water logs
- Achievement badges
- Daily wellness challenges
- Dedicated 30-day wellness challenge
- Challenge completion tracking

### 09. Nutrition & Weight Analytics

The analytics module provides tools for monitoring personal progress.

**Capabilities:**
- Weight-entry tracking
- Weight history visualization
- Target-weight reference
- Nutritional target overview
- Weekly report interface
- PDF report generation

Some weekly compliance indicators are currently illustrative rather than derived from a complete historical meal-tracking dataset.

### 10. Smart Grocery Management

A dedicated grocery management module connects nutritional planning with practical food purchasing.

**Features:**
- Categorized grocery lists
- Produce and vegetables
- Protein sources
- Dairy and alternatives
- Grains and bakery products
- Pantry essentials
- Custom grocery entries
- Completion tracking
- PDF checklist export

---

## ⚙️ Nutritional Calculation Framework

NutriSynth uses structured mathematical models and nutritional reference data to estimate individual requirements.

| Parameter | Calculation approach |
|---|---|
| BMR | Mifflin–St Jeor equation |
| TDEE | BMR × activity multiplier |
| Protein | Activity-based protein allocation |
| Carbohydrates | Remaining energy allocation |
| Fat | Percentage-based energy allocation |
| Fibre | Gender-based reference targets |
| Micronutrients | Structured nutrient reference data |

### Activity Multipliers

| Activity category | Multiplier |
|---|---:|
| Sedentary | 1.20 |
| Light | 1.375 |
| Moderate | 1.55 |
| Active | 1.725 |
| Extra Active | 1.90 |

These values are used as estimation factors, not direct measurements of metabolic expenditure.

### Nutritional Reference Framework

The platform's nutritional information is informed by reference material associated with:

- ICMR – Indian Council of Medical Research
- WHO – World Health Organization
- NIH – National Institutes of Health
- USDA FoodData Central
- National Academies Dietary Reference Intakes

Reference values and calculated outputs should be interpreted in the context of individual requirements and the limitations of the underlying datasets.

---

## 🏗️ Technology Stack

| Technology | Application |
|---|---|
| React 18 | Component-based user interface |
| TypeScript | Application logic and type safety |
| Vite | Development server and build system |
| Tailwind CSS | Interface styling |
| Firebase Authentication | Authentication integration |
| Cloud Firestore | Optional cloud data persistence |
| Lucide React | Interface icons |
| jsPDF | PDF report generation |
| html2canvas | HTML-to-image rendering |
| PptxGenJS | Presentation generation dependency |

### Application Architecture

```text
NutriSynth
│
├── Presentation Layer
│   ├── Landing Page
│   ├── User Onboarding
│   ├── Dashboard
│   ├── Meal Planner
│   └── Analytics
│
├── Nutrition Layer
│   ├── BMR & TDEE Calculations
│   ├── Macronutrient Allocation
│   ├── Food Database
│   ├── Recipe Recommendations
│   └── Nutrient Reference Data
│
├── Wellness Layer
│   ├── Food Logger
│   ├── Deficiency Information
│   ├── Hydration Tracking
│   ├── Daily Streaks
│   └── Wellness Challenges
│
├── Intelligence Layer
│   ├── Nutrition Assistant
│   ├── Food Lookup
│   └── Recommendation Logic
│
└── Persistence Layer
    ├── Local Storage
    ├── Firebase Authentication
    └── Cloud Firestore
```

---

## 📂 Project Structure

```text
NutriSynth/
│
└── NutriSynth-main/
    │
    ├── public/
    │
    ├── src/
    │   ├── assets/
    │   ├── components/
    │   │   ├── Dashboard.tsx
    │   │   ├── Onboarding.tsx
    │   │   ├── DeficiencyCheck.tsx
    │   │   ├── SmartMealPlanner.tsx
    │   │   ├── Chatbot.tsx
    │   │   └── ...
    │   │
    │   ├── context/
    │   ├── data/
    │   │   ├── foods.ts
    │   │   ├── nutrients.ts
    │   │   └── personalizedRecipes.ts
    │   │
    │   ├── lib/
    │   │   ├── calculations.ts
    │   │   ├── aiChatbot.ts
    │   │   ├── firebase.ts
    │   │   ├── cloudStore.ts
    │   │   ├── foodRecognitionService.ts
    │   │   └── streakService.ts
    │   │
    │   ├── App.tsx
    │   ├── index.css
    │   └── main.tsx
    │
    ├── index.html
    ├── package.json
    ├── package-lock.json
    ├── vite.config.ts
    ├── tailwind.config.js
    └── tsconfig.json
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js (recommended: Node.js 20 or newer)
- npm
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/astitwasi-11/NutriSynth.git
```

### 2. Navigate to the Application Directory

```bash
cd NutriSynth/NutriSynth-main
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Firebase (Optional)

Create a `.env` file inside `NutriSynth-main`:

```env
VITE_FIREBASE_API_KEY=your_firebase_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_APP_ID=your_firebase_app_id
```

Configure Firebase Authentication and Cloud Firestore if cloud-based accounts and synchronization are required.

Without Firebase configuration, the application supports local fallback functionality using browser storage.

### 5. Run the Development Server

```bash
npm run dev
```

### 6. Build for Production

```bash
npm run build
```

### 7. Preview Production Build

```bash
npm run preview
```

---

## 🔒 Data Handling & Privacy

NutriSynth supports both browser-based storage and optional Firebase cloud persistence.

- Guest and local fallback functionality uses browser storage.
- User profiles and nutrition results can be synchronized through Firestore when configured.
- Authentication can be provided through Firebase Authentication.
- Cloud synchronization depends on Firebase configuration and security rules.

Users should avoid entering sensitive medical information into an experimental application without reviewing its privacy and security arrangements.

---

## ⚕️ Health & Medical Disclaimer

NutriSynth is an educational and informational nutrition platform.

Its calculated values are estimates based on mathematical models and structured nutritional reference data.

The platform:

- Does not diagnose nutritional deficiencies.
- Does not replace laboratory investigations.
- Does not provide medical treatment.
- Does not replace a registered dietitian or qualified healthcare professional.
- May not account for every individual medical condition, medication interaction, or variation in nutrient absorption.

Always consult a qualified healthcare professional before making significant dietary changes, particularly during pregnancy, lactation, or when managing a medical condition.

---

## 🛣️ Future Development Roadmap

NutriSynth is designed as an extensible platform. Potential development directions include:

- [ ] Integration of a real AI-powered food image recognition model.
- [ ] More extensive Indian food composition datasets.
- [ ] Advanced recipe optimization.
- [ ] Real-time nutrition data integration.
- [ ] More comprehensive female-specific nutrition pathways.
- [ ] Historical nutrition trend analysis using actual logged data.
- [ ] Improved nutrient screening validation.
- [ ] Multilingual support.
- [ ] Expanded food allergy and intolerance validation.
- [ ] Advanced downloadable nutrition reports.
- [ ] Integration with wearable health data.

---

## 🤝 Contributing

Contributions, suggestions, and technical discussions are welcome.

If you would like to contribute:

1. Fork the repository.
2. Create a feature branch.
3. Implement and test your changes.
4. Commit your changes with a descriptive message.
5. Submit a pull request.

```bash
git checkout -b feature/your-feature
git add .
git commit -m "Add: your feature description"
git push origin feature/your-feature
```

---

## 👨‍💻 Project & Developer

**NutriSynth** is an independently developed project exploring the intersection of nutritional science, computational methods, software engineering, and digital wellness.

Developed by **Astitwa Si**

- GitHub: [@astitwasi-11](https://github.com/astitwasi-11)
- Project Repository: [NutriSynth](https://github.com/astitwasi-11/NutriSynth)
- Live Application: [nutri-synth.vercel.app](https://nutri-synth.vercel.app/)

---

## 📜 License

No license file is currently included in the inspected repository. Add a `LICENSE` file to explicitly define the terms under which others may use, modify, and distribute this project.

---

<p align="center">
  <strong>NutriSynth — Beyond Calories. Towards Intelligent Nutrition.</strong>
  <br/>
  <sub>Building a more informed, personalized, and sustainable approach to everyday nutrition.</sub>
</p>
