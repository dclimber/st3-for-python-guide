# Установка Sublime Text 3 для разработки на Python
[Sublime Text 3](http://www.sublimetext.com/3) — это легкий, кросс-платформенный редактор кода, известный за свою скорость, лёгкость в использовании и хорошим коммьюнити.

Sublime очень крут из коробки, но выжать максимум из него можно, используя расширения и создание индивидуальных настроек.


## Установка Sublime Text 3
Перейдите по ссылке и скачайте установщик для своей Операционной системы: http://www.sublimetext.com/3

## Создайте кастомные настройки
В Sublime можно создавать кастомные настройки под себя на JSON.

Доступные настройки смотрите в [неофициальной документации](https://sublime-text-unofficial-documentation.readthedocs.io/en/latest/reference/settings.html).

### Базовые настройки
Чтобы создать базовый файл настроек, нажмите сюда: `Preferences > Settings`

Базовые настройки по рекомендации сайта RealPython — [тут](https://github.com/mjhea0/sublime-setup-for-python/blob/master/dotfiles/Preferences.sublime-settings)


### Настройки под язык программирования
Чтобы создать настройки под конкретный язык программирования, сделайте так:

1. Нажмите `Preferences > Settings — Syntax Specific`;
2. Сохраните файл, в следующем формате: `LANGUAGE_NAME.sublime-settings`.


#### Настройки для Python

1. Нажмите `Preferences > Settings — Syntax Specific`;
2. Добавьте в файл рекомедованные RealPython [настройки для Python](https://github.com/mjhea0/sublime-setup-for-python/blob/master/dotfiles/Python.sublime-settings);
3. Сохраните файл, назвав его: `Python.sublime-settings`.


## Установка Package Control
**Package Control** — это пакетный менеджер, который позволяет устанавливать расширения, его нужно установить.

Официальная инструкция по установке тут: https://packagecontrol.io/installation#st3

### Простейший способ установки — через меню:

1. Откройте меню `Tools`;
2. Выберите опцию `Install Package Control…`;
3. Перезагрузите Sublime — выйдите `ctrl+q` и откройте Sublime вновь.


## Установка внешних пакетов
**Теперь вы можете устанавливать внешние пакеты, таким образом:**

1. Нажимаете сочетание клавиш `Ctrl + Shift + P`;
2. В открывшейся строке поиска вводите: `install`;
3. Выберите опцию `Package Control: Install Package`;
4. Нажмите `Enter`;
5. Найдите нужный вам пакет, package.

Список всех доступных команд по **Package Control** смотрите в документации: https://packagecontrol.io/docs/usage


### Рекомендуемые пакеты для Python:
1. [SublimeCodeIntel](https://sublime.wbond.net/packages/SublimeCodeIntel)
2. [Djaneiro](https://sublime.wbond.net/packages/Djaneiro)
3. [SublimeLinter](https://sublime.wbond.net/packages/SublimeLinter)
⋅⋅* [SublimeLinter-pyflakes](https://packagecontrol.io/packages/SublimeLinter-pyflakes) — установите [pyflakes](https://github.com/PyCQA/pyflakes) чтобы его использовать.
⋅⋅* [SublimeLinter-pycodestyle](https://github.com/SublimeLinter/SublimeLinter-pycodestyle) — установите [pycodestyle](https://github.com/PyCQA/pycodestyle) чтобы его использовать.
4. [Emmet](https://packagecontrol.io/packages/Emmet)
