# NUTRISYNTH
### An Integrated Personalized Nutrition Intelligence & Digital Wellness Ecosystem

<p align="center">
  <strong>Beyond Calories. Towards Intelligent Nutrition.</strong>
  <br/>
  Transforming nutritional science into structured, personalized and actionable digital experiences.
</p>

<p align="center">
  <a href="https://nutri-synth-black.vercel.app/"><strong>EXPLORE LIVE PLATFORM ↗</strong></a>
  &nbsp; • &nbsp;
  <a href="https://github.com/astitwasi-11/NutriSynth"><strong>VIEW SOURCE CODE</strong></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-5.5-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-5.4-646CFF?logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-Integration-FFCA28?logo=firebase&logoColor=black" />
  <img src="https://img.shields.io/badge/Deployment-Vercel-black?logo=vercel" />
  <img src="https://img.shields.io/badge/License-See%20Repository-lightgrey" />
</p>

---

## 01 — Project Overview

Nutrition is a multidimensional system influenced by individual physiology, dietary composition, metabolic requirements, lifestyle patterns and long-term behavioural consistency.

However, nutritional information is frequently distributed across disconnected applications, static databases, independent calculators and conventional food-tracking platforms.

**NutriSynth** explores a more integrated approach.

It is a personalized nutrition intelligence and digital wellness ecosystem developed to connect nutritional calculations, dietary profiling, food composition, meal planning, nutrient awareness and behavioural tracking within a unified application.

The platform translates individual characteristics into estimated nutritional requirements and organizes them into practical digital workflows, allowing users to explore their nutritional profiles, discover food options, monitor consumption and understand their progress.

Developed using a modular React and TypeScript architecture, NutriSynth brings together computational nutrition models, structured food information, recommendation logic, interactive interfaces and optional cloud-based persistence.

The project focuses on three interconnected dimensions:

- **Nutritional Intelligence:** Estimating individual requirements through structured mathematical models and reference data.
- **Dietary Implementation:** Translating nutritional targets into meal recommendations, food selection and grocery planning.
- **Behavioural Continuity:** Supporting consistent wellness practices through tracking, progress monitoring and habit-oriented features.

The ultimate objective is to make personalized nutrition more accessible, interpretable and actionable through technology.

---

## 02 — Design Philosophy

NutriSynth is developed around the idea that nutritional planning should not be limited to calorie estimation.

A useful nutritional ecosystem must connect the entire process:

**Individual Profile → Nutritional Assessment → Dietary Planning → Food Consumption → Progress Monitoring → Continuous Improvement**

This approach establishes a relationship between nutritional requirements and everyday dietary decisions.

Rather than presenting isolated numerical outputs, the platform organizes information into interconnected modules that support different stages of an individual's nutritional journey.

### Core Development Principles

| Principle | Implementation Direction |
|---|---|
| Personalization | Individualized nutritional calculations |
| Scientific grounding | Established equations and nutritional references |
| Accessibility | Structured and understandable interfaces |
| Integration | Connected nutrition and wellness modules |
| Modularity | Independent, maintainable application components |
| Extensibility | Architecture prepared for future integrations |
| Transparency | Clear distinction between estimates and medical assessments |

---

## 03 — Platform Architecture & Functional Ecosystem

NutriSynth consists of interconnected functional modules designed to support personalized nutrition management.

### 3.1 Personalized Nutritional Assessment Engine

The nutritional assessment engine forms the computational foundation of the platform.

It processes user-specific characteristics to estimate energy expenditure and organize daily nutritional targets.

**Input parameters**

- Age
- Biological sex
- Height
- Body weight
- Physical activity level
- Dietary preference
- Nutritional objectives
- Food allergies and intolerances
- Relevant female life-stage information

**Computational outputs**

- Basal Metabolic Rate (BMR)
- Total Daily Energy Expenditure (TDEE)
- Estimated daily energy requirements
- Protein requirements
- Carbohydrate requirements
- Fat requirements
- Dietary fibre targets
- Selected micronutrient reference values

