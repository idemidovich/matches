Lucky Matches
===========

Приложение для айфона, иммитирующее вытягивание спичек, среди которых есть одна или несколько коротких

___

Проблема, которую решает приложение
---

Когда нужно выбрать неудачника который должен бежать за пивом обычно используют спички. Кто вытянет короткую - тот и бежит. Но в век прогресса,информационных технологий и электронных сигарет скорее под рукой может оказаться айфончик чем коробок спичек.

Аудитория приложения
---

Необходимость случайно выбрать одного из нескольких человек может возникнуть в очень разных ситуациях, поэтому аудитория приложения очень широкая. Любой пользователь айфона может захотеть иметь это приложение в своем телефоне.

Пример сценария использования приложения
---

Четыре друга встретили симпатичную девушку в баре. Друга четыре, а девушка одна. Нужно выбрать кто из ребят отлично проведет вечер в компании очаровательной представительницы слабого пола, а кому достанется лишь пиво и футбол. Один из друзей запускает приложение, введет количество участников(4) розыгрыша и количество счастливчиков(1), переходит к следующему окну и видит 4  наполовину закрытые спички. Каждый тянет одну спичку по собственному выбору. Одному из друзей достается счастливая короткая. Проблема решена без мордобоя!:)

Описание поведения.
---

* После загрузки приложения пользователь видит на экране 2 текстовых поля с подписями и кнопку "Тянуть"
Первое текстовое поле "Количество спичек" служит для ввода количества участников розыгрыша. Максимальное значение для этого поля 6, минимальное 2. Вводить можно только цифры.

* Второе текстовое поле "Короткие спички" служит для ввода количества участников которые могут выбрать. Максимальное  значение для этого поля на единицу меньше общего количества спичек. Минимальное значение 1. Вводить можно только цифры.

* По-умолчанию в полях "Количество спичек" и "Короткие спички" стоит 3 и 1 соответственно.

* Кнопка "Тянуть!" служит для перехода к окну, где могут быть вытянуты спички. В этом окне отображаются наполовину прикрытые спички, соответствующие количеству, введенному в первом окне. Часть спичек(по количеству веденному на первом окне) короче остальных, но этого не видно
    
* Все спички можно сдвигать пальцем вверх или вниз, пока они не будут видны на всю длину. Когда все спички будут вытянуты из-под прикрытия можно будет легко визуально определить, какие из них оказались короткими.

* Из второго окна можно попасть в первое окно настроек нажав на кнопку "Назад".

---

__На данном этапе разработки реализован только примерный интерфес приложения, который может быть изменен. Функциональность приложения еще не полная__

_sotoryboard файл находится в matches / Спички1 / Спички1 / en.lproj директории_