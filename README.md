# Splate VPN | VLESS и Shadowsocks подписка

Публичная VPN-подписка с конфигурациями VLESS и Shadowsocks для Happ, Karing, INCY и других клиентов с импортом подписок. Серверы проверяются из Сибири, РФ, и собираются в один список с названиями стран и результатами проверки задержки.

Подписка обновляется автоматически из панели SplateVPN. Добавьте ссылку в клиент один раз, затем обновляйте список серверов в приложении.

## Ссылка подписки

```text
https://raw.githubusercontent.com/splatedk-web/vless-splate-configs-country/refs/heads/main/subscriptions/vless.txt
```

[Открыть подписку](https://raw.githubusercontent.com/splatedk-web/vless-splate-configs-country/refs/heads/main/subscriptions/vless.txt)

## Как подключить

1. Скопируйте ссылку подписки из блока выше.
2. Откройте Happ, Karing, INCY или другой клиент с поддержкой VLESS и Shadowsocks.
3. Добавьте подписку через пункт импорта по URL. Название пункта зависит от приложения.
4. Обновите подписку и запустите проверку доступности серверов в клиенте.
5. Выберите доступный сервер и подключитесь.

Если список устарел, обновите подписку в приложении. Текущее содержимое можно посмотреть в файле репозитория. [Список конфигураций](subscriptions/vless.txt)

## Что входит в подписку

| Параметр | Содержимое |
| --- | --- |
| Протоколы | VLESS и Shadowsocks |
| Формат | Текстовый список, одна ссылка подключения на строку |
| Файл | `subscriptions/vless.txt` |
| Названия серверов | Флаг и страна, если геолокация определена, а также результат проверки задержки |
| Проверка доступности | Из Сибири, РФ |
| Обновление файла | Автоматическая публикация из панели SplateVPN |

Несмотря на имя `vless.txt`, файл может содержать ссылки обоих протоколов. Состав и количество серверов меняются при обновлении.

В названиях `XX` означает, что страна не определена. Значение задержки относится к проверке со стороны панели. Доступность и скорость у вас зависят от провайдера, региона и текущей нагрузки.

## Обновления и обратная связь

История коммитов показывает, когда файл подписки менялся. Если при публикации состав серверов остался прежним, новый коммит может отсутствовать. [История обновлений](https://github.com/splatedk-web/vless-splate-configs-country/commits/main/subscriptions/vless.txt)

Если возникла проблема с импортом или подключением, укажите клиент, его версию, регион, провайдера и название сервера. [Сообщить о проблеме](https://github.com/splatedk-web/vless-splate-configs-country/issues)

## English

Splate VPN provides a public VLESS and Shadowsocks subscription for Happ, Karing, INCY and other compatible proxy clients. Servers are checked from Siberia, Russia. The subscription includes country labels when location is available and latency results measured by the panel.

Import the subscription URL above into your client, refresh the server list and run a connectivity check. The feed is published automatically by the SplateVPN panel. Server availability and performance vary by network and location.