The engine uses the Mifflin–St Jeor equation for BMR estimation and activity-based multipliers for estimating total daily energy expenditure.

### 3.2 Intelligent Dietary Recommendation System

The dietary recommendation module connects nutritional targets with structured food and recipe information.

It supports personalized food exploration based on dietary preferences and selected restrictions.

**Functional capabilities**

- Vegetarian, non-vegetarian and vegan preferences
- Dietary restriction filtering
- Allergy and intolerance considerations
- Ingredient-based meal exploration
- Breakfast, lunch and dinner recommendations
- Recipe nutritional information
- Meal selection according to individual preferences

### 3.3 Micronutrient Intelligence & Deficiency Awareness

The micronutrient module provides structured nutritional information across 16 nutrient categories.

The system includes:

| Nutritional category | Examples |
|---|---|
| Vitamins | A, B12, C, D, E, K and Folate |
| Minerals | Iron, Calcium, Zinc, Magnesium, Iodine, Selenium and Potassium |
| Other nutritional components | Protein and Dietary Fibre |

The module supports the exploration of nutritional requirements, reference information and selected laboratory-result inputs.

Its purpose is educational nutritional awareness and preliminary screening support, not clinical diagnosis.

### 3.4 Smart Meal Planning System

The meal-planning environment translates nutritional preferences into organized meal options.

**Capabilities**

- Recipe discovery
- Meal-category organization
- Dietary preference filtering
- Cooking-time filtering
- Budget-oriented recipe categories
- Ingredient and allergy-related filtering
- Daily meal organization
- Four-meal planning workflow
- Nutritional breakdown of selected recipes
- Integration with daily food logging
- Grocery-list generation

### 3.5 Food Composition & Dietary Logging

The food logging module provides an interface for recording daily dietary consumption.

**Functional capabilities**

- Food database search
- Nutritional information retrieval
- Portion-size adjustment
- Calorie tracking
- Macronutrient monitoring
- Custom food entries
- Daily meal logging
- Integration with nutritional progress indicators

### 3.6 Visual Food Logging Interface

NutriSynth includes a photo-based food interaction workflow designed to support food selection and logging.

The current implementation uses predefined database-backed suggestions rather than a deployed computer-vision recognition model.

The module establishes a foundation for future image-recognition integration.

### 3.7 Conversational Nutrition Assistant

The integrated nutrition assistant provides a conversational interface for selected nutrition-related tasks.

Its current implementation uses structured information and locally implemented rule-based logic.

**Supported functional areas**

- Food and calorie lookup
- Macronutrient explanations
- Recipe guidance
- Nutrition-related educational responses
- Platform navigation
- Supported meal-logging interactions

It is designed as an extensible conversational layer rather than a substitute for professional nutritional consultation.

### 3.8 Wellness & Habit Management

The wellness module addresses the behavioural dimension of nutrition.

**Features**

- Daily wellness check-ins
- Hydration tracking
- Daily food and water logs
- Consecutive-day streak tracking
- Achievement indicators
- Daily wellness challenges
- Dedicated 30-day wellness challenge
- Challenge completion monitoring

### 3.9 Nutrition Analytics & Weight Monitoring

The analytics environment provides tools for tracking selected personal progress indicators.

**Capabilities**

- Weight-entry management
- Historical weight visualization
- Target-weight reference
- Nutritional target overview
- Weekly report interface
- PDF report generation

Historical analytics and compliance indicators depend on the availability of actual recorded data; illustrative indicators should not be interpreted as measured outcomes.

### 3.10 Smart Grocery Management

The grocery module connects meal planning with practical ingredient organization.

**Features**

- Categorized grocery lists
- Produce and vegetables
- Protein sources
- Dairy and alternatives
- Grains and bakery products
- Pantry essentials
- Custom grocery entries
- Shopping completion tracking
- PDF checklist export

