# numerology-calculator
# NUMEROLOGY CALCULATOR

A single-page web application for calculating numerology values based on Thai and English names, following Thai astrology standards.

## 📦 Project Structure

```
numerology-calculator/
├── index.html           # Main application page (HTML, CSS, JS)
├── css/
│   └── styles.css       # (optional) External stylesheet
├── js/
│   └── app.js           # (optional) External JavaScript
├── data/
│   └── Numerology_map.json  # Numerology mapping data
├── assets/
│   └── logo.png         # Logo file
├── README.md            # This documentation
├── LICENSE              # Open-source license
└── .github/
    └── workflows/       # CI/CD configurations (optional)
```

## 🚀 Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/<username>/numerology-calculator.git
   cd numerology-calculator
   ```

2. Open `index.html` in your browser:

   * Double-click the file, or
   * Serve via a local HTTP server:

     ```bash
     npx http-server .
     ```

## 🌐 GitHub Pages Deployment

To publish the app:

1. Push this repository to GitHub.
2. In **Settings > Pages**, set **Branch** to `main` and **Folder** to `/ (root)`.
3. The site will be available at:

   ```
   https://<username>.github.io/numerology-calculator/
   ```

## 📝 Usage

1. Enter your Thai name and surname, and your English first and last name.
2. Click **Calculate**.
3. View:

   * **Master Mapping** table (value, consonants, vowels, tone marks, English letters).
   * **Results** for Thai and English, showing total sum and reduced single digit.
   * **Calculation Details** to see individual character values.

## 🛠️ Customization

* **Mapping Data**: Edit `data/Numerology_map.json` to adjust letter–value mapping.
* **Styles**: Modify variables in `<style>` or `css/styles.css` for colors, fonts, spacing.
* **Script**: Enhance interactivity in `js/app.js`.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

© NAKOLEO 2025
