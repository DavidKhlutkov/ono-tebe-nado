# ono-tebe-nado
Проект "Оно тебе надо"
был дан макет в фигме, по началу он мне показался слишком простым, потому что я когда начал учиться в августе , делал все по книжке и слово про лэйаут я не знал (думал сайт про margin paddin и img).
Сайт состоит из стандартных элементов <header> <main> <nav> <section> и <footer>
<header> не сложный элемент, состоит из навигационой панели, ссылки-лого и контактной информации
Подводный камень есть в <address> потому что в задании практикума есть намек на одиночный тег <br>, но при его использовании будут проблемы с адаптивностью футера , такая своеобразная заподляночка от яндекса), впринципе я сразу делал без него, потому что использование одиночных тегов в современной верстке не рекомендуется, делал сразу через задание max-width
Сам элемент хотел выровнять с помощью флекса, но это почему-то не получалось от слова совсем те задал спейс бетвин и выравнивание блочных элемнтов по центру, но пиксель перфект постоянно не сходился, увидел подсказку от преподователя, что лучше не морочить себе голову и сделать через гриды так и поступил, но хотел бы через флекс-контейнер реализовать хедер, впринципе с этим элемнтов все особой сложности он у меня не вызвал, далее интереснее, я даже там поплакал
Секция <main> На мой взгляд самая сложная секция, потому что когда я ее начинал делать, я понятия не имел ,что такое гриды ,немного понимал что-то во флексах, а слова position и z-index прошли мимо меня.
И вот окунаемся в станцию 9 и 3/4 и врезаемся в нее со всей силы.
<section class="cover"> простая секция была вначале , но с ее помощью я очень хорошо разобрался в z-ndex и впринципе все бы ничего, но на моменте, когда я подставил пиксел перфект, я не сказать что удивился, но дико растроился, я ее переверстывал раз 5, проблема вызвала строка надо не знаю почему и до сих пор не понимаю, она захотела не прилипать к правой стенке решил это падингом слева в 20px, честно если это можно сделать по-другому буду рад послушать и получить за это критику, про момент с кнопкой не особо помню потому как она сразу получилась обратил внимание на разные отступы кнопки и текста, но в целом она не показалась мне сложной, после оверлея который чернил всю страницу)
<section class="lots"> Вот здесь я реально плакал , не какие навождения в яндекс заданиях ничего мне не помогало пока я не понял что нижний регистр _ указал вот так - в элементе css кода))) Смешно ? Мне было не до смеха, когда у всех получается ее сврестать , я уже и понимал как ее гридами сделать и флексами и думал о ней на работе. Ошибка была найдена, времени было потрачено много , но ничего страшного "я не гордый"
слезы собрал в кулак и путем заданий размеров , ну и про flex wrap не забыли все получилось тексту задал падинги открываю пиксель перфект и все один в один, даже мама была рада)
<section class="about"> Вроде бы эта секция сложнее своим обилием знание о падингах и гридах , но я ее делал после карточек и нервов на эту секцию у меня не осталось, я ее делал ночью хотелось дико спать , но у самурая нет цели , есть только путь, поэтому я шел, на этой секции я научился работать с клавишей F12 и познал все ее прелести оказывается можно не искать в нтернете информацию о флексах и каждый раз смотреть, что делает то или иное условие, а делать вначале это в консоли , а только потом вносить правки в код, хорошая практика, плохо все помню именно с чем я сталкивался , но точно что меня смутило это 1 пискель который не додали одному из элементов, решил просто перед этим отступу дал на один пиксель больше, я поставил все в css смотрю сходится и на радостях пошел спать (наивный)
на следущий день я встал на работу в перерыве сделал футер, потому что просто хотел он получился давольно быстро, не дам соврать пока грелась микроволновка и я ел , футер уже был готов
отматываем время назад я сталкиваюсь с about еще раз, потому что открыв пиксель перфект, я понял , что потерял один гап в 25px
Задав вопрос в пачке понял что есть лишнее как задание размеров этой секции ну и там еще не хватало пару вещей, решил переписать код, секцию с лого я оставил, потому что было жалко потраченный сон, но задал в грид мин контент заместо 1fr , дошел до этого когда преподователь объяснял на вебе про мин контент и как он работает решил попробовать на этой секции и все получилось
Единственое что осталось для меня вопросиком это гап между текстами, не знаю либо я потерял 3px либо это мой браузер мне привирает, но при гапе в 28px, а не в 25px как по макету все показывает идеально , но не хотел себя показать человеком который все подгоняет под размеры лишь бы сделать , поэтому оставил как есть, как мне кажется я потяерял 3px
По футеру скажу это просто, когда делал предыдущие секции, если бы я так долго не разбирался в карточках, я бы не сделал его условно за 20мин
В заключении скажу это неплохой опыт для того , чтобы разобраться во флексах и гридах, и вообще я очень рад что взял курс от яндекса, а не от другой компании
