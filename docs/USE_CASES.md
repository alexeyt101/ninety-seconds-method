### Use cases:
##### Добавление новых слов (фраз) в бота
1. Добавление слов (фраз) по одной штуке 
	1. Говорю боту, что хочу добавить новое слово
	2. Бот отвечает, что готов принимать фразу
	3. Отправляем ему фразу
	4. Он спрашивает какое слово мы изучаем в этой фразе и какой у него перевод
	5. Мы отправляем ему изучаемое слово и его перевод
	6. ЗЫ: Возможно Telegram позволяет сократить количество шагов здесь, используя какие-нибудь формы или шаблоны.
2. Импорт сразу большого кол-ва слов через файл
	1. Мы говорим боту, что хотим загрузить файл с новыми словами (фразами)
	2. Бот отвечает, что готов принимать файл и предлагает посмотреть в каком формате ожидаются данные
	3. Мы загружаем файл в бота 
	4. Бот отвечает, что файл получил и ему нужно время на обработку
	5. Когда бот обработал файл он возвращается к пользователю с результатом
##### Получение ежедневной подборки фраз для тренировки
1. Бот позволяет настраивать кол-во изучаемых фраз в день, а также время, когда будет приходить ежедневная подборка
2. В назначенное время бот присылает подборку изучаемых слов на сегодня. Сюда могут входить:
	1. Слова, которые мы изучаем сегодня в первом цикле метода 90 секунд. (первая неделя)
	2. Также здесь могут быть слова, которые мы уже изучали в течении недели и которые необходимо повторить.