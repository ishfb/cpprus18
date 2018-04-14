## Тема

Как научить языку C++: опыт создания курсов на Coursera

## Аннотация

В своём докладе я хочу рассказать:
* с какими проблемами мы столкнулись в работе над курсами (например, через 3 месяца работы мы выбросили все материалы и начали заново)
* как мы формируем программу курсов и почему именно так (например, почему слово "указатель" не прозвучало в двух наших первых курсах ни разу)
* что мы узнали нового, работая над курсами и общаясь со слушателями
* байки, курьёзы и интересные факты

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

* дать практические советы по обучению и донесению информации до коллег
* пропиарить наши курсы

Я бы мог просто рассказать какие-то истории о том, как мы делаем специализацию. Но я не думаю, что это будет очень полезно для слушателей. Такой вариант хорош для дружеской встречи за кружкой пива. А это всё-таки выступление на конференции. Оно должно быть полезно слушателям. Поэтому его надо сделать так, чтобы люди, уходя, задумывались: «Хм, а вот это надо попробовать». Поэтому надо постараться переложить опыт дистанционного обучения языку С++ на повседневные задачи, которые выполняют IT-шники на работе.

Какие это могут быть задачи:
* интеграция нового сотрудника в проект
* code-review, на котором ты стараешься донести свой подход человеку, смотрящему на вещи совершенно иначе
* рассказ коллегам о том, как ты собираешься решать крупную задачу
* взращивание молодых программистов
* найм

В то же время это не должен быть доклад о том, как делать code-review или интегрировать нового сотрудника в проект. Эти задачи - это просто пример, на что можно переложить опыт.

Какие интересные и полезные истории о наших курсах я бы мог рассказать:
* Страуструп говорит: "Don't be too clever". Рассказать нашу историю о перезагрузке. Изначально программа создавалась с опорой на Майерса, Саттера, Александреску и т.д. Хотелось сделать так же круто, но по-русски. Страуструп говорит: "Don't go bottom up". Рассказать, что мы не пользовались вектором, потому что это шаблон класса, а шаблоны мы ещё не проходили.
* Программирование на C++ - это навык, его нельзя приобрести сразу, на это нужно время. Навыки нарабатываются практикой, поэтому что-то сделать важнее, чем о чём-то услышать.
* Понятность важнее полноты. Демонстрация с переливанием воды. Человек не способен сразу воспринять весь объём информации, поэтому её надо давать частями, выделяя время на усвоение.

## Концепция доклада

Мы начнём со ссылки на Страуструпа про "We are all teachers". Дальше пройдём по пунктам нашей большой картины и от каждого **будем пытаться** провести аналогию с адаптацией нового сотрудника, code-review, рассказом о большой идее.

Кроме того, надо привести примеры того, как мы объясняем те или иные особенности языка, чтобы доклад не был абстрактной болтовнёй. Наконец, содержание всей специализации, чтобы начальники понимали, стоит ли туда направлять молодняк.

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

## План доклада

* Я являюсь соавтором онлайн-специализации по C++ на Coursera, которая разрабатывается Яндексом и МФТИ. В своём докладе я хочу рассказать вам о ней и о том, как мы её делаем.
* Однако начну я немного с другого. На CppCon'2017 Страуструп выступил с докладом "Learning and Teaching Modern C++", в котором заявил, что мы все являемся учителями. За 1,5 года работы над специализацией у нас выработался набор принципов, которые, я уверен, применимы и в повседневной работе:
  * в процессе интеграции нового сотрудника в проект
  * во время code-review
  * при найме
Поэтому я не просто хочу рассказать, как мы делаем специализацию, но и попытаюсь переложить полученный опыт на повседневные задачи.
* Рассказать о специализации и уже запущенных курсах
  * всего будет пять курсов, два из них уже запущены и имеют высокие оценки, остальные увидят свет в течение 2018 года
  * описать целевую аудиторию
  * перечислить цели специализации, обратить внимание на их практичность - среди целей нет слов "знать" или "помнить", они все сформулированы как "уметь делать"
  * курсы о C++ 14/17
  * преподаватели - старшие разработчики Яндекса с богатым опытом участия в высоконагруженных распределённых проектах и преподавания в ШАД
* История о том, как мы начали, а потом всё выбросили
  * Итак, я говорил, что хочу рассказать, как мы делаем курсы, и начну с того, как мы начинали
  * Изначально программа создавалась с опорой на Майерса, Саттера, Александреску и т.д. Хотелось сделать так же круто, но по-русски.
  * Коллектив - сильнейшие разработчики, которые знают уйму нюансов работы с C++; очень хотелось рассказать обо всех них слушателям.
  * И мы начали рассказывать об этих нюансах. Показать первый вариант программы. Рассказать, что курсы состоят из четырёх недель.
  * История, как я случайно посмотрел доклад Kate Gregory и понял, что мы все делаем не так
    * Она рассказывает о многих ошибках, которые допускают люди, обучая языку С++ тех, кто о нём ничего не знает
    * Слайд про гипотетическую книгу, и главная мысль - концентрация на нюансах с самого начала заставляет думать, что С++ - это сложно, и люди решают, что им его не потянуть.
    * «Несмотря на начальные намерения, мы всё-таки пали жертвой собственной экспертизы и стали углубляться во внутреннее устройство С++ вместо того, чтобы рассказывать, как с его помощью легко решать практические задачи».
    * Здесь нужны примеры того, что говорят Кейт и Страуструп в своих докладах и их отражение на наш первый подход
  * Мы поняли, что мы делаем чепуху и приняли самое главное решение, определившее судьбу дальнейших курсов - все выбросить и начать с нуля.
  * Эта история наталкивает нас на первый вывод, который можно применить в работе. Как только вы поняли, что у вас получается результат низкого качества, надо останавливаться и что-то менять. Для этого нужно обладать мужеством, потому что не все примут ваше решение. Если бы мы его не приняли, у нас получилась бы посредственность, я бы сейчас перед вами не стоял и мы бы не получали вот таких отзывов: *пара отзывов*
