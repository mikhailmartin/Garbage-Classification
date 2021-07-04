# Garbafe Classification
This project was implemented as part of the Bachelor's FQP (final qualifying work).  
I had to choose a theme for the FQP, and when I saw the video below on instagram, I immediately decided that I needed to try to do something similar.
Initially, there was no knowledge in the field of Computer Vision, so I managed to make only a neural network-classifier of digital images of garbage.
## Dataset
Stored in the "dataset" folder. [Kaggle dataset](https://www.kaggle.com/asdasdasasdas/garbage-classification) was taken as a basis.
Later, I expanded it with several classes of garbage, images for which I parsed from search engines. As a result, the dataset consists of 10 classes:
![](visualization\\histogramm.png)
## Neural Network
Stored in model.hdf5 and has the following architecture:
![](visualization\\nn.png)
Accuracy graph during training:
![](visualization\\accuracy_history.png)
Confusion matrix after training:
![](visualization\\confusion_matrix.png)

# Interpreter and environment
I used [Python 3.8.3](https://www.python.org/downloads/release/python-383/) interpreter.

I recommend using a virtual environment. It can be created with the following command:
```
python -m venv env
```
All required packages are collected in the requirements.txt file.
Remember to activate the virtual environment before installing the packages.
You can install packages with one command:
```
pip install -r requirements.txt
```

# Классификация мусора
Этот проект был реализован в рамках выполнения ВКР (выпускной квалификационной работы) бакалавра.  
Мне нужно было выбрать тему для ВКР, и, когда я увидел в instagram нижепредставленный ролик, сразу решил, что нужно попробовать сделать что-то подобное.
Знаний в области компьютерного зрения изначально не было, поэтому успел сделать только нейросеть-классификатор цифровых изображений мусора.
![](visualization\\motivation.gif)
## Набор данных
Хранится в папке "dataset". За основу был взят [датасет с Kaggle](https://www.kaggle.com/asdasdasasdas/garbage-classification).
В дальнейшем я его расширил несколькими классами мусора, изображения для которых парсил из поисковиков.
В итоге набор данных состоит из 10 классов:
![](visualization\\histogramm.png)
## Нейросеть
Хранится в model.hdf5 и имеет следующую архитектуру:
![](visualization\\nn.png)
График точности в процессе обучения:
![](visualization\\accuracy_history.png)
Матрица ошибок после процесса обучения:
![](visualization\\confusion_matrix.png)

# Интерпретатор и окружение
Я использовал интерпретатор [Python 3.8.3](https://www.python.org/downloads/release/python-383/).

Рекомендую использовать виртуальное окружение. Его можно создать следующей командой:
```
python -m venv env
```
Все необходимые пакеты собраны в файле requirements.txt.
Перед установкой пакетов не забудьте активирвоать виртуальную среду.
Вы можете установить пакеты одной командой:
```
pip install -r requirements.txt
```
