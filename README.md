## Тайна переписки в Телеграм
* 1 способ: секретный чат и самоуничтожающиеся сообщения в Телеграм
  + создать секретный чат и включить самоуничтожение сообщений, как описано здесь https://lifehacker.ru/kak-sozdat-sekretnyj-chat-telegram/
  + только на смартфоне, в десктопной версии Телеграмм этой функции нет
  + только для общения двух людей
  + все данные, переданные ВНЕ секретных чатов, сохраняются на серверах Телеграм, даже если пользователь удалит данные с телефона
* 2 способ: второй аккаунт Телеграм
  + Завести какую-нибудь сим-карту
    - возможно виртуальный номер телефона вместо настоящего мобильного
  + Выучить наизусть номер телефона этой сим-карты
  + Хранить саму сим-карту у кого-то из знакомых
  + В приложении Телеграм завести второй аккаунт с этим номером телефона
  + Выходить из второго аккаунта Телеграм каждый раз после использования
  + При входе в аккаунт просить знакомого передать код (код будут запрашивать не каждый раз)
  + Стирать каждый раз информацию о том, как знакомый передавал Вам код
  + Можно облегчить вход в аккаунт, чтобы меньше беспокоить знакомого:
    - завести какой-нибудь мейл
    - выучить наизусть этот мейл и пароль от него
    - указать этот мейл в акаунте Телеграм
    - в этом случае код для входа в Телеграм будет приходить на мейл, а не на телефон знакомому (кажется иногда и на телефон, но чаще на мейл) (код будут запрашивать не каждый раз)
    - выходить из мейла каждый раз после использования
    - не сохранять в браузере этот мейл
 
## Сохранить аккаунт Телеграм в случае потери сим-карты
* 1 способ: заранее установить в аккаунте Телеграм двухфакторную аутентификацию (мейл и облачный пароль к аккаунту Телеграм)
  + Вы сможете зайти в аккаунт без сим-карты
  + надо позаботиться, чтобы никто не получил доступ к этому мейлу
  + вводить этот пароль вы будете нечасто, поэтому его очень легко забыть, так что лучше сохранить его в каком-нибудь надежном месте [^1]
  + Если Вы забудете этот облачный пароль к аккаунту Телеграм, то
    - Вы можете отправить заявку на полное удаление аккаунта
    - через семь дней учетная запись удалится (со всеми контактами, чатами и подписками на каналы)
    - Вы сможете завести новый, совершенно пустой аккаунт на тот же номер телефона
    - другого способа восстановить аккаунт Телеграм с забытым паролем нет
    - имейте в виду, что эту же операцию может провести злоумышленник, если у него будет доступ к Вашей сим-карте, поэтому постарайтесь не терять пароль
  + этот облачный пароль к аккаунту Телеграм - не то же самое, что локальный пароль на приложение телеграм
* 2 способ: использовать аккаунт Телеграм, не привязанный вообще к номеру телефона 
  + Телеграм продает такие аккаунты за криптовалюту
  + не нужна симка
  + код для входа в Телеграм будет приходить на криптокошелек
  + невозможно взломать такой аккаунт, выпустив копию сим-карты
 
## Другая информация о Телеграм
* В приложении Телеграм, в настройках, в разделе "Устройства", можно видеть все телефоны и компьютеры, у которых есть доступ к Вашему аккаунту
* Идентификационный номер
  + у каждого пользователя Телеграм есть идентификационный номер (не связанный с номером телефона)
  + узнать свой идентицикацонный номер можно здесь @getmyid_bot
  + если злоумышленник отслеживает чаты с помощью программы и знает Ваш идентификацонный номер, то у него есть информация о всех Ваших чатах и сообщениях, даже если Вы уже покинули эти чаты. Для этого злоумышленнику не обязательно знать Ваш номер телефона.
* IP-адрес
  + IP-адрес даёт информацию о Вашем физическом местонахождении
  + скрыть свой IP-адрес можно c помощью VPN
* Если при входе в аккаунт Телеграм Вы выбираете опцию "Cинхронизировать контакты", то
  + Ваши контакты из Телеграм копируются в Ваш аккаунт gmail
  + даже после выхода из аккаунта Телеграм или после удаления приложения Телеграм, Ваши контакты будут доступны в аккаунте gmail (через телефон или компьютер)
  + на серверы Телеграм попадают Ваши контакты из телефона, в том числе и контактная информация тех, кто не давал мессенджеру доступа к своим контактам, или вообще не пользуется Телеграм
* Сохранение всей этой информации на серверах Телеграм
  + возможно российские провайдеры имеют оборудование, которое фильтрует, мониторит и записывает трафик
  + вроде бы пишут, что все или некоторые сервера Телеграм находятся в России
  + Телеграм может сообщать эту информацию, например, по запросу правоохранительных органов
  + Телеграм НЕ может сообщать информацию из секретных чатов (т.к. она не сохраняется на серверах)
