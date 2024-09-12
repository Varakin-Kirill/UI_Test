# Инструкция по запуску теста
Следуйте этим шагам для настройки и запуска проекта на вашем локальном компьютере:
1. **Создать виртуальное окружение в корневой папке проекта строкой в терминале**
    ```bash
    python -m venv venv
2. **Активировать виртуальную среду строкой в терминале из корневой папки проекта**
    ```bash
   venv/scripts/activate
3. **Установить все пакеты указанные в requirements.txt строкой в терминале**
    ```bash
   pip install -r requirements.txt
4. **Запустить наш тест из корневой папки проекта строкой в терминале**
    ```bash
   pytest tests/test.py
