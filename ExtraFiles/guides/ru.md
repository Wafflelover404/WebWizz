# Руководство пользователя для WebWizz

## Введение
WebWizz — это веб-сервис, разработанный для создания и редактирования веб-страниц с использованием искусственного интеллекта. Сервис предоставляет инструменты для генерации, конструирования и редактирования HTML-кода, а также для управления файлами и настройкой параметров. WebWizz имеет открытый исходный код на GitHub (Лицензия: GNU-GPL 3.0)

# Начало работы

## Основные функции

### Навигация по страницам
В боковой панели вы можете выбрать одну из следующих страниц:
- **About us ℹ️**: Информация о проекте.
- **Account 👤**: Управление учетной записью и файлами.
- **Settings ⚙️**: Настройка параметров и токенов.
- **Generate ✨**: Генерация веб-страниц с использованием AI.
- **Build 🛠️**: Конструирование веб-страниц.
- **Edit 👨‍💻**: Редактирование HTML-кода.

### Страница "Account 👤"
На этой странице вы можете:
- **Создать новую учетную запись** или **войти в существующую**.
- **Загрузить файлы** или **добавить их вручную**.
- **Просмотреть и управлять файлами**, сохраненными в вашей учетной записи.

### Страница "Settings ⚙️"
Здесь вы можете:
- **Настроить ваши токены** для HuggingFace и Pixabay. (Для лучшей производительности)

### Страница "Generate ✨"
Эта страница позволяет:
- **Ввести тему и описание** для генерации веб-страницы.
- **Сгенерировать HTML-код** с использованием AI-алгоритмов.
- **Просмотреть и скачать** сгенерированный код и саму страницу.
- **Сохранить код** в вашей учетной записи.

### Страница "Build 🛠️"
На этой странице вы можете:
- **Добавлять, редактировать и удалять элементы** на веб-странице.
    - Добавлять текст с множеством возможностей кастомизации. (Цвет, фон, рамка, и т.д.)
    - Добавлять изображения с множеством возможностей кастомизации. (Размер, рамка, и т.д.)
    - Создавать группы элементов.
    - Редактировать, удалять уже существующие элементы.
- **Сохранять и скачивать** готовый HTML-код.

### Страница "Edit 👨‍💻"
Здесь вы можете:
- **Загрузить существующий HTML-файл** или **создать пустой файл**.
- **Редактировать код** с использованием встроенного редактора. (Редактор может быть настроен под пользователя с использованием встроенного меню. Также редактор будет автодополнять код пользователя и форматировать скобки.)
- **Использовать AI-ассистента** для генерации и редактирования кода пользователя и возможностью видеть все внесенные изменения.
- **Видеть превью страницы** нажав на кнопку запуска кода.
- **Сохранять и скачивать** исходный код страницы.

# Установка и запуск (Локальный запуск)

1. **Клонирование репозитория**:
   ```bash
   git clone https://github.com/Wafflelover404/WebWizz.git
   cd WebWizz
   ```

2. **Установка зависимостей**:
   ```bash
   pip3 install -r requirements.txt
   ```

3. **Запуск приложения**:
   ```bash
   python3 -m streamlit run streamlit_app.py
   ```

### Настройка токенов
Для полноценной работы WebWizz требуются токены от HuggingFace и Pixabay.

1. **HuggingFace Token**:
   - Перейдите на [страницу настроек токенов HuggingFace](https://huggingface.co/settings/tokens).
   - Зарегистрируйтесь и получите ваш API-ключ.

2. **Pixabay Token**:
   - Перейдите на [страницу документации Pixabay API](https://pixabay.com/api/docs/).
   - Зарегистрируйтесь и получите ваш API-ключ.