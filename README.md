# Структура

* `0.Journal 📔` - заметки по дням, дашборды и всё такое.
	* `Daily 📝` - каталог для дневника.
	* `Overview 🧐` - дашборд задач.
* `1.Inbox 📥` - входящая информация, которая сразу не попала в имеющиеся проекты или области. Разбирается по алгоритму GTD.
	* `TODO ✅` - разовые задачи / действия вне проектов, по которым есть срок, но не требуются заметки или дополнительные действия.
* `2.Projects 💼` - любая актуальная цель, для достижения которой нужно выполнить более одного действия и есть срок.
* `3.Areas 🧳` - процессы / направления, по которым регулярно производятся какие-то действия, ведутся заметки и задачи.
	* `People 👥` - люди, с которыми взаимодействуем.
		* `@ФИО` - заметка о конкретном человеке.
* `4.Resources 🗄️` - библиотека знаний и заметки на будущее.
	* `TBD ☑️` - список задач "когда-нибудь / может быть"
* `5.Archive 📦` - выполненные проекты и другие знания, утратившие актуальность.
* `10.Templates 🫥` - шаблоны заметок.

# Ссылки

* [Исчерпывающее руководство Getting Things Done (GTD) метода с примерами](https://habr.com/ru/articles/599391/)
* [Организовываем свою активность, через пространства. Философия P.A.R.A. + Obsidian](https://habr.com/ru/articles/755982/)
* [How to Easily Organize Your Life with the PARA Method](https://thomasjfrank.com/productivity/how-to-easily-organize-your-life-with-the-para-method/)
* [Эффективное ведение дел или Obsidian + GTD](https://habr.com/ru/articles/743628/)
* [GTD за 15 минут: прагматическое руководство](https://habr.com/ru/companies/wunderfund/articles/648663/)
* [GTD. Мифы, ошибки, заблуждения](https://habr.com/ru/articles/123669/)
* [Управление личными делами на базовом уровне](https://habr.com/ru/articles/719558/)

![](https://habrastorage.org/getpro/habr/upload_files/a74/49f/3f8/a7449f3f8a3762a581e65fb68280edb8.png)

# Теги задач

- без тега — выполнить;
- `#next` — отложено до выполнения предыдущих шагов (актуализируется после их достижения, чтобы перейти в активные задачи);
- `#waiting` — результат ожидается от кого-то;
- `#project` — корневая задача проекта;
- `#someday` — когда-нибудь / может быть.

# Obsidian 

Внесены настройки для поддержки подхода (генерация файлов в целевых каталогах и источники шаблонов).

Если захочется настроить всё с чистого листа - достаточно удалить каталог .obsidian и заново открыть хранилище.
## подключенные community плагины

* `Tasks`
* `Calendar`
* `Advanced tables`
## some hotkeys

* `cmd+n` - новая заметка (создастся в папке `1.Inbox 📥`)
* `cmd+o` - меню перехода по заметкам (поиск по заголовкам)
* `cmd+p` - меню команд (например можно вбить `tasks: create or edit` для вызова расширенного меню создания или редактирования задачи)
* `cmd+e` - переключение режима редактирование / чтение
