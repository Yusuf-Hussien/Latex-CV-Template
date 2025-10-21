# 📄 LaTeX CV Template

A professional and elegant **CV template** built using **LaTeX**, designed for use with [Overleaf](https://www.overleaf.com/) or your local LaTeX environment.

---

## 🖼️ Preview

![CV Template Preview](./assets/Preview.jpg)

---

## 🚀 Getting Started


### Option 1: Overleaf Template
1. Go to [This Overleaf Template](https://www.overleaf.com/read/hwcyskcxprgv#7470ac).
2. Click **Menu → Copy Project**.
3. Open `sections` and start editing your information.

### Option 2:Create Overleaf Template from this Repositoy
1. Go to [Overleaf](https://www.overleaf.com/).
2. Click **New Project → Upload Project**.
3. Upload all files from this repository.
4. Open `sections` and start editing your information.

### Option 3: Local Setup
1. Make sure you have LaTeX installed.  
   - For Windows: install [MiKTeX](https://miktex.org/download)
   - For Linux: `sudo apt install texlive-full`
   - For macOS: install [MacTeX](https://tug.org/mactex/)
2. Clone this repository:
   ```bash
   git clone https://github.com/Yusuf-Hussien/Latex-CV-Template.git
   cd Latex-CV-Template
   ```
3. Compile the main file:
   ```bash
   pdflatex resume.tex
   ```

---

## 🧩 Files Structure

```
.
├── resume.tex          # Main LaTeX file
├── style.tex          # contains style and customization
├── sections/         # Folder containing CV sections (Experience, Education, etc.)
├── README.md         # This file
└── assets/           # Optional folder for icons or additional resources
```

---

## 🪄 Customization

- Update your **personal info** in `sections/` directory.
- Adjust formatting or colors in  `style.tex` section.

---

## 📬 License

This project is open-source
- Author [Mohamed Hany](linkedin.com/in/mohammedhanymaher)
- Enhanced By [Yusuf Hussien](linkedin.com/in/yusuf-7ussien)
