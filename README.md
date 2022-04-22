# RNN-vs-CNN

## Ведение

Этот небольшой эксперемент выполнясня мной в качаестве решения тестовой задачи для поступления на базовые кафедры МФТИ ИППИ РАН и ВЦ РАН.
В статье "Quasi-Recurrent Neural Networks" (https://arxiv.org/abs/1611.01576) рассматривалась новая архитектура нейронной сети для решения задач NLP. В статье удтвержданось, что новая модель обучается быстрее страндартных LSTM и показывает аналогичные результаты. Я решил это проверить. Кроме того в эксперимент я включил обычные RNN и CNN. При выполнении задачи частично использовался код семинара по RNN образовательного поекта Deep Learning School (https://www.dlschool.org).

## Эксперимент

В эксперименте я сравнивал модели по времени обучения и точности классификации на датасете ag_news от HuggingFace. Он состоит из небольших газетных статей, новости в которых делятся на четыре класса: "World, Sports, Business, Sci/Tech".

### CNN

<img src="https://user-images.githubusercontent.com/77685420/164813999-ac0e9282-9a68-4ca5-a101-8d9d0d880818.png" width="790" height="500">
<img src="https://user-images.githubusercontent.com/77685420/164814015-544dd15b-4f88-4c72-8b12-082bf9dff875.png" width="790" height="500">


