# Лабораторная работа 5
«Модели создания и функционирования потоков»

## Условие
> Реализовать умножение матрицы на вектор

* Разработать многопоточные приложения в вариантах:
	* **Модель делегирования I**: 
	> ![](http://res.cloudinary.com/dzsjwgjii/image/upload/v1493855905/ps-5-1.png)
  > *Управляющий поток создаёт новый поток для каждого нового запроса*

	* **Модель делегирования II**:
  > ![](http://res.cloudinary.com/dzsjwgjii/image/upload/v1493855905/ps-5-2.png)
  > *Управляющий поток создаёт пул потоков, которые обрабатывают все запросы*

* Представить таблицу с результатами вычислительных экспериментов.

## Отчёт
![](http://res.cloudinary.com/dzsjwgjii/image/upload/v1493992391/ps-5-3.png)