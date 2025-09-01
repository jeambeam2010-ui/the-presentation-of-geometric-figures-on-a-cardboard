# 🔷 Определение геометрических фигур на изображении  

Проект для автоматического распознавания простых геометрических фигур (круги, квадраты, треугольники и др.) на изображениях.  
Используется **Python** и библиотеки компьютерного зрения (**OpenCV, NumPy, Matplotlib**).  

---

## 📌 Возможности
- 🖼 Загрузка изображения и обработка в серых тонах  
- ✨ Предобработка: бинаризация, сглаживание, выделение контуров  
- 🔺 Определение фигур: круги, квадраты, прямоугольники, треугольники, многоугольники  
- 📊 Отображение результатов с выделенными контурами и подписями  

---

## 🛠 Технологии
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff&style=flat)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=fff&style=flat)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=fff&style=flat)
![Matplotlib](https://img.shields.io/badge/Matplotlib-005C5C?style=flat)

---

## 🚀 Установка и запуск

```bash
# Клонировать репозиторий
git clone https://github.com/username/shapes-detector.git
cd shapes-detector

# Установить зависимости
pip install -r requirements.txt

# Запустить
python detect_shapes.py --image input.png
