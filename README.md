# **Quick Start решения**

1. ⬇️ Скачайте репозиторий проекта
    
    ```
    $ git clone https://github.com/Siyavush3/gpt-assistants-ldt-hack.git
    ```
    
2. 🔑 Настройте переменные окружения
    
    Создайте .env файл.
    
    ```
    AZURE_OPENAI_ENDPOINT = "YOUR_ENDPOINT"
    AZURE_OPENAI_KEY="YOUR_KEY"
    ASSISTANT_ID="YOUR_ID"
    
    ASSISTANT_TITLE="Умный помощник по комплексному подбору инвестиционных площадок"
    ENABLED_FILE_UPLOAD_MESSAGE="" 
    
    AUTHENTICATION_REQUIRED="False" 
    
    ```
    
3. 💽 Скомпилируйте docker проекта
    
    ```
    $ docker compose build
    ```
    
4. 🏃‍️ Запустите приложение
    
    ```
    $ docker compose up
    ```
    

Оно будет доступно на [http://localhost:8501](http://localhost:8501/).