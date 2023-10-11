# Определение возраста покупателей по фото

 [ipynb](https://github.com/DinaGreb/Portfolio/blob/main/Computer_vision/Project2_vision_for_shop.ipynb)

## Описание проекта

Построить и обучить модель, которая по изображению с камеры определит приблизительный возраст человека. Такая функция нужна для контроля продажи алкоголя и для будущей аналитики чеков по возрастным группам.


## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- **matplotlib**
- **keras**
- **PIL**
- tensorflow.keras.preprocessing.image.**ImageDataGenerator**
- tensorflow.keras.models.**Sequential**
- tensorflow.keras.applications.resnet.**ResNet50**
- tensorflow.keras.layers**Conv2D, Flatten, Dense, AvgPool2D,MaxPooling2D,GlobalAveragePooling2D**
- tensorflow.keras.optimizers.**Adam**


## Общий вывод

Был проведен исследователький анализ фото в наборе, осуществлены необходимые аугментации. Была дообучена модель нейронной сети ResNet50, надстроены два последних ее слоя. Значение исходной метрики было достигнуто. Намечены дальнейшие шаги по возможному улучшению качества модели.


