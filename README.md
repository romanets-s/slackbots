#@valentine - бот, що має на меті об'єднувати душі <3

###Гайд по користування ботом для самих зацікавлених.

Після апдейту доступно два варіанти надсилання валентинок:

* Написати боту особисте повідомлення. Якщо не знаєте, як писати особисті повідомлення в слаці, то ось [man] (https://get.slack.help/hc/en-us/articles/212281468-Direct-messages-and-group-DMs).
Ви можете відразу написати йому валентинку по заданому скрипту або ж напишіть йому будь що і він вам напише підказу.

* Запросити бота до каналу (відкритиго або закритого) або до групового повідомлення (`див man DM`:point_up_2:) і там викликати його згідно скрипта. Щоб вивелася підказка потрібно тегнути бота з ключовим словом `sendto` (приклад `@bot_name sendto`)

Скрипт:
`@bot_name sendto @user_name "message"`

:warning:  повідомлення обовязково має бути в прямих подвійних лапках `"`.
Це такі ж самі лапки, які ви використовуєте при ініціалізції строк без вказування розміру. На англ розкладці shift + клавіша, що праворуч від ` ; `. На маках на укр розкладці можна також використовувати shift + 2, але інколи ставляються косі лапки і тоді повідомлення не валідне. В самому повідомленні також можуть бути подвійні лапки. Буде відправлено текст між першим і останнім входженням лапок в текст. Все, що йтиме після останніх подвійних лапок буде втрачено навічно))
також можна надсилати фото вставляючи посилання на це фото в текст між лапками. (наприклад `@bot_name sendto @user_name "message https:/url.ur message"`)