* Кажется Телеграм очень сложно заблокировать, вот что пишут:
  + вроде бы его пытались заблокировать в России, Иране, Афганистане и Китае, но полного блокирования не удалось достичь нигде, с замедлением / через VPN-сервисы / частные сети и "серые" клиенты Телеграм продолжают работать
  + если от провайдеров будут требовать, чтобы они блокировали направления трафика, порты и т.д., то будет частичная блокировка, но скорее всего не полная
  + сам Телеграм создан таким образом, чтобы предотвращать блокировку
    
## Мессенжер Signal
* тоже можно настрорить автоудаляющиеся сообщения

## Безопасный мессенжер для компьютера uTox
* https://tox.chat/index.html
* желательно задать пароль
* настройки Advanced
  + выключить протокол IPv6
  + включить протокол UDP для общения удалённо без возможности определения IP 
* не надо сохранять историю сообщений, тогда они будут исчезать каждый раз при закрытии чата
* безопасный сервис для передачи позывных https://pwpush.com/

## Безопасный мессенжер для смартфона Briar
* https://briarproject.org/

## gmail
* Установите двухэтапную идентификацию одним из следующих способов:
  + Электронный ключ
     - https://landing.google.com/advancedprotection/
  + Приложение Google Authenticator
  + 10 кодов, которые надо сохранить в безопасном месте [^1]
  + Номер телефона (не стоит использовать этот способ, если есть риск потерять телефон вместе с компьютером)
  + Подтверждение через приглашение на телефоне (не стоит использовать этот способ, если есть риск потерять телефон вместе с компьютером)
* Каждый раз после использования выходите из аккаунта
* Если вы удаляете какой-то мейл, то он не удаляется сразу окончательно, он попадает в корзину и его всё ещё можно прочитать в течение 30 дней или что-то около этого
  + чтобы окончательно удалить мейл, надо удалить его из корзины
  + то же самое происходит при удалении контактов - в течение какого-то времени после удаления они доступны в корзине
* Злоумышленник может получить доступ к истории местоположения телефона, если
  + на телефоне включено определение местоположения через gps
  + в аккаунте gmail включена опция "сохранять историю местороложения"
  + злоумышленник вошёл в Ваш gmail, используемый на телефоне (через телефон или компьютер)
* Имейте в виду, что здесь https://myactivity.google.com/myactivity сохраняется много информации
  
## Тайна просмотра веб-страниц через интернет-браузер
* 1 способ: 
  + использовать отдельный браузер (Google chome, Firefox, Opera, ...) для просмотра конфиденциальной информации 
  + отключить в браузере сохранение истории просмотров
  + отключить сохранение куки
* 2 способ:
  + открывать вкладку "Инкогнито"

## На заметку
* Существуют сервисы для пересылки смс на email
* После использования любых аккаунтов на чужом компьютере не забывайте выходить из аккаунта
* Если Ваш телефон попадёт в руки к злоумышленнику хотя бы на несколько минут, то он может установить программу, которая будет сообщать ему постоянно всю Вашу переписку (смс, Телеграм, WhatsApp, и т.д.), аудиозапись Ваших телефоннных звонков, историю Вашего местоположения, даже кажется записывать на микрофон и видеокамеру телефона всё, что происходит, и др. информацию. Примеры таких программ (это не очень актуальный список): Free Android Spy, ns cloud, super sound, hoverwatch, iKeyMonitor, telspy, FlexiSPY, mobiletool, mSpy, spyera, Spyic.app, cocospy, evezy, mspy-app.co, spylix, neospy, SpyBubble, umobix, spyZie, Children Tracker, qustodio, Cell Tracker, observer, Alfred Camera, Android Spy, callr, Cerberus, Ear Agent, Ear spy, EyeZy, finda, geofy, Home Security Camera, reptilicus.net, ntego ContentBarrier, iSpyoo, JumpCloud, mobile-find.mobi, MobileTracker, mobilocator, MobiStealth, monitorMinor, OpinionSpy, PhoneSpector, Reptilicus, spy message, SpyHuman, statlook, XNSPY.app, Клевгард, миншпион, Мобильный шпион, ПКTattletale, Правда-шпион, шпион, Шпионская Камера HD 

<!-- TOC --><a name="welcome-to-the-app"></a>
## Если Вам нужна более подробная информация <img align="right" width="60" height="60" src="https://github.com/akostrik/stage_telegram/assets/22834202/9d78c9d6-c4c6-4566-9e83-3dcbc02e311e"> 
или здесь что-то недостаточно понятно описано, [напишите пожалуйста мне](mailto:stage.mongodb@gmail.com), и я постараюсь разузнать и добавить сюда необходимую информацию

 [^1]: например, у кого-то из знакомых, или в менеджере паролей, или в каком-то онлайн аккаунте, существование которого держится в секрете (и использование этого аккаунта не сохранено в браузере)
