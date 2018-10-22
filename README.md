## Тема

Просто о сложном: опыт создания курсов по C++ на Coursera

## Аннотация

В своём докладе я хочу рассказать:
* как устроена наша специализация по C++
* какие принципы лежат в основе процесса создания наших курсов
* как устроена наша тестирующая система
* какие нетривиальные задачи нам пришлось решить в процессе её создания

## Мотивирующие мысли

* (+) Stroustrup: "Teaching is relatively easy. Getting people to learn is hard"
* (+) Stroustrup: "Don't teach features. The standard says what's valid, not what's useful"
* (+) Stroustrup: "The purpose of good teaching is getting ideas into people's heads"
* Stroustrup: "Most students are not like you" - добавить в историю по перезагрузке
* ODR не работает при объяснении
* Kate Gregory: "C++ is not only for smart people"
* (+) Мы забили на производительность до определенного момента
* (+) using namespace std везде, придёт время, расскажем
* Мы жертвуем полнотой и строгостью изложения ради понятности. Нам важно, чтобы после каждого примера, каждого объяснения, каждого видео в голове слушателя мелькала мысль: "Я понял"
* (+) Можно рассказать, как мы учим людей писать тесты
* Когда мы решаем, рассказывать про фичу или нет, мы задаём вопрос, а какие практические задачи она помогает решать.

## Цель

* пропиарить наши курсы - увеличить количество людей, которые о них знают
* рассказать технические детали проверки решений - лишний раз упомянуть принципы KISS и YAGNI и показать, как простые решения полезны на практике

Какие интересные и полезные истории о наших курсах я бы мог рассказать:
* Страуструп говорит: "Don't be too clever". Рассказать нашу историю о перезагрузке. Изначально программа создавалась с опорой на Майерса, Саттера, Александреску и т.д. Хотелось сделать так же круто, но по-русски. Страуструп говорит: "Don't go bottom up". Рассказать, что мы не пользовались вектором, потому что это шаблон класса, а шаблоны мы ещё не проходили.
* Программирование на C++ - это навык, его нельзя приобрести сразу, на это нужно время. Навыки нарабатываются практикой, поэтому что-то сделать важнее, чем о чём-то услышать.
* Понятность важнее полноты. Демонстрация с переливанием воды. Человек не способен сразу воспринять весь объём информации, поэтому её надо давать частями, выделяя время на усвоение.

## Цитаты отзывов

* Являясь программистом, который на время продолжительного декрета ушел в сказки про Колобков и Зайчиков, было очень не просто вернуться опять в профессию... В этом мне Ваш курс очень сильно помог.
* Один курс, наверное, пол года или год обучения в универе заменил.
* Великолепный курс, великолепные преподы! Приду еще :)
* Команда курса показывает, насколько это простой и удобный инструмент. Как же у меня отлегло от сердца, когда понял, что если не хочешь - можешь С++ использовать как язык очень даже высокого уровня! Ну вот на самом деле: Си - это почти ассемблер, а Си++ - это уже почти что Python (только сильно быстрее и строго типизированный).
* Огромное спасибо, этот курс показал мне нормальный C++, а не тот, которому меня учили в университете.
* Вашим курсам, парни, можно доверять. Спасибо!)
* Отличный курс! Мне он дал базовое понимание языка С++, ООП и, что самое важное, реальную практику программирования.
* На работе пригодились и знания по декомпозиции, и по контейнерам и алгоритмам. и по юнит-тест фреймворку. Сложное финальное задание. В некоторых местах задачи были простые, в некоторых пришлось мнго времени потратить на обдумывание. В целом курс классный, С++ тренируется, и преподаватели хорошо все объясняют.
* Anton Eryomin: «Добрый день, Илья. На мой взгдяд есть несколько отличительных особенностей, что отличает курс от всех остальных. Во-первых,  это количество заданий. Многие задания на других курсах довольно малочисленны и выглядят больше как упражнения, да и тех очень мало. Во-вторых, это сами задания. Это именно не упражнения на повторение синтаксиса, а каждый раз это мини программа. В-третьих, это соотношение между продолжительностью видео и информации в нем. Видео не затянуты, те вам не приходится каждую неделю просматривать триллогию «Властелин колец», но при этом вы и не стараетесь за 5 минут пересказать весь С++. Ну и в четвертых, лично для меня, это сисьема оценивания заданий. Получив ошибку вида wrong test 6/16 нас (как учеников) подлалкивает к перечитыванию задания, дебаггингу кода и продумыванию тестовых сценариев. Вот 4е пункта, которые лично для меня отличают курс от всех остальных»
* Alexander Maltsev: «Когда преподаватель пишет код попутно объясняя что делается - это воспринимается более понятно и живо по сравнению с демонстрацией готовых фрагментов, которые часто разбирают в других курсах. По сути получается парное программирование, пусть и удалённое, что является мощным инструментом обучения»
* Boris Egorov: «Я думаю, вы нашли отличный баланс между теорией и практикой. Теории достаточно для усвоения материала, а десятки примеров и задач здорово закрепляют знания.
Ещё очень понравился проект, который на протяжении жёлтого пояса пишется. Собирает воедино весь материал. При этом достаточно других задачек, чтобы не заскучать. Ах да, и ещё очень радует идиоматичное использование последних стандартов C++, огонь прям! Я не встречал курсов по плюсам (даже на английском), которые бы настолько основательно подходили к выбору тем, подходов, задач. А я многое смотрел =) 3-4 курса на Степике, курс от Майкрософта на edX, что-то ещё на Coursera. Всё не то. Либо старые стандарты и вообще почти не о C++ (Stepik, mail.ru) либо очень поверхностный материал и задачи (EdX), либо уж слишком глубокий, требующий неплохого опыта (Stepik, CSC/mail.ru). Пожалуй, ближе всех к вам подошёл другой курс Яндекса, тоже на Stepik (Михаил Густокашин ведёт, если не ошибаюсь в имени). Но он более простой, для совсем новичков (хотя бы в силу того, что это не серия курсов).»
* Я хотела вас поблагодарить за то, что вы сделали курс настолько понятным, что даже семиклассница смогла его пройти и понять. Благодаря вам я сделала первый шаг к своей мечте!
* Я бывший юрист меняю профессию, занимаюсь самообучением и уже почти опустил руки пока не нашел ваши курсы. На данный момент благодаря Вам усиленно учусь постигаю профессию своей мечты.

