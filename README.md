# Базовый курс по разработке веб-приложений

## Зачем
Ко мне время от времени обращаются люди с просьбой помочь им начать обучение премудростям IT. ~~Вас много а я одна~~ желающих становится всё больше, поэтому возникло понимание, что пришло время систематизировать знания и сделать их общедоступными.

Я создал этот курс для друзей. Возможно, друзей друзей. Если он выйдет куда-то за пределы моего непосредственного круга общения - окей, сорян, whatever, рады всем.


## Содержание курса
- [Блок 0: подготовка](0.setup)
- [Блок 1: первое приложение](1.first_app)


## Disclaimer
1. Курс в некоторых местах будет сознательно _opinionated_. I.e. мной будет осознанно, а местами, возможно, и неосознанно, принято какое-то единственное решение в ситуациях, где теоретически возможен выбор подхода к решению той или иной задачи. В общем виде это будет касаться одной из следующих вещей:
   - как то или иное место должно выглядеть в рамках данного курса (_чтобы материал лучше усвоился_)
   - как та или иная практика должна применяться в полноценной работе (чтобы полезная, _на мой взгляд_, привычка закрепилась сразу)
2. В местах, где ~~мне не будет лень~~ это будет по моему мнению оправдано, безусловно, будет предоставляться право выбора подхода к решению задач: несколько вариантов консольных команд, несколько вариантов конструкций кода, несколько версий/разновидностей программного обеспечения.
3. Сорян, я с гитхабом "на вы и с переводчиком", поэтому со всякими премудростями вроде "коллективной разработки", "форков", "пул-реквестов" и "ишью-трекинга" в рамках конкретной этой платформы ещё не сталкивался; но обещаю всему научиться в процессе. Если есть, что предложить, подправить, указать на косяки - велкам, но не обещаю, что среагирую мгновенно.


## Про курс
Несколько моментов о курсе.


#### Цель курса
Это **базовый** курс **_по разработке веб-приложений_**.
Его главная задача - не в том, чтобы научить _программировать на том или ином языке_, или _использовать тот или иной фреймворк_. Курсов, книг, статей по конкретным языкам, фреймворкам и прочим ~~проблемам индейцев~~ - полный Интернет, а лучше официальной документации вообще никто ничего не придумал.

Безусловно, всё будет довольно подробно разбираться по ходу пьесы, и код в том числе. Но основной фокус этого курса - **фундаментальные знания** домена веб-разработки: некие универсальные концепты, разобрав которые на конкретных примерах в процессе его прохождения, вы сможете без труда освоиться с любым другим языком/фреймворком. Возможно даже, что в последствии появится похожая версия на другом языке - просто чтобы посмотреть, насколько быстро прошедшие первую версию смогут переключиться на вторую.  
  
Именно поэтому это **современный** курс. _Классические курсы_ по этой теме чаще всего сфокусированы на _программировании_ веб-сервисов.
А чем отличается **_разработка_** от **_программирования_**?
   - программирование - это умение ~~вставлять костыли~~ решать задачи с помощью того или иного языка программирования
   - разработка - это процесс, в центре которого находится **продукт** - в нашем случае _веб-сервис_; этот процесс начинается с проработки требований к веб-сервису, проходит все стадии его жизненного цикла, и заканчивается (на самом деле нет) выкаткой веб-сервиса в продакшен  

И если в первом случае специалисту нужно только знать язык программирования на достаточном уровне, то во втором также нужен целый спектр знаний и навыков, касающихся любого этапа жизненного цикла веб-сервиса - собственно разработки (в том числе командной), тестирования, развёртывания, мониторинга, логирования - а также просто колоссальный и постоянно меняющийся джентельменский набор инструментов для каждого из этих этапов.