---

## 04 — Computational Nutrition Framework

The computational layer is designed around established nutritional estimation methods.

### 4.1 Basal Metabolic Rate

The Mifflin–St Jeor equation is used to estimate basal metabolic rate.

For males:

BMR = 10W + 6.25H − 5A + 5

For females:

BMR = 10W + 6.25H − 5A − 161

Where:

- W = Body weight in kilograms
- H = Height in centimetres
- A = Age in years

### 4.2 Total Daily Energy Expenditure

Estimated energy expenditure is calculated using an activity multiplier.

TDEE = BMR × Activity Factor

### 4.3 Activity Classification

| Activity level | Multiplier |
|---|---:|
| Sedentary | 1.20 |
| Lightly Active | 1.375 |
| Moderately Active | 1.55 |
| Very Active | 1.725 |
| Extra Active | 1.90 |

### 4.4 Macronutrient Allocation

The platform organizes macronutrient targets around estimated daily energy requirements.

- Protein: Activity- and goal-dependent allocation.
- Carbohydrates: Energy allocation after accounting for protein and fat.
- Fat: Percentage-based energy allocation.
- Fibre: Reference-based daily target.

These calculations are estimates and should be interpreted with consideration of individual requirements.

### 4.5 Nutritional Reference Framework

The platform's nutritional information is informed by established nutritional resources, including:

- Indian Council of Medical Research (ICMR)
- World Health Organization (WHO)
- National Institutes of Health (NIH)
- USDA FoodData Central
- National Academies Dietary Reference Intakes

Reference datasets and recommendations may differ according to population, age, biological sex and physiological conditions.

---

## 05 — Technical Architecture

NutriSynth follows a component-oriented application architecture built around reusable interfaces, modular logic and separated functional responsibilities.

### Technology Stack

| Technology | Purpose |
|---|---|
| React 18 | Frontend application framework |
| TypeScript | Typed application development |
| Vite | Development and production build system |
| Tailwind CSS | Utility-based interface styling |
| Firebase Authentication | Optional user authentication |
| Cloud Firestore | Optional cloud data persistence |
| Lucide React | Iconography |
| jsPDF | PDF document generation |
| html2canvas | Interface-to-image rendering |
| PptxGenJS | Presentation generation dependency |

### System Architecture

```text
                    NUTRISYNTH
                        |
          +-------------+-------------+
          |             |             |
      USER LAYER    LOGIC LAYER   DATA LAYER
          |             |             |
     Dashboard     Nutrition       Food Data
     Onboarding    Calculations    Recipe Data
     Meal Planner  Recommendations Nutrient Data
     Analytics     Tracking Logic  User Records
          |             |             |
          +-------------+-------------+
                        |
                APPLICATION SERVICES
                        |
          +-------------+-------------+
          |             |             |
      Local Storage  Firebase     Reporting
                     Services     & Export
```

### Application Structure

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
    │   │   ├── Dashboard
    │   │   ├── Onboarding
    │   │   ├── SmartMealPlanner
    │   │   ├── DeficiencyCheck
    │   │   ├── FoodSearchLogger
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
    │   │   ├── recentFoods.ts
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

## 06 — Installation & Local Development

### System Requirements

- Node.js 20 or newer recommended
- npm package manager
- Git
- Modern web browser

### Step 1 — Clone the Repository

```bash
git clone https://github.com/astitwasi-11/NutriSynth.git
```

### Step 2 — Navigate to the Project

```bash
cd NutriSynth/NutriSynth-main
```

### Step 3 — Install Dependencies

```bash
npm install
```

### Step 4 — Configure Environment Variables

For optional Firebase integration, create a `.env` file in the application directory.

```env
VITE_FIREBASE_API_KEY=your_api_key
VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
VITE_FIREBASE_PROJECT_ID=your_project_id
VITE_FIREBASE_APP_ID=your_app_id
```

