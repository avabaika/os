# Лабораторные работы по курсу "Операционные системы"

**Курс:** Операционные системы  
**Код курса:** os-intro  
**Автор:** Фёдор Симонов  
**Email:** 1032183983@pfur.ru  
**Учебный год:** 2024-2025  
**Учебное заведение:** РУДН (Российский университет дружбы народов)

## Описание

Данный репозиторий содержит выполненные лабораторные работы по курсу "Операционные системы". Каждая лабораторная работа посвящена различным аспектам администрирования Unix/Linux систем, использованию интерфейса командной строки и освоению системных инструментов. Все отчёты написаны на языке разметки Markdown и автоматически генерируются в несколько форматов (PDF, DOCX, HTML) с использованием Pandoc.

## Обзор выполненных лабораторных работ

| № | Название лабораторной работы | Статус | Форматы |
|---|------------------------------|--------|---------|
| 01 | Введение в операционные системы | ✅ Выполнена | PDF |
| 02 | Первоначальная настройка git | ✅ Выполнена | PDF, DOCX, HTML, MD |
| 03 | Язык разметки Markdown | ✅ Выполнена | PDF, DOCX, HTML, MD |
| 04 | Основы интерфейса взаимодействия пользователя с системой Unix на уровне командной строки | ✅ Выполнена | PDF, DOCX, HTML, MD |
| 05 | Анализ файловой системы Linux. Команды для работы с файлами и каталогами | ✅ Выполнена | PDF, DOCX, HTML, MD |
| 06 | Поиск файлов. Перенаправление ввода-вывода. Просмотр запущенных процессов | ✅ Выполнена | PDF, DOCX, HTML, MD |
| 07 | Командная оболочка Midnight Commander | ✅ Выполнена | PDF, DOCX, HTML, MD |
| 08 | Текстовой редактор vi | ✅ Выполнена | PDF, DOCX, HTML, MD |

## Подробное описание лабораторных работ

### Лабораторная работа №1: Введение в операционные системы
- **Формат:** PDF-презентация
- **Файл:** `ЛР1_ОС_Симонов.pdf`
- Базовое введение в концепции операционных систем

### Лабораторная работа №2: Первоначальная настройка git
- **Цель работы:** Изучить идеологию и применение средств контроля версий. Освоить умения по работе с git
- **Основные темы:**
  - Установка и настройка git
  - Создание SSH-ключей (ed25519)
  - Создание и настройка GPG-ключей
  - Интеграция с GitHub
  - Создание и настройка репозитория
  - Настройка автоматических подписей коммитов
- **Изученные технологии:** Git, SSH, GPG, GitHub CLI (gh)
- **Полученные навыки:** Работа с системами контроля версий, безопасная аутентификация, управление репозиториями

### Лабораторная работа №3: Язык разметки Markdown
- **Цель работы:** Научиться оформлять отчёты с помощью легковесного языка разметки Markdown
- **Основные темы:**
  - Синтаксис Markdown (заголовки, выделение, списки, ссылки, изображения)
  - Структурирование и форматирование документов
  - Использование Pandoc для конвертации документов
  - Генерация документов в различных форматах
- **Изученные технологии:** Markdown, Pandoc, обработка документов
- **Полученные навыки:** Написание технической документации, автоматизированная генерация документов

### Лабораторная работа №4: Основы интерфейса командной строки Unix
- **Цель работы:** Приобретение практических навыков взаимодействия пользователя с системой посредством командной строки
- **Основные темы:**
  - Основные команды Unix: `man`, `cd`, `pwd`, `ls`, `mkdir`, `rm`
  - Опции и параметры команд
  - Навигация по файловой системе
  - Использование истории команд
  - Работа со справочной системой
- **Изученные технологии:** Командная оболочка Bash, команды Unix
- **Полученные навыки:** Владение командной строкой, навигация по системе, использование справочной системы

### Лабораторная работа №5: Анализ файловой системы Linux
- **Цель работы:** Ознакомление с файловой системой Linux, её структурой, именами и содержанием каталогов. Приобретение практических навыков по применению команд для работы с файлами и каталогами
- **Основные темы:**
  - Типы файловых систем (ext2/3/4, ReiserFS, XFS)
  - Операции с файлами: `touch`, `cat`, `less`, `head`, `tail`
  - Копирование и перемещение файлов: `cp`, `mv`
  - Права доступа и команда `chmod`
  - Анализ использования диска: `df`, `du`
- **Изученные технологии:** Файловые системы Linux, команды управления файлами
- **Полученные навыки:** Понимание файловых систем, управление правами доступа, мониторинг дискового пространства

### Лабораторная работа №6: Поиск файлов. Перенаправление ввода-вывода
- **Цель работы:** Ознакомление с инструментами поиска файлов и фильтрации текстовых данных. Приобретение практических навыков по управлению процессами и заданиями
- **Основные темы:**
  - Операторы перенаправления ввода-вывода (`>`, `>>`, `<`, `|`)
  - Поиск файлов с помощью команды `find`
  - Фильтрация текста с помощью `grep`
  - Фоновые процессы и управление заданиями
  - Управление процессами: `ps`, `kill`, `jobs`
  - Мониторинг системы: `df`, `du`
