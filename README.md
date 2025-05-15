# Yolo-captioining
🌸 Flower Detection with YOLOv8  
**Автоматическая детекция 14 видов цветов на изображениях**  
---
## 📋 Классы цветов  
1. Bellflower (Колокольчик)  
2. Black-eyed Susan (Рудбекия)  
3. Calendula (Календула)  
4. California poppy (Эшшольция)  
5. Carnation (Гвоздика)  
6. Daffodil (Нарцисс)  
7. Daisy (Ромашка)  
8. Dandelion (Одуванчик)  
9. Iris (Ирис)  
10. Magnolia (Магнолия)  
11. Rose (Роза)  
12. Sunflower (Подсолнух)  
13. Tulip (Тюльпан)  
14. Water lily (Кувшинка)  

---

### Локальная установка
```
git clone https://github.com/kgalimullina/Yolo-captioining
cd Yolo-captioining
streamlit run app.py
```
## Технические детали
#### Модель: YOLOv8 
#### Данные: 
 - Датасет  основной: https://drive.google.com/drive/folders/11uqwJ5_yap4T2M-04xr5cgyFlEL23UWw?usp=sharing
 - Дообучение на более 700 размеченных вручную фотографий с помощью label studio: https://drive.google.com/file/d/1lBm4XkbRg7GO2S6Yb1zVcL5jCFrY2EJF/view?usp=sharing
---
### Структура папок
- model.ipynb     # Ноутбук с начальной моделью
- yolo.ipynb        # Ноутбук дообучения YOLO
- metrics
   weights        # Веса моделей
     best.pt       # Лучшие веса YOLO
     last.pt       # Последние веса YOLO
   всякие графики 
- app.py         # Основное приложение

