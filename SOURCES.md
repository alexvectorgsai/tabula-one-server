# Component sources and license notices

Текущий комплект: **server-beta-2026.10.31.2 / v0.2.35-beta.20261031**. [Малые обновления и восстановление](UPDATE.md); [описание источников текущего комплекта](https://github.com/alexvectorgsai/tabula-one-server/releases/download/server-beta-2026.10.31.2/SOURCES.json). Зависимости и инфраструктура прежние; актуальные локальные образы после малого обновления указаны в BUNDLE-MANIFEST.json и подписанном update.current.json.


Предыдущий комплект: **server-beta-2026.10.31.1 / v0.2.32-beta.20261031**. Исправлены удаление и повторное добавление еженедельного времени, добавлена кнопка «К группам», верхняя часть календаря стала компактнее. Обновлены app/shared и public-edge/web; три инфраструктурных образа, 50 миграций, зависимости и beta-политика сохранены. [SOURCES.json текущего выпуска](https://github.com/alexvectorgsai/tabula-one-server/releases/download/server-beta-2026.10.31.1/SOURCES.json) описывает сборку и образы.


Предыдущий комплект: **server-beta-2026.10.30.2 / v0.2.31-beta.20261030**. Обновлены app/API/shared и public-edge/web: связь при заморозке вкладки, постепенная загрузка PDF, доставка реакций и грустная эмоция, зелёные/красные отметки по 14 px. Схема из 50 миграций, зависимости, beta-политика и три инфраструктурных образа сохранены. [SOURCES.json текущего выпуска](https://github.com/alexvectorgsai/tabula-one-server/releases/download/server-beta-2026.10.30.2/SOURCES.json) описывает сборку и пять образов.


Предыдущий комплект: **server-beta-2026.10.30.1 / v0.2.30-beta.20261030**. Исправлены просмотр завершённого урока и PDF с заметками, поля ответа без права рисования, слои медиа и меню, жизненный цикл подсказок и отдельное воспроизведение YouTube в домашнем задании. Изменён только веб-интерфейс. Приложение/API, схема из 50 миграций, beta-политика и три инфраструктурных образа сохранены. [SOURCES.json текущего выпуска](https://github.com/alexvectorgsai/tabula-one-server/releases/download/server-beta-2026.10.30.1/SOURCES.json) содержит все пять образов и рецепт обновления. Версии и исходные архивы сторонних компонентов прежние.


Предыдущий комплект: **server-beta-2026.10.28.1 / v0.2.29-beta.20261028**. Обновлён только веб-интерфейс: мобильные панели и начальное время календаря 12:00. Приложение/API, схема из 50 миграций, beta-политика и три инфраструктурных образа сохранены. [SOURCES.json текущего выпуска](https://github.com/alexvectorgsai/tabula-one-server/releases/download/server-beta-2026.10.28.1/SOURCES.json) содержит все пять образов и рецепт обновления. Версии и исходные архивы сторонних компонентов прежние.


Предыдущий комплект: **server-beta-2026.10.26.3 / v0.2.28-beta.20261026**. В нём обновлены приложение/API и веб-интерфейс: добавлено расписание преподавателя. Версии сторонних компонентов и их исходные архивы сохранены. [SOURCES.json текущего выпуска](https://github.com/alexvectorgsai/tabula-one-server/releases/download/server-beta-2026.10.26.3/SOURCES.json) содержит идентификаторы всех пяти образов, исходный commit и рецепт обновления.


The source collection for server beta revision 2026.10.24.3 is prepared and published separately from the installer.

- [Source-only release](https://github.com/alexvectorgsai/tabula-one-server/releases/tag/component-sources-2026.10.24.3)
- [Source guide](https://github.com/alexvectorgsai/tabula-one-server/releases/download/component-sources-2026.10.24.3/SOURCE-README.md)
- [Exact source index and SHA-256 values](https://github.com/alexvectorgsai/tabula-one-server/releases/download/component-sources-2026.10.24.3/SOURCES.json)
- [Third-party license notices](https://github.com/alexvectorgsai/tabula-one-server/releases/download/component-sources-2026.10.24.3/THIRD-PARTY-NOTICES.txt)
- [Checksum catalogue](https://github.com/alexvectorgsai/tabula-one-server/releases/download/component-sources-2026.10.24.3/SHA256SUMS)

The five standalone source archive parts contain 2,425 verified source inputs: exact Debian source packages and Alpine recipes, native libvips inputs, Rust sources from the Garage/librsvg lockfiles, and Go modules/toolchains matched to the shipped binaries. The catalogue identifies the part containing each file.

Coverage: 305 Debian source versions, 30 Alpine recipes, 34 libvips source/patch inputs, 859 Rust inputs, 245 Go inputs and 1998 distinct license/notice texts. The two Alpine release meta-packages generate their files directly; their complete recipes are included. Source checks include Debian SHA-256/snapshot hashes, Alpine SHA-512, Cargo checksums, Go h1 hashes, Node release SHA-256 and sharp npm integrity.

The checksum catalogue covers both optional sources and the separate installer. With GNU coreutils, use `sha256sum --check --ignore-missing SHA256SUMS` to verify the files you downloaded. The installer also has its own single-file .sha256 document. Standard Linux checksum handling of CRLF lines was checked.

Sources retain upstream licenses and build instructions. The application beta terms do not replace or restrict third-party rights. The source release remains available independently of an installation's beta expiry. The application owner signing key and user data are excluded.

Public installer downloads remain held until the first agreed real server passes its network and installation acceptance. This document records technical source provenance and notices; it does not claim an independent legal opinion.
