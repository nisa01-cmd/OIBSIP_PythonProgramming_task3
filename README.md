# 🔐 Advanced Password Generator (Tkinter GUI)

A modern, visually appealing password generator built with Python using `Tkinter` and `ttkbootstrap`. It features a glass-style floating card interface, a tech-inspired background image, and customizable options for generating strong passwords.

---

## 🎯 Objective

To design and develop an interactive desktop-based password generator with:
- A stylish, modern user interface
- A futuristic background image
- Customizable options for password length and character sets
- A convenient clipboard copy feature

---

## 🛠️ Tools & Technologies Used

| Tool / Library     | Purpose                                  |
|--------------------|-------------------------------------------|
| Python             | Core programming language                 |
| Tkinter            | GUI framework (standard with Python)      |
| ttkbootstrap       | Modern themed widgets for Tkinter         |
| Pillow (`PIL`)     | Handling and displaying background image  |
| Random, String     | For password generation logic             |

> To install dependencies:

```bash
pip install ttkbootstrap pillow
````

---

## 🔧 Features Implemented

* 💠 Floating glass-style UI card over a tech-themed background
* 🎚️ Slider to choose password length
* ✅ Checkboxes to include:

  * Letters (A-Z, a-z)
  * Digits (0–9)
  * Symbols (!@#\$...)
* 🚀 Generate button to instantly create secure passwords
* 📋 Copy to clipboard button
* 📸 High-quality coding-themed background image
* Responsive design and modern color palette

---

## 🪜 Steps Performed

1. **Designed UI layout** using `ttkbootstrap` and `Tkinter` Frame system
2. **Integrated background image** using Pillow (`PIL.ImageTk`)
3. **Styled main content area** as a frosted-glass style "card" over the image
4. Added:

   * Password length slider
   * Character type toggle checkboxes
   * Generate + Copy buttons
5. Connected the **backend logic** for password generation
6. Added clipboard copy integration
7. Matched all colors/fonts with the background for high visual appeal

---

## 🎉 Outcome

* A completely standalone, beautiful, and functional desktop password generator app.
* Allows users to easily generate secure passwords with chosen character sets.
* Runs smoothly with a futuristic tech-inspired interface that enhances user experience.

---

## 🚀 How to Run

1. Clone or download this repository.
2. Ensure the image file (background) is in the same folder as the script.
3. Run the Python script:

```bash
python rpg.py
```

---

## 📂 File Structure

```
project-folder/
│
├── rpg.py
└── README.md
```

---

## 👤 Author

Made with ❤️ using Python, Tkinter, and ttkbootstrap.
Built for modern users who want both security and style.

```