## Концепция доклада

* Надо обязательно рассказать, что мы делаем. Описать специализацию, цели и методы преподавания
* Можно убрать или сократить историю про перезапуск
* Не упоминать Страуструпа и не тратить время на аналогии с повседневной практикой
* Но надо накинуть технического мясца
  * Описать устройство тестирующей системы на высоком уровне
    * Docker → Ubuntu → Python → C++
  * Кратко описать наш юнит-тест фреймворк
    * Мы показывали в программе, что учим тестировать код, сейчас я расскажу подробности
    * Написали свой юнит-тест фреймворк, чтобы люди не воспринимали его как магию, а понимали, как он устроен внутри; кроме того, для его использования достаточно только тех знаний, которые были у них на тот момент
    * Показываем, как выглядит юнит-тест и функция main
    * Показываем код TestRunner'а
  * Как мы тестируем интерфейс:
    * Привести пример задачи
    * Показать заготовку, которую мы выдаём
    * Описать проблему — нам надо уметь удалять функции из кода, особенно функцию `main` (на примере задачи SendNotifications)
    * Рассказать, что пробовали руками, но решение плохое, так как баланс скобок не учитывает комментарии
    * Поняли — зачем удалять, когда можно переименовать?!
    * Попробовали clang-rename, но он не подошёл.
    * Оставили простое решение — нашли объявление функции и переименовали её.
    * Работает как часы уже 1,5 года!
  * Как мы ограничиваем использование заголовочных файлов
    * Показываем задачу SimpleVector и говорим, что самое простое её решение — использовать внутри `std::vector`
    * Нам надо запретить использовать стандартные контейнеры и уметь проверять это автоматически
    * Парсить код участника и заглядывать в секцию `private` — хачно и выглядит ненадёжно
    * И тут мы вспомнили, что у нас фиксирован компилятор! Нам не нужен кроссплатформенный способ, нам нужен способ, который работает с нашим компилятором
    * Мы посмотрели, как в нашем GCC именуются include-guard'ы, и вставили нужные ifdef'ы
  * Как мы используем detector idiom для улучшения feedback'а
    * На примере SimpleVector показываем, что нам надо проверить, что `operator[]` возвращает ссылку
    * Рассказываем, что если просто вставить в какой-то юнит-тест, то сообщение об ошибке получается страшное.
    * Упоминаем detector idiom

## План доклада

* Я являюсь соавтором онлайн-специализации по C++ на Coursera, которая разрабатывается Яндексом и МФТИ. В своём докладе я хочу рассказать вам о ней и о том, как мы её делаем.
* Рассказать о специализации и уже запущенных курсах
  * всего будет пять курсов, три из них уже запущены и имеют высокие оценки, над остальными мы во всю работаем
  * вопрос: кто слышал о поясах по С++?
  * описать целевую аудиторию
  * перечислить цели специализации, обратить внимание на их практичность - среди целей нет слов "знать" или "помнить", они все сформулированы как "уметь делать"
  * преподаватели — старшие разработчики Яндекса с богатым опытом участия в высоконагруженных распределённых проектах и преподавания в ШАД
