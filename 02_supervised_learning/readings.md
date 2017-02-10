# Обучение на размеченных данных

Второй [курс](https://www.coursera.org/learn/supervised-learning/) из [специализации Машинное обучение и анализ данных](https://www.coursera.org/specializations/mashinnoye-obucheniye) от МФТИ и Yandex Data Factory.

Содержание:

1. Машинное обучение и линейные модели
2. Борьба с переобучением и оценивание качества
3. Линейные модели: классификация и практические аспекты
4. Решающие деревья и композиции алгоритмов
5. Нейронные сети и обзор методов



## Интересные ресурсы

#### Ресурсы по материалам 1 недели:

* В заданиях прошедшей недели вам пришлось рисовать много графиков и отправлять их на проверку коллегам — наверняка Вы заметили, что это не так уж просто. [Вот](http://www.ruf.rice.edu/~bioslabs/tools/data_analysis/graphic_examples.html?utm_source=coursera&utm_medium=coursera&utm_campaign=2-1-1-res)
* Машинное обучение часто противопоставляют классическому математическому моделированию. [Тут](https://miguelgfierro.com/blog/2016/a-gentle-introduction-to-the-basics-of-machine-learning/?utm_source=coursera&utm_medium=coursera&utm_campaign=2-1-2-res) вы можете прочитать о том, что это такое и в чём заключаются отличия.
* Градиентный спуск на пальцах разобран вот [здесь](https://nplus1.ru/material/2016/09/06/mistakesflow?utm_source=telegram&utm_campaign=autumn).

#### Ресурсы по материалам 2 недели:

* Под переобучением можно понимать не только ситуации, в которых модель слишком сильно подгоняется под данные. Статью про другие способы переобучиться можно найти [Link](http://hunch.net/?p=22&utm_source=coursera&utm_medium=coursera&utm_campaign=2-2-1-res)
* Поначалу метрика AUC-ROC может казаться очень нелогичной, но на самом деле у неё есть много интерпретаций. [Link](http://stats.stackexchange.com/questions/132777/what-does-auc-stand-for-and-what-is-it?utm_source=coursera&utm_medium=coursera&utm_campaign=2-2-2-res)

#### Ресурсы по материалам 3 недели:

* Как вы узнали из прошедшего модуля, в логистической регрессии оптимизируется метрика log-loss. [Тут](http://rdipietro.github.io/friendly-intro-to-cross-entropy-loss/?utm_source=coursera&utm_medium=coursera&utm_campaign=2-3-1-res) можно чуть больше узнать о том, откуда она берётся.
* Некоторые практические рекомендации по работе с линейными моделями можно [найти](http://www.astroml.org/sklearn_tutorial/practical.html?utm_source=coursera&utm_medium=coursera&utm_campaign=2-3-2-res).

#### Ресурсы по материалам 4,5 недели:

* Интересную визуализацию обучения и применения решающих деревьев можно [найти](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/?utm_source=coursera&utm_medium=coursera&utm_campaign=2-4-1-res).
* Машинное обучение можно применять для решения достаточно неожиданных задач — например, определять пол по имени. [Подробности](http://blog.ayoungprogrammer.com/2016/04/determining-gender-of-name-with-80.html/?utm_source=coursera&utm_medium=coursera&utm_campaign=2-4-2-res).
* Если вам нравятся красивые картинки про работу композиций, то [сюда](http://manish-m.com/?p=794&utm_source=coursera&utm_medium=coursera&utm_campaign=2-4-3-res).
* А [тут](https://www.analyticsvidhya.com/blog/2016/02/complete-guide-parameter-tuning-gradient-boosting-gbm-python/?utm_source=coursera&utm_medium=coursera&utm_campaign=2-4-4-res) можно прочитать о том, как настраивать параметры градиентного бустинга в sklearn.
* Посмотреть на то, как выглядят разделяющие поверхности у нейросетей при разных значениях гиперпараметров, можно [здесь](http://playground.tensorflow.org/?utm_source=coursera&utm_medium=coursera&utm_campaign=2-4-5-res#activation=tanh&batchSize=10&dataset=circle&regDataset=reg-plane&learningRate=0.03&regularizationRate=0&noise=0&networkShape=4,2&seed=0.53436&showTestData=false&discretize=false&percTrainData=50&x=true&y=true&xTimesY=false&xSquared=false&ySquared=false&cosX=false&sinX=false&cosY=false&sinY=false&collectStats=false&problem=classification&initZero=false&hideText=false)



## Список литературы

Мы составили для вас список наших любимых учебников по темам, рассматривавшимся в этом курсе, с короткими комментариями. Лучше всего изучать прямо в такой последовательности.

* Hastie, Tibshirani, Friedman. *The elements of statistical learning* — классический способ начать знакомиться с машинным обучением, если вас не пугает математика
* Bishop. *Pattern recognition and machine learning* — (чрезмерно) подробный справочник методов, дающий возможность познакомиться, например, с десятью версиями метода главных компонент
* Murphy. *Machine learning a probabilistic perspective* — очень объемная и содержательная книга из MIT (~1000 страниц), освещена большая часть мейнстримовых методов машинного обучения.

Если в начале математика в *The elements of statistical learning* покажется сложной, можно попробовать облегчённую версию учебника от тех же авторов — *James, Witten, Hastie, Tibshirani. An Introduction to Statistical Learning.*

Если хочется на русском, то можно начать с лекций [Константина Вячеславовича Воронцова](http://machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B0%D1%88%D0%B8%D0%BD%D0%BD%D0%BE%D0%B5_%D0%BE%D0%B1%D1%83%D1%87%D0%B5%D0%BD%D0%B8%D0%B5_%28%D0%BA%D1%83%D1%80%D1%81_%D0%BB%D0%B5%D0%BA%D1%86%D0%B8%D0%B9%2C_%D0%9A.%D0%92.%D0%92%D0%BE%D1%80%D0%BE%D0%BD%D1%86%D0%BE%D0%B2%29) по машинному обучению. Но решающие деревья в этом случае лучше изучить по *User Guide scikit-learn*, а градиентный бустинг и случайный лес — все-таки по *The elements of statistical learning*.

Если до погружения в математику хочется понять на инженерном уровне “что как работает”, то для этого хорошо подойдут:

* Harrington. *Machine Learning in Action* — дается базовое знакомство с методами машинного обучения, без перегрузки математическими деталями
* Marshland. *Machine Learning: An Algorithmic Perspective* — приводятся и объясняются реализации разных методов машинного обучения на Python
* Richert, Coelho. *Building Machine Learning Systems with Python* — очень доступное изложение разных задач машинного обучения (анализ изображений, текстов, звука) с описанием того, как это сделать в Python (прямо с кодом).

Отдельно про нейросети можно почитать:

* Хайкин. *Нейронные сети. Полный курс.*
* Goodfellow, Bengio, Courville. *Deep Learning* (для сильных духом любителей складывать слои как блинчики)
