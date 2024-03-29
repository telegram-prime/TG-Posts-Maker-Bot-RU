# T4BT - Бот для создания уникальных постов для рассылки по Telegram.

## Телеграмм-бот, предназначенный для создания уникального контента для рассылки. Это ключевой и неотъемлемый инструмент для людей, работающих с рассылками в Telegram.
## Если Вы работаете с рассылками в Telegram, Т4ВТ - ваш незаменимый помощник. Этот бот поможет Вам создать уникальные сообщения для массовой рассылки.
 
 * Software description is also available in English. See [T4BT - TG Posts Maker Bot EN](https://github.com/telegram-prime/TG-Posts-Maker-Bot)
 * 描述也可以在Chineese中提供。 参见 [T4BT - TG Posts Maker Bot CN](https://github.com/telegram-prime/TG-Posts-Maker-Bot-CN)


## Что умеет T4BT Бот.
 - Создание поста(ов) с содержанием:
   * текстовое сообщение;
   * изображение;
   * видео обычное;
   * видео кружочком;
   * GIF анимацию;
   * аудио файл;
   * голосовое сообщение.
 - Возможность задать описание к каждому отправляемому медиа файлу.
 - В описании к медиа файлу, как и просто в текстовом посте, поддерживается спинтакc, формат: `{Text_1|Text_2|Text_3|Text_4}`.
 - Так же поддерживается MARKDOWN формат для создания гиперссылки в описании к медиа файлу либо в обычном тесктовом посте, формат `[Link Text](https://www.example.com)`.
 - Возможность создания поста как с кнопками под постом, так и без кнопок.
 - Возможность выбора количества кнопок на пост, а так же количество кнопок в ряду.
 - При создании кнопок поддерживается спинтакc, формат: `{Button1|Button2} | {{https|http}://example1.com/|{https|http}://example2.com/}`. Данные для формирования кнопки можно отправлять как текстом в бота, так и текстовым файлом (для создания большого объема постов).
 - Возможность к каждой ссылке в кнопке добавлять рандомную переменную в виде `https://example1.com?jd73hddsk83`.
 - Возможность создавать ссылку на сообщение для перехода на пост в виде: `https://t.me/YourBotName_bot?start=c747ca0a61d46131`.
 - Возможность отдельно создать дефолтный пост (он же пост по-умолчанию) для бота. Т.е. при любом переходе в бота (напрямую по юзернейму) каждому посетителю будет показан этот пост. Он может отличаться от тех созданных постов, которые предназначены для рассылки.
 - Возможность запускать бота через прокси.
 - Возможность запускать бота на определенный промежуток времени.
 - Мульти-доступ к базе постов на одном ПК, т.е. база созданных постов может быть доступна из любого запущеного бота на одной и той же машине.
 - Возможность запускать несколько ботов в рамках одного ПК.
 - Привязка ключа к железу, с возможностью сброса ключа. Сброс бесплатен.
 - Детальная пошаговая инструкция внутри бота.
 - Бот дотсупен на четырех языках: 🇺🇸 🇷🇺 🇪🇸 🇨🇳.
 - Бесплатные обновления.
 - Онлайн поддержка.


## Режим работы T4BT Бота.

 - В режиме `INLINE` - самый перспективный и эффективный метод.
   * Это Ваш собственный ака `@postbot`, вот только с именно Вами созданным ТГ юзернеймом для него под Ваш личный проект или оффер!
   * Главное отличие от стандартного постбота в том, что он генерирует не один, а множество уникальных ID для одного поста или же множества созданных постов.
   * Используя рандомизацию текста как для описания медиа файла, так и для просто текстового поста, каждое сообщение, отправленное с использованием одного из ID, будет уникальным.
   * Тоже самое касается и медиа файла в посте, т.е. в каждом отправленном посте будет уникальный идентификатор медиа файла.
   * Тоже самое будет касаться и кнопок в посте, т.е. каждый пост будет иметь уникальную кнопку, конечно же при условии, что будет задана кнопка спинтаксом. К примеру: `{Button1|Button2} | {{https|http}://example1.com/|{https|http}://example2.com/|...}` и так далее 1-2-5-10 тысяч вариаций разделенных прямым слэшем (`|`).


- В режиме `обычного бота`.
  * В этом режиме для каждого поста будет сгенерирована отдельная ссылка с уникальным ID для перехода на пост по нажатию на кнопку /start.
  * Весь процесс уникализации поста идентичен описанному выше.


## Для запуска бота будет необходимо: 
 - Бот-токен Вашего бота из `@BotFather`.
 - Telegram ID аккаунта, который будет админом бота для управления и создания постов.


## Мы предоставляем 24-часовой БЕСПЛАТНЫЙ пробный период, во время которого пользователи получают полный доступ без ограничения для тестирования продукта и подтверждения эффективности системы перед покупкой.
### - Кнопка для запроса демо-ключа находится внутри программы.

## После окончания пробного периода продукт доступен по двум платным подпискам:
- Лицензия: Месячная  - 1 Месяц без ограничений.
- Лицензия: Годовая   - 1 год без ограничений.


## Скачать:
 - [Всегда актуальный релиз тут](https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU/releases/latest)


## Видео:
 - [YouTube](https://youtu.be/LS0AnAYDonU)


## Скриншоты:

<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU/assets/94137664/c3ef2999-0918-4f33-aca6-95c386f25366" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU/assets/94137664/67c5eebe-478e-4ac2-b625-c4c86d7a7690" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU/assets/94137664/9dbc2daf-8336-434b-9638-4cc3e4ef94ee" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU/assets/94137664/694ae9c9-c31b-4ab8-ba75-02fb50a11f31" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU/assets/94137664/0c592191-4f60-44d3-8e4b-ed5f60731497" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU/assets/94137664/737571bf-7e2a-446e-ab1a-066f8c9a1bab" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU/assets/94137664/7532affb-89b7-4d53-98c8-ffc413af1ba4" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU/assets/94137664/e74b0337-e438-4759-aa9a-28b96dcd1ecd" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU/assets/94137664/4a9141d5-4a2e-4590-bc1a-e8fba3552e79" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU/assets/94137664/0b1ca886-502f-411e-82f1-7b55ca07002b" width="200" height="200">
<img src="https://github.com/telegram-prime/TG-Posts-Maker-Bot-RU/assets/94137664/67df658c-25d9-4043-b873-459ed0c5f273" width="200" height="200">




##  Контакты:
- Email:    manager[@]telegramprime.com
- Telegram: [Send message](https://telegramprime.com/telegram-contact)
- ICQ:      [Send message](https://telegramprime.com/icq-contact)
- TamTam:   [Send message](https://telegramprime.com/tamtam-contact)
- Discord:  [Send message](https://telegramprime.com/discord-contact)
- Element:  [Send message](https://telegramprime.com/element-contact)

* либо через форму связи на наших сайтах Telegram PRIME:
- Wеb: https://telegramprime.net/ - EN Version
- Wеb: https://telegramprime.com/ - RU Version


## Донаты:
* [Купить нам кофе :)](https://nowpayments.io/donation/telegramprime)
* Благодарим Вас!