- **Изученные технологии:** Перенаправление в shell, управление процессами, системный мониторинг
- **Полученные навыки:** Продвинутое использование shell, контроль процессов, основы системного администрирования

### Лабораторная работа №7: Командная оболочка Midnight Commander
- **Цель работы:** Освоение основных возможностей командной оболочки Midnight Commander. Приобретение навыков практической работы по просмотру каталогов и файлов
- **Основные темы:**
  - Структура интерфейса MC (двухпанельный дизайн)
  - Операции с файлами (копирование, перемещение, удаление, переименование)
  - Встроенные просмотрщик и редактор файлов
  - Режимы панелей и опции отображения
  - Навигация по системе меню
  - Возможности поиска и фильтрации
- **Изученные технологии:** Midnight Commander, управление файлами
- **Полученные навыки:** Эффективное управление файлами, использование псевдографического интерфейса

### Лабораторная работа №8: Текстовой редактор vi
- **Цель работы:** Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором vi
- **Основные темы:**
  - Режимы работы vi (командный, вставки, последней строки)
  - Команды навигации и перемещения курсора
  - Операции редактирования текста (вставка, удаление, копирование, вставка)
  - Функции поиска и замены
  - Операции с файлами и настройка редактора
  - Продвинутые техники редактирования
- **Изученные технологии:** Текстовый редактор Vi/Vim
- **Полученные навыки:** Профессиональное редактирование текста, владение модальным редактором, эффективное редактирование кода

## Структура репозитория

Каждая лабораторная работа содержит:

```
labs/
├── lab01/                    # Лабораторная работа №1
│   └── ЛР1_ОС_Симонов.pdf   # PDF-презентация
├── lab02/                    # Лабораторная работа №2
│   ├── presentation/         # Презентация к лабораторной
│   │   ├── Makefile         # Автоматизация сборки
│   │   ├── presentation.md  # Исходный код в Markdown
│   │   ├── presentation.pdf # Сгенерированный PDF
│   │   ├── presentation.html# Сгенерированный HTML
│   │   └── image/           # Скриншоты и иллюстрации
│   ├── report/              # Отчёт по лабораторной
│   │   ├── Makefile         # Автоматизация сборки
│   │   ├── report.md        # Исходный код в Markdown
│   │   ├── report.pdf       # Сгенерированный PDF
│   │   ├── report.docx      # Сгенерированный DOCX
│   │   ├── bib/             # Библиография
│   │   ├── pandoc/          # Настройки Pandoc
│   │   └── image/           # Скриншоты и иллюстрации
│   └── 02.zip               # Архив с исходными материалами
└── ...                      # Аналогично для lab03-lab08
```

## Техническая информация

### Генерация документов
- **Исходный формат:** Markdown с академическими расширениями
- **Система сборки:** GNU Make
- **Конвертер:** Pandoc с пользовательскими фильтрами
- **Выходные форматы:** PDF (через LaTeX), DOCX, HTML
- **Библиография:** BibLaTeX с оформлением по ГОСТ
- **Перекрёстные ссылки:** фильтры pandoc-xnos
- **Шрифты:** семейство IBM Plex, STIX Two Math

### Команды сборки
```bash
# В любой директории report/ или presentation/:
make          # Собрать все форматы
make clean    # Удалить сгенерированные файлы
make cleanall # Глубокая очистка
```

### Требования
- pandoc ≥ 2.0
- Дистрибутив LaTeX (TeXLive/MiKTeX)
- Фильтры pandoc-xnos
- Система сборки Make

## Соответствие академическим стандартам

Все лабораторные работы соответствуют российским академическим стандартам:
- **ГОСТ Р 7.0.5-2008** для оформления библиографии
- **Conventional commits** для контроля версий
- **Семантическое версионирование** для релизов
- Стандарты **профессиональной документации**
- Требования **технической отчётности**

## Информация об авторе

**Студент:** Фёдор Симонов  
**Email:** 1032183983@pfur.ru  
**Университет:** РУДН (Российский университет дружбы народов)  
**Факультет:** Факультет физико-математических и естественных наук  
**Кафедра:** Кафедра прикладной информатики и теории вероятностей  
**Курс:** Операционные системы  
**Учебный год:** 2024-2025

## Прогресс обучения

Данный репозиторий демонстрирует практическое освоение:

1. **Системы контроля версий** - настройка git, работа с GitHub, GPG-подписи
2. **Документооборот** - создание технической документации в Markdown, автоматизация генерации
3. **Командная строка Unix** - базовые команды, навигация, справочная система
4. **Файловые системы** - структура, права доступа, операции с файлами и каталогами
5. **Системное администрирование** - поиск файлов, управление процессами, перенаправление ввода-вывода
6. **Инструменты разработки** - файловые менеджеры, текстовые редакторы, эффективная работа в терминале

Каждая лабораторная работа строится на знаниях, полученных в предыдущих работах, обеспечивая последовательное изучение от базовых концепций до продвинутых техник системного администрирования.

---

*Данный репозиторий демонстрирует практическое освоение Unix/Linux систем администрирования, инструментов командной строки и стандартов академической документации.*