Use the actual configuration values from your Firebase project.

Do not commit private environment files or credentials.

### Step 5 — Start Development Server

```bash
npm run dev
```

### Step 6 — Generate Production Build

```bash
npm run build
```

### Step 7 — Preview Production Build

```bash
npm run preview
```

---

## 07 — Data Management & Persistence

NutriSynth supports browser-based storage and optional Firebase integration.

The persistence architecture is designed to support different application environments.

| Component | Responsibility |
|---|---|
| Local Storage | Browser-based persistence and fallback functionality |
| Firebase Authentication | Optional authentication |
| Cloud Firestore | Optional cloud-based data synchronization |
| Structured Data Modules | Food, recipe and nutrient reference information |

Cloud-based capabilities depend on the configured Firebase services and applicable security rules.

---

## 08 — Development Roadmap

NutriSynth is an evolving platform with opportunities for further technical and nutritional development.

### Planned Development Directions

- [ ] Computer-vision-based food recognition.
- [ ] Expanded Indian food composition database.
- [ ] Advanced meal optimization algorithms.
- [ ] More comprehensive nutritional reference validation.
- [ ] Advanced female-specific nutrition pathways.
- [ ] Improved historical dietary analytics.
- [ ] Wearable health data integration.
- [ ] Multilingual nutritional interfaces.
- [ ] Expanded food allergy and intolerance validation.
- [ ] Advanced personalized reporting.
- [ ] External nutrition database integration.
- [ ] Enhanced cloud synchronization and data management.

---

## 09 — Health, Safety & Limitations

NutriSynth is an educational and informational nutrition platform.

All calculated nutritional values are estimates derived from mathematical models and structured reference information.

The platform is not a medical diagnostic system and does not replace:

- Clinical nutritional assessment.
- Laboratory investigations.
- Registered dietitian consultation.
- Medical treatment or professional healthcare guidance.

Nutrient screening information must not be interpreted as confirmation of a deficiency. Users with medical conditions, pregnancy-related nutritional requirements or other specialized needs should consult qualified healthcare professionals.

---

## 10 — Contribution & Open Development

NutriSynth welcomes technical feedback, suggestions and contributions.

Developers interested in improving the platform can:

1. Fork the repository.
2. Create a dedicated feature branch.
3. Implement and test their changes.
4. Submit a pull request.
5. Describe the proposed changes and their technical relevance.

```bash
git checkout -b feature/new-feature
git add .
git commit -m "Add: feature description"
git push origin feature/new-feature
```

---

## 11 — Project Information

| Attribute | Details |
|---|---|
| Project | NutriSynth |
| Category | Personalized Nutrition & Digital Wellness |
| Architecture | Component-oriented web application |
| Frontend | React + TypeScript |
| Build System | Vite |
| Cloud Integration | Firebase |
| Deployment | Vercel |
| Development Status | Active |

### Project Resources

**Live Application**

https://nutri-synth-black.vercel.app/

**GitHub Repository**

https://github.com/astitwasi-11/NutriSynth

**Developer**

Astitwa Si

GitHub: https://github.com/astitwasi-11

---

## 12 — Closing Perspective

NutriSynth represents an exploration of how computational methods, nutritional science and software engineering can be brought together to address everyday nutritional challenges.

The project moves beyond isolated calorie calculations and explores a connected framework involving nutritional estimation, dietary recommendations, food information, behavioural tracking and analytical interpretation.

Its architecture is intended to evolve through better datasets, validated calculations, expanded integrations and improved personalization.

**The broader vision is to transform nutrition from disconnected information into a more structured, understandable and actionable digital experience.**

---

<p align="center">
  <strong>NUTRISYNTH</strong>
  <br/>
  <em>Beyond Calories. Towards Intelligent Nutrition.</em>
  <br/><br/>
  Built with curiosity, computational thinking and a commitment to better nutritional awareness.
  <br/><br/>
  © 2026 Astitwa Si
</p>