* Теперь о том, как мы делаем курсы и сначала об ограничениях
  * мы делаем массовые онлайн-курсы, на которых одновременно обучаются сотни людей, поэтому у нас полностью автоматическая проверка работ
  * мы работаем в области обучения взрослых, которые тратят свои время и деньги, поэтому люди должны в каждый момент понимать, зачем они это делают
  * как следствие, очень важен ранний эффект - нельзя три недели пичкать сухой теорией, люди как можно скорее должны почувствовать, что научились делать что-то новое
  * и ещё одно ограничение, которое мы создали себе сами - мы не пересказываем учебник, а рассказываем только то, в чём обладаем опытом.
* Кратко изложить содержание первых трёх курсов
  * Упомянуть финальные проекты и сказать, что они сложные
* Описание тестирующей системы
  * Мы сказали, что у нас очень много задач и что все решения участников тестируются автоматически. Сегодня я хочу рассказать, как устроена наша тестирующая система, с какими задачами мы столкнулись, работая над ней, и как их решили.
  * Причём особенность этой истории в том, что в ней не будут упоминаться тёмные потаённые уголки С++ или какие-то внутренности компилятора. Хотя именно о таких вещах обычно рассказывают на конференциях. Нет, это история о том, как простые решения позволяют получить хорошие результаты на практике, а сужение задачи порой позволяет получить подходящий результат за разумное время.
  * Описываем тестирующую систему на высоком уровне в виде матрёшки
* Наш юнит-тест фреймворк
  * Я сказал, что у нас есть блок про юнит-тестирование, где мы объясняем, чем хороши юнит-тесты и как их писать.
  * При этом мы используем свой юнит-тест фреймворк, который разработали сами прямо в видеолекциях.
  * Нас можно раскритиковать за велосипедизм, однако это было сделано осознанно — описываем причины
  * Приводим код теста вместе с использованием TestRunner'а, показываем вывод на консоль.
  * Показываем код TestRunner'а, чтобы показать, что он устроен довольно просто
  * Показываем заготовку решения задачи с юнит-тестами, показывая, что мы таким образом стимулируем людей писать юнит-тесты
* Тестирование решений участников
  * Ставим проблему — человек присылает нам файл, в котором может содержаться функция `main`. Нам нужно запустить свою функцию `main` с юнит-тестами.
  * Рассказать, что пробовали руками, но решение плохое, так как баланс скобок не учитывает комментарии
  * Поняли — зачем удалять, когда можно переименовать?!
  * Попробовали clang-rename, но он не подошёл.
  * Оставили простое решение — нашли объявление функции и переименовали её.
  * Работает как часы уже 1,5 года!
* Как мы ограничиваем использование заголовочных файлов
  * Показываем задачу SimpleVector и говорим, что самое простое её решение — использовать внутри `std::vector`
  * Нам надо запретить использовать стандартные контейнеры и уметь проверять это автоматически
  * Парсить код участника и заглядывать в секцию `private` — хачно и выглядит ненадёжно
  * И тут мы вспомнили, что у нас фиксирован компилятор! Нам не нужен кроссплатформенный способ, нам нужен способ, который работает с нашим компилятором
  * Мы посмотрели, как в нашем GCC именуются include-guard'ы, и вставили нужные ifdef'ы
* Как мы используем detector idiom для улучшения feedback'а
  * На примере SimpleVector показываем, что нам надо проверить, что `operator[]` возвращает ссылку
  * Рассказываем, что если просто вставить в какой-то юнит-тест, то сообщение об ошибке получается страшное.
  * Упоминаем detector idiom
* Результаты
  * приводим статистику по числу учащихся и выпускников
  * показываем отзывы
* Заключение — ещё раз привести ключевые выводы, которые мы сделали в процессе работы над курсами по C++:
  * Stroustrup: "Teaching is relatively easy. Getting people to learn is hard". Понятность важнее полноты и строгости изложения. Если человек вас понял, он продвинулся по пути освоения темы. Если вы рассказали всё строго и полно, но люди вас не поняли, вы не принесли никакой пользы.
  * Программирование — это, в первую очередь, навык, который нарабатывается практикой. Поэтому что-то сделать важнее, чем о чём-то услышать. Это дополнительное оправдание превосходства понятности над полнотой. В конце концов, не так важно, что вы скажете в лекции, гораздо важнее, какие навыки приобретёт человек после обучения у вас.
  * Простые решения легко реализовывать, понимать и поддерживать
  * Отзыв семиклассницы: «создавая качественный образовательный контент, мы влияем на жизни людей, и это очень вдохновляет»