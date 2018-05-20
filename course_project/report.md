# Создание базы изображений участков земной поверхности и обучение свёрточной нейронной сети для их распознавания с борта дрона
##### Калабук Дмитрий

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
## Использованные подходы
- Классические алгоритмы
	- Линейный SVM
	- KNN
	- Random Forest (случайный лес)
- Нейронные сети для классификации
- Полноконволюционные нейронные сети для сегментации

---
## Сегментация
<img src="results/segmentation.png" alt="Drawing" style="width: 900px;"/>

---
## Номализация изображений
<img src="results/norm_example.png" alt="Drawing" style="width: 900px;"/>

---
## Данные с OpenStreetMap
<img src="results/germany0.png" alt="Drawing" style="width: 400px;"/>
<img src="results/germany0_mask.png" alt="Drawing" style="width: 400px;"/>

---
# Спасибо за внимание!