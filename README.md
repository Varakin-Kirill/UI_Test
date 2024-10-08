## Описание проекта
Этот проект представляет собой автоматизированный e2e (end-to-end) тест для проверки сценария покупки товара на сайте saucedemo.com. Тест реализован с использованием Python и Selenium и охватывает полный процесс от авторизации до завершения покупки. Тест реализован при помощи базового POM (Page Object Model)

# Инструкция по запуску теста
Следуйте этим шагам для настройки и запуска проекта на вашем локальном компьютере:

1. **Создайте виртуальное окружение в корневой папке проекта**
   В терминале выполните команду:
   ```bash
   python -m venv venv
   ```
3. **Активируйте виртуальное окружение**
   В зависимости от вашей операционной системы, используйте одну из следующих команд:
   - Для Windows:
    ```bash
    venv/scripts/activate
    ```
   - Для macOS/Linux:
    ```bash
   source venv/bin/activate
    ```
5. **Установите все пакеты, указанные в requirements.txt**
   Убедитесь, что виртуальное окружение активировано, и выполните команду:
    ```bash
   pip install -r requirements.txt
7. **Запустите тест**
   В корневой папке проекта выполните команду:
    ```bash
   pytest tests/test.py -v
    ```
