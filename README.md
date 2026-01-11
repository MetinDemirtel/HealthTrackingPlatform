# 🎯 Health Tracking Platform

A comprehensive, privacy-first health tracking web application with personalized water & calorie goals, body measurements, achievement badges, and smart progress predictions.

![Health Tracker](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

### 📊 Weight Tracking
- Daily weight entries with interactive chart
- BMI calculation and categorization
- Smart runrate predictions and timeline estimates
- Visual progress indicators

### 💧 Water Tracking
- **Personalized daily goals** based on gender and weight
  - Male: Weight × 37.5 ml
  - Female: Weight × 32.5 ml
- Quick add buttons (+250ml, +500ml)
- Progress bar visualization
- Automatic daily reset

### 🍎 Calorie Tracking
- **Science-based calculations** using Harris-Benedict formula
- BMR (Basal Metabolic Rate) computation
- TDEE (Total Daily Energy Expenditure) estimation
- Goal-adjusted targets:
  - Weight loss: TDEE - 500 kcal
  - Weight gain: TDEE + 300 kcal
- Daily tracking with progress visualization

### 📐 Body Measurements
- Waist, chest, hips, neck circumference
- Integrated with daily records
- Track changes independent of weight

### 🏆 Achievement System
8 unlockable badges:
- 🎯 First Entry
- 📅 7 Day Streak
- 🔥 30 Day Consistency
- 💪 2.5kg Milestone
- ⭐ 5kg Milestone
- 🏆 10kg Milestone
- 🎖️ 50% Progress
- 👑 Goal Achieved

### 📈 Data Export
- **Excel**: Complete data with multiple sheets
- **PDF**: Professional reports with pagination
- All measurements, water, and calorie data included

### 🎨 Design
- Modern glassmorphism UI
- Plus Jakarta Sans font family
- Responsive design (desktop, tablet, mobile)
- Smooth animations and transitions
- Accessibility-focused

## 🚀 Quick Start

### Option 1: Download and Open
1. Download `health-tracker-en.html` (English) or `saglik-takip-tr.html` (Turkish)
2. Open the file in any modern web browser
3. Start tracking immediately!

### Option 2: Host on GitHub Pages
1. Fork this repository
2. Go to Settings → Pages
3. Select main branch as source
4. Visit `https://yourusername.github.io/health-tracker`

### Option 3: Run Locally
```bash
# Clone the repository
git clone https://github.com/yourusername/health-tracker.git

# Open in browser
cd health-tracker
open health-tracker-en.html  # Mac
start health-tracker-en.html # Windows
```

## 📱 Usage

### Initial Setup
1. Click the **? button** in header for detailed guide
2. Enter your information:
   - Gender (for personalized calculations)
   - Age (for BMR calculation)
   - Start & target dates
   - Height (cm)
   - Starting weight (kg)
   - Target weight (kg)
3. Click **Start**

### Daily Routine
1. **Enter daily weight** (required)
2. **Add body measurements** (optional)
3. **Track water intake** using quick buttons or manual entry
4. **Log calories** consumed
5. Click **Save** to record

### Viewing Progress
- **Click on chart points** for detailed daily breakdown
- **Recent Entries** shows last 10 records with all data
- **Edit** button loads entry into form for updates
- **Progress indicators** show percentage toward goal

### Exporting Data
- **Excel**: Multi-sheet workbook with daily records and summary
- **PDF**: Formatted report with all measurements

## 🔧 Technical Details

### Technologies
- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Charts**: Chart.js
- **Export**: SheetJS (xlsx), jsPDF
- **Storage**: localStorage (client-side only)
- **No Backend**: Completely privacy-preserving

### Browser Support
- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

### Data Privacy
- **100% local storage** - your data never leaves your device
- **No tracking** - no analytics, cookies, or external calls
- **No account required** - instant start
- **Exportable** - full data ownership

## 📊 Calculation Formulas

### BMR (Basal Metabolic Rate)
```
Male: 88.362 + (13.397 × weight_kg) + (4.799 × height_cm) - (5.677 × age)
Female: 447.593 + (9.247 × weight_kg) + (3.098 × height_cm) - (4.330 × age)
```

### TDEE (Total Daily Energy Expenditure)
```
TDEE = BMR × 1.5 (lightly active activity level)
```

### Water Goal
```
Male: weight_kg × 37.5 ml
Female: weight_kg × 32.5 ml
```

### BMI (Body Mass Index)
```
BMI = weight_kg ÷ (height_m)²

Categories:
- < 18.5: Underweight
- 18.5 - 24.9: Normal
- 25.0 - 29.9: Overweight
- ≥ 30.0: Obese
```

## 🌐 Localization

Currently available in:
- 🇬🇧 **English** (`health-tracker-en.html`)
- 🇹🇷 **Turkish** (`saglik-takip-tr.html`)

Both versions include:
- Full feature parity
- Localized UI text
- Date formatting
- Export file naming

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- Additional language translations
- New achievement badges
- Additional chart types
- Dark mode theme
- Meal tracking integration
- Exercise logging
- Photo progress comparison

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Metin Demirtel**
- LinkedIn: [linkedin.com/in/metindemirtel](https://linkedin.com/in/metindemirtel)
- GitHub: [@metindemirtel](https://github.com/metindemirtel)

## 🙏 Acknowledgments

- Chart.js for beautiful visualizations
- SheetJS for Excel export functionality
- jsPDF for PDF generation
- Plus Jakarta Sans font by Tokotype

## 📸 Screenshots

### Main Dashboard
Comprehensive overview with stats, achievements, and progress indicators.

### Daily Entry Form
Integrated form for weight, measurements, water, and calories.

### Interactive Chart
Click any point for detailed breakdown with BMI, changes, and measurements.

### Achievement Badges
Gamified progress tracking with 8 unlockable badges.

### Export Options
Professional Excel and PDF reports with all your data.

## 🔮 Roadmap

- [ ] Dark mode theme
- [ ] Meal planning integration
- [ ] Exercise tracking
- [ ] Photo progress comparison
- [ ] Social sharing features
- [ ] Cloud sync (optional)
- [ ] Mobile app versions (iOS/Android)
- [ ] Additional languages (Spanish, French, German)

## 💡 Tips for Best Results

📅 **Weigh yourself consistently** - Same time each morning, before eating

💧 **Track water regularly** - Hydration affects weight measurements

🍎 **Be honest with calories** - Accurate logging leads to better insights

📏 **Update measurements weekly** - More frequent than weight changes

📊 **Focus on trends, not daily fluctuations** - Weight varies naturally

🎯 **Set realistic goals** - 0.5-1kg per week is healthy and sustainable

---

Made with ❤️ by Metin Demirtel | © 2026

*Star ⭐ this repo if you find it helpful!*
