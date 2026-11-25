# povel durev Observatory

## О проекте / токене

Povel Durev \(DUREV\) — мем-токен сети TON. На сайте проекта он представлен как сообщество, создающее мемы о пародийном персонаже Povel Durev. Контракт сверён с адресом на сайте и в канале проекта.

Краткое описание по указанным первичным источникам.

Источники (проверены 2026-11-25):

- <https://poveldurev.net/>
- <https://t.me/s/poveldurev>
- <https://tonapi.io/v2/jettons/EQB02DJ0cdUD4iQDRbBv4aYG3htePHBRK1tGeRtCnatescK0>

Generated from https://github.com/Freebielife/TON-Observatory-Template.

Run python3 -m scripts.refresh_observatory; python3 build.py; python3 verify.py.
Publish index.html in TON Sites only after independent on-chain verification.
Snapshot contains verified DUREV holder balances and successful native TON swaps collected on 2026-11-25. Historical coverage is partial and accumulates on later refreshes.
Only native TON swap pairs supported. Locks, staking and custom project NFT badges are configured through project.json and verified against TonAPI.
Configure your GitHub workflow scheduler before launch.

Foundation version: 1.3.0. Holders show 10, expandable to top 20.
`project.json` is the per-project specification. Contract/pool/precision changes require regenerating from the factory; do not reuse another token's snapshot.
Run `python3 build.py` for an atomic bundle and `build/report.json` size report.
No external fonts, scripts or images are needed to render the saved page. Fresh data checks and manual wallet lookups require network access.
Cloudflare dispatch registration and GitHub repository access remain separate deployment steps. No credentials go into HTML.

## Оформление и запуск

Баннер: изображение пользователя image(20261125-172824).png; оно заменяет изображение из метаданных по прямому указанию пользователя. Флаг разделов: выбранный пользователем №196 каталога TONecoFlags. Тикер в интерфейсе DUREV; в метаданных контракта — durev.

Сайт проекта: https://poveldurev.net/ (указан в канале проекта). Старый durev.xyz из метаданных на 2026-11-25 показывает парковочную страницу продажи домена.

Источник шаблона: Freebielife/TON-Observatory-Template, commit 6578013. В репозиторий добавлен workflow update.yml; подключение к внешнему планировщику сообщил пользователь. Публикация через TON Storage и плановый запуск должны проверяться отдельно.
