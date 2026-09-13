# Журнал использования ИИ

## ChatGPT(Codex)

<p align="center">
  <img src="../.github/assets/mem.png" width="300" alt="Mem">
</p>

### prompts

1. Проверка перед commit, проверь все скриншоты на имя компьютера/пользователя, Product ID, серийные номера, IP, MAC и личные пути.  И скажи на каком из скринов это есть что бы потом убрать.
2. Создай структуру согласно схеме.
    ```
        os-linux-course/
        ├── README.md
        ├── assets/
        │   └── screenshots/
        │       ├── 01_winver.png
        │       ├── 02_about.png
        │       ├── 03_cpu.png
        │       ├── 04_memory.png
        │       ├── 05_disk.png
        │       ├── 06_gpu.png
        │       ├── 07_processes.png
        │       └── 08_msinfo32.png
        ├── labs/
        │   └── lab01/
        │       ├── investigation.md
        │       └── reproducibility.md
        ├── reports/
        │   ├── system-passport.md
        │   ├── os-types.md
        │   └── ai-log.md
        └── scripts/
        └── README.md
    ```

3. Поправь все формулировки в файле на более корректные и понятные, чтобы текст был проще для восприятия, а также сократи лишние слова.  Сделай текст более информативным с сохранением оригинала.

4. Заполни файл labs\lab01\reproducibility.md согласно заданию из ворд файла.

5. Из скншотов возьми данные и заполни таблицу в файле reports/system-passport.md.

#### Ошибки формулировок

1. Проблема с созданием структуры папок. В начале проблема с создание структуры такова, что ИИ создал папки не в корне, а в паке os-linux-course которую он сам создал. В итоге структура была создана в папке os-linux-course_class/os-linux-course.