* Кратко изложить содержание первых трёх курсов
  * Упомянуть финальные проекты
  * vector, map и string появляются во втором видео, сразу после "Hello, world!", sort и count - в четвёртом
* Первый принцип - понятность вместо полноты изложения
  * у нас практикоориентированный курс, у нас нет цели рассказать "весь" С++, мы концентрируемся только на том, что, по нашему опыту, полезно на практике
  * если сразу рассказывать всё, то бОльшая часть просто не осядет у людей в голове
    * Stroustrup: "Don't teach features. The standard says what's valid, not what's useful"
    * Stroustrup: "The purpose of good teaching is getting ideas into people's heads"
  * на освоение материала нужно время, нужно обдумать, что-то попробовать
  * демонстрация с переливанием воды
  * примеры из наших курсов
    * забили на эффективность до поры до времени
    * `using namespace std` везде
    * [введение в шаблоны в первом подходе](https://yadi.sk/i/w43lGt7c3TnmAt): за 11 минут мы рассказали про шаблоны очень много; можно сравнить с тем, как мы рассказали шаблоны в жёлтом и красном поясах
* Демонстрация проблемы
  * Аналогия со сборкой паззла
    * показываем частично собранный паззл и спрашиваем, как добавляете новый кусок?
    * мало кто берёт случайный кусок и ставит его в середину паззла
    * обычно мы ищем кусок, который можно пристыковать к уже имеющимся
  * Так же и в наших курсах мы пытаемся связать новый материал с тем, который люди уже знают. Чтобы ввести новую возможность языка, мы создаём проблему, которая не может быть решена с использованием того подмножества С++, о котором мы уже рассказали.
  * Пример 1 — объяснение ссылок
    * Плохо: Страуструп, с. 137
    * Хорошо: люди уже знают функции и передачу параметров по значению, как написать функцию `swap`?
  * Пример 2 — const
  * Пример 3 — знаковость и диапазоны значений типов
    * Как обычно рассказывают о цилочисленных типах в C++? В самом начале показывают подобную таблицу и говорят: "В С++ есть вот такие целочисленные типы, они имеют размер столько-то байт и вот такие диапазоны значений"
    * Это может вызвать кучу вопросов и непонимания
    * Вместо этого мы в первом курсе рассказали только о типе `int`, а уже во втором продемонстрировали и проблему переполнения, и проблему приведения знаковых к беззнаковым
  * Пример 4 — code review
    * Вы пришли на работу и собираетесь покодить, но вдруг вам прилетает code-review
    * В нём нет описания, и оно огромное — вам тяжко
    * Это пример одинокого кусочка паззла
    * А можно было бы сделать вот так...
* Наглядность
  * Аналогия с айсбергом — наверху какая-то простая фраза типа: «Скомпилируем, запустим и посмотрим вывод», а снизу куча подробностей и вопросов:
      * что значит «скомпилируем?»
      * `g++ -Wall -std=c++14 -O2 example.cpp -o example`
      * что такое `g++`? где его взять?
      * что значат все эти параметры?
      * что значит «запустим»?
      * `./example`
      * А если у меня Windows?
      * Где смотреть вывод?
  * Показываем, как было при первом подходе (видео 1_1.mp4 из первого подхода (00:59 - 01:38))
  * Показываем, как стало ([Вводное видео из курса](https://www.coursera.org/learn/c-plus-plus-white/lecture/ytgSK/hello-world) (01:38 - 02:59)). Все действия, которые мы делаем с кодом в наших лекциях, слушатели должны иметь возможность повторить.
  * Другие примеры:
    * пишем код и правим ошибки компиляции
    * работаем с отладчиком
    * запускаем `g++ -E`
  * Мы в видео пишем код в IDE. Если мы опечатались и у нас не компилится, мы прямо в видео ищем причину и исправляем её. Если мы запускаем компилятор с какими-то особыми опциями, то мы прям в видео открываем консоль и вбиваем в неё нужную команду. Это делает наши лекции более приземлёнными, люди видят, что конкретно им надо сделать, на какие кнопки нажать, чтобы у них получилось то же, что и у нас.
  * Где это можно применить в работе? — Везде!
    * Багрепорты: скриншот с пометками или скринкаст вместо словесного описания
    * Поддержка пользователей: вместо «пришлите служебную информацию» видео, из которого очевидно, что надо прислать и где это взять.
* Заключение — ещё раз привести ключевые выводы, которые мы сделали в процессе работы над курсами по C++:
  * Если результат вас не устраивает, нужно набраться мужества и сделать хорошо
  * Stroustrup: "Teaching is relatively easy. Getting people to learn is hard". Понятность важнее полноты и строгости изложения. Если человек вас понял, он продвинулся по пути освоения темы. Если вы рассказали всё строго и полно, но люди вас не поняли, вы не принесли никакой пользы.
  * Программирование — это, в первую очередь, навык, который нарабатывается практикой. Поэтому что-то сделать важнее, чем о чём-то услышать. Это дополнительное оправдание превосходства понятности над полнотой. В конце концов, не так важно, что вы скажете в лекции, гораздо важнее, какие навыки приобретёт человек по обучения у вас.
  * Чем приземлённее ваш способ донесения информации, тем проще она усваивается.