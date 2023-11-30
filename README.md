# <a name="up" /> Тестирование функционала формы регистрации сайта [kinomax.ru](https://kinomax.ru)

Целью  являлось тестирование функционала формы регистрации сайта Kinomax.ru путем применения различных методов тестирования, а также определения видов дефектов, их выявление и фиксация.<br>

### Для достижения поставленной цели были решены следующие  задачи: <br>
- использованы методы функционального и нефункционального тестирования;<br>
- для увеличения плотности тестового покрытия применены не критичные  методы функционального тестирования   (такие как  эквивалентное разбиение и граничные значения);<br>
- разработана тестовая документация:<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 1. для наглядного видения функционала формы регистрации и этапов тестирования была структурирована [интеллект-карта (mindmap)](#mind-map) <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2. для логичности и последовательности проверок был составлен  [чек-лист](#check-list), что позволило структурировать информацию<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 3. были разработанны и пройденны  [тест-кейсы](#test-cases) с методами эквивалентного разбиения и граничных значений<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 4. на основании тест-кейсов оформлены [баг-репорты](#bug-reports)<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 5. составлен итоговый  [отчет с результатом и анализом тестирования](#test-result-report), где был сделан [список выполеных проверок](#list-of-completed-checks) и [список дефектов](#list-of-defects) <br>
- сделана оценка эффективности проведенного тестирования на основе сбора итоговых результатов с помощью  [метрик и графиков](#metrics-and-graphs);<br>
  


<img src="https://i.ibb.co/kQrVGCc/2023-11-29-030222.jpg" alt="2023-11-29-030222" border="0">

## <a name="testings" />Тестовая документация 

## <a name="mind-map" />Mindmap
<img src="https://i.ibb.co/G9gwWHw/image.jpg" alt="image" border="0">

## <a name="check-list" />Check list
Разбили задачи на множество подзадач, упрощая и акцентируя внимание на деталях <br>

<img src="https://i.ibb.co/PYq61fy/1.jpg" alt="1" border="0">
<img src="https://i.ibb.co/5KqhHRY/2.jpg" alt="2" border="0">

## <a name="test-cases" />Test cases

<img src="https://i.ibb.co/NWw5RMD/1.jpg" alt="1" border="0">
<img src="https://i.ibb.co/5x5bHBx/2.jpg" alt="2" border="0">
<img src="https://i.ibb.co/kmXMb0v/3.jpg" alt="3" border="0">
<img src="https://i.ibb.co/3Sh0DFx/4.jpg" alt="4" border="0">
<img src="https://i.ibb.co/xFnFNpr/5.jpg" alt="5" border="0">

## <a name="bug-reports" />Bug reports

<img src="https://i.ibb.co/dfD9wq9/1.jpg" alt="1" border="0">
<img src="https://i.ibb.co/L6z7trg/2.jpg" alt="2" border="0">
<img src="https://i.ibb.co/rmZnqmy/3.jpg" alt="3" border="0">
<img src="https://i.ibb.co/j8vJVhq/4.jpg" alt="4" border="0">

# <a name="test-result-report" />Test result report
## Отчет о тестировании формы регистрации сайта [kinomax.ru](https://kinomax.ru) <br>
 ### Введение.<br>
В данном отчете представлены выводы по результатам испытаний, также общая статистика по  найденным дефектам, которые были выявлены в результате тестирования и составленной тестовой документации. <br>
Основной задачей было проведение  тестирования  функционала формы регистрации сайта [kinomax.ru](https://kinomax.ru), а так же ее корректного отображения на различных устройствах (Desktop, mobile device, emulator) и в разных браузерах.
###Описание объекта тестирования.<br>
Был протестирован модуль формы регистрации сайта [kinomax.ru](https://kinomax.ru) со следующими подмодулями:<br>
-Текстовые поля ввода:   Введите ваш email; Введите ваше имя; Введите вашу Фамилию; Введите пароль; Подтвердите пароль<br>
-Кнопка выпадающего списка (drop-down button) с выбором пола<br>
-Чек-боксы: "О новостях компании" ; "Политика конфиденциальности"<br>
### Тестовое окружение:<br>
Тестирование было проведено: в 2-ух браузерах: Yandex Браузер 22.9.1.1095  и  Mozila Firefox;  на системе OS Windows 11 ( разрешение: 1920 x 1080) <br>
Мобильное тестирование  проведено на девайсе: Huawei p smart 9 (разр: 2160х1080)<br>
Во время тестирования использовались инструменты: Developer Tools<br>
### Описание процесса тестирования<br>
В рамках тестирования  были проведены следующие виды тестирования: <br>
-Функциональное тестирование: дымовое smoke; не критическое функциональное тестирование (проверка полей на ввод данных методами эквивалентного разбиения и граничных значений); позитивное и негативное тестирование.<br>
-Нефункциональное: UI тестирование; тестирование удобства использования (Usability); тестирование безопасности; тестирование локализации; кроссплатформенность и кроссбраузерность;<br>
-Дополнительно проводилось ad-hoc тестирование и тестирование прерывания (для мобильного устройства)<br>
Не проводилось тестирование : Производительности<br>
### Статистика по дефектам. <br>
Было создано 40 тест-кейсов. Из которых 19 имеют статус "passed", 20 "failed" и 1 "blocked". В период испытаний был выявлен 21 дефект. Из них 2 критических, 16 средней важности и 3 тривиальных. [Список дефектов](#list-of-defects) приведен ниже. Так же для большей эффективности отслеживания дефектов и улучшения качества продукта  были выбраны и составлены необходимые [метрики и графики](#metrics-and-graphs). <br> 
### Рекомендации.<br>
 По результатам тестирования формы регистрации, можно сделать следующие выводы: в целом основные функции  модуль выполняет успешно, но с некоторыми замечаниями по пользовательскому интерфейсу и удобству использования.  При вводе невалидных значений в поля отсутствуют подсказки, либо они являются некорректными  и имеют разногласие в оповещениях и с фактически введенными данными.  Приходится заполнять всю форму целиком и уже потом пытаться понять, в каких полях допущена ошибка.  Есть и критические дефекты, которые рекомендуется устранить в первую очередь - особенно, это касается  удобства использования на доступность. Например, для людей со слабым зрением при увеличении масштаба в десктопной версии, регистрация становится затруднительной, страница не прокручивается и исчезает кнопка "зарегистрироваться". Также критическая проблема возникает при перемещении при помощи клавиш TAB и Enter, - пытаясь выбрать обязательный чек-бокс "Пользовательское соглашение" и завершить регистрацию, нас вместо этого перебрасывает на ссылки, потому что велика область кликабельности чек-бокса и не происходит выделение этого модуля  при табуляции. <br>

## <a name="list-of-completed-checks" />List of completed checks

<img src="https://i.ibb.co/DfXLvFb/1.jpg" alt="1" border="0">
<img src="https://i.ibb.co/4dR208r/2.jpg" alt="2" border="0">
<img src="https://i.ibb.co/c2fyQ50/3.jpg" alt="3" border="0">


## <a name="list-of-defects" />List of defects

<img src="https://i.ibb.co/k6N7L3B/1.jpg" alt="1" border="0">
<img src="https://i.ibb.co/vPT8KjJ/2.jpg" alt="2" border="0">

## <a name="metrics-and-graphs" /> Metrics and graphs

<img src="https://i.ibb.co/PzG8sbL/2023-11-29-044009.jpg" alt="2023-11-29-044009" border="0">
<img src="https://i.ibb.co/QcJ7vdJ/2023-11-29-044031.jpg" alt="2023-11-29-044031" border="0">
<img src="https://i.ibb.co/Z1s7FKf/2023-11-29-044113.jpg" alt="2023-11-29-044113" border="0">
<img src="https://i.ibb.co/MnZ74gj/2023-11-29-044155.jpg" alt="2023-11-29-044155" border="0">
<img src="https://i.ibb.co/ggVT3z9/2023-11-29-044220.jpg" alt="2023-11-29-044220" border="0">





