## 🛠️ Домашняя проверка

### 1. Установка необходимого ПО
🔽 **Скачайте и установите:**
- [SQL Server](https://www.microsoft.com/sql-server/sql-server-downloads) | [SSMS](https://learn.microsoft.com/ru-ru/sql/ssms/download-sql-server-management-studio-ssms)

💾 *Совет: Сохраните итоговое окно установки SQL Server!*

### 2. Импорт базы данных
1. В **SSMS**:
   - ПКМ на `Databases` → `Import Data-tier Application`
2. В мастере импорта:
   - Выберите `Import from local disk`
   - Укажите ваш файл `.bacpac`

   

### 3. Настройка подключения
1. Найдите в проекте файл `App.config`

![Импорт БД](https://github.com/user-attachments/assets/e3f7ea18-c9db-4a11-bc38-10bd30bdaa9b)
   
2. Замените имя сервера на свое:
![App.config](https://github.com/user-attachments/assets/90a2e2c3-4756-491c-bc8a-54e361fb173d)
   ```xml
   <connectionStrings>
     <add name="MyDB" connectionString="Server=ВАШ_СЕРВЕР;..." />
   </connectionStrings>
   ```
   Имя Сервера можно чекнуть здесь:
   
![image](https://github.com/user-attachments/assets/749fed88-91b6-41ea-9c90-fb550b317273)

3. Тестирование приложения
   Запустите проект (F5)
   Проверьте:
     - Добавление записей во все таблицы
     - Работу всех функций интерфейса
     - Корректность отображения данных

## 🖥️ Настройка на сервере Масловой
### 1. Зайти в пк под админа Пароль: `Baltimor1152262`
### 2. Зайти на локальный сервер
Примерно будет так:

![image](https://github.com/user-attachments/assets/51f1b026-b8e9-4cdb-9c92-28cda6222343)
### 3. Закинуть бд как делал дома
### 4. Зайти в проекте в файл App.Config и поменять сервер на сервер масловой

# Если у тебя не получилось знай ты долбаеб иди и перечитай инструкцию. Удачи 😊




