<h1>Tunnel LTE Universal Checked</h1> 

Не просто список VLESS-конфигураций.  
Это автоматически обновляемый whitelist-oriented пул серверов для Tunnel, предварительно проверенный real-delay методом.

VLESS · Xray · LTE whitelist · real-delay check · auto-update · Tunnel-ready subscription · 50+ sources

![status](https://img.shields.io/badge/status-active-brightgreen)
![type](https://img.shields.io/badge/type-VLESS%20subscription-blue)
![client](https://img.shields.io/badge/recommended%20client-Tunnel-00bcd4)
![update](https://img.shields.io/badge/update-automatic-orange)
![format](https://img.shields.io/badge/format-whitelist.txt-lightgrey)

<hr>
</div>

## О репозитории

**Tunnel LTE Universal Checked** — это публичный репозиторий с автоматически обновляемым списком конфигураций, ориентированных на работу в условиях LTE whitelist-фильтрации.

Репозиторий создан специально для проекта **Tunnel**:

```text
https://github.com/hussaroff/tunnel
```
---

## Для чего это нужно

В сетях с whitelist-фильтрацией обычный подход часто не работает:

```text
нашёл VLESS → импортировал → нажал подключиться → не работает
```

Проблема в том, что доступность конфигурации зависит не только от самого сервера.

На работу влияют:

- мобильный оператор;
- регион;
- LTE / 3G / Wi-Fi;
- DNS;
- IP / CIDR;
- SNI;
- TLS / REALITY;
- WebSocket / TCP / XHTTP;
- DPI-фильтрация;
- маршрут от конкретного пользователя до сервера.

Потому мы предварительно тестируем все конфигурации и после чего делимся с вами. Это ненадежное и временное решение, намного сильно уступающее Premium обходу Белых Списков от Tunnel.

---

## Основная подписка

Файл подписки:

```text
whitelist.txt
```

Raw-ссылка:

```text
https://raw.githubusercontent.com/hussaroff/lte-universal-checked/main/whitelist.txt
```

Эту ссылку можно добавить в Tunnel (или аналоги вроде Happ, v2ray...) как источник VLESS-конфигураций.

---

## Почему рекомендуется Tunnel

Для использования этого списка рекомендуется приложение **Tunnel**:

```text
https://github.com/hussaroff/tunnel
```

Tunnel создаётся не как обычный технический клиент для ручного импорта конфигов, а как приложение, которое помогает найти рабочий маршрут в сложных сетевых условиях.

Tunnel может использовать:

- автоматическую загрузку конфигураций;
- проверку доступности серверов;
- real-delay проверку;
- underlay проверку;
- failover-логику (Smart Connect);
- работу с whitelist-oriented пулами;
- пользовательскую обратную связь о работоспособности серверов;
- выбор подходящего маршрута на стороне устройства.

Обычный клиент может показать, что сервер имеет TCP-ping, но это ещё не значит, что VLESS реально работает. Tunnel ориентирован именно на практический сценарий: найти тот профиль, который отвечает в текущей сети пользователя.

---

## Дисклеймер

Этот репозиторий предоставляет технический список конфигураций.

Авторы репозитория не гарантируют, что каждый сервер будет работать у каждого пользователя.

Фактическая доступность зависит от:

- сети пользователя;
- оператора;
- региона;
- текущей фильтрации;
- состояния сервера;
- корректности маршрутизации;
- параметров конкретной конфигурации.

Для наилучшего результата используйте приложение Tunnel Premium:

```text
https://github.com/hussaroff/tunnel
```

---

## Tunnel
Основной проект:

```text
https://github.com/hussaroff/tunnel
```

Tunnel — рекомендуемый клиент для работы с этим списком.

Он предназначен для сценариев, где важно не просто импортировать конфиг, а найти реально рабочее подключение в условиях DPI, нестабильной маршрутизации и whitelist-фильтрации.

---

## Subscription

```text
https://raw.githubusercontent.com/hussaroff/lte-universal-checked/main/whitelist.txt
```
