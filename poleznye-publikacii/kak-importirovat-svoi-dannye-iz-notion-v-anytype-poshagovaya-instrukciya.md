# 🧰 Как импортировать свои данные из Notion в Anytype - пошаговая инструкция

Привет, я Евгений, [эксперт по цифровым технологиям и нейросетям.](https://t.me/lukafund) За 3 года я интегрировал их в десятки компаний и лично обучил более 150 человек эффективному использованию разных инструментов.&#x20;

### 🚨 Что происходит?

Я рассказал об этом в своей статье [Как продолжить пользоваться Notion после ухода из России: Гайд от эксперта](https://vc.ru/services/1426767-kak-prodolzhit-polzovatsya-notion-posle-uhoda-iz-rossii-gaid-ot-eksperta), которая набрала уже больше 5 000 просмотров 👀

### 🤔 Что делать?

_Если коротко, то есть 2 пути:_&#x20;

1\. Сделать перенос данных из Notion в другой сервис.

> [Аналоги Notion: Лучшие решения для бизнеса и личного пользования и как импортировать в них данные](https://vc.ru/services/1452053-analogi-notion-luchshie-resheniya-dlya-biznesa-i-lichnogo-polzovaniya-i-kak-importirovat-v-nih-dannye)
>
> Выбрать наиболее подходящий можно здесь 👆

2\. Обязательно сделать резервную копию данных, и продолжить использовать Notion.

_Anytype подходит для обоих вариантов, поэтому я решил сделать более подробный обзор, как перенести в него данные._

### ❗ Важные замечание, перед тем как начать

* Поскольку не все функции Notion реализованы в Anytype, некоторые данные Notion могут быть импортированы неправильно.
* Рекомендую все операции выполнять под VPN, если вы делаете это в России. Блокировки Notion могу влиять на работу по API !\


### 🚶‍♂ Пошаговое руководство

ШАГ 1.

1\. Откройте в Notion _Settings & members._

<figure><img src="https://leonardo.osnova.io/4f7940c2-6ccc-5b53-9126-290cb4c7bcab/-/preview/592x/" alt="Как импортировать свои данные из Notion в Anytype - пошаговая инструкция."><figcaption></figcaption></figure>

2\. Откройте _My Connections_ и выберите _Develop or manage integrations._

<figure><img src="https://leonardo.osnova.io/0b8e4eb4-85b5-56a2-a986-b7fdf8113866/-/preview/592x/" alt="Как импортировать свои данные из Notion в Anytype - пошаговая инструкция."><figcaption></figcaption></figure>

3\. Нажмите _New integration._

<figure><img src="https://leonardo.osnova.io/50de13b0-91a8-58b3-bd94-d9b690763823/-/preview/592x/" alt="Как импортировать свои данные из Notion в Anytype - пошаговая инструкция."><figcaption></figcaption></figure>

4\. Выберите ваше рабочее место и задайте имя для интеграции.

<figure><img src="https://leonardo.osnova.io/4a0f5b70-c5d3-5eac-a0ce-8469a966733b/-/preview/592x/" alt="Как импортировать свои данные из Notion в Anytype - пошаговая инструкция."><figcaption></figcaption></figure>

5\. Важно! Перейдите в _Configure integration settings_&#x20;

<figure><img src="https://leonardo.osnova.io/2397f165-7dc0-5cb2-9b46-59241e5d92d2/-/preview/592x/" alt="Как импортировать свои данные из Notion в Anytype - пошаговая инструкция."><figcaption></figcaption></figure>

6\. Дайте права: _Read content_ и _Read user information_, затем сохраните - _Save._

<figure><img src="https://leonardo.osnova.io/5a7c1aed-605b-5ac5-afa4-ffcbf6ae4bae/-/preview/592x/" alt="Как импортировать свои данные из Notion в Anytype - пошаговая инструкция."><figcaption></figcaption></figure>

7\. Скопируйте _Internal Integration Secret._ Сохраните его, он потребуется чуть позже, на шаге 3.

<figure><img src="https://leonardo.osnova.io/14523fcc-d1af-53b0-9354-100ef7e5975e/-/preview/592x/" alt="Как импортировать свои данные из Notion в Anytype - пошаговая инструкция."><figcaption></figcaption></figure>

ШАГ 2

Добавьте интеграцию на страницы, которые вы хотите импортировать в Anytype. Страницы будут импортированы вместе со всеми дочерними документами.

1\. Нажмите на три точки в правом верхнем углу страницы, которая должна участвовать в экспорте. Затем выберите _Connect to_ (возможно, вам потребуется прокрутить меню вниз). Выберите вашу интеграцию с Anytype (по названию из списка).

<figure><img src="https://leonardo.osnova.io/eb24acfb-5bd7-56d4-a3f9-39fd07a9dbff/-/preview/592x/" alt="Как импортировать свои данные из Notion в Anytype - пошаговая инструкция."><figcaption></figcaption></figure>

2\. Убедитесь, что вы выбрали все корневые страницы, чтобы избежать неработающих ссылок любого типа после импорта.

3\. Подтвердите доступ ко всем страницам, связанным с той, которую включаете в экспорт.

<figure><img src="https://leonardo.osnova.io/664ce82b-250f-5fc5-bd6d-6543ccbaefa3/-/preview/592x/" alt="Как импортировать свои данные из Notion в Anytype - пошаговая инструкция."><figcaption></figcaption></figure>

ШАГ 3

Завершите импорт и обеспечьте бесперебойный процесс:

1\. Скопируйте и вставьте _Internal Integration Token_ в Anytype. Для этого войдите в ваше пространство и выберите пункт _Интеграции_ - _Импортировать в пространство._

<figure><img src="https://leonardo.osnova.io/b626b7e2-3602-5e05-ae66-a597f9da6fb5/-/preview/592x/" alt="Как импортировать свои данные из Notion в Anytype - пошаговая инструкция."><figcaption></figcaption></figure>

2\. Далее выбирайте _Notion,_ вставляйте ваш _Интеграционный токен_ и запускайте _Импорт данных_

<figure><img src="https://leonardo.osnova.io/f8f3f8f6-b820-55eb-97c7-5c2ce5897f6d/-/preview/592x/" alt="Как импортировать свои данные из Notion в Anytype - пошаговая инструкция."><figcaption></figcaption></figure>

3\. Убедитесь ещё раз, что выполнили все шаги по инструкции

<figure><img src="https://leonardo.osnova.io/2f95372d-9082-5325-a0fc-f2816e7c7f26/-/preview/592x/" alt="Как импортировать свои данные из Notion в Anytype - пошаговая инструкция."><figcaption></figcaption></figure>

### ⏰ Время и ОЧЕНЬ важная информация

* Используйте хорошее подключение к Интернету, особенно если у вас большое количество файлов.
* Не отключайте компьютер от сети.
* Отключите спящий режим на компьютере, чтобы процесс импорта завершался без сбоев.\


### 🤝 Нужна помощь?

Если вам нужна помощь в переносе данных или есть вопросы, не стесняйтесь [обращаться ко мне напрямую](https://t.me/lukafund).

### 🔔 Оставайтесь в курсе

Перенос данных прошёл у меня удачно, занял несколько часов.

Если вы хотите также - [подписывайтесь на мой канал](https://t.me/lukafund), где я рассказываю об эффективном и безопасном использовании цифровых инструментов, включая Notion.&#x20;

Там я [буду держать вас в курсе](https://t.me/lukafund) всех новостей и делиться лайфхаками по работе с Notion и другими инструментами, такими как нейросети.\
\
**Первоисточник:**\
[https://vc.ru/services/1461561-kak-importirovat-svoi-dannye-iz-notion-v-anytype-poshagovaya-instrukciya](https://vc.ru/services/1461561-kak-importirovat-svoi-dannye-iz-notion-v-anytype-poshagovaya-instrukciya)
