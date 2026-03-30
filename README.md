# MedPhy-Explorer
# ⚛️ MedPhysExplorer - Interactive Medical Physics Infographic Website

![Medical Physics](https://img.shields.io/badge/Medical-Physics-blue)
![Three.js](https://img.shields.io/badge/Three.js-3D-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌟 Project Overview

**MedPhysExplorer** is an interactive, educational website designed to make medical physics concepts accessible and engaging. Created for medical physics students, healthcare professionals, and science enthusiasts, this website combines stunning 3D visualizations with comprehensive educational content to explain how physics principles power modern medicine.

### 🎯 Mission
*"Demystifying the Physics of Medicine"*

The website aims to bridge the gap between complex physics concepts and their practical medical applications, making the subject approachable for learners at all levels.

---

## 📁 Project Structure
medical-physics-website/

│
├── index.html # Home Page - Introduction to Medical Physics

├── principles.html # Core Principles Page - Physics Concepts

├── applications.html # Applications Page - Clinical Impact

├── README.md # Documentation (this file)

│
└── assets/ # (Optional) Additional resources

├── images/ # Image assets

└── models/ # 3D model files


---

## 🚀 Live Demo Features

### Page 1: Home - Introduction
- **Interactive 3D Atom Model**: Rotatable, zoomable atom with orbiting electrons and particle effects
- **Physics Principles Section**: Explains how physics powers medical technology
- **Medical Physics Pun**: Fun, engaging content to lighten the learning experience
- **Key Areas Cards**: Interactive cards for Diagnostic Imaging, Radiation Therapy, Nuclear Medicine, and Radiation Safety
- **Scroll Animations**: Smooth fade-in effects as you scroll

### Page 2: Core Principles
- **X-ray Physics Module**:
  - 3D X-ray tube visualization with moving electrons
  - Adjustable kVp and mA sliders with real-time visual feedback
  - Multiple-choice quiz with impact explanations
  
- **MRI Physics Module**:
  - 3D visualization of hydrogen protons in magnetic field
  - Adjustable magnetic field strength slider
  - RF pulse button to simulate spin flip
  - Comprehensive quiz with detailed feedback
  
- **Radiation Therapy Module**:
  - 3D LINAC and tumor visualization
  - Beam energy slider affecting particle intensity and color
  - Pulsing tumor animation based on beam energy
  - Interactive quiz with physics explanations

### Page 3: Applications & Impact
- **Interactive Body Explorer**:
  - 3D human body model with clickable organ hotspots
  - Detailed physics explanations for each imaging modality
  - Covers Brain, Chest/Lungs, Heart, Liver, Prostate/Uterus
  
- **Cancer Treatment Comparison**:
  - Before/after visualization of tumor response
  - PSA level tracking and symptom severity metrics
  - Explanation of the physics behind treatment response
  
- **Dose Distribution Map**:
  - 3D color-coded dose distribution visualization
  - Tumor dose vs. organ-at-risk sparing metrics
  
- **Future Technologies Section**:
  - Proton Therapy: Bragg peak physics
  - FLASH Radiotherapy: Ultra-high dose rate effects
  - AI-Assisted Planning: Machine learning optimization
  - Theranostics: Diagnostic + therapeutic radionuclides
  
- **Global Impact Statistics**:
  - Treatment outcomes improvement data
  - Global adoption metrics

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure and semantic markup |
| **CSS3** | Styling, animations, responsive design |
| **JavaScript** | Interactivity, DOM manipulation, quiz system |
| **Three.js** | 3D graphics, animations, particle systems |
| **Google Fonts** | Inter and Montserrat typography |

---

## 🎨 Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Deep Navy | `#0B1E33` | Primary background |
| Charcoal Blue | `#1A2A3A` | Secondary background |
| Slate Gray | `#253544` | Card surfaces |
| Medical Blue | `#2A7DE1` | Primary accent |
| Teal | `#20C9B0` | Secondary accent |
| Soft Purple | `#8B5CF6` | Highlight accent |
| Amber | `#FBBF24` | Warning/radiation |

---

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop**: Full 3D experience with all interactive features
- **Tablet**: Adjusted layouts with touch-friendly interactions
- **Mobile**: Simplified navigation, optimized 3D performance

---

## 🧠 Educational Content

### Physics Principles Covered

| Module | Key Concepts |
|--------|--------------|
| **X-ray Physics** | Bremsstrahlung, characteristic radiation, kVp, mA, attenuation |
| **MRI Physics** | Nuclear magnetic resonance, Larmor equation, T1/T2 relaxation, RF pulses |
| **Radiation Therapy** | Photon interactions, dose distribution, Bragg peak, IMRT, LINAC |
| **Diagnostic Imaging** | CT, PET, SPECT, Ultrasound physics |
| **Nuclear Medicine** | Positron annihilation, gamma camera, radionuclide decay |

---

## 💡 Interactive Features

### Quizzes
- **Multiple-choice questions** with immediate feedback
- **Impact explanations** for each answer option
- **Progressive quizzes** with multiple questions per module
- **Score tracking** at quiz completion

### 3D Interactions
- **Click and drag** to rotate 3D models
- **Scroll to zoom** for detailed viewing
- **Hover effects** on interactive elements
- **Real-time parameter adjustment** with visual feedback

### Hotspots
- **Click on body parts** in the interactive anatomy model
- **Detailed physics explanations** for each imaging modality
- **Visual feedback** with pulsing animations

---

## 🎯 Learning Objectives

After exploring MedPhysExplorer, users will be able to:

1. **Understand** how X-rays are produced and interact with matter
2. **Explain** the principles of magnetic resonance imaging (MRI)
3. **Describe** how radiation therapy treats cancer
4. **Identify** appropriate imaging modalities for different body systems
5. **Appreciate** the role of physics in modern medical technology
6. **Recognize** emerging technologies in medical physics

---

## 🚦 Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Fully supported |
| Firefox | 88+ | ✅ Fully supported |
| Safari | 14+ | ✅ Fully supported |
| Edge | 90+ | ✅ Fully supported |
| Opera | 76+ | ✅ Fully supported |
| iOS Safari | 14+ | ✅ Supported |
| Chrome Android | 90+ | ✅ Supported |

---

## 📊 Performance Optimization

- **Lazy loading** of 3D assets
- **Efficient geometry** with optimized polygon counts
- **Mobile detection** for reduced particle count on phones
- **WebGL fallback** for unsupported browsers
- **Minified** CSS and JavaScript (production version)

