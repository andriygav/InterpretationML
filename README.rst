##############################################################
Visualisation of Machine Learning Training  and Interpretation
##############################################################

Yellowbrick
===============
Утилита для визуализации данных в машинном обучении. Обертка над sklearn, позволяющая выводить сразу метрики качества, автоматически выполнять отбор признаков, для моделей из sklearn.

- `Документация <https://www.scikit-yb.org/en/latest/>`_.
- `Пример в ноутбуке <https://github.com/andriygav/InterpretationML/blob/master/yellowbrick/main.ipynb>`_.

Local Interpretable Model-agnostic Explanations (LIME)
========================================================
Метод предназначен для интерпретации моделей машинного обучения. Работает на основе ресемплинга данных в окрестности некоторой точки и постронения локально линейно моделей. На основе построенной линейной модели получается важность того или иного признака объекта. Для текста это важность того или иного слова. Для изображения это важность той или иной части изображения.

- `Статья <https://arxiv.org/pdf/1602.04938.pdf>`_.
- `Документация <https://github.com/marcotcr/lime>`_.
- `Пример в ноутбуке <https://github.com/andriygav/InterpretationML/blob/master/lime/main.ipynb>`_.

TensorBoard
===============
Утилита для отслеживания моделей во время их обучения (оптимизации параметров).

- `Документация <https://pytorch.org/docs/stable/tensorboard.html>`_.
- `Пример для LSTM <https://github.com/andriygav/InterpretationML/blob/master/tensorboard/lstm.ipynb>`_.
- `Пример для CNN <https://github.com/andriygav/InterpretationML/blob/master/tensorboard/CNN.ipynb>`_.
- `Пример для FNN <https://github.com/andriygav/InterpretationML/blob/master/tensorboard/FNN.ipynb>`_.
