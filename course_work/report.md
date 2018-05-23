# Создание базы изображений участков земной поверхности и обучение свёрточной нейронной сети для их распознавания с борта дрона
##### Калабук Дмитрий
##### Руководитель: Калиновский А.А.
##### Оффициальный руководитель: Ковалёв В.А.

---
## Использованные алгоритмы
- Классические алгоритмы машинного обучения
	- Линейный SVM
	- KNN
	- Random Forest (случайный лес)
- Нейронные сети для классификации
- Полноконволюционные нейронные сети для сегментации

---
## Подготовка данных
<center>
<img src="regions/Grodno0/ESRI_z16.jpg" alt="Drawing" style="height: 280px;"/>
<img src="regions/Brest0/ESRI_z16.jpg" alt="Drawing" style="height: 280px;"/>
<img src="results/grodno0_mask.png" alt="Drawing" style="height: 280px;"/>
<img src="results/brest0_mask.png" alt="Drawing" style="height: 280px;"/>
</center>

---
## Проблема вариативности данных
| <img src="results/yandex.png" alt="Drawing" style="width: 200px;"/> | <img src="results/bing.png" alt="Drawing" style="width: 200px;"/> | <img src="results/google.png" alt="Drawing" style="width: 200px;"/> | <img src="results/esri.png" alt="Drawing" style="width: 200px;"/> |
|-|-|-|-|
|Yandex | Bing | Google | ESRI |

---
# Подходы к решению проблемы вариативности данных
- Аугментация
- Номализация изображений
<img src="results/norm_example.png" alt="Drawing" style="width: 900px;"/>
- Доменная адаптация

---
## Результат сегментации
<img src="results/segmentation.png" alt="Drawing" style="width: 900px;"/>

---
## Данные из OpenStreetMap
<img src="results/germany0.png" alt="Drawing" style="width: 400px;"/>
<img src="results/germany0_mask.png" alt="Drawing" style="width: 400px;"/>

---
## Результаты сегментации зданий
<img src="results/z20_03_g.png" alt="Drawing" style="width: 800px;"/> 

---
## Результаты сегментации зданий
<img src="results/z20_03_m.png" alt="Drawing" style="width: 800px;"/>

---
## Результаты сегментации зданий
<img src="results/20_03_gg.png" alt="Drawing" style="width: 800px;"/>

---
#### Исходный код:
https://github.com/kalabukdima/earth-surface-segmentation
# Спасибо за внимание!
