# Отчёт по лабораторной работе
## Свёрточные нейронные сети

### Студенты: 

| ФИО       | Роль в проекте                     | Оценка       |
|-----------|------------------------------------|--------------|
| Озеров Владимир Константинович |  |          |


> *Комментарии проверяющего*


## Pet Faces

В качестве основы для разработки использовалась архитектура нейронной сети AlexNet. Обучение модели проводилось в течение 20 эпох с использованием оптимизатора Adam при значении learning rate, равном 0.0001. Результаты показали, что точность модели достигла почти 62%, что было ожидаемым результатом. При этом точность в топ-3 составила 84%.
В случае двоичной классификации результаты были значительно лучше, достигнув 94%. Для этой задачи также была построена матрица ошибок, на которой чётко просматривалась диагональ, указывая на высокое качество классификации.
  
  
## Oxford Pets и Transfer Learing
Для классификации пород животных были обучены модели VGG16, VGG19 и ResNet. Процесс обучения проводился на протяжении 5 эпох при значении learning rate 0.0001. Наилучшие результаты на валидационной выборке показала модель ResNet, достигнув точности в 86%. В последующих задачах я буду использовать именно эту модель.

При выполнении бинарной классификации кошек и собак точность модели составила 99%. Точность в топ-3 и топ-5 для этой классификации достигла 100%.

Кроме того, была построена матрица ошибок, на которой чётко и ясно видна диагональ, что подтверждает высокую точность модели.

  
## Выводы
 В ходе выполнения лабораторной работы я освоил проектирование и обучение сверточных нейросетей, а также применение transfer learning для адаптации предобученных моделей к конкретным задачам. Я научился эффективно использовать модели AlexNet, VGG16, VGG19 и ResNet, оптимизируя гиперпараметры для повышения точности. Практические навыки работы с оптимизаторами, такими как Adam, позволили мне понять их влияние на производительность модели. Также я научился оценивать качество моделей с помощью матриц ошибок и анализа точности классификации. Эти знания и навыки стали основой для дальнейших исследований и разработки сложных нейронных сетей.