Осознавая эту разницу, я поставил перед собой цель сразу воспитывать людей с широким техническим кругозором, и показать, как выглядит весь процесс разработки целиком, а не только кодинг.  
Меня бесят горе-программисты, которые заявляют вещи вроде _"а я не знаю, что там вообще нжинкс логирует, и знать не хочу"_ (был недавно такой диалог).

["Специализация - удел насекомых"](https://en.wikiquote.org/wiki/Time_Enough_for_Love).  
Рынку сегодня нужны действительно качественные специалисты, понимающие не только, как формализовать бизнес-требования в коде, но и то, как их имплементация будет работать в тех или иных условиях, почему, и как этим управлять, чтобы решать возникающие проблемы.

Этот курс - вроде карты достопримечательностей для туристов, только подробный. Я хочу, чтобы люди, которые его будут проходить, не просто освоили те или иные ~~обезьяньи~~ технические навыки, но самое главное - умели **_ориентироваться_** в том, как всё устроено в домене веб-сервисов, и чувствовали себя в этом пространстве по-настоящему свободно.

Но так как это всё-таки _базовый_ курс, он охватит всего понемножку, и вкратце познакомит читателя с вообще-то огромными темами, углубить знания о которых можно будет либо самостоятельно, либо в рамках более специализированных курсов (на которые, надеюсь, мне хватит времени).


#### Структура курса
Он разбит на блоки. Разбиение может показаться странным на первый взгляд, но на самом деле оно логично с точки зрения объяснения того, что будет в нём происходить.

Подразумевается, что блоки будут проходиться один за другим.

При этом, в начале некоторых блоков будет раздел пререквизитов, а в конце каждого - итоговый чеклист (что должно было быть сделано за блок).

Теоретически можно попробовать читать блоки выборочно, на свой страх и риск. Проходить практику выборочно не получится.


#### Технологический стек
   - язык - `Python` (версии 3, на текущий момент это 3.8)
   - фреймворк для веб-приложения - `Flask`  

Где-то там выше что-то было про _opinionated_, помните? _По моему мнению_, именно сочетание Python/Flask позволит нам в рамках курса, с одной стороны, писать как можно меньше лишнего кода (код же нужно ещё и объяснять, верно?), а с другой стороны - получать как можно больше _действительно_ полезных знаний. Заковыряться в особенности того или иного языка вы всегда успеете, но сперва нужно разобраться с тем, как всё устроено.


#### Пререквизиты
Чтобы начать проходить этот курс, нужно три вещи:
1. Желание учиться новому.  
   Нового будет **очень** много. Это будет конденсированный курс, с большим количеством понятий, терминов, с подробными пояснениями, регулярными перекрёстными ссылками и отсылками к сторонним материалам. Содержимое курса будет не такое занудное, как это README, но нужно быть готовым грызть этот гранит.
2. Рабочая станция (пк/ноутбук).
3. "Общая компьютерная грамотность": навык установки ПО, редактирования текста

Опциональными для курса, но ключевыми в будущей карьере, являются:
   - английский (читать придётся **очень** много, и поверьте, на русском ~~нет~~ ~~вообще нет~~ ~~не существует~~ почти нет действительно качественного материала, он весь на английском)
   - гугление (+stackoverflow)


## Ты вообще кто
7 лет в IT, самоучка. Карьерный путь довольно странный: три года в веб-разработке на PHP, год в автоматизации тестирования на Python, три года в DevOps (и время от времени даже просто Ops) на всём, на чём придётся. Из разраба через тестирование в девопса-админа, кому расскажешь не поверят. За это время было очень много интересного, заходите в личку, расскажу.

На текущий момент продолжаю работу девопсом, автоматизацией настройки инфраструктуры, CI/CD и всем вот этим вот.

Сейчас в свободное время мастерю компилируемые языки, потому что надоело.

Этот курс - мой первый open-source проект, и мой первый выход в свет в качестве ITшника. Никогда ранее не писал публичных курсов, статей, не выступал на конференциях, да и не хожу на них. ~~А ещё жутко не люблю хабр, как явление.